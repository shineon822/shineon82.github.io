---
title: Esce Wordpress, entra Jekyll
date: 2016-01-27 00:00:00 +01:00
categories:
- sito
tags:
- sito
- blog
- Jekyll
- WordPress
- CMS
layout: post
subtitle: 'Shineon.it: da Wordpress a Jekyyl. Perchè?'
image: "/img/featured/jekyll-logo.jpg"
---

Ci pensavo già da un po': WordPress è un gran bel CMS, molto potente e flessibile, probabilmente eccessivo per queste poche pagine che mi ritrovo, cerchiamo alternative più performanti e snelle, magari anche senza database.

Così, nel -poco- tempo libero ho iniziato a guardarmi in giro per trovare alternative: ho valutato, più o meno velocemente, l'utilizzo di diversi CMS sviluppati sempre in PHP, ma, appunto, *databaseless*:

- *RazorCMS*
- *Monstra*
- *Pluck*
- *Flatpress*
- *GetSimple CMS*
- *Kirby ($)*
- *Statamic ($)*
- *Grav*
- *Nibbleblog*
- *Htmly*

...e sicuramente ne dimentico altri.

Mi sono soffermato di più sugli ultimi due, pensando di aver trovato quello che cercavo: velocità, facilità di utilizzo e personalizzazione sufficiente senza dover perdere tempo a metterci troppo le mani.

Qui però entra in gioco la mia voglia di complicarmi un pochino la vita...

### E Jekyll?!
Così mi è venuto mi sono ricordato di *Jekyll*, il famoso generatore di siti statici scritto in *Ruby* che è alla base di *Github Pages*.

> *Ruby*? Oddio, non saprei dove mettere le mani! :/

Calma, basta editare pochi file di configurazione, post e pagine si trovano su singoli file, scritti semplicemente in **Markdown**.  
D'accordo, all'inizio non sarà come usare un editor WYSIWYG, ma una volta imparata la sintassi, è comodissimo.  

Infine basta eseguire ```jekyll build``` e voilà, delle belle paginette html pronte a essere caricate sul server.

> Però aspetta, vuol dire che per usare Jekyll devo installarmi Ruby?!

Non necessariamente, perchè ora entra in gioco **Github Pages**: hosting gratuito per pagine statiche ( PHP non è supportato) ma anche... Jekyll installato sui loro server: ergo per aggiornare il nostro blog basterà *pushare* il nostro file .md nella cartella **_posts** e automaticamente nel giro di pochi secondi sarà stato generato e pubblicato.  

Comodo, no? Hosting praticamente a costo zero, potete configurare i DNS del vostro dominio e farli puntare alla vostra repository su Github.

Postare in mobilità? Per Android esiste l'ottima app [*MrHyde*](https://play.google.com/store/apps/details?id=org.faudroids.mrhyde), che fa sia il lavoro di un editor sia quello di un client GIT.  

Dopo aver provato parecchi temi, indecisioni, soluzioni apparse definitive... ho trovato in *[Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll)* quello che fa per me: <s>qualche</s> diverse modifiche qua e là  ed ecco che il tutto inizia a prendere forma.
