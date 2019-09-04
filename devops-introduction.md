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
- Lego 4 DevOps (Atelier)
- Concepts
- DevOps is / DevOps is not
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

---

## Lego 4 Devops (Atelier)

<!-- .slide: data-state="chapter-page" -->

---

## Origines ... la scène post-atelier

### Le mur de la confusion <!-- .element: class="fragment" data-fragment-index="1" -->

Note:
Débriefer sur l'atelier lego sur Devops

--

### Ce que veulent les Dev

- le développement de nouvelles fonctionnalités
- la qualité (non-régression, nombre de bugs réduit)
- la rapidité de mise à disposition aux utilisateurs finaux
- le feedback

Culture du **produit** en y apportant du **changement**

<!-- .element: class="fragment" data-fragment-index="1" -->

--

### Ce que veulent les Ops

- la stabilité et la robustesse,
- la maîtrise,
- la performance et la sécurité
- les possibilités d'industrialisation avec une certaine efficience économique

Culture du **service** en y apportant de la **stabilité**

 <!-- .element: class="fragment" data-fragment-index="1" -->

--

### Le mur de la confusion

![Le mur de la confusion](./media/mur-de-la-confusion.png)

Note:
Chaque équipe se reconnaît et défend la légitimité de ses propres objectifs.
Ils n'ont pas tort, et c'est la qu'il y a confusion : Ces objectifs sont des objectifs intermédiaires et non exclusifs.
C'est ce qu'on appelle le mur de la confusion.

--

### Les causes de la confusion

- objectifs non alignés
- organisation en silo de ces deux équipes
- Les équipes n'évoluent pas dans les même échelles de temps
- language et outils différents
- Méconnaissance des contraintes

---

## Concepts

DevOps **n’est pas** une **méthodologie**

<!-- .element: class="fragment" data-fragment-index="1" -->

C'est une **culture**

<!-- .element: class="fragment" data-fragment-index="2" -->

Note:
Le DevOps est né. On le définit ?

Ce que n'est pas le DevOps

DevOps est une Culture

Stop opposition Dev vs Ops

<!-- .slide: data-state="chapter-page" -->

--

### Définition

> DevOps is the union of people, process, and products to enable continuous delivery of value to our end users.
>
> -- _Donovan Brown_

<!-- .element: class="fragment" data-fragment-index="1" -->

Note:
Donovan Brown, responsable DevOps chez Microsoft

Slide la plus importante !

Lire Definition

Qui ? Pourquoi ? Comment ?

Agile++

--

### Principe Agile

> Notre plus haute priorité est de satisfaire le client en livrant rapidement et régulièrement des fonctionnalités à grande valeur ajoutée.
>
> -- _1<sup>er</sup> principe du « Manifeste agile »_

