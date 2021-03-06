Évolutions envisagées
=====================

Ce fichier récapitule les principales évolutions envisagées par rapport à la version actuelle du site.


Concepts généraux
-----------------

### Rubriques

À l'heure actuelle, les « sections » sont tellement nombreuses qu'au lieu de regrouper les articles traitant différent sujets d'un même domaine, elles cloisonnent à l'extrême. On en compte aujourd'hui 77 (!), basiquement une par distribution et par langage de programmation... Les sections sont donc utilisées comme des tags alors que cette autre fonctionnalité est implémentée par ailleurs (on y reviendra après).

Il paraît nécessaire de rebrasser tout ça vers des rubriques moins nombreuses. Ces rubriques devront être suffisament vastes pour qu'elles soient porteuses de sens et suffisamment diverses pour refléter la diversité des contenus présents sur le site. En gros, je vois ça comme un moyen de clarifier le positionnement de linuxfr.org sur la toile. Peut-être avez-vous des idées là-dessus, en attendant je verrais le classement suivant :

- applications & services
- distributions & bureaux
- culture & jeux
- systèmes & réseaux
- bidouille & développement
- économie & entreprise
- revue de presse

> Ça fait beaucoup de &

### Tags

Les tags servent à identifier les différentes thématiques abordées par un même article. Ils servent à faire des passerelles entre des contenus répartis dans différentes sections. Ils ont donc une utilité un peu différente de ces dernières. C'est pas choquant qu'on en ait un nombre élevé.

L'actuel système comporte des tags privés et des tags publics. Comment savoir, lorsque j'ajoute un tag, son périmètre de diffusion ? Quelle utilité d'avoir des tags juste pour soi ?

> Apparemment, la réponse à ces deux questions est la même : on considère un tag comme intéressant pour les visiteurs à partir du moment où il est affecté à un même contenu par différentes personnes. [D'après le wiki](https://linuxfr.org/wiki/tags).

### Rubriques ou non ?

Souhaite-t-on vraiment refondre les sections et non pas juste les mettre à la poubelle, si on a les tags ?

> Les « sections » ont un autre intérêt indirect que la classification : elles amènent une image/un logo pour égayer un peu, et le fait d'en avoir beaucoup permet de varier l'image.

### Blogs

Sur la terminologie, on trouve que le mot « journaux », utilisé actuellement, prête à confusion avec les « dépêches » : pour les non habitués, il n'est pas évident qu'il s'agit de journaux personnels. On pense qu'il est plus évocateur de parler de « blogs », sur lesquels les auteurs peuvent publier des « billets ».

### Salons

Encore une question de terminologie. Le mot « tribune », qui suggère une communication à l'attention d'une foule, semblerait plus approprié pour qualifier un billet de blog qu'un canal de messagerie instantannée. C'est pourquoi on préfèrera ici parler de « salons ».


Page d'accueil
--------------

### Journaux promus

Un problème que l'on a actuellement est que lorsqu'un journal est promu en dépêche, la note et les commentaires sont perdus (au risque de refaire les mêmes discussions). Pour résoudre cela, j'avais d'abord envisagé faire en sorte que ces données restent associés à l'article initial, dont il « suffirait » de changer la nature par la suite, en la passant de journal à dépêche. Et puis en fait le plus évident pour l'utilisateur, c'est bien que les journaux qui sont promus apparaissent certes sur la page d'accueil, mais pas dans le fil des dépêches. Peut-être qu'on pourra envisager un système de badge pour repérer dans les flux de journaux ceux qui ont été promus ?

### Pied de page

Comme c'est une information secondaire, on déporte la liste des sites amis vers une page dédiée. Par contre on peut profiter de cette nouvelle page pour mettre en valeur les liens en y associant une brève présentation des sites, et dire en quoi ils sont amis avec LinuxFr.


Espace de rédaction
-------------------

### Statistiques

À l'heure actuelle, la liste des plus gros contributeurs est ostensiblement affichée dans l'espace de rédaction. J'ai peur que cela provoque l'effet inverse de celui attendu : au lieu d'attirer de nouveaux contributeurs qui voudraient rentrer dans une compétition de celui qui a la plus grosse, cela peut dissuader les nouveaux arrivants qui perçoivent ces scores comme inatteignables. On ne sait même pas ce que signifient ces scores, raison de plus pour ne pas les surexposer. On laissera donc tout ça derrière un lien « Statistiques ».

### Rédactions en cours

Tous les titres des articles en cours sont sur une colonne, pour éviter que nos infographistes préférés fassent des zigzag avec les yeux.

### Salon

J'ai remis les norloges pour défroisser les vieilles moules. Pour les êtres humains normaux, j'ai accompagné la norloge d'un bouton répondre. Il faut encore élaborer ce à quoi ça doit ressembler quand on utilise cette fonctionnalité justement. Pour que la faible largeur de la colonne ne soit pas trop limitante, le champ de saisie de texte s'allonge verticalement au fur-et-à-mesure qu'il est rempli.

### Règles de modération

Les règles de modération gagneraient à être plus digestes. C'est une excellente chose que d'expliquer pourquoi des efforts sont demandés sur tel ou tel point, par contre ça surcharge un peu la page et peut dissuader de la lire. Il serait intéressant de permettre aux rédacteurs de ne visualiser les explications que lorsqu'ils ne comprennent pas un point.


Commentaires
------------

On utilise le même mécanisme de commentaire aussi bien pour les dépêches, que les billets ou les évènements. Les forums sont un cas particulier puisque les discussions sont initiées from scratch, et ne sont pas liées à un contenu préexistant.

### Discussions

À l'heure actuelle la section commentaire permet de gérer plusieurs fils de discussion. Parfois on observe des commentaires qui rallongent indéfiniment un même fil alors que l'objet a été changé plusieurs fois. Sur nos dessins, on a retiré la possibilité de modifier l'objet lorsqu'on répond au sein d'un fil. Une alternative serait de laisser cette possibilité, mais que si elle est utilisée, un nouveau fil de discussion apparaîtra dans la zone des commentaires.

### Tri des commentaires

Lorsqu'un article contient des coquilles, c'est souvent qu'on voit toute une série de commentaires pour les signaler. Il serait intéressant de permettre de les signaler aux modérateurs de manière discrète, sans polluer les fils de discussions. J'essaierai d'intégrer ça dans les prochains dessins.

> Voir l'[entrée de suivi](https://linuxfr.org/suivi/ajouter-un-bouton-signaler-un-truc) et l'approche de [NextInpact](https://nextinpact.com)

### Identification de l'auteur de l'article

Dans les discussions, ça peut être intéressant de mettre en valeur les interventions de l'auteur de l'article (dépêche, billet...) qui a donné naissance aux discussions. Voir un [exemple ici](https://eischmann.wordpress.com/2017/04/10/netflix-blocks-fedora-users/#comments) sur Wordpress.


Forums
------

Les forums sont des espaces permettant de s'adresser à la communauté du site, typiquement afin de soliciter leur avis sur un sujet particulier. Il pourrait également permettre à la communauté de discuter de sujets au fil de l'eau, sans réagir à un article donné.

### Sondages

Un sondage est une entrée de forum particulière puisqu'il comporte un questionnaire à choix multiples (QCM) et est ouvert aussi aux non-inscrits.

### Notation

Noter le message initial d'une discussion de forum est-il utile ? Noter les réponses peut aider à identifier les solutions les plus intéressantes au problème posé.


Agenda
------

Les évènements donnant l'occasion de rassembler les différentes communautés sont suffisament importants pour justifier la création d'une section dédiée. Actuellement, linuxfr.org relaie chaque semaine les évènements publiés dans l'agendadulibre.org. D'autres évènements peuvent également être annoncés via la procédure habituelle de publication (et de modération).

Dans cette section, les visiteurs pourront :

- retrouver instantanément les prochains évènements prévus près de chez eux
- visualiser les emplacements des évènements sur une carte

Dans cette section, on pensait d'abord afficher les ressources de l'Agenda du Libre en plus de celles propres à LinuxFr. Gérer plusieurs sources de données dans le cas présent semble ajouter de la complexité sans ajouter de valeur. Au contraire, il serait intéressant que les évènements annoncés sur linuxfr.org soient remontés à l'Agenda du Libre, et donc se servir de ce dernier comme unique source d'évènements.

On ne sait pas dans quelle mesure l'intégration à l'Agenda du Libre est faisable techniquement (API ? transfert de fichiers .ics ?). Politiquement, cela n'est pas évident non plus. D'une part parce que nous n'avons pas trouvé de licence concernant les données de l'agendadulibre.org. D'autre part, les deux sites ont chacun leur propre politique de modération appliquée par des personnes différentes.

Idéalement, proposer un nouvel évènement serait possible directement depuis LinuxFr, ou bien nous redirigerions vers le site de l'Agenda du Libre. Les bénéfices attendus sont les suivants :

- les visiteurs de linuxfr auraient accès à un agenda du libre lisible et fonctionnel
- l'agenda et son filtre géographique seraient une raison supplémentaire de créer un compte sur linuxfr
- l'agenda du libre bénéficierait automatiquement des évènements remontés par linuxfr (sur lequel linuxfr n'effectuerait aucune modération)


TODO :
- suggérer à l'agendadulibre.org de diffuser ses données sous licence odbl ?
- faisabilité ?

> Une autre piste envisagée est au contraire la disparition totale de la notion d'évènement.
> Souci de ne pas voler d'audience.
> L'agenda du libre intègre une fonctionnalité de soumission de dépêche.


Style
-----

### Polices

Pour les contenus, on pourrait utilise la police système par défaut du poste client. Pour le texte propre au site (bandeaux de navigation, titre de l'espace de rédaction, etc), on utilise DéjàVu Serif.

### Palette de couleurs

Bandeau de navigation blanc et fond gris très léger sur toutes les pages. On utilise un bleu sombre pour les rubriques, on rappelle le jaune du logo, et on utilise plusieurs teintes de bleu.

> gare à ne pas remplacé le côté «fouilli sympathique» et chaleureux, par une austérité froide

### Illustrations

En dépit de nos efforts pour inciter à illustrer les articles, il ne faut pas que l'absence d'illustration soit un point de blocage pour la publication. Ça peut valoir le coup de constituer une petite collection d'images libres pour chacune des rubriques. Ensuite, les modérateurs pourraient retrouver facilement une image pas totalement déconnectée du sujet.


Pistes de réflexion
-------------------

### Modération

Pour les nouveaux venus, c'est pas évident de comprendre qu'on peut publier directement un journal d'une part, mais que la publication de dépêche est soumise à modération d'autre part.

On pourrait distinguer plusieurs phases, par exemple 3 ou 4 :

- rédaction -> relecture -> modération -> publication
- création -> rédaction -> validation

On ne veut pas non plus donner une impression de lourdeur.

### Aiguillage

La question d'où publier quoi se pose souvent, comme le montrent de nombreux débâts, par exemple concernant la longueur des dépêches ou les journaux hors-sujets. De même, lorsqu'on a une question, il peut être tentant de publier un journal plutôt qu'ouvrir une discussion sur le forum, peut-être parce que cela assure une meilleure visibilité ? D'autre part, le wiki ne semble pas énormément utilisé, peut-être parce que son objet n'est pas clair : s'agit-il d'expliquer le fonctionnement de LinuxFr.org ou bien de partager des connaissances sur des logiciels libres ?

> Les données montrent que le forum et le wiki sont largement moins utilisés que les autres sections.


### Intégration

On a discuté plus haut de l'intégration à l'Agenda du Libre. On pourrait envisager aussi l'intégration à d'autres sites, en particulier :

- [Journal du Hacker](https://www.journalduhacker.net/)

### Bloquer les utilisateurs

Dans les commentaires il y a des intervenants qui sont particulièrement pénibles, dont on aimerait ne plus voir aucun de leurs messages. Le système de karma n'est d'aucun remède. On peut envisager permettre aux utilisateurs de bloquer les personnes les plus insupportables. Pour éviter qu'un utilisateur ne voit jamais son karma baisser du fait que tout le monde l'a bloqué, on peut envisager lui retirer des points pour chaque blocage (par exemple, -20 pts par blocage).

> Fonction à désactiver pour les modérateurs !

### Notation

S'il peut inciter à publier pour marquer des points, le système de notation peut être perçu comme violent. On pourrait envisager remplacer la notation des commentaires, pour aller vers un système à la Slashdot. En associant des adjectifs à chaque commentaire, le système de slashdot permet de filtrer selon le ton des messages (All Insightful Informative Interesting Funny), plutôt que sur leur popularité.

> L'approche Slashdot n'est adaptée à notre cas : on a bien moins de visiteurs et de contenus.

