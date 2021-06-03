---
layout: default
title: main
---

<section markdown="1" id="intro">



# Junior Grégoire, Développeur logiciel

  Bienvenue sur mon portfolio. C’est ici que je présente mes projets afin de démontrer mes compétences professionnelles en informatiques. J’espère pouvoir intéresser de futurs collaborateurs et ainsi faire profiter mon modeste savoir-faire pour faire avancer des projets passionnants et innovants pour la société québécoise et l’humanité.

  Si mes projets vous parlent et/ou que mes habilités vous intéressent, n’hésitez pas à me contacter. Les informations sont dans la section contact. Bonne visite !

  *Ce portfolio a été implémenté avec three.js et jekyll.*
</section>

<section markdown="1" id="projets">

## Mes projets
### Le blogue du MoisiOMètre

[Le blogue du MoisiOMètre](https://moisiometre.xyz) est un site web transactionnel que j’ai développé durant la pandémie. J’ai programmé ce blogue pour trois raisons. D’abord, c’est un projet qui m’a permis d’acquérir des compétences avec Django, VueJS (framework frontend en JavaScript) et Bulma (framework responsive en sass/css). Ça m’a permis de toucher au site transactionnel en implémenter des interfaces avec PayPal et Printful. Et finalement, l’écriture d’article m’a permis d’améliorer ma communication écrite.

Il y a aussi un sous-projet relié au blogue du MoisiOMètre. C’est [le Bullsh*tOMètre](https://moisiometre.xyz/bullshit)! Désolé, le nom n’est pas politiquement correct, mais ça donne un indice sur le but du projet. L’objectif de celui-ci est d’évaluer un contenu web (vidéo YouTube et site web) afin d’y détecter si celui-ci contient des éléments de fake news et du contenu conspirationniste. Pour le moment, j’utilise la librairie d’apprentissage machine scikit-learn pour le classement du contenu et spacy comme libraire pour traiter le langage naturel des textes. Ce projet m’a permis de touché à l’apprentissage machine, au traitement du langage naturel et de faire du « web scrapping »

### ParkMonBaïk

[ParkMonBaïk](https://parkmonbaik.xyz) est un projet qui est à sa deuxième itération. Ça fait des années que je travaille dessus en temps perdu, mais un jour je caresse le rêve de le finir. L’idée du projet m’est venu est regardant le données ouvertes de la ville de Montréal qui sont disponible sur [donnees.montreal.com](https://donnees.montreal.ca/).

Je me déplace souvent en vélo à Montréal et souvent je me cherche un endroit pour le stationner. Sur le site de données de la ville, il y a des informations sur la position des arceaux à vélos et d’autres emplacements pour cadenasser un vélo. Quand, j’ai vu ça, je me suis dit que ça serait bien de placer ces positions sur une carte géographique. Je pourrais ainsi voir les différentes options quand je me cherche un emplacement pour attacher ma bicyclette.

Pour le moment, je peux afficher ces endroits sur un plan de la ville grâce à [Leaflet](https://leafletjs.com/) et [OpenStreeMap](https://www.openstreetmap.org/). Par contre, les données de la ville de Montréal sont  incomplètes. Ils manquent des positions, donc la prochaine serait de donner à l’utilisateur la possibilité d’ajouter d’autres emplacements. Comme ça, éventuellement peut-être les utilisateurs motivés pourraient compléter les données eux-mêmes.

Je suis quand même bien avancé dans l’implémentation d’une version complète. Un jour peut-être je vais aboutir à quelque chose d’intéressant et utile pour les cyclistes de Montréal.

</section>

<section markdown="1" id="parcours">
## Mon parcours

  mon parcours

</section>

<section markdown="0" id="contact">
  <h2>Contact</h2>

  <div class="contacts">
    <span>Couriel: <a href="mailto:{{site.email}}">{{site.email}}</a></span>
    <span>Github: <a href="https://github.com/{{site.github_username}}">{{site.github_username}}</a></span>
  </div>
</section>
