---
ID: 961
post_title: 'Comment connaître le temps d&#039;execution d&#039;une fonction ? system.time'
author: vincent
post_excerpt: ""
layout: post
permalink: >
  https://abcdr.thinkr.fr/comment-connaitre-le-temps-dexecution-dune-fonction-system-time/
published: true
post_date: 2011-12-03 10:33:32
---
Lorsque l'on réalise des scripts qui vont tourner un certain temps avant d'aboutir au résultat final, il est essentiel d'en optimiser le fonctionnement pour gagner du temps. Il nous faut pour cela un bon indicateur : comment savoir le temps que dure une fonction ou un script ? <br />Vous pouvez utiliser la fonction <strong>system.time</strong><br /><br /><br /><br /> <pre><code><br />system.time(for ( i in 1:10000){print(i)})<br />system.time(for ( i in 1:10000){cat(i)}) <br /></code></pre>