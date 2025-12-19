---
#layout: post
title:  "Noun classification thoughts II"
subtitle: "Noun classification and sadilar data"
date:   2025-12-20 00:08:00
categories: [hlt, nguni]
permalink: /post/2025-nounclassification
---


The exam period, and all its admin, is officially over. As a way of winding down, I decided to take some time and revisit the noun classification task.

## Open question(s)

In the last instalment, detailed in my last [post](https://adeebnqo.github.io/post/2025-nounclassification), where I was investigating the extent to which a simple multilingual model can solve noun class disambiguation for Niger-Congo B languages, I had relied on the tokenizer created by Meyer, 2024. Since then, I’ve been thinking about stripping out that tokenizer and relying on something even simpler to get a sense of how such models perform. Interestedly, after I made that post, I noted that Nakashole, 2025 has investigated the use of even more complex models on a new and open dataset (see [https://github.com/okalai-ai/moimoe](https://github.com/okalai-ai/moimoe)).

The work is relevant to us because it also featured isiXhosa and isiZulu. Instead of increasing complexity and, perhaps following Nakashole’s lead, investigating a Mixture-of-Experts approach, I’ve been really wondering to what extent even simpler models are successful at this task. Specifically, I am curious to understand the extent to which can one rely on a simpler model but focus on hyperparam. optimisation to yield a good model.


## Updated model and question

To investigate this, I created a simple multilingual model using PyTorch on the same dataset used for the last post (see [https://adeebnqo.github.io/post/2025-nounclassification](https://adeebnqo.github.io/post/2025-nounclassification)). An overview of the model, with some detailed dropped for simplicity, is given in the following visualisation:

![](/images/SimpleSelfAttentionModel.png)

The model shows some improvement from the last iteration/version as demonstrated by the following results: 

|   | Prec | Rec  | F1  |
|---|---|---|---|---|
| Micro  | 0.56  | 0.56  | 0.56  |
| Macro  | 0.57  |  0.53 | 0.53  |

The hyperparam. search that we did was focused on tweaking the learning rate, weight decay, and betas when training the model. When we look at the final output, it is clear that the performance is still not great. Given this fact, the one question that is at the back of my head now is: while existing dictionaries are dated, do they not capture linguistic knowledge that still holds for noun classification at the current moment?

# References

- Meyer, 2024: [https://huggingface.co/francois-meyer/nguni-xlmr-large](https://huggingface.co/francois-meyer/nguni-xlmr-large)
- Nakashole, 2025: [https://ndapa.us/assets/docs/papers/2025-moi-acl.pdf](https://ndapa.us/assets/docs/papers/2025-moi-acl.pdf)
