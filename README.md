
# On était au hackathon Elm de Décembre à Rennes... #
... et c'était vachement cool.

A Rennes le 03/12/2019 était organiser un hackathon autour du language Elm.
Chez KNP ça fait un petit moment regarde du coin de l'oeil ce language plein de belles promesses, alors on a sauté sur l'occasion d'un évènement se déroulant si près de Nantes.

![Alt](/small-elm-logo.png "Logo Elm")

## Elm, c'est quoi ? ##
Elm, c'est un language fonctionnel destiné principalement a la réalisation d'interfaces graphiques web, ceci en compilant en JavaScript.

Inspiré d'Haskell, il à été conçu pour être plus accessible que ce dernier, notamment en offusquant certains concepts avancés de la programmation fonctionnel. Pas besoin de savoir ce qu'est un Semigroupoid ou un Profunctor pour coder en Elm.

C'est à la fois un language et un framework, car il induit directement un pattern pour organiser son code, dit *MVU* (Model - View - Update). La célèbre libraire JS *Redux* s'en est ouvertement inspiré.

C'est de cette manière qu'Elm implémente le reactive progamming, qui consiste à représenter son code comme un flux de données asynchrone :

Chaque évènements (action utilisateur, réponse http, etc...) déclenche un **message**, qui passe dans une méthode **update** pour mettre a jour le **model** de l'application (son état, la représentation des données qu'elle contient), et mettre à jour les **vues** en conséquence.

### Ses autres caractéristiques ? ###
- Un typage fort,
- une syntaxe zen et épurée,
- pas de runtime errors grace à un compilateur qui guide le développeur jusqu'à ce que le code gère tous les cas qu'on puisse lui présenter. Coder du Elm, c'est littéralement dialoguer avec la machine.

## Le déroulement  ##
Chacun se présente, autour d'un croissant et d'un café, puis on nous présente des petits projets Elm publiés récemment, un rubik cube en WebGL par exemple, le temps de comblé un petit trou dans le planning.

Viens ensuite le retour sur experience de Vincent Josse, CTO d'AlloMédia. AlloMédia n'utilise qu'Elm pour leur frontend, dans leur codebase, on ne retrouve qu'une petite centaine de lignes de JS. La conclusion est selon lui sans appel :  Elm est prêt pour la prod, et ce depuis un moment déjà.

Comparativement à une codebase JS, une codebase Elm est plus simple et moins coûteuse à maintenir et enrichir, et on aura beaucoup moins de retours de bug.

Après une session de questions réponse, les participants sont invités à se répartir : Soit vers un atelier d'initiation, soit pour participer à des projets open sources.

De notre côté, on a joué la sécurité et participés à l'initiation. Bien qu'on ai déjà mis les mains dedans, il est toujours bon de s'assurer que nos bases sont solides. Pas de regret de ce côté là : le support de formation, écrit par l'un des organisateurs, est très qualitatif : nous sommes guidés dans la réalisation d'un moteur de recherche d'images. Chacun avance à son rythme, ceux qui finissent plus tôt peuvent ensuite rejoindre les autres équipes, ou démarrer un projet.

A la fin de la journée, chacun présente ce qu'il a réalisé. On aura donc entre autre :
- Un prototype de puzzle game, où l'on déplace une forme vers un point d'arrivée en lui écrivant des instructions textuel
- Un outil de gestion de JDR, en utilisant le client Kinto, qui est un backend serverless développé par Mozilla
- Un petit jeu où l'on doit faire atterir un vaisseau sur une plateforme.
- Une infructueuse mais belle tentative de compiler du code Elm en WebAssembly !

##   Ce qu'on a aimé ##
- L'enthousiasme et le plaisir qui émanait des participants et des organisateurs. C'était palpable que les gens étaient là car ils appréciaient l'expérience offerte par ce language.
- La chance d'échanger avec des vétérans qui pratiquent Elm professionelement et quotidiennement.
- La découverte de projet open sources intéressant, on explore grace a ça un peu plus en profondeur l'ecosystème Elm.
- Les compétences acquises en pratiquant aux cotés de gens instruits.

## Conclusion ##
On en ressort motivé à persisté dans notre apprentissage du language, avec l'envie d'un jour nous en servir en "situation réelle".

Un grand merci aux organisateurs, qui investissent leur temps et leur énergie pour populariser ce language si prometteur.

Si ça vous a donné envie de participer a la prochaine édition, tenez vous au courant sur le twitter Elm France : [https://twitter.com/elmfrance](https://twitter.com/elmfrance) ou sur le site dédié [https://hackathon-elm-france.github.io/](https://hackathon-elm-france.github.io/).

![Alt](/rubikcube.jpeg "Présentation d'un Rubik cube WebGL codé avec Elm, le matin.")
