---
layout: post
current: post
cover: assets/images/retour_france.png
navigation: True
title: Nous sommes de retour en France
date: 2019-11-11 08:00:00
tags: [Our Journey]
class: post-template
subclass: "post tag-getting-started"
author: antoine
---

### Roti.express : Naissance et adolescence chez AWS
AWS (Amazon Web Services) c'était pratique pour démarrer ! On connaissait déjà, ils proposent toute une gamme de services intéressants dont on s'est dit qu'on pourrait avoir besoin un jour (ou pas) et par ailleurs ils sont très agressifs sur les prix.

Nous avions besoin d'un Cloud-provider qui "fait le job" et nous qui permette de nous concentrer sur notre produit et uniquement sur notre produit.

Nous sommes donc restés chez AWS un bout de temps, depuis la création du MVP (Minimum Viable Product) jusqu'à cette date clé du 11 novembre 2019 à laquelle nous avons déménagé.

Nous souhaitons remercier Amazon et Mr Jeff Bezos pour leurs bons et loyaux services pendant ces 18 mois.

Notre décision est irrévocable, nous partons !

### Pourquoi partir ?
Nos serveurs ont toujours été sécurisés et nos bases de données encryptées, nous n'avons jamais subi de piratage malgré plusieurs tentatives.

Cependant, comme toute application hébergée chez un Cloud-provider Américain nous étions soumis au <a href="https://fr.wikipedia.org/wiki/CLOUD_Act" target="_blank">Cloud Act</a> et cela est vite devenu un problème.

>En résumé le Cloud Act c'est une loi fédérale qui permet aux forces de l'ordre Américaines de contraindre les fournisseurs de services américains à fournir les données demandées stockées sur des serveurs, qu'ils soient situés aux États-Unis ou dans des pays étrangers.

Et certains clients nous l'ont reproché, notamment les équipes Data en charge du RGPD et de la conformité. Pour certains clients du monde bancaire cela était un point bloquant pour souscrire au service et travailler avec nous.

Nous avons mis un peu de temps car notre produit sert à analyser <u>la forme</u> des réunions et normalement pas le fond, cependant nous ne sommes pas à l'abri des dérives et nous avons constaté que certains utilisateurs parlaient bien du fond lorsqu'ils laissaient un commentaire.

On a donc du devenir irréprochables, et on s’est dit que ce serait quand même bien de revenir sur un produit français, soutenir les solutions et les hébergeurs Made in France qui font le choix de payer des impôts !

### Ou aller ?
En octobre 2019 nous avons mené une petite étude et identifié 3 candidats potentiels : OVH, Clever-Cloud et Scaleway

Notre choix s’est porté sur <a href="https://clever-cloud.com" target="_blank">Clever-Cloud</a> qui offre un niveau de service qui surpasse notre ancien hébergeur :
<ul>
<li>Les possibilités de scaling sont plus finement réglables.</li>
<li>Les bases de données sont fortement cryptées.</li>
<li>Les pipelines de déploiement sont directement reliés à l'application.</li>
<li>Le support technique est au top ! on parle à des humains qui nous considèrent malgré notre taille modeste.</li>

<li>Les prix sont grosso-modo les mêmes, on a même eu une bonne surprise</li>
</ul>

On pensait être à peu près au même niveau de prix, on est finalement moins cher car nous récupérons 20% de TVA sur la note mensuelle !! c’est donc une opération qui devient financièrement rentable.

### Migration, les gestes techniques
Concrètement la migration s'est déroulée dans la nuit du 10 au 11 novembre, nous avions choisi cette date car nous savions qu'il y aurait une courte interruption de service et nous ne souhaitions pas impacter nos clients.

Les grandes étapes ont été :
<ul>
<li>Ouverture du compte CleverCloud</li>
<li>Copie de la base de données de production</li>
<li>Déploiement de l’application sur un nouveau noeud</li>
<li>Tests en tout genre !</li>
<li>Validation du bon fonctionnement sur la copie</li>
<li>Le jour J : re-copie de la base et migration DNS</li>
</ul>

Une pensée particulière pour notre CTO <a href="https://www.linkedin.com/in/guillaume-darbonne-85783a6/" target="_blank">Guillaume</a> qui a mené cette opération d'une main experte et nous a fait un sans-faute !

### Et après ?
Les tests techniques montrent que les performances sont meilleures, nous sommes tout simplement ravis !

Nous sommes désormais hébergés en France, et fiers de l'être. Nous espérons que notre action sera remarquée et que d'autres applications Françaises ou Européennes suivront le même chemin que nous.

Si cela suscite de l'intérêt nous pourrons en parler lors d'un Meetup REX (retour d'expérience).

Si cet article vous a plu, n'hésitez pas à partager sur votre réseau social favori.

A bientôt !
