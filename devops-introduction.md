---
theme: 'black'
transition: 'slide'
# highlightTheme: "darkula"
slideNumber: false
separator: '^\r?\n---\r?\n$'
verticalSeparator: '^\r?\n--\r?\n$'

# logoImg: "soat/LOGO_COULEUR_BLANC_BASELINE.png"
logoImg: ''
customTheme: 'soat'
# custom_theme = "reveal-hugo/themes/custom-theme.scss"
# custom_theme_compile = true
# Navigation arrows
controls: false
#controlsLayout: 'edges'
progress: true

# Display the page number of the current slide
showNotes: false

# Vertical centering of slides
center: true
---

# DevOps

## Journée d'acculturation

<!-- .slide: class="title" -->
<!-- .slide: data-state="title-page"-->

---

## Agenda

- Introduction
- DevOps is / DevOps is not
- Lego 4 DevOps (Atelier)
- Concepts
- Impacts
- Bénéfices
- Démo / REx
- World Café (Atelier)
- Conclusion

<!-- .slide: class="title" -->
<!-- .slide: data-state="title-page"-->

---

## Introduction

<!-- .slide: data-state="chapter-page"-->

--

### Origines

#### Cousin du mouvement Agile

#### Le mur de la confusion

---

## Lego 4 Devops (Atelier)

<!-- .slide: data-state="chapter-page"-->

---

## Concepts

<!-- .slide: data-state="chapter-page"-->

--

### Besoin

--

### Facteur Humain

--

### Processus

--

### Outils

---

## DevOps is / DevOps is not

<!-- .slide: data-state="chapter-page"-->

--

### DevOps is

--

### DevOps is

> Centré sur le produit utilisateur

Note:
La qualité et la pertinence du produit fourni à l'utilisateur final est la seule chose qui importe.

--

### DevOps is

> Se concentre sur une réalisation minimal apportant un maximum de valeur

Note:
Toute réalisation doit être itérative, pour accélérer l'arrivée de la boucle de feedback. En ce sens, on doit chercher le plus petit élément de réalisation qui apporte le maximum de valeur.

--

### DevOps is

> Réduit la documentation à sa plus juste utilité

Note:
Elle peut même être remplacée par le partage des outils, des méthodes, du même espace de travail et les rituels de partage de connaissance (stand up meeting, peer-programming, démo).

--

### DevOps is

> You build it, you run it
>
> -- _Werner Vogels_

Note:
Les Dev et les Ops sont (co-)responsable de ce qui arrive en Prod (y-compris dans les astreintes).

--

### DevOps is

> Les Ops sont des facilitateurs, non des limiteurs

Note:
Dans les domaines dont il est le garant, l’OPS doit être facilitateur (par son savoir-faire) et non-pas censeur.

--

### DevOps is

> Measure Anything, Measure Everything
>
> -- _Etsy_

Note:
L’obsession de la mesure et de la traçabilité. Ce qui ne se mesure pas n’est qu’affaire d’opinion.

--

### DevOps is

> Plan, do, check, act (PDCA)

Note:
L'amélioration continue : cette démarche est basée sur l'expérimentation perpétuelle et la mesure du résultat qui en ressort.

--

### DevOps is

> Refus de l'over-engineering

Note:
Il s’agit de garder un certain pragmatisme dans les fonctionnalités réalisées. Ne pas développer un tableau de bord d’Airbus quand une calculette suffit. Prenons l’exemple du principe de KISS (Keep it simple, stupid, Keep it Smart & Simple)

--

### DevOps is

> Testabilité

Note:
Toute réalisation n'est achevée que lorsque le test garantissant la conformité de son fonctionnement est associé.

--

### DevOps is

> Tolérance aux pannes

Note:
Les Pannes et les erreurs humaines sont inévitables. Par design, on doit les circonscrire et mettre en place les contre-mesures qui rendent ces pannes indolores.

--

### DevOps is not

--

### DevOps is not

> Un outil permettant de tout gérer

Note:
Le partage d'outils doit répondre à un besoin de coopération et d'autonomie et pas seulement au besoin d'industrialisation ou de respect des standards.
L'usage d'un outil fréquemment utilisé dans les organisations DevOps n'est ni nécessaire ni suffisant pour faire du DevOps, mais vous vous apercevrez que sans c'est quand même bien plus compliqué.

--

### DevOps is not

> no-Ops

Note:
L'automatisation est un vecteur d'autonomisation des acteurs et d'amélioration des opérations. Le DevOps ne doit en aucun cas être compris comme un moyen de se décharger de sa responsabilité.

--

### DevOps is not

> Les Devs ont tous les droits

Note:
Le DevOps est un mouvement favorisant la coopération, pas le remplacement des Ops par des Dev.
Il arrive que certains Dev aient besoin de privilèges, comme des droits d'accès par exemple. Mais par nature même, le DevOps doit minimiser ce besoin.
L'idée n'est pas d'autoriser tous les Dev à accéder aux ressources critiques, et pour cela il est nécessaire de bien cadrer le besoin.

--

### DevOps is not

> Faire coder les Ops & administrer des machines aux Dev

Note:
Le DevOps n'implique pas la polyvalence de tous les acteurs. La coopération étroite ne doit pas donner lieu à une inversion des rôles. C'est au contraire une façon de reconnaître les forces et les faiblesses de chacun et d'en tirer le meilleur, collectivement.

--

### DevOps is not

> Un Rôle

Note:
Contrairement à une erreur répandue, le DevOps n'est pas un rôle. Comme nous le définissons toute la journée, il s'agit d'un mouvement englobant les devs et les ops.

--

### DevOps is not

> Une nouvelle équipe

Note:
Comme DevOps n'est pas un role, il ne peux etre non plus une équipe. Le but de cette démarche est de rapprocher et d'améliorer la communication entre les Dev et les Ops. Rajouter une équipe entre les deux serait donc aller à l'encontre de cela.

---

## Impacts

<!-- .slide: data-state="chapter-page"-->

Note:
Le DevOps arrive seconde vague de l'émergence de l'agilité au sein des équipes projets, du cloud et des outils type conteneurs.
Le déclencheur est donc le suivant : un choc de productivité et d’agilité.
Les DSI sont-elles prêtes à s'adapter à ce nouvel écosystème ?
On notera que, plus que la DSI elle-même, dans son rôle global, ce sont ses structures internes - directions de l’ingénierie, de l’infrastructure informatique et de la production informatique - qui sont secouées par ces évolutions.

--

### Impacts organisationnels

- Collaboration
- Automatisation
  - automatisation du déploiement
  - intégration continue
  - automatisation de l'infrastructure
- Outils
- Plateformes

Note:
La collaboration doit être inscripte dans les process de gestion de projets (intégration des Ops et Sec tout au long du cycle de vie projet)
Besoin d'outils de gestions de tickets, de code source, d'automatisation de test et de livraison
Besoin de plateformes adaptées (Cloud, Conteneurs, ...) pour faciliter l'automatisation

--

### Impacts humains

- Faire accepter le changement
- Culture du partage

Note:
Chaque acteur du projet garde sa compétence et son expertise mais doit partager ses contraintes et collaborer au maximum

---

## Bénéfices

<!-- .slide: data-state="chapter-page"-->

--

### Bénéfices organisationnels

- Résolution des points de contention
- Performance
  - nombre de déploiements de code
  - délai de bascule du commit au déploiement
  - taux d'échec
  - stabilité des systèmes
- Amelioration continue
  - automatisation de la validation des changements
  - visualisation des métriques de productivité et de qualité
- Flexibilité et agilité

Note:
Les entreprises recourent au DevOps pour résoudre les points de contentions. Ces derniers varient en fonction de la responsabilité des équipes IT, chacun voyant un intérêt particulier à installer une approche DevOps.

- Rapidité et sécurisation de livraison de valeur
  - Accélération des livraisons et déploiements
  - Sécurisation des livraisons et déploiements
- Les pratiques d’amélioration continue (lean) sont des optimisations une fois mis en place les éléments précédents.

--

### Bénéfices humains

- Efficacité
- Estime de soi
- Confiance
- Engagement
- Collaboration
- Montée en compétence (cross-skilling)
- Respect du top-management

Note: Globalement il s'agit du moral des équipes
Mieux les équipes communiquent, mieux elles travaillent ensemble
Et plus elles travaillent ensemble, plus elles sont heureuses.

--

### Bénéfices business

- Time-to-market
- Customer experience
- Résolution de problèmes
- Temps pour l'innovation

Note:
Time-To-Market
- Amélioration du temps nécessaire à la livraison de résultats
- C'est probablement le bénéfice que les utilisateurs ou PO comprennent le mieux
Customer experience
- 70% des DSI remontent une aélioration de l'XP utilisateur après la mise en place du DevOps
Résolution de problèmes
- Plus un problème est olng à résoudre, plus la société perd d'argent
Innovation
- plus les process sont rodées et efficaces, plus vos équipes auront de temps dégagé pour brainstormer et déveloper de nouvelles idées, et plus l'expérimentation sera aisée et rapide



---

## Démo / REx

<!-- .slide: data-state="chapter-page"-->

---

## World Café (Atelier)

<!-- .slide: data-state="chapter-page"-->

---

## Conclusion

<!-- .slide: data-state="chapter-page"-->
