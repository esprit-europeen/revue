---
title: Présentation du site de la revue *l'Esprit européen*
author: Jules Rostand
date: 2020-11-16
---

Le site de la revue *l'Esprit européen* propose une expérience de lecture centrée sur le texte reprenant les travaux d'[Ewdard Tufte](https://www.edwardtufte.com/tufte/). Répondant aux exigences d'une publication numérique libre et modulaire, ce site propulsé par [Jekyll](https://jekyllrb.com) est né de la rencontre avec les réflexions proposées par [Arthur Perret](https://arthurperret.fr/) dans ses billets.

# Fonctionnalités générales

Développé à partir du [thème ```tufte-pandoc-jekyll```de @jez](https://github.com/jez/tufte-pandoc-jekyll) auquel a été ajouté les fonctionnalités du [thème ```tufte-pandoc``` de @clayh53](https://github.com/clayh53/tufte-jekyll), ce site utilise -- au-delà spécifications propre à Jekyll -- les plugins suivants :

* [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
* [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
* [jekyll-feed](https://github.com/jekyll/jekyll-feed)
* [jekyll-microtypo](https://github.com/borisschapira/jekyll-microtypo)
* [jekyll-favicon](https://github.com/afaundez/jekyll-favicon)

La [documentation de Jekyll](https://jekyllrb.com/docs/), notamment le [tutoriel pas-à-pas](https://jekyllrb.com/docs/step-by-step/01-setup/), ainsi que le [tutoriel d'utilisation de Bundle](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/#initialize-bundler), ont été d'une aide précieuse.

# Fonctionnalités spécifiques

Au cours du développement du site, ce dernier a bénéficié des contributions suivantes :

* Gestion des auteurs multiples : reprise de [la suggestion d'@jbranchaud](https://stackoverflow.com/questions/15189008/how-can-i-have-multiple-authors-for-one-post-in-jekyll#15208484) du 6 mars 2013. 
* Affichage des dates en français : reprise de [la suggestion d'Albin Kauffmann](https://github.com/albinou/albinou.github.io/blob/3e74deacab33d31e15dae603e8ba3454d4bd997f/_plugins/date_filter_french.rb) du 19 octobre 2017, disponible sur son compte GitHub [@albinou](https://github.com/albinou/albinou.github.io/blob/3e74deacab33d31e15dae603e8ba3454d4bd997f/_plugins/date_filter_french.rb).
* Microtypographie : personnalisation de la solution de Boris Schapira pour la [microtypographie française](https://github.com/borisschapira/jekyll-microtypo) pour la mise en indice supérieur des [nombres en lettres romaines](https://stackoverflow.com/a/36576402) de I jusqu'à XXXVIII (XVIIIe siècle par exemple).
* Gestion des images : reprise de la solution de Lincoln Mullen du 20 mars 2014 pour [agrandir les images en cliquant](https://github.com/lmullen/jekyll_figure/commit/21814d6d3e059a0a7e04ea78c582d7db7028cd4c#diff-9c3e0c47cd175a319d9cb4f6175f55d0)
* Citation Style Language : personnalisation du style bibliographique développé par Nicolas Chachereau et Martin Grandjean pour l'[Université de Lausanne (Histoire)](https://github.com/LausanneCitationStyle/Lausanne)

# Mentions légales

Les contenus publiés sur ce dépôt appartiennent exclusivement à *l'Esprit européen* et ne peuvent être réutilisés sans accord préalable, à l'exception des contenus relatifs à la publication numérique (classes de style, thème, polices, etc.) qui relèvent des licences d'utilisation de leurs auteurs ou, à défaut, de la licence [Creative Commons Attribution 4.0 International (CC BY)](https://creativecommons.org/licenses/by/4.0/).
