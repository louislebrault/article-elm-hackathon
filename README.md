
# On était au hackathon Elm de Décembre à Rennes... #
... et c'était vachement cool.

À Rennes le 03/12/2019 était organisé un hackathon autour du language Elm.
Chez KNP ça fait un petit moment qu'on regarde du coin de l'oeil ce language plein de belles promesses, alors on a sauté sur l'occasion de participer à un évènement se déroulant si près de Nantes.

![Alt](/small-elm-logo.png "Logo Elm")

## Elm, c'est quoi ? ##
Elm, c'est un language fonctionnel destiné principalement à la réalisation d'interfaces graphiques web, ceci en compilant en JavaScript.

Inspiré d'Haskell, il à été conçu pour être plus accessible que ce dernier, notamment en offusquant certains concepts avancés de la programmation fonctionnel. Pas besoin de savoir ce qu'est un Semigroupoid ou un Profunctor pour coder en Elm.

C'est à la fois un language et un framework, car il induit directement un pattern pour organiser son code, dit *MVU (Model View Update)*. La célèbre libraire JS *Redux* s'en est ouvertement inspiré :

Chaque évènement (action utilisateur, réponse http, etc...) déclenche un **message**, qui passe dans une fonction **update** pour modifier le **model** de l'application (son état, la représentation des données qu'elle contient), et mettre à jour les **vues** en conséquence.

Elm c'est également :
- Un typage fort,
- une syntaxe zen et épurée,
- un compilateur qui accompagne le developpeur afin de l'aider à gérer tous le cas que l'application va rencontrer. Ce faisant, le risque d'avoir une runtime error en Elm est quasi-inexistant. Si le code compile, il fonctionne.


## Le déroulement  ##
Chacun s'introduit autour d'un croissant et d'un café. En attendant que les derniers participants arrivent, on nous présente de petits projets Elm publiés récemment, un rubik cube en WebGL par exemple.

Vient ensuite le retour d'expérience de Vincent Josse, CTO d'Allo-Media. Allo-Media n'utilise qu'Elm pour leur frontend. La conclusion est selon lui sans appel : Elm est prêt pour la prod, et ce depuis un moment déjà.
L'équipe est productive, le produit est quali, très peu de bugs arrivent jusqu'aux utilisateurs. Le constat est élogieux.

Après une session de questions/réponses, les participants sont invités à se répartir : soit vers un atelier d'initiation, soit pour participer à des projets open sources.

De notre côté, on a joués la sécurité et participés à l'initiation. Bien qu'on ai déjà mis les mains dedans, il est toujours bon de s'assurer de la solidité de nos bases. Pas de regret de ce côté là : le support de formation, écrit par l'un des organisateurs, est très qualitatif : nous sommes guidés dans la réalisation d'un moteur de recherche d'images. Chacun avance à son rythme, ceux qui finissent plus tôt peuvent ensuite rejoindre les autres équipes, ou démarrer un projet.

A la fin de la journée, chacun présente ce qu'il a réalisé. On aura donc entre autre :
- Un prototype de puzzle game, où l'on déplace une forme vers un point d'arrivée en lui écrivant des instructions textuel
- Un outil de gestion de JDR, utilisant le client Kinto, qui est un backend serverless développé par Mozilla
- Un petit jeu où l'on doit faire atterir un vaisseau sur une plateforme.
- Une infructueuse mais très intéressante tentative de compiler du code Elm en WebAssembly !

##   Ce qu'on a aimé ##
- L'enthousiasme et le plaisir qui émanait des participants et des organisateurs. C'était palpable que les gens appréciaient l'expérience offerte par ce language.
- L'opportunité d'échanger avec des vétérans qui pratiquent Elm professionnellement et quotidiennement.
- La découverte de projets open source intéressants, on explore grâce à ça un peu plus en profondeur l'écosystème Elm.
- Les compétences acquises en pratiquant aux cotés de gens instruits.

## Conclusion ##
On en ressort plus motivé que jamais à persisté dans notre apprentissage du language, avec l'envie d'un jour nous en servir en "situation réelle".

Un grand merci aux organisateurs, [Pascal Le Merrer](https://twitter.com/pascallemerrer) et [Rémy Hubscher](https://twitter.com/natim) qui investissent de leur temps et de leur énergie pour populariser ce language si prometteur, en plus d'être des personnes fort sympathiques et accessibles.

La prochaine édition se déroulera **16 janvier**, 18h30 à 22h30 à Cesson-Sévigné (35510).
Plus d'informations sur le site dédié [https://hackathon-elm-france.github.io/](https://hackathon-elm-france.github.io/) ou sur le twitter Elm France [https://twitter.com/elmfrance](https://twitter.com/elmfrance). Foncez !

![Alt](/rubikcube.jpeg "Présentation d'un Rubik cube WebGL codé avec Elm, le matin.")
