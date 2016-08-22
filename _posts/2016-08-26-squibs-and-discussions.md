---
layout: post
title:  "Real versus Template-Based Natural Language Generation"
subtitle: "Real versus Template-Based Natural Language Generation : A False Opposition? by Kees van Deemter, Emiel Krahmer & Mariet Theune"
date:   2016-08-16 16:00:00
categories: [nlg, isiXhosa]
---

Namhlanje siqwalasela umsebenzi ka Deenter, Krahmer kunye no-Theune. Bathu bafuna ukubonisa ukuba iisystems ezisebenzisa iitemplates xa zikhupha imibhalo nazo ziyakwazi ukukhuphisana neesystems ezisebenzisa iigrammar xa sijonga imaintanability, usetyenziswa kolwazi lwe-lingistics kunye nomgangatho wombhalo eziwukhuphayo. Bathi zikhona iisystems zamandulo eziyibonisileyo le nto.

Ababhali basibonisa ukuba abantu bayathanda ukwehlula iiNLG systems bubini. Kwicala elinye sine-systems ezakhelwe isizathu esithile kodwa azongezi nto kwi-theory. Kwelinye icala sine-systems ezakhiwe phezu kwe-theory kwaye zichaza ulwazi ngolwimi ngendlela apho zingasetyenziswa kumacala amaninzi. Abantu abaninzi iitemplates bazibona zingena kwii-systems ezi zokuqala. Ababhali bayaphikisa le nto kodwa - bathi kufuneka siyeke ukuzijongela phantsi iitemplates.

Sizokuqala ngokuthetha ngendlela ezibonwa ngayo ezintlobo zee-NLG systems. Kubalulekile ukubona kwethu ukuba akukho lula ukwehlula ezintlobo ze-systems. Siso esi isizathu esibangela ukuba ababhali bathi bazakusibonisa izizathu zokuba ukucinga ngoluhlobo akuzosinceda. Iingcinga ezikhoyo kodwa ziveza ukuba abantu bathi iisystems ezisebenzisa iitemplates zithatha ulwazi malunga nombhalo ofunekayo, likhuphe umbhalo lowo. Ezi systems zisebenzisa ilinguistic structure esinemingxunyo ezakuvalwa kumbhalo lo uzakukhutshwa. Ukuba uyaqwalasela, singathi i-Canned text yi-template engenamingxunyo. Ii-standard systems zona azithumeli i-input kumbhalo nqo okanye ngoko nangoko. Zisebenzisa imibonakaliso emininzi phambi kokuba zifike kumbhalo. Phakathi kwezi systems, eyona nto ibonwa yakhukile kukuba kwi-standard systems imibonakaliso igcina ulwazi nge-lexical entries kunye nendlela izivakalisi zizokuma ngayo, kodwa i-linguistic morphology yona ayikabikho kulemibonakaliso isesiphakathini.

Indlela abantu badilishana nazo ii-systems ezisebenzisa iitemplates ibonakalisa ukuba abantu bacinga ukuba azibalulekanga. uReiter kunye noDale [1] bathi kunzima ukuzigcina ezi systems kwaye azikhuphi imibhalo ehluke kakhulu, imibhalo le kunzima ukuba itshintshe ukwenzela ibengathi ibhalwe ngabantu. Ababhali baphinda bathi ababhali abafana no Busemann kunye no Horacek [2] bayayibaxa bona ngoba bathi ezi-systems azigcini lwazi oluphangaleleyo ngolwimi ukwenzela zikwazi ukusetyenziswa kumanye amacala ngaphandle kwalawo zazakhelwe zona. Zezi 'zizathu ezibangela ukuba ababhali balencwadi inye kwicala le Natural Language Generation bangathethi kabanzi nge-systems ezisebenzisa ii-templates. Ababhali bathi bazosibonisa isizathu sokuba kutheni kufuneka siyeke ukucinga kwaye nokuthetha ngathi ezi systems zohlukile.

Sizokuqala ngokujonga indlela iisystems ezisebenzisa iitemplates ezakhiwa ngayo kwaye nezisetyenziswa ngayo ebomini. Zininzi iisystems zetemplates ezintsha, ezakhiwa phakathi kwe-late '90s ukuya kwi-early 2000's. Ezi systems zenze umsebenzi omkhulu kwaye ongalindelwanga kwi-systems ezisebenzisa ii-templates. Kweli phepha, ababhali bazakusebenzisa ulwazi lwabo nge-system ekuthiwa yi-D2S yokuguqula ulwazi iluse kwilizwi, ngamanye amazwi, ifunde umbhalo lowo isystems iwukhuphayo. Enye ye-systems ezabekwa iliso yi-GoalGetter. Le yisystem ekhupha ingcazelo ze-soccer ngesi-Dutch. I-D2S yahlulwe kabini, ine-module ekhupha umbhalo. Inayo ne-module efunda umbhalo lowo. Ababhali baqwalasela le module ikhupha umbhalo, eyona into inomtsalane yindlela eyisebenzisayo efaka i-syntax kwi-templates. Ii-data structures ezisetyenziswa yi-GoalGetter zizehlakalo ezifana nokukora komntu, ukufumana i-card elityheli okanye elibomvu ebaleni, nezinye. Ababhali bayayicacisa [4, p18] indlela apho ii-slots kwi-GoalGetter zivalwa ngayo. Umbuzo endinawo kodwa kukuba ingaba ukusebenzisa imithi kunyenceda? Andikamboni umsebenzi wayo. Ingaba uyambona wena? 


Phambi kokuba sifike kulemibuzo ingentla, masiqale sihoye imibuzo engcono. Ingaba ii-systems ezisebenzisa ii-templates ziqhuba njani kule-criteria ibekwe ngababhali inezinto ezifana ne-maintainability, nezinye. Ababhali bathi asikwazi ukujonga iisystems ezakhiwe zodwa xa sifuna ukuphendula lo mbuzo. Sizakujonga nezingakwazi ukwakhiwa. Baqala ngokuhoya i-maintainability ababhali ngokuthi; le nto yokuba ii-systems ze-templates zihlala ziqhuba kakubi kwicala le maintainability ayonto icacileyo kwaye ayonyani ngoba zikhona ii-systems ezaphinda zasetyenziswa kumanye amacala angengawo la yayokhelwe yona. Ingxaki endinayo nalento bayithethayo yinto yokuba akukho mntu othi ZONKE ii-systems ze-templates azikwazi ukusetyenziswa kumanye amacala angengawo la zazakhelwe wona. Ababhali basinika ii-systems ezintathu ngokungathi ithi lo nto zonke ii-systems ze-templates zikumgangatho omnye kunye ne-systems ezisebenzisa ii-grammar. Eyona nto, ngokubona kwam, yile well-foundedness yezi-systems. Bathi bafuna ukuqwalasela le nto ye well-foundedness ngokujonga ii-processes ezikhoyo kwi-NLG (ezi zixhaphake kwi-pipeline architecture)

Kwi-content determination, kulapho sikhetha ulwazi kunye namagama azokusetyenziswa kwi-system yethu. Kumele ukuba akhukho mehluko phakathi kwendlela ii-systems ze-grammar kunye neze-templates ezisebenza ngayo. Kwi-systems ezakhiweyo kodwa siyawubona umehluko. Umzekelo, ii-systems ze-templates zisebenzisa ulwazi ekuthiwa lumcaba ("flat data"), izinto ezifana ne-records ezisuka kwi-database. Ii-systems ze-grammar ngelaxesha zithatha i-input yomgangatho ophezulu. Zona zithatha i-input apho, ngamanye amaxesha, ixelalo ukuba i-output izokuma njani.

Ababhali bayagqina ukuba xa sifika kwi-linguistic realisation, ii-systems ze-grammar zihamba phambili ngoba ii-templates ziyasokola xa kufikwa ukuchaza ezi zinto zilandelayo.

> Gender, Number, Person Agreement.

Ababhali basamile kodwa ukuba akukho nto inqanda abakhi be-systems ze-templates ekufakeni ii-morphological rules. Into endiyibonayo kodwa kuyo yonke le nto bayithethayo kukuba akusekho lula ukwehlula phakathi kwezi ntlobo ze-systems ngoba ii-systems ze-templates sifaka ii-grammar kakhulu nazo ngoku.



References

1. Reiter, E., Dale, R. and Feng, Z., 2000. Building natural language generation systems (Vol. 33). Cambridge: Cambridge university press.
2. Busemann, S. and Horacek, H., 1998. A flexible shallow approach to text generation. arXiv preprint cs/9812018.
3. Van Deemter, K., Krahmer, E. and Theune, M., 2005. Real versus template-based natural language generation: A false opposition?. Computational Linguistics, 31(1), pp.15-24.