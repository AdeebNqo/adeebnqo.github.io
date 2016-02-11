---
layout: post
title:  "Welcome to Jekyll!"
subtitle: "Feel home!"
date:   2015-03-11 23:34:01
categories: [nlg, isiXhosa]
---
Ukuguqula ulwimi uluse kwelinye usebenzisa icomputer yinto enzima.
Ndiyaqonda ukuba umntu ongenalwazi oluphangaleleyo ngalemeko angavele
ajonge izinto ezifana noGoogle Translate acinge ukuba singabantu
sele siphumelele. Indaba ezimbi yinto yokuba uGoogle Translate
akasebenzi ncam.


Xa unolwazi ufuna ulungcina kwikhomputha usebenzisa iilwimi ezifana
neXMl, JSON, kunye nezinye iSerialization formats. UWikipedia, xa ecacisa iXML, uthi:

  > Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format which is
  > both human-readable and machine-readable. It is defined by the W3C's XML 1.0 Specification and by several other related specifications,
  > all of which are free open standards.
 
Ukuba ufuna ukubona umzekelo walelwimi, musa ukoyika - sizakubonisa. IYinto efana nale ingezantsi:

{% highlight xml %}
  <food>
    <name>Umgqusho</name>
    <price>R5.95</price>
    <description>
        Xhosa dish. Samp and beans. Best enjoyed in chilly weather
    </description>
  </food>
{% endhighlight %}
  
Ukuba uyaqwalasela, singcina ulwazi oluninzi ngoluhlubo. Izinto ezifana ne gama, xabiso kunye nengcaciso yokukutya.
Kulula ufumana into oyifunayo kolulwazi. Mhlwawumbi xa ufuna igama lokutya uzakwenza oluhlobo:

 {% highlight java %}
 Food foodObject = new Food(xmlData);
 String name = foodObject.getName();
 String price = foodObject.getPrice();
 String description = foodObject.getDescription();
{% endhighlight %}
 
Xa uzivumene ezinto zintathu, ungazisebezinsa xa ufuna ukulibhala ngolwimi labantu olulwazi. Umzekelo, esiNgesini ungathi:


  > We serve `foodObject.getName()` at the price of `foodObject.getPrice()`


Akukho lula ukwenza into efanayo ngeeLwimi zesiNguni. Ezilwimi ziquka isiXhosa, isiZulu, isiSwati kunye nesiNdebele.
Esinye sesizathu sokuba kube njalo yinto yokuba ezilwimi kuthiwa ziilwimi ezi-agglutinative. Ndicela uqaphele ukuba
umzekelo lo ndiwudwelise ngentla ubonakilisa imeko enye kwaye elula.


Ungacinga ukuba ukubhala le nto ilandelayo kwaznele:

  > Sithengisa `foodObject.getDescription()` ngemali engange-`foodObject.getPrice()`

Ingxaki apha yinto yokuba isimaphambili sengema sixhomekeka kwamanye amagama asetyenzisiweyo
ecaleni kwegama elo. Ukuba unikwe olulwazi lulandelayo, le nto besithetha ngayo ngentla ayisasebenzi.

 {% highlight xml %}
  <food>
    <name>Spinach</name>
    <price>R5.95</price>
    <description>Siluhlaza kwaye sisaphilele.</description>
  </food>
{% endhighlight %}

Kukho isibe lemfundo phakathi kweComputer Science ekuthiwa yi-Natural language generation (NLG).
Umsebenzi welisebe kukuthatha ulwazi olubonakaliswe ngendlela ezifanele icomputer liluse kwisiNgesi
okanye kwezinye iilwimi zabantu. Ngenxa yeNLG singakwazi ukwenza iincwadi, iingcaciso kwicomputer kunye
nezinye iintlobo zemibhalo.

Kulonyaka ndizama (kunye nabanye abantu) ukwakha iSystem engakhupha iilwimi zesiNguni, ndiqwalasele isiXhosa
kakhulu.