---
title: Fonctionnement du site
author: Jules Rostand
date: 2020-05-12
---

Ce site, propulsé par Jekyll, reprend les thèmes créés sur la base des travaux d'Ewdard Tufte pour proposer une expérience de lecture numérique centrée sur le texte. 

# Outils et documentation techniques

Ce site a été développé à l'aide des outils et des documentations techniques suivantes : 

1. [La documentation de Jekyll](https://jekyllrb.com/docs/), notamment [le tutoriel pas-à-pas](https://jekyllrb.com/docs/step-by-step/01-setup/) et [le tutoriel d'utilisation de Bundle](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/#initialize-bundler);
2. Le [thème ```tufte-pandoc-jekyll```de @jez](https://github.com/jez/tufte-pandoc-jekyll) auquel a été ajouté les fonctionnalités du [thème ```tufte-pandoc``` de @clayh53](https://github.com/clayh53/tufte-jekyll);
3. Les réflexions sur le texte brut et la publication numérique [d'Arthur Perret](https://arthurperret.fr/).

# Fonctionnalités spécifiques

Les fonctionnalités spécifiques développées au cours de ce projet ont bénéficé des contributions suivantes : 

* Gestion des auteurs multiples : reprise de [la suggestion d'@jbranchaud](https://stackoverflow.com/questions/15189008/how-can-i-have-multiple-authors-for-one-post-in-jekyll#15208484) du 6 mars 2013. 
* Affichage des dates en français : reprise de [la suggestion d'Albin Kauffmann](https://github.com/albinou/albinou.github.io/blob/3e74deacab33d31e15dae603e8ba3454d4bd997f/_plugins/date_filter_french.rb) du 19 octobre 2017, disponible sur son compte GitHub [@albinou](https://github.com/albinou/albinou.github.io/blob/3e74deacab33d31e15dae603e8ba3454d4bd997f/_plugins/date_filter_french.rb).
* [Intégration du format bibliographique](https://github.com/mfenner/jekyll-pandoc/pull/6/files/c0dfd710f326634237f9b2ec2d384af4c5523b31#diff-35bfb52f0221e5edcda1be07a2ae9d59)
* [Microtypographie française](https://github.com/borisschapira/jekyll-microtypo), modifiée pour la mise en indice supérieur des [nombres en lettres romaines](https://stackoverflow.com/a/36576402) de I jusqu'à XXXVIII (XVIIIe siècle par exemple) et [ayant conduit à une personnalisation de la CSS](https://stackoverflow.com/a/1530819).

# Mentions légales

Les contenus publiés sur ce dépôt appartiennent exclusivement à *l'Esprit européen* et ne peuvent être réutilisés sans accord préalable, à l'exception des contenus relatifs à la publication numérique (classes de style, thème, polices, etc.) qui relèvent des licences d'utilisation de leurs auteurs ou, à défaut, de la licence [Creative Commons Attribution 4.0 International (CC BY)](https://creativecommons.org/licenses/by/4.0/).
