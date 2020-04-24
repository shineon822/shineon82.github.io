---
title: Escursioni
permalink: "/escursioni/"
layout: page
tags:
- escursioni
- montagna
- appennini
bigimg:
- "/img/big/antola.jpg": Panorama dal M. Antola (2010)
redirect_from:
- "/trekking/"
- "/escursioni/liguria/"
- "/escursioni/piemonte/"
- "/escursioni/emilia-romagna/"
---

> Eppure, le Alpi sono solo la cornice esterna del paese.  
Gli Appennini invece ne sono l'anima, lo stomaco, la colonna vertebrale.  
E sono lunghi quasi il doppio.  
Senza di loro, la patria si affloscerebbe come uno Zeppelin senza gas nella pancia.
>
**<sub>Paolo Rumiz, La leggenda dei monti naviganti, 2007, Feltrinelli</sub>**

Fin da piccolo ho amato la montagna e il camminare in genere.  
Però, nonostante sia nato a due passi dalla Grigna, il mio sguardo si è sempre rivolto a sud anzichè a nord: l'Appennino mi ha sempre affascinato di più.

Qui sotto due progetti chiusi nel cassetto da ormai parecchi, troppi, anni: due trekking non eccessivamente lunghi.

##### [La via del sale, da Montalto Pavese a Portofino](/escursioni/via-del-sale/)  
itinerario recuperato da un numero di Airone di trentanni fa...

##### [La via del mare, da Tortona a Portofino](/escursioni/via-del-mare/)
---
Le -poche- escursioni finora presenti, divise per regione:

#### [PIEMONTE](#piemonte)
{% for post in site.categories.Piemonte %}
<li><time class="icon-calendar pr20" datetime="{{ post.date | date: "%d-%m-%Y" }}" itemprop="datePublished"> {{ post.date | date: "%d-%m-%Y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

#### [LIGURIA](#liguria)
{% for post in site.categories.Liguria %}
<li><time class="icon-calendar pr20" datetime="{{ post.date | date: "%d-%m-%Y" }}" itemprop="datePublished"> {{ post.date | date: "%d-%m-%Y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

#### [EMILIA ROMAGNA](#emilia-romagna)
{% for post in site.categories.Emilia-Romagna %}
<li><time class="icon-calendar pr20" datetime="{{ post.date | date: "%d-%m-%Y" }}" itemprop="datePublished"> {{ post.date | date: "%d-%m-%Y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
