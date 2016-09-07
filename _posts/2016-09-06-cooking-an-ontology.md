---
layout: post
title:  "Cooking an ontology"
subtitle: "Cooking an ontology by R. Ribeiro, F. Batista, J.P. Pardal, N.J Mamede  and H.S. Pinto"
date:   2016-09-06 16:00:00
categories: [nlg, isiXhosa]
---

Elinye lamaphepha endicinga limnandi lithiywe lisenzisa i-ontology yokutya ekwakheni izivakalisi xa unikwe i-RDF data [1]. Enye yezinto bendibawela ukuyazi yindlela abazikhe ngazo ezindlela zokupheka bathetha ngazo [1, p11]. Bandithumele kwiphepha loo Ribeiro et al [2], apho bathetha ngee-dialogue systems kunye nokusebenzisa kwazo ii-ontologies. Aba babhali bathi enye yendlela zokuphucula ii-dialogue systems kukwehlula kakuhle i-system kunye nolwazi malunga necala elo i-system isebenza kulo (umzekelo; elezimpilo, imozulu, etc). Le nto ingenziwa ngokusebenzisa i-intology njengento elindelwe yi-system. Eliphepha lababhali lithetha ngokwakhiwa kwe-ontology kwicala lokupheka, ontology leyo izokusetyenziswa kwi-dialogue system. I-ontology le izakuthetha ngezinto ezine; actions, food, recipes kunye nee-utensils. Inazo nee-modules ezine zokwandisa; units & measures, equivalencies kunye neentlobo zee-plates.

Ukusetyenziswa kwe-ontology kwi-dialogue system inganika umakhi we-system indlela yokuhlula ulwazi kunye nokusebenza kwe-system. Isizathu salento yinto yokuba ii-ontologies zisetyenziswa in conceptualising knowledge.
Le nto ithi singakwazi ukuba nee-systems apho kufuneka utshintshe ii-ontologies zodwa, hay i-system yonke.


Ukwakhiwa kwe-ontology le yokupheka khange kulandele i-methodology ethile. I-scope se-ontology siye saxelwa/savavanywa ngokwakha imibuzo e-informal yokuxela i-competency ezakusetyenziswa ukubona ukuba i-ontology ingakwazi ukuyiphendula. I-version entsha ye-ontology kumele ikwazi ukuyiphendula le mibuzo ukwenzela ijongwe ngokuba iifezile uvavanyo. Ngexesha elabhalwa ngalo eliphepha, i-ontology le sithetha ngayo ibine-classes eziyi-1151, 92 slots kunye ne-instances eziyi-311.


Ababhalu bebedibana qho ngeveki; bebethetha ngezinto kunye nendlela zokuphucula i-ontology. Baye bohlulelana ngomsebenzi wokuqwalasela ulwazi oluthile. I-formalization ye-knowledge model yona yenze kwi-[Protégé](http://protege.stanford.edu/)

Into yokuqala abayenzileyo ababhali kukuqokelela ulwazi malunga nendlela zokupheka ngokufunda iincwadi zokupheka. Incwadi ezi bazifundileyo sithethe kwaye zicebise izinto ezahlukileyo, kodwa zingqinelene ekwahluleni kwe-concepts.
Kwiincwadi zonke, into yokuqala ebeziyenza kukudwelisa izinto ezizokusetyenziswa ekuphekeni. Bezohlulwe malunga nokuzala kwe-concepts ezo, umzekelo; izixhobo bezizodwa, inyama (nkomo, hagu, mvundla, etc) ibiyodwa, etc. Emva kokuqhaphela izinto ezinjena, ababhali baye benza ii-sessions apho bebefuna ukubona ii-concepts zonke ezisetyenziswayo ekuphekeni, amaqela wezo concepts kunye ne-properties ze-concepts ezo. Ilandeliswe yi-formalization yezizinto - kwaye bakhe abaqela ngamaqela azaku-formalizer ii-concepts ezithile.

Enye yezinto evele kwamsinya kukuba ingaba i-relations phakathi kwe-concepts zizokwenziwa njani. Ii-concepts ezininzi abanazo ababhali (ezifana ne `Food`, `Utensils`) zibonisa ii-hierarchies kwazona (Ngamanye amazwi, kuzofuneka wenze ezinye ii-concepts ezingaphantsi kwazo). Ezi zi-concepts zingaphantsi kwazo zidityaniswa nabazali 
abo zii `IS-A` relations. Ii-attribute based relations zisetyenziswe ekuchazeni uzalwano phakathi kwe-concepts ezikwi-hierarchies ezahlukileyo. Umzekelo, i-recipe isebenzisa ii-utensils kwaye lo nto iboniswa njenge slot kwi Recipe class. Enye yezinto eye yavela yinto yokuba ingaba zonke ii-concepts zizakuba zii-class okanye ii-instances.

Uvavanyo lwe-ontology khange lusebenzise izinto ezifana ne-OntoClean. I-client ibikhona kuwo wonke amaxa apho bekukhutshwa i-version entsha ye-ontology. Umsebenzi we-client ibikukusebenzisa ii-competency questions ukubona ukuba i-ontology ingasetyenziswa ekuyiphenduleni.


References

1. Cimiano, P., Lüker, J., Nagel, D. and Unger, C., 2013, August. Exploiting ontology lexica for generating natural language texts from RDF data. In Proceedings of the 14th European Workshop on Natural Language Generation (pp. 10-19).
2. Ribeiro, R., Batista, F., Pardal, J.P., Mamede, N.J. and Pinto, H.S., 2006, September. Cooking an ontology. In International Conference on Artificial Intelligence: Methodology, Systems, and Applications (pp. 213-221). Springer Berlin Heidelberg.