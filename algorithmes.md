<!-- .slide: data-background-image="img/williamBetts.jpeg" data-background-size="contain" -->

## Tous calculés ?

<!-- .element: class="grandtitre" -->

### Comprendre l’influence des algorithmes

<!-- .element: class="grandtitre" -->

Source : William Betts

<!-- .element: class="source" -->

===
Nous allons poursuivre notre portrait du récepteur moderne : l'internaute ou usager des medias numériques.

L'angle que j'ai choisi d'aborder avec vous aujourd'hui, est celui de l'influence des algorithmes. Je vais poser quelques éléments de définition tout à l'heure, mais je voudrais d'abord justifier ma démarche : pourquoi est-ce si important de comprendre le fonctionnement d'un algorithme ?

Tout simplement parce que ce sont les algo qui structurent le web, qui en sont les "architectes".


Objectif : vous faire comprendre les enjeux d'une bonne indexation et le fonctionnement de base des principales familles d'algo, puisqu'il y a fort à parier que vous serez confrontés un jour à ces questions dans le cadre de votre carrière, où vous serez par exemple amenés à décrire les contenus que vous publiez, à optimiser l'indexation d'un site web-vitrine. Une petite intro théorique ne fait donc pas de mal, ne serait-ce que pour savoir, globalement, ce dont on parle.


L'organisation des différentes données sur le web : pourquoi, lorsque l'on tape un mot sur un moteur de recherche, c'est tel résultat qui tombe en premier, et dans quelle mesure ce résultat sera le seul que je vais consulter et qui va m'influencer par la suite.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/stats3.png" data-background-size="contain" -->

===

Rappel d'un problème que l'on a vu il y a 2 semaines : l'hégémonie des moteurs de recherche sur le web. En gros, on utilise tous Google. Cela ne serait pas si grave si nous ne l'utilisions pas si mal : la paresse, le manque de littératie numérique (cad de connaissance de la façon dont fonctionne vraiment ces outils) nous pousse à ne consulter que les premiers résultats de la première page, sans aller plus loin.

Pourquoi dire que nous utilisons mal les outils ? Arrêtons nous d'abord sur les problèmes posés par cette manière de chercher...

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Structuration du web, structuration du réel ?
* Si je cherche un service sur *google maps*, j'ai tendance à ne considérer que la liste donnée par l'outil...
* Je ne consulte souvent que les premiers résultats de ma recherche... (cf. la bataille du référencement pour les sites d'information sur la contraception et l'avortement)

===

Le web, c'est un amas de données, sans cesse en train de s'augmenter de manière exponentielle, des contenus en tous genre en quantités astronomiques, ce que l'on appelle le big data, tellement gigantesque qu'il n'est pas appréhendable par l'esprit humain.

Comme il n'est pas appréhendable, il faut l'organiser. Et comme nous ne sommes pas capable de l'organiser nous-mêmes directement, nous laissons les algorithmes le faire pour nous.

Sauf que nous n'avons pas toujours bien conscience des règles de cette organisation.

Il ne s'agit pas de dire que les algorithmes sont mauvais, il s'agit de dire que ceux-ci doivent être transparents, doivent exposer les règles qui les régissent, afin que nous sachions exactement quels sont les biais auxquels nous sommes soumis lorsque nous réalisons des recherches en ligne.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/streetview.png" data-background-size="contain" -->


===

J'en cite ici un exemple : le fantastique outil de Google Maps, qui nous permet de ne plus jamais nous perdre, a agrégé une série d'informations qui ne relèvent plus seulement de la simple cartographie :
  - des adresses de magasins
  - des adresses de restaurants
Toutes ces adresses font l'objet d'une évaluation et de commentaire. On peut connaître aussi l'achalandage en fonction des heures. Tant et si bien que lorsque je décide, par exemple, de me promener dans le quartier de la Sorbonne, je vais avoir en même temps une série de suggestions de cafés où me rendre : c'est une sorte de publicité - un autre terme est souvent avancé dans le domaine des économies numérique - celui de l'influence...

AUtre exemple, encore plus simple et plus parlant probablement : celui des sites d'information pour les IVG : régulièrement, il y a une sorte de combat d'indexation entre le site d'information du gouvernement et des sites militants, généralement anti-OVG, pour la première place du classement.

Tout cela pour dire que si la question de la structuration du web est aussi problématique, c'est parce qu'elle structure en fait le réel. Elle a un impact effectif sur notre monde et notre manière de l'habiter.

Ce qui est intéressant, c'est de constater combien ces façons de faire, désormais courantes avec nos usages numériques, nous paraîtraient totalement inconcevables dans d'autres sphères d'action.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->

## Problématique

Comment le web est-il formé, structuré, organisé ? Comment se structure le media qui constitue notre fenêtre sur le monde contemporain et qui donc participe à structurer notre monde ?

===

Je voudrais commencer par une petite digression épistémologique : ce cours est un cours en théorie des media. J'ai finalement peu défini, je me rends compte, ce qu'il faut entendre par media. Un media, au sens général du terme, c'est ce qui est "entre" les choses. Les mass media (la presse, la TV, les réseaux sociaux), médient des informations: ils se placent entre les événements, les faits, et nous. Ils fabriquent ainsi l'actualité. Mais les livres, le cinéma, la radio sont eux aussi des media: ils proposent des formes d'enregistrement, de représentation du monde et du réel, qui se trouvent de fait médiés. Notre accès au réel, au monde, est ainsi dans 90% des cas médié : les choses du monde me parviennent par le biais d'un livre, d'un journal, d'une écriture... mais aussi d'une voix, par exemple.

De fait, Médier le réel, c'est le construire, et c'est le construire en le modélisant, en le rendant appréhendable, compréhensible - au sens étymologique du terme, "prendre avec soi". Représenter le monde, c'est chercher à le prendre avec soi, à s'en saisir, afin de mieux y habiter. Or comment représenter, comment comprendre et donc comment habiter le monde aujourd'hui ?

Cette question résonne tout particulièrement dès lors que l'on s'intéresse à un outil numérique devenu incontournable : le web. Pour utiliser une métaphore propre à la représentation, le web est aujourd'hui une fenêtre sur notre monde. Mais il n'est pas seulement cela : il a tendance à le structurer largement, en influençant notre accès à l'information et par conséquent nos comportements. Du coup, la question à se poser est la suivante : comment le web est-il lui-même formé et lui-même structuré ? Comment, pour compléter la problématique, est construit, est structuré le media qui constitue notre fenêtre sur le monde contemporain et qui donc participe à structurer notre monde ?

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/bookshop.jpg" data-background-size="contain" -->


===

Comparez un peu vos pratiques avec, par exemple, celle du flânage en libraire, ou dans un magasin de vêtements. Vous arrêtez-vous toujours seulement sur ce qui est présenté en vitrine ? Vous contentez-vous seulement de choisir les livres mis en évidences sur les présentoirs ? Ce goût que nous avons pour le flanage, la fouille dans les rayons d'une librairie, d'une boutique quelconque, nous le perdons la plupart du temps lors de nos recherches sur Google. Peu d'utilisateurs vont explorer les 100aines de résultats...


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/amazon1.png" data-background-size="contain" -->


===

Chez Amazon aussi j'ai un "tri".

Possibilité d'une personnalisation : par exemple, des filtres thématiques.
Avec même l'illusion que le tri est fait par mes semblables, les autres internautes.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/amazon2.png" data-background-size="contain" -->


===
Le problème qui se pose ici est notamment celui de l'autorité, de la légitimité. CHez mon libraire, même si je me contente de regarder les livres sélectionnés sur un présentoir, je peux identifier la personne qui est à l'origine de ce tri, de cette sélection. C'est d'ailleurs pour cela que nous finissons par avoir des "libraires" préférés : on sait que nous pouvons faire confiance en une personne qui aura du goût, parfois le même que le nôtre mais pas toujours. On se fie au jugement d'un professionnel du livre. C'est aussi de cette façon que l'on va choisir notre journal ou notre magazine préféré : nous identifions un groupe de journalistes, avec lesquels nous partageons des valeurs, notamment.

Le problème d'un moteur de recherche comme celui d'Amazon, équivalent de mon libraire en ligne, c'est qu'il nous propose également un tri, mais sans que l'on sache très bien 1) qui se cache derrière ce tri 2) sur quels critères ce tri s'est opéré.

Cette question résonne de fait avec une problématique que nous avons étudiée il y a quelques semaines : celle la crise de la vérité. On a vu en effet que cette crise résidait d'abord dans la remise en cause profonde d'un modèle de légitimation qui ne fonctionne plus comme avant. Mais sur le moteur de recherche Google, par exemple, qui légitimise les contenus ?

On voit bien ici que la question est complexe : déjà, le moteur de recherche que nous utilisons est avant tout une machine qui, en tant que telle, nous semble dénuée de "volonté". Il y a là une illusion d'objectivité qui se dégage de la nature informatique de l'outil : une série de calcul, dans lesquels personne n'interviendrait.
Sauf que ces calculs ont été déterminés par des être humains... et que ces être humains ont, de leur côté, importés leurs biais. Le fait que les programmeurs de chez Google soient majoritairement des hommes blanc a souvent été dénoncé : on s'appercevait que certains algorithmes avaient tendance à reproduire des comportement racistes ou sexistes. Autre problème : le code, l'algorithme utilisé par les grands monopoles du web - GOogle, FB, etc - ne sont pas public, ou du moins pas complètement publics. C'est-à-dire que l'on e sait pas, globalement, comment ils fonctionnent.

Sans aller jusqu'à l'échelle des GAFAM, ce problème de la transparence du code a été posée pour des algorithmes qui vous concerne directement : notamment celui de parcours sup, dont personne (à part le ministère), ne sait vraiment comment il fonctionne. N'est-ce pas là problématique ? Ce manque de transparence est ce que dénoncent les associations militantes en faveur d'une plus grande démocratie numérique :
- la CNIL, dont il a été question la semaine dernière
- la Quadrature du net


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

### Le web à l'heure du "big data"
* "big" : un explosion quantitative
* "data" : des informations sur-mesure

===

Je commencerai par une première définition, que je vous encourage à retenir, mais surtout à bien comprendre : le *big data*. Nul besoin d'être traducteur de Shakespeare pour comprendre qu'il s'agit ici de désigner la masse des données produites et diffusées chaque jour en ligne. Souvent citée, la notion de *big data* demeure cependant mal maîtrisée dès lors qu'on demande une définition claire, notamment parce que les propres termes qui la composent sont faussement simples.

"Big", tout d'abord, est un adjectif quantitatif, il vient désigner une quantité de contenus, de données et donc d'information, particulièrement grande, grosse ou conséquente. Mais que veut dire "grand ou conséquent" aujourd'hui ? À partir de quand devient-on "Big"? Ce qui caractérise ce "big data", c'est que sa masse est tellement importante, et qui plus est exponentielle, qu'elle n'est désormais plus appréhendable par l'esprit humain. Elle dépasse complètement les capacités humaines d'analyse (et d'ailleurs même celles des outils informatiques classiques, c'est pour cette raison d'ailleurs que l'on va avoir recours à des outils algorithmiques, comme on le verra la semaine prochaine).


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

### Données vs Information
* La définition et la collecte d'une donnée sont arbitraires
* Une (bonne) information doit :
  - Avoir un intérêt pour le public (cf. loi des proximités)
  - Être factuelle (information n’est pas opinion)
  - Reposer sur des sources traçables, identifiables, vérifiables

===

Une seconde difficulté tient dans le terme de "data", que l'on traduit en français par "donnée", et qui est en quelque sorte un faux-ami, puisqu'il nous laisse croire en une certaine objectivité qui serait propre à ladite donnée.

En effet, dans sa définition la plus générale, une donnée désigne un fait ou un élément "brut", qui n'a pas encore été traité ou mise en contexte - c'est ce qui la distingue d'ailleurs de l'information.

Une information sera une donnée interprétée et médiatisée, recontextualisée.

Un exemple très simple : si je suis météorologue, je vais m'appuyer sur un ensemble de données telles que la température, la puissance et le sens du vent, la pression atmosphérique. les précipitations, etc. Tous ces éléments peuvent être considérés comme des données. Si je décide de faire un bulletin météo, je vais alors mettre ces données en relation pour tenter d'en tirer une synthèse voire une interprétation. Afin de diffuser ma synthèse au public, je vais l'organiser avec des visualisations, une narration. Mes données deviennent alors une information.

Si la distinction entre donnée brute et information interprétée et contextualisée est donc importante, il faut tout de même se méfier d'une tendance qui attribue à la donnée une objectivité pure. La donnée, justement, n'est pas toujours "donnée" : elle est construite, arbitraire. Pour savoir que je dois connaître la pression atmosphérique afin de faire un bon bulletin météo, cela exige des connaissances préalables. Une donnée s'appuie donc toujours sur un choix, une connaissance en amont, qui exige que l'on choisisse d'analyser tel aspect du réel plutôt qu'un autre.

Si la donnée n'est donc pas toujours objective, c'est encore moins le cas d'une information (dans le sens d'une nouvelle) transmise par un journaliste, un media ou une personne.

En journalisme, Une information digne de ce nom doit obéir à un trois impératifs fondamentaux :
- Avoir un intérêt pour le public (cf. loi des proximités)
- Être factuelle (information n’est pas opinion)
- Reposer sur des sources traçables, identifiables, vérifiables


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->


### Données numériques
* Donnée : représentation d'une information dans un programme informatique
* *Big data* : explosion quantitative de la production / stockage des données
* Données personnelles :

>"toute information relative à une personne physique identifiée ou qui peut être identifiée, directement ou indirectement, par référence à un numéro d'identification ou à un ou plusieurs éléments qui lui sont propres" (définition légale)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


===
On a vu la semaine passée la différence entre une donnée et une information : Dans sa définition la plus générale, une donnée désigne un fait ou un élément "brut", qui n'a pas encore été traité ou mise en contexte - qui n'est donc pas encore transformée en information.

Dans le domaine plus précis de l'informatique, une donnée est la représentation d'une information dans un programme : une donnée peut donc être du texte, du son, une image, etc.

Avec le développement et la démocratisation des outils numériques, en particulier du web, l'ensemble des données produites et stockées sur les serveurs est devenu si volumineux qu'il dépasse de loin les capacités humaines d'analyse et même celles des outils informatiques classiques. Cette masse d'informations, de données, est appelée le *big data*.

>L’explosion quantitative (et souvent redondante) de la donnée numérique contraint à de nouvelles manières de voir et analyser le monde. De nouveaux ordres de grandeur concernent la capture, le stockage, la recherche, le partage, l'analyse et la visualisation des données. (Wikipédia)

Une donnée à caractère personnel ou DCP (couramment « données personnelles ») correspond en droit français à toute information relative à une personne physique identifiée ou qui peut être identifiée, directement ou indirectement, par référence à un numéro d'identification ou à un ou plusieurs éléments qui lui sont propres : Loi n° 78-17 du 6 janvier 1978 relative à l'informatique, aux fichiers et aux libertés, article 2.

On voit donc les problèmes poindre : sur le web, aujourd'hui, les contenus et les données sont publiés et circulent en masse. Il y a trop de données, potentiellement d'Ailleurs des données personnelles, dont on ne maîtrise plus les flux et dans lesquelles on peut se perdre.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Indexation et métadonnées
* Qu'est-ce qu'une métadonnée ?
  * Une métadonnée est littéralement une donnée sur une donnée. Il s'agit d'un ensemble structuré d'informations décrivant une ressource quelconque, en vue de retrouver cette ressource parmi d'autres.

===
De manière générale, pour s'y retrouver dans une masse d'informations ou de document, de données (informatique ou non), nous avons recours à un processus d'indexation.
Le mot « indexation » fait référence à des processus de représentation de l'information. Pour indexer des contenus, documents ou données, nous avons donc créé les métadonnées. Une métadonnée est littéralement une donnée sur une donnée. Il s'agit d'un ensemble structuré d'informations décrivant une ressource quelconque, en vue de retrouver cette ressource parmi d'autres.

Les métadonnées sont la carte d’identité d’un document. Elles permettent de l’identifier, de le décrire, d’expliquer l’origine de sa création, son utilité et ses destinataires.

Au-delà de cette seule description, elles facilitent la recherche et le partage des ressources, la gestion de collections, leur préservation autant que la gestion des droits et l’authentification des documents.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/metadonneePage.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->


===

* Métadonnées embarquées (balise d'une page web)


Dans un contexte numérique, les métadonnées sont présentes soit de manière embarquée : elles font partie du document, en étant incluses par exemple dans un fichier informatique : photo, logiciel, document, ….

Il faut envisager le web comme une sorte de grosse bibliothèque : comment retrouver des contenus ? Tt simplement grâce à leur indexation. Il est important, ainsi, de façonner des contenus qui soient toujours bien indexés. Cette indexation permet aussi d'assurer la pérennité des contenus.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->

### Les types de métadonnées :
* métadonnées de gestion permettant d’accéder au document (auteur, titre, date de création, date de modification, langue…) ;
* métadonnées de description, pour en comprendre le contenu (sujet, description) ;
* métadonnées de préservation, pour garantir la pérennité de l’accès et de la compréhension du document (droits, format du fichier, source, résolution, relation, couverture…).

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

## Données et métadonnées : une gestion qui nous échappe
* Les données collectées à notre insu
* Les données personnelles dont nous ne sommes pas propriétaires

===

Sachant que ces métadonnées d'indexation sont, parfois, créées à notre insu : d'où un certain nombre de problèmes potentiels.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/tweetmetadata.png" data-background-size="contain" -->

===
Vous serez surpris par tout ce que vos tweets peuvent révéler de vous et de vos habitudes
Une analyse de l’activité des comptes Twitter

Comme tous les réseaux sociaux, Twitter sait beaucoup de choses sur vous, grâce aux métadonnées. En effet, pour un message de 140 caractères, vous aurez plus de 30 métadonnées, plus de 20 fois la taille du contenu initial que vous avez saisi ! Le texte d’un tweet représente moins de 10% de l’information.

Et vous savez quoi ? Presque toutes les métadonnées sont accessibles par l’API ouverte de Twitter.
Voici quelques exemples qui peuvent être exploités par n’importe qui (pas seulement les gouvernements) pour pister quelqu’un et en déduire son empreinte numérique :

Fuseau horaire et langue choisie pour l’interface de twitter
Langues détectées dans les tweets
Sources utilisées (application pour mobile, navigateur web…)
Géolocalisation
Hashtags les plus utilisés, utilisateurs les plus retweetés, etc.
Activité quotidienne/hebdomadaire

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover" -->

## L'organisation algorithmique
* Dominique Cardon :
  * *La démocratie Internet* (2010)
  * "Dans l'esprit du PageRank. Une enquête sur l'algorithme de Google" (2013)
  * *À quoi rêvent les algorithmes ?* (2015)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

===


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


### Qu'est-ce qu'un algorithme ?
Un algorithme désigne une suite d’instructions qui, une fois exécutée correctement, conduit à un résultat donné...
Une recette de cuisine est, en un sens, un algorithme. En informatique, les algorithmes s’efforcent de nous suppléer dans de nombreuses tâches en réalisant à notre place une série d'opérations fastidieuses, notamment la sélection, le tri et la hiérarchisation de l’information.


===

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/recette.JPG" data-background-size="contain" -->


===

Avez-vous déjà ouvert un livre de recettes de cuisine ? Avez vous déjà déchiffré un mode d’emploi traduit directement du coréen pour faire fonctionner un magnétoscope ou un répondeur téléphonique réticent ? Si oui, sans le savoir, vous avez déjà exécuté des algorithmes.
Plus fort : avez-vous déjà indiqué un chemin à un touriste égaré ? Avez vous fait chercher un objet à quelqu’un par téléphone ? Ecrit une lettre anonyme stipulant comment procéder à une remise de rançon ? Si oui, vous avez déjà fabriqué – et fait exécuter – des algorithmes.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain"-->
<!-- .slide: class="hover"-->

### Les biais algorithmiques
* Un algorithme n'est pas neutre
* Un algorithme n'est pas une émanation machinique : il a été programmé par les humains

===

* De nombreux travaux montrent combien les algorithmes ont tendance à :
  - reproduire les préjugés
  - encourager des comportements sociaux discriminants (sexisme, racisme)

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

>Les algorithmes qui permettent de hiérarchiser les informations enferment des principes de classement et des visions du monde. Ils structurent très profondément la manière dont les internautes voient les informations et se représentent le monde numérique dans lequel ils se promènent, sans toujours soupçonner le travail souterrain qu’exercent les algorithmes sur leur itinéraire.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===
Représenter, c'est structurer, en particulier dans le cas de l'algorithme

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

### Les quatre familles d'algorithmes
* *à côté du web* (mesure d'audience et popularité des sites)
* *au-dessus du web* (algorithme de hiérarchisation de l’autorité)
* *dans le web* (algorithme de mesure de réputation)
* *au-dessous* (algorithme prédictif)
===

Cardon distingue quatre familles de calcul numérique, différenciées à la fois selon leur positionnement figuratif par rapport à l’objet du calcul et selon leur principe de référence

* *à côté du web* (ordonnent la popularité des sites)
* *au-dessus du web* (hiérarchisent l’autorité des sites,
* *dans le web* (les mesures de réputation des personnes et des choses)
* *au-dessous*, les calculs qui cherchent à déchiffrer le comportement d’un internaute à travers une prédiction déduite du comportement d’un autre internaute.

La popularité, l’autorité, la réputation, la prédiction, voilà les quatre valeurs fondamentales qui sont à la fois productrices et produits des différents types d’algorithmes qui, dans les plateformes actuelles, s’intègrent l’un à l’autre et dont Cardon esquisse l’histoire.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

### Algorithme de mesure d'audience
* dit "à côté du web"
* calcule le nombre de "clics" ou de "vues"
* exemple : médiamétrie, affichage publicitaire, google analytics

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/GAateliers.png" data-background-size="contain" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/gaAtelier2.png" data-background-size="contain" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

* De la visite au "visiteur" unique (adresse IP)

>Déjà imparfaite dans le monde de la télévision, cette mesure révèle de redoutables imprécisions lorsqu’elle est appliquée au web. Car cette méthode ne sait jamais très bien qui se trouve derrière l’ordinateur familial. Elle suppose que les parcours multiples, rapides et enchevêtrés d’une navigation sur le web équivalent à une information lue, vue ou entendue dans les médias traditionnels.
<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===

Modèle primitif, né dès les 1990's qd on cherchait à connaître le nombre de visites.
Inspiré des mesures de médiamétrie traditionnelles, liés aux médias de masse comme la TV

Soumis aux pressions concurrentielles d’un marché publicitaire qui paie peu, les sites d’informations cherchent à attirer de l’audience à travers des contenus divertissants « attrape-clics » (pratique qualifiée de clickbait).

la médiocrité de la mesure d’audience a contribué à la chute des tarifs publicitaires sur Internet. Mais cette métrique présente, pour les annonceurs, un autre défaut. Comme l’affichage publicitaire classique, elle enregistre la fréquentation des sites et non l’efficacité des messages.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/clickbait-quiz-1.jpg" data-background-size="contain" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

### Algorithme de hiérarchisation de l'autorité
* dit "au-dessus" du web
* établit l'autorité d'un site en fonction du nombre d'hyperliens qui pointent vers lui
* Exemple : PageRank (moteur de recherche Google) ; Wikipédia (plus une page est "*linkée*", plus elle est considérée comme fiable)

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/google.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->

* Comment retrouver un document ?
* Du classement lexical (recherche par mot-clés) à l'indice de citation (force sociale de la page)

===
Problème : comment trouver un document sur le web, qd des millions de documents sont publiés chaque jour ?


Avant Google, les premiers moteurs de recherche (Lycos, Alta Vista) étaient lexicaux : ils classaient mieux les sites qui contenaient le plus de fois le mot-clé de la requête de l’utilisateur dans leurs pages.

Les créateurs de Google vont opter pour une tout autre stratégie : plutôt que de demander à l’algorithme de comprendre ce qui dit la page, ils vont proposer de mesurer la force sociale de la page dans la structure du web.


L’algorithme du moteur de recherche ordonne les informations en considérant qu’un site qui reçoit d’un autre un lien reçoit en même temps un témoignage de reconnaissance qui lui donne de l’autorité.
il classe les sites à partir d’un vote censitaire au fondement méritocratique.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/PageRank-hi-res.png" data-background-size="contain" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

* De la sagesse des foules à l'intelligence collective ?

>Dans son principe initial, le PageRank, l’algorithme qui a fait la fortune de Google, considère que les liens hypertextes enferment la reconnaissance d’une autorité : si le site A adresse un lien vers le site B, c’est qu’il lui accorde de l’importance. Qu’il dise du bien ou du mal de B n’est pas la question ; ce qui importe est le fait que A ait jugé nécessaire de citer B comme une référence, une source, une preuve, un exemple ou un contre-exemple.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->


Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

* Les limites de la méritocratie

>Les lecteurs silencieux sont oubliés et le dénombrement des liens n’a rien du vote démocratique. Plus un site est cité par les autres, plus la reconnaissance qu’il adresse à d’autres a de poids dans le calcul d’autorité. Empruntée au système de valeurs de la communauté scientifique et notamment aux classements des revues scientifiques qui donnent plus de poids aux articles les plus cités par les autres, cette mesure de reconnaissance a spectaculairement prouvé qu’elle constituait l’une des meilleures approximations possible de la qualité des informations.

<!-- .element: style="font-size:1.6rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

>Alors que les journalistes filtrent l’information sur la base d’un jugement humain avant de la publier, les moteurs de recherche (ainsi que Google News) filtrent a posteriori une information déjà publiée sur la base des jugements humains émis par l’ensemble des internautes qui publient sur le web.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


* Détournement et optimisation : une valse sans fin
>À la manière de la claque théâtrale, les stratèges du marché du référencement paient ou fabriquent des sites qui citent leurs clients : ils placent des liens vers le site cible dans les commentaires de blogs, glissent subrepticement un lien dans Wikipédia, créent des « fermes » de faux sites liés les uns aux autres pour adresser ensuite un lien hypertexte vers la cible, produisent de faux contenus (parfois produits par des robots) pour tromper l'algorithme. La plupart de ces techniques sont aujourd’hui devenues inefficaces en raison des modifications incessantes que Google apporte à l’algorithme pour décourager ceux qui essaient de tromper son classement. Mais ce jeu du chat et de la souris entre les webmestres et les concepteurs de l’algorithme est sans fin.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/like.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Algorithme de mesure de réputation
* dit "dans le web"
* utilise les compteurs valorisant la réputation des personnes et des choses (les "*like*")
* exemple : les réseaux sociaux

===

"les réseaux sociaux d’Internet proposent-ils d’éclater les classements, afin de les réorganiser par affinités autour du cercle d’« amis » ou de followers que s’est choisi l'internaute"


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/like.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->

* Je suis donc je "like"
>Alors que Google cherche à cacher le calculateur au-dessus du web afin que les internautes ne s’en emparent pas, les métriques de réputation du web social le glissent dans le web pour que les internautes se mesurent eux-mêmes. Le symbole de ces nouveaux calculs est le like de Facebook, pointe avancée d’un ensemble beaucoup plus large et disparate d’indicateurs mesurant la taille des réseaux personnels par le nombre d’amis, la réputation acquise en fonction du nombre d’informations publiées que d’autres internautes ont ensuite commentées ou partagées, le nombre de fois où le nom de l’internaute a été prononcé dans la conversation des autres, etc.

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


* Le sacre de l'"influenceur"
>Le web social de Facebook, Twitter, Pinterest, Instagram, etc., s’est ainsi couvert de chiffres et de petits compteurs, des « gloriomètres », pour reprendre une expression de Gabriel Tarde. Alors que dans le monde de l’autorité, la visibilité se mérite, dans celui des affinités numériques, elle peut se fabriquer. Façonner sa réputation, animer sa communauté d’admirateurs ou anticiper la viralité de ses messages constitue même un savoir-faire valorisé. (Dominique Cardon, *À quoi rêvent les algorithmes*)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/influenceur.png" data-background-size="contain" -->


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

* Le règne de l'évaluation
>Dans le cas des biens culturels, comme l’évaluation des films cinématographiques, les notes ont plus d’importance qu’une collection d’avis singuliers9. Lorsque l’évaluation du bien comporte des aspects techniques, la parole d’experts est préférée à l’agrégation des notes de consommateurs peu compétents. La démocratisation de l’évaluation profane associe l’idée de pouvoir tout noter à celle de faire noter tout le monde. (Dominique Cardon, *À quoi rêvent les algorithmes*)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

* Tous dans sa bulle (de filtres) ? (Eli Pariser)
  - filtrage de l'information en fonction de notre "profil"
  - isolement intellectuel et culturel
  - un bulle construite par nos choix + les algorithmes


===
La bulle de filtres1 ou bulle de filtrage (de l’anglais : filter bubble) est un concept développé par le militant d'Internet Eli Pariser. Selon Pariser, la « bulle de filtres » désigne à la fois le filtrage de l'information qui parvient à l'internaute par différents filtres ; et l'état d'« isolement intellectuel » et culturel dans lequel il se retrouve quand les informations qu'il recherche sur Internet résultent d'une personnalisation mise en place à son insu.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/bulle.jpeg" data-background-size="contain" -->


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/predictif.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Algorithme prédictif
* dit "sous le web"
* utilise des méthodes statistiques pour calculer / prédire, à partir des traces de nos navigations, nos comportements
* exemple : recommandation Netflix, Amazon, sites d'achat en ligne, publicité ciblée

===

les mesures prédictives destinées à personnaliser les informations présentées à l’utilisateur déploient, sous le web, des méthodes statistiques d’apprentissage pour calculer les traces de navigation des internautes et leur prédire leur comportement à partir de celui des autres.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/predictif.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->


* Collecte de données / traces disséminées par l'internaute
* Machine learning (personnalisation du calcul à partir de la comparaison des comportements des internautes)


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/predictif.jpeg" data-background-size="contain" -->
<!-- .slide: class="hover"-->


>À grand renfort de travaux de psychologie et d’économie expérimentales, les architectes des nouveaux algorithmes des big data assurent qu’il ne faut faire confiance qu’aux conduites réelles des individus, et non à ce qu’ils prétendent faire lorsqu’ils se racontent sur les très expressives plateformes du web social. Les régularités globales observées sur de grandes masses de traces doivent permettre d’estimer ce que l’utilisateur risque de faire
réellement. Les algorithmes prédictifs ne donnent pas une réponse à ce que les gens disent vouloir faire, mais à ce qu’ils font sans vouloir vraiment se le dire. (Dominique Cardon, *À quoi rêvent les algorithmes*)


<!-- .element: style="font-size:1.7rem; text-align:justify" -->

Source : Dominique Cardon, *À quoi rêvent les algorithmes ?*

<!-- .element: class="source" -->

===

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/youtube.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->

* Les algorithmes prédictifs : outils marketing des industries culturelles
* Prédiction ou prescription ?


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Comprendre la structuration du web : un enjeu ontologique et politique
* Toute médiation joue un rôle structurant et déterminant dans la construction du réel
* Nous construisons des outils pour calculer, structurer, organiser le web...
* Ces calculateurs, en retour, nous construisent à leur tour...

===
En résumé, comprendre le web est un enjeu ontologique et politique.
Je me répète : Le Réel est toujours médié - il n'est donc pas question de dire ici que le numérique est une médiation pire que les autres... Mais puisque toute médiation cherche par nature à se faire oublier, à se rendre transparente, on oublie qu'elles ont un rôle structurant et même déterminant sur le réel. C'est la fonction performative des médias et des représentations.
En raison même de cette tendance à la superposition entre le monde tel qu'il est représenté et ses conceptions, il nous faut au moins être capable de comprendre comment la représentation du monde contemporain s'effectue.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/photolit.png" data-background-size="contain" -->
<!-- .slide: class="hover"-->

### Maîtrise de la déprise
* Bien structurer les contenus (en vue de leur organisation / appropriation) = métadonnées
* Comprendre les logiques de recherche / indexation = algorithmes

===
Alors évidemment, un premier comportement pourrait nous pousser vers un rejet total des nouvelles technos... Mais bon, nous n'avons pas tout à fait le choix : on voit bien aujourd'hui qu'elles sont très utiles. Et surtout, la technophobie ne semble pas être une solution sage au long terme.

L'enjeu sera plutôt de maîtriser la déprise imposée par certains outils. La déprise, c'est le fait que nécessairement le fonctionnement de certains outils nous échappe. La maîtrise de cette déprise, c'est de trouver de quoi compenser cette déprise. La première chose : c'est l'éducation ! La connaissance des outils que l'on utilise.s

La fameuse littératie numérique : non pas savoir coder, mais comprendre les présupposés épistémologiques qui guident la construction des outils que nous utilisons chaque jour.

Première leçon, sorte de pré-requis à l'algorithme, c'est la métadonnée.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


>Comme les GPS dans les véhicules, les algorithmes se sont silencieusement glissés dans nos vies. Ils ne nous imposent pas la destination. Ils ne choisissent pas ce qui nous intéresse. Nous leur donnons la destination et ils nous demandent de suivre "leur" route. La conduite GPS s'est si fortement inscrite dans les pratiques des conducteurs que ceux-ci ont parfois perdu toute idée de la carte, des manières de la lire, de la diversité de ses chemins et des joies de l'égarement.
Les algorithmes [procèdent] d'un désir d'autonomie et de liberté. Mais ils contribuent aussi à assujettir l'internaute à cette route calculée, efficace, automatique, qui s'adapte à nos désirs en se réglant secrètement sur le désir des autres. Avec la carte, nous avons perdu le paysage. Le chemin que nous suivons est le "meilleur" pour nous. (Dominique Cardon, *À quoi rêvent les algorithmes*)

<!-- .element: style="font-size:1.7rem; text-align:justify" -->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

## Conclusion
Comment le web est-il construit ? Comment, en d'autres termes, se structure le media qui constitue aujourd'hui notre fenêtre sur le monde, et qui participe à structurer le réel ? L'organisation des contenus sur le web passe par des outils - métadonnées, algorithmes - dont les concepteurs, humains, laissent une signature. Le résultat d'une recherche, d'une navigation, n'est donc jamais neutre. Connaître le fonctionnement de l'indexation est essentiel pour être conscient des biais dans l'organisation des contenus sur les moteurs de recherche ou les grandes plateformes. C'est tout le sens d'une littératie numérique : utiliser en toute conscience, en connaissance de cause, des outils qui font désormais partie de notre quotidien. C'est enfin le sens d'une "maîtrise" de la "déprise".

<!-- .element: style="font-size:1.7rem; text-align:justify" -->