[agilemanifesto.org](https://agilemanifesto.org)

Note:
Introduire Manifeste Agile - Février 2001 naissance du manifest agile

Lire Définition

Parallèle : Continuous Delivery

Et mes objectifs ?

--

### Besoin

Apporter de la valeur aux utilisateurs finaux plus rapidement et de manière plus sécurisante :

- Réduire le **Time to Market**
- **Accélérer la boucle de _feedback_**
- **Accélérer les livraisons** en allégeant les processus
- **Garder/augmenter la fiabilité** pour minimiser l'erreur humaine
- **Amélioration continue**

Note:
Ramener à la réalité

Time-To-Market : livrer vite les nouveautés et fix

Utilisateur final : qualité feedback

Accélération VS Qualité ? Non!

Amélioration continue

--

### Facteur Humain

- partage de responsabilité
- échange
- collaboration
- confiance

- Prendre le temps de créer, d'évangéliser cette culture qu'est le DevOps et d'accompagner sa mise en place
- Co-localiser les équipes pour permettre une meilleur collaboration
- L'engagement de l'ensemble des acteurs sur la chaîne de production de valeur
- La collaboration des équipes plutôt que le protectionnisme
- Le partage d'informations et de responsabilités

note:
engagement: objectif commun et partagé
partage = communication

--

### Processus

- Plus d'échange au plus tôt afin de connaitre les besoins et contraintes des équipes
- première boucle de feedback

--

### Outils

- Outils de communication (tickets, discussion, meetings, ...)
- Methodologies communes
- Partager des livrables communs et acceptés de tous, qu'il soient documentaires ou binaires
- Automatisation
- Chaine d’intégration et de livraison continue

---

### CALMS

- Culture
- Automatisation
- Lean
- Mesure
- Solidarité

Note:
"Lean" => Amélioration continue

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

## Continuous Delivery

<!-- .slide: data-state="chapter-page"-->

Note:
Rappel DevOps: union des gens, des process et des outils pour délivrer RAPIDEMENT de la valeur aux utilisateurs finaux.
Un processus de livraison continu implique de pouvoir livrer à tout moment, avec une qualité élevée. Cela contraste avec ce que l'on peut voir en général.

--

## Continuous Delivery: Pourquoi ?

On peut publier le correctif ?

<!-- .element: class="fragment" data-fragment-index="1" -->

- NON! Fred est en vacances et c'est lui qui a les droits<!-- .element: class="fragment" data-fragment-index="2" -->
- NON! Nous n’avons pas terminé le cycle complet d’assurance qualité<!-- .element: class="fragment" data-fragment-index="3" -->
- NON! Le processus de publication n'est pas clair<!-- .element: class="fragment" data-fragment-index="4" -->

Note:
Prenons l'exemple d'une application mobile.
NON! Fred est en vacances et il est le seul membre de l’équipe à pouvoir créer, signer pour distribution et déposer sur le store.
NON! Nous n’avons pas terminé le cycle complet d’assurance qualité de la branche principale actuelle et il faudra trois jours pour effectuer les tests de régression manuels. En passant, qui a un iPhone 4S sous iOS 9.2 pour faire un test?
NON! Nous ne savons pas exactement combien de temps le processus de publication prend; la validation peut prendre entre 5 et 12 jours.
Cela vous semble familier?

--

## Continuous Delivery: Et chez vous ?

- À quelle fréquence publiez-vous des mises à jour?<!-- .element: class="fragment" data-fragment-index="1" -->
  - Quelques fois par an? Trimestriel? Mensuel, bi-hebdomadaire? Tous les jours? Plusieurs fois par jour?<!-- .element: class="fragment" data-fragment-index="2" -->
- C'est absurbe, non ?<!-- .element: class="fragment" data-fragment-index="3" -->
- Vraiment ?!<!-- .element: class="fragment" data-fragment-index="4" -->

Note:
Pensez à l'une de vos applications. À quelle fréquence publiez-vous des mises à jour? Quelques fois par an? Trimestriel? Mensuel, bi-hebdomadaire? Tous les jours? Plusieurs fois par jour? Non! C'est absurde, non?
Est-ce vraiment absurde ?
Certaines équipes techniques d’applications de niveau mondial sont en mesure de livrer leurs applications de manière régulière toutes les semaines ou toutes les deux semaines avec une qualité élevée. Comment parviennent-elles à faire cela? Une partie de l'explication est l'engagement dans un processus de livraison continu sous une forme ou une autre. Examinons quelques-uns des challenges et des bénéfices du DevOps et, plus important encore, pourquoi cela est accessible à tous. Vous n'avez pas besoin d'être une start-up soutenue par une entreprise ou une énorme entreprise pour commencer!

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

--

### Impacts business

- Money, money, money
  - Quality isn't cheap
- Une transition lente (à l'echelle de l'IT)
  - 85% des migrations/adoption DevOps prennent un an
- Une décision à bien mûrir

Note:
Les transitions organisationnelles ne sont pas connues pour être rapides, la mise en place de l'agilité au préalable peut aider

--

![DevOps impacts](./media/devops-impacts-kms-technology.png)

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
- Plus un problème est long à résoudre, plus la société perd d'argent
  Innovation
- plus les process sont rodées et efficaces, plus vos équipes auront de temps dégagé pour brainstormer et déveloper de nouvelles idées, et plus l'expérimentation sera aisée et rapide

---

## Démo / REx

<!-- .slide: data-state="chapter-page"-->

--

![DevOps Loop](./media/devops-loop.png)

---

## World Café (Atelier)

<!-- .slide: data-state="chapter-page"-->

---

## Conclusion

<!-- .slide: data-state="chapter-page"-->
