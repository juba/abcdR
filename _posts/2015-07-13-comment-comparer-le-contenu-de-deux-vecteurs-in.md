---
ID: 3119
post_title: 'Comment comparer le contenu de deux vecteurs ? %in%'
author: helene
post_excerpt: ""
layout: post
permalink: >
  https://abcdr.thinkr.fr/comment-comparer-le-contenu-de-deux-vecteurs-in/
published: true
post_date: 2015-07-13 08:10:18
---
<p>L'opérateur <b>%in%</b> teste le contenu de deux vecteurs en retournant des éléments booléens (TRUE si l’élément est présent dans les deux vecteurs, False sinon), de la même longueur que le premier vecteur testé.</p><p> </p> <pre><code><br /><p></p><p></p><p>fleurs_A &lt;- c("Bleuet", "Campanule", "Capucines", "Clématite", "Coquelicot")</p><p> </p><p>fleurs_B &lt;- c("Bleuet", "Bruyère", "Campanule", "Capucines", "Colchique", "Clématite", "Coquelicot", "Gentiane", "Géranium", "Iris")</p><p> </p><p>fleurs_B %in% fleurs_A</p><p>#On teste si le contenu de « fleurs_B » est présent dans  «  fleurs_A »</p><p></code></pre>   </p><p> </p><p>On obtient :</p><p> <pre><code></p><p>fleurs_B %in% fleurs_A</p><p>TRUE FALSE  TRUE  TRUE FALSE  TRUE  TRUE FALSE FALSE FALSE  TRUE  TRUE<br /> </code></pre>   </p>