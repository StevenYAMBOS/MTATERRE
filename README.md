<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://mtaterre.fr/wp-content/uploads/2023/11/logo-mtaterre.png" width="200" alt="Nest Logo" /></a>
</p>

# Documentation Technique

## Projet - Groupe 6

### Membres du Groupe

- Zerin **KABAR**
- Rayane **ABDEDOU**
- Bel **LINGONGA**
- Chérifa **BOUHASSOUN**
- Léa **JARGEAU**
- Yasmine **BENHASSEN**
- Steven **YAMBOS**

## Sommaire

- [I - Technologies utilisées](#i---technologies-utilisées)
  - [A - Back-End](#a---back-end)
  - [B - Front-End](#b---front-end)
- [II - Solution proposée](#ii---solution-proposée)
- [III - Analyse décisionnelle](#iii---analyse-décisionnelle)
  - [A - Interface d'application](#a---interface-dapplication)
  - [B - Bundles](#b---bundles)
  - [C - Applications](#c---applications)
- [IV - Planning](#iv---planning)
- [V - Budget](#v---budget)
- [VI - Sources](#vi---sources)

## I - Technologies utilisées

- Front-End : **ReactJS** <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png" width="30px" alt="ReactJS logo" />
- Back-End : **Golang** <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Go_Logo_Blue.svg/1200px-Go_Logo_Blue.svg.png" width="30px" alt="Golang logo" />
- Base de données : **MongoDB** <img src="https://www.svgrepo.com/show/331488/mongodb.svg" width="30px" alt="MongoDB logo" />

## II - Solution proposée

Dans le cadre de notre expertise, pour répondre aux besoins et attentes demandés par le porteur de projet, nous avons établi différentes solutions possibles pour la mise en place d'une solution qui répond aux attentes du client. Nous avons étudié plusieurs approches, nous retenons cependant une solution qui nous semble la plus adaptée pour ce projet compte tenu du budget disponible, des compétences et des compétences de notre équipe.

Pour cela, nous avons comparé les différentes solutions possibles à adopter pour ce projet en une matrice qui regroupe différents critères de comparaison :

| Critères                        | Performance | Coût de développement | Durabilité à long terme | Temps de développement | Consommation d'énergie | Popularité de la technologie |
|---------------------------------|-------------|------------------------|-------------------------|------------------------|-------------------------|------------------------------|
| Application mobile              |      7/10   |           6/10         |           8/10          |          5/10          |          6/10           |             8/10             |
| Progressive Web App (PWA)       |      8/10   |           7/10         |           7/10          |          8/10          |          8/10           |             7/10             |
| Site Internet                   |      6/10   |           5/10         |           6/10          |          7/10          |          5/10           |             6/10             |
| Application Web                 |      7/10   |           6/10         |           7/10          |          6/10          |          6/10           |             7/10             |

Maintenant que nous avons attribué des notes à chaque solution pour chaque critère, nous pouvons les comparer et déterminer la solution la plus adaptée pour notre projet.

En nous basant sur les notes attribuées, voici une analyse comparative des solutions :

- **Application mobile** : Bien qu'elle bénéficie d'une bonne performance et d'une grande popularité, une application mobile pourrait nécessiter un développement coûteux et relativement long, ainsi qu'une consommation d'énergie plus élevée en raison de l'utilisation intensive du matériel du smartphone. Sa durabilité à long terme peut également être limitée en raison des mises à jour nécessaires pour rester compatibles avec les nouveaux appareils et systèmes d'exploitation. Enfin, les applications mobiles sont aussi dépendantes des stores qui peuvent avoir beaucoup de contraintes.

- **Progressive Web App (PWA)** : La PWA obtient de bonnes notes dans tous les critères, avec une performance élevée, des coûts de développement relativement bas, une durabilité à long terme solide, un temps de développement raisonnable, une faible consommation d'énergie et une popularité croissante en raison de son adoption par de nombreuses entreprises. Cela en fait une option attrayante pour votre projet, en particulier compte tenu de ses avantages en termes de coût, de facilité de développement et de compatibilité multiplateforme.

- **Site Internet** : Un site internet peut être une option moins coûteuse et plus rapide à développer, mais il pourrait souffrir en termes de performance et d'expérience utilisateur par rapport aux autres solutions. De plus, son accessibilité limitée sur les appareils mobiles peut être un inconvénient, surtout compte tenu de votre public cible jeune.

- **Application Web** : Une application web pourrait offrir une meilleure performance et une durabilité à long terme par rapport à un site internet, mais elle pourrait nécessiter un développement plus complexe et des coûts plus élevés. Sa popularité est également moindre par rapport aux autres options.

Nous avons donc opté pour le développement d'une **Progressive Web App (PWA)**.

Une **Application Web Progressive** en Français (PWA) est un site Web qui dispose de fonctionnalités habituellement propres aux applications mobiles, comme le fait de **fonctionner hors ligne** ou d’envoyer des **notifications push**. La PWA est une solution tout-en-un et qui peut être adaptée à tous les appareils en une seule fois sans les difficultés de la publication sur un store contrairement aux applications mobiles. En termes d’UX, il existe un large éventail de PWA.

Une PWA dispose de plusieurs avantages non seulement pour les utilisateurs mais aussi pour les entreprises.

**Pour les utilisateurs**

- **Installation facile et rapide :** Les PWA s'installent directement depuis le navigateur, sans passer par les stores d'applications.
- **Accessible hors ligne :** Les PWA peuvent être utilisées même sans connexion internet, grâce à la mise en cache des données.
- **Chargement rapide :** Les PWA sont optimisées pour une utilisation mobile et se chargent rapidement, même sur des réseaux lents.
- **Expérience utilisateur fluide :** Les PWA offrent une expérience utilisateur fluide et immersive, comparable aux applications natives.
- **Notifications push :** Les PWA peuvent envoyer des notifications push aux utilisateurs, pour les tenir informés des actualités et des offres.
- **Moins de place de stockage :** Les PWA occupent moins d'espace de stockage que les applications natives.

**Pour les entreprises**

- **Coût de développement réduit :** Les PWA peuvent être développées avec des technologies web standard, ce qui réduit le coût de développement.
- **Meilleure engagement :** Les PWA peuvent améliorer l'engagement des utilisateurs, grâce aux notifications push et à l'expérience utilisateur fluide.
- **Augmentation des conversions :** Les PWA peuvent augmenter les conversions, en facilitant l'achat de produits ou de services.
- **Meilleure visibilité :** Les PWA peuvent être référencées dans les moteurs de recherche, ce qui permet d'améliorer la visibilité de l'entreprise.
- **Facilité de maintenance :** Les PWA sont plus faciles à mettre à jour que les applications natives.
- Une PWA n’a pas besoin d’être mise à jour, elle se met à jour automatiquement.

## III - Analyse décisionnelle

### A - Back-End

Ayant décidé de nous orienter vers le développement d'une PWA, nous avons décidé d'utiliser des technologies adaptées à cette solution.
En outre, pour continuer dans l'utilisation de technologies peu consommatrices en énergie et performantes, nous avons réalisé une analyse comparative des différents langages de programmation les plus à même de répondre à la problématique écologique.

Selon l'étude ***Energy Efficiency across Programming Languages: How does Energy, Time and Memory Relate?*** réalisé en 2017
, voici ce que nous pouvons conclure de l'impact des différents langage de programmations en fonction de différents critères :

<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://media.licdn.com/dms/image/D4E12AQHkRu1-aet1xQ/article-inline_image-shrink_1500_2232/0/1662223703652?e=1717632000&v=beta&t=fWfG9AbSJ_pixqPTX2-gJuJiG3Asu4uevcmbLP-Hc98" width="600" /></a>
</p>

| Langages | Performance | Facilité d'apprentissage | Coût de développement | Durabilité à long terme | Temps de développement | Consommation d'énergie | Popularité du langage | Syntaxe et lisibilité |
|----------|-------------|--------------------------|-----------------------|-------------------------|------------------------|-----------------------|----------------------|----------------------|
| C        |     9       |            6             |          7            |           8             |          7             |          9            |         8            |          7           |
| Rust     |     9       |            7             |          8            |           9             |          8             |          9            |         7            |          8           |
| Java     |     8       |            7             |          7            |           8             |          8             |          7            |         8            |          8           |
| Python   |     7       |            9             |          8            |           8             |          9             |          6            |         10           |          9           |
| JavaScript|    7       |            8             |          8            |           7             |          9             |          6            |         9            |          8           |
| Go       |     8       |            7             |          8            |           8             |          8             |          8            |         7            |          8           |
| C#       |     8       |            7             |          7            |           8             |          8             |          7            |         8            |          8           |
| PHP      |     6       |            8             |          7            |           7             |          8             |          6            |         7            |          7           |
| Swift    |     7       |            7             |          7            |           7             |          8             |          7            |         7            |          8           |
| Ruby     |     6       |            8             |          7            |           7             |          8             |          5            |         6            |          8           |

La notation sur 10 est basée sur une combinaison de l'**efficacité énergétique** (comme indiqué dans l'image plus haut) et d'autres facteurs tels que la **popularité du langage**, la **facilité d'apprentissage**, le **temps de développement**, la **syntaxe et la lisibilité**.

Voici comment nous avons procédé :

Nous avons pris en compte l'efficacité énergétique et la rapidité d'exécution des langages de programmation tels qu'indiqués dans l'étude. Par exemple, **C** et **Rust** sont connus pour leur **haute performance**, d'où leur note élevée.

Cette évaluation est basée sur la **complexité syntaxique** et conceptuelle du langage. Par exemple, C est un langage de bas niveau avec une syntaxe complexe, donc il a une note plus basse pour la facilité d'apprentissage.

Nous avons pris en compte la disponibilité des **bibliothèques**, des **frameworks** et des **outils de développement**, ainsi que la **taille de la communauté** de développeurs. Par exemple, Java a une grande communauté et de nombreux outils de développement, ce qui réduit le coût de développement.

Nous avons évalué la **stabilité**, la **maintenance** et l'**évolutivité** des langages de programmation. Par exemple, Rust est un langage moderne avec un bon support pour la maintenance et l'évolutivité, d'où sa note élevée pour la durabilité à long terme.

Les 2 langages qui ce démarquent des autres selon nous sont **Rust** et **Golang**.

#### Rust

- Rust est conçu pour être très performant et est souvent comparé à C en termes de vitesse. C'est un langage de bas niveau (proche de la machine).
- Sa courbe d'apprentissage peut être plus difficile à apprendre en raison de sa gestion unique de la mémoire et de ses concepts avancés.
- Aussi, le développement en Rust peut être plus lent en raison de sa complexité et de sa courbe d'apprentissage plus raide comme cité plus tôt.
- Rust gère la mémoire à la compilation, ce qui peut conduire à des programmes plus performants, mais cela peut aussi rendre le langage plus difficile à apprendre pour les débutants, sachant que notre équipe n'a pas encore développé dans ce langage.
- Rust est l'un des langages les plus efficaces en termes d'énergie, le tableau précédent le démontre bien, il est en concurrence avec C.
- Rust est moins populaire que Golang, mais sa communauté est en croissance et il est de plus en plus utilisé dans l'industrie.

Cependant au vu des compétences de notre équipe ainsi que des performances du langage, nous avons décidé de nous orienter vers **Golang**.
Nous pensons que Rust est plus adapté pour ce projet au vu de ces performances ainsi que de sa consommation d'énergie basse, mais sa courbe d'apprentissage est un frein pour notre équipe ainsi que de sa difficulté.

#### Golang

- **Performance** : Golang est conçu pour être performant, en particulier grâce à sa gestion de la concurrence avec les goroutines.
- **Compétence de l'équipe** : Notre équipe a déjà développée en Golang, sa courbe d'apprentissage est rapide et sa syntaxe est simple à apprendre et comprendre
- **Temps de développement** : La syntaxe simple de Golang et sa bibliothèque standard riche permettent un développement rapide, notre solution n'est pas une application complexe a développer, l'intégration des fonctionnalités en Golang est donc un choix judicieux.
- **Gestion de la mémoire** : Golang utilise un ramasse-miettes pour la gestion de la mémoire, ce qui simplifie le développement.
- **Efficacité énergétique** : Bien que Golang ne soit pas le langage le plus efficace en termes d'énergie, il offre un bon équilibre entre performance et efficacité énergétique.
- **Popularité** : Golang est largement utilisé et dispose d'une grande communauté, ce qui signifie que nous pourrons facilement trouver des ressources d'apprentissage.

### B - Front-End

Enfin, pour justifier nos choix technologique sur la partie Front-End de l'application nous avons réalisé une analyse similaire à la partie **Back-End**.
De ce fait, nous avons décidé de directement réaliser une analyse comparative des **frameworks Javascript**. Pourquoi ? Nous avons décidé d'utiliser Javacript en Front-End car toujours selon l'étude citée plus tôt il est le langage (en tout cas en développement Front-End) qui possède les meilleurs performances pour cette tâche. C'est pouquoi la comparaison s'effectue sur ses frameworks.
Ainsi nous avons comparé les framework **React**, **VueJS** et **Angular**.

Selon les résultats de **Google Trends** en 2023, en termes de recherche, React écrase Angular et Vue. Angular est à la traîne avec un intérêt de recherche allant de 11% à 2% en 5 ans. Vue se stabilise, son intérêt de recherche se maintient autour de 15% à 20%

React est clairement la technologie la plus populaire avec une hausse conséquente du nombre de recherches en 2023, elles restent en 2024, la technologie javascript la plus cherchée.

Pour réaliser une comparaison pertinente le site [LogRocket](https://blog.logrocket.com/) a développé la même **Landing Page** avec des technologies différentes.

**Angular**

<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://blog.logrocket.com/wp-content/uploads/2021/10/angular-landing-page-performance-audit.png" width="500" /></a>
</p>

**VueJS**

<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://blog.logrocket.com/wp-content/uploads/2021/10/vue-landing-page-performance-audit.png" width="500" /></a>
</p>

**React**

<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://blog.logrocket.com/wp-content/uploads/2021/10/react-landing-page-performance-audit.png" width="500" /></a>
</p>

**Résultats**

- React arrive en première position avec 0,8 seconde, Angular arrive en deuxième position avec 1,1 seconde, et Vue arrive en dernier avec 1,2 seconde.
- React et Vue n'avaient aucun TBT, tandis qu'Angular avait un TBT de 200 ms.
- React a le plus rapide indice de vitesse à 0,8 seconde, Angular arrive en deuxième place à 1,2 seconde et Vue arrive en dernier à 1,7 seconde.
- Angular et React ont eu le même LCP de 2,3 secondes, tandis que le LCP de Vue était de 2,4 secondes.
- Ils ont tous eu le même décalage de mise en page cumulatif puisque le décalage s'est produit à cause de l'image et non des cadres eux-mêmes.
- PageSpeed Insight donne à la page d'accueil React la meilleure note de performance avec 82, Vue arrive ensuite avec 81 et Angular arrive en dernier avec 79.

Au vu des résultats que cette comparaison offre ainsi que des compétences de notre équipe Front-End nous avons décidés d'utiliser **React** comme framework.
React dispose de plusieurs avantages et est adapté au développement d'un PWA :

**Modularité des composants**

- ReactJS est basé sur un modèle de composants, ce qui le rend parfaitement adapté à notre PWA. Nous  pouvons diviser chaque fonctionnalité de l'application en composants réutilisables, tels que le composant de prise de photo, le composant de swipe et le composant de gestion des récompenses. Cela rend le développement plus modulaire, facile à maintenir et à étendre à mesure que de nouvelles fonctionnalités sont ajoutées.

**Virtual DOM pour des performances optimales**

- Le système de Virtual DOM de ReactJS garantit des performances optimales, ce qui est crucial pour une application réactive et fluide comme la nôtre. Avec la fonction de prise de photo et le système de swipe, où les interactions de l'utilisateur doivent être instantanées, ReactJS offre une expérience utilisateur réactive en minimisant les mises à jour du DOM réel.

**Gestion de l'état efficace avec React Hooks**

- React Hooks, introduits dans les versions récentes de ReactJS, offrent une excellente solution pour gérer l'état des composants de manière efficace. Nous pouvons utiliser `useState` pour gérer l'état local des composants, ce qui est utile pour suivre l'état des interactions utilisateur telles que le swipe ou le téléchargement des photos. De plus, useContext et useReducer peuvent être utilisés pour gérer l'état global de l'application, facilitant ainsi la gestion de l'état partagé entre les différents composants.

**Large écosystème de bibliothèques et de packages**

- ReactJS bénéficie d'un vaste écosystème de bibliothèques tierces et de packages qui peuvent simplifier le développement de votre application. Par exemple, vous pouvez utiliser des bibliothèques comme React Router pour la gestion de la navigation, React Native Camera pour la prise de photo, et React Swipeable pour implémenter le système de swipe de manière élégante.

**Compatibilité avec les PWAs**

- ReactJS est parfaitement compatible avec le développement de Progressive Web Apps (PWA). Vous pouvez utiliser des outils comme Create React App pour initialiser rapidement votre projet PWA et profiter des fonctionnalités telles que le service worker pour le caching des données et le chargement hors ligne, ce qui améliore l'expérience utilisateur, notamment pour les utilisateurs ayant une connectivité limitée.

### C - Base de données

Pour un projet de ce type, il est judicieux de prendre en compte plusieurs facteurs pour choisir son modèle de base de données.

Notre équipe dispose de compétences avec les modèles de base de données relationnelle. Notamment en **PostgreSQL** (SQL) ainsi qu'en **MongoDB** (NoSQL)

Selon une enquête de **Stack Overflow** en 2023 Postgres est devenue la base de données la plus appréciée.

<p align="center">
  <a href="https://mtaterre.fr/" target="blank"><img src="https://www.bytebase.com/_next/image/?url=%2Fcontent%2Fblog%2Fpostgres-vs-mongodb%2Fstackoverflow.webp&w=1080&q=100" width="500" alt="Nest Logo" /></a>
</p>

Pour le choix de la base de données notre approche conciste à évaluer les pours et les contres des différents modèles de base de données.

Postgres est un système de gestion de base de données relationnelles. Il stocke les données dans des tables avec des colonnes prédéfinies et des types de données. Les relations entre les tables sont établies en utilisant des clés étrangères.

MongoDB est une base de données orientée document, ce qui signifie que les données sont stockées sous forme de documents dans une collection. Chaque document est une structure JSON qui peut contenir des champs et des tableaux imbriqués. MongoDB est conçu pour gérer les données non structurées et semi-structurées.

Les base de données MongoDB ont 3 niveaux :

- **Collection** (niveau 1)
- **Document** (niveau 2)
- **Champs** (niveau 3)

Chaque **collection** contient des **documents**, ces documents contiennent des **champs** relatifs à la collection et au document.
Par exemple la collection `User` contient un document `test@gmail.com`, ce document a pour **Id** l'**adresse email** d'un utilisateur. Le document *<test@gmail.com>* contient les champs relatifs à un utilisateur (nom, prénom etc...).

**Collections**

```markdown
User
Chat
Album
Message
Post
```

**Documents** (d'une collection, ici `User`)

```markdown
test@gmail.com
exemple@gmail.com
microsoft@gmail.com
google@gmail.com
```

**Champs** (d'un document, ici *<test@gmail.com>*)

```json
username: "Dwayne Johnson"
password: "$2b$10$X.QlvWQW0uCJa1oaSOmJaeoP2jEfKndKBkPghZveaTlATLtblMdam"
email: "test@gmail.com"
created_at: 5 janvier 2024 à 09:47:44 UTC+1
etc...
```

Voici un tableau comparatif entre Postgres et MongoDB, basé sur différents aspects :

| Critère        | Postgres                                  | MongoDB                                         |
|----------------|-------------------------------------------|------------------------------------------------|
| Licence        | Licence PostgreSQL (semblable à MIT)      | Licence SSPL                                   |
| Modèle de données | Modèle tabulaire, relationnel           | Document                                      |
| Support JSON   | Capacités et intégration avec SQL        | Validateur de schéma intégré                  |
| Performance    | Optimisé pour les requêtes complexes     | Optimisé pour les données dénormalisées       |
| Fiabilité      | Support complet des transactions ACID     | Transaction + basculement automatique intégré |
| Scalabilité    | Mise à l'échelle verticale               | Mise à l'échelle horizontale                  |
| Facilité d'utilisation | Capacités de requête rigoureuses     | Contraintes moins strictes et démarrage facile |
| Opérabilité    | Optimisé pour un seul nœud et une large gamme de fournisseurs d'hébergement | Optimisé pour plusieurs nœuds et un service d'hébergement raffiné |
| Écosystème     | Animé par la communauté, décentralisé   | Dirigé par l'entreprise, centralisé           |

Pour cette matrice spécifique nous avons pensé que classer 2 modèles de base de données avec des notes n'est pas pertinent car chacun des modèles dispose de ses propres avantages et inconvénients, et le choix dépend du cas de notre solution.

Pour faciliter l'intégration avec le Back-End en Golang ainsi que pour des soucis d'évolutivité (notamment lié aux volume de données qui pourrait être assez conséquent), nous pensons qu'il est préférable d'utiliser **MongoDB** pour notre système de gestion de base de données.
Aussi, les bases de données non relationnelles, telles que MongoDB, offrent une flexibilité beaucoup plus grande en termes de schéma de données. Contrairement aux bases de données relationnelles, qui ont des schémas rigides et prédéfinis, les bases de données non relationnelles permettent de stocker des données de manière plus flexible, sans nécessiter de structure de table prédéfinie.

### D - Hébergement vert

Le porteur de projet dispose actuellement d'un hébergement web. Nous n'imposons pas de changement d'hébergeur web, cependant, nous souhaitons proposer un avis sur un hébergeur web green que nous pensons adapté à la solution et en adéquation avec les valeurs de l'association.

Voici une matrice décisionnelle pour comparer les différents hébergements web verts que nous considérons les plus pertinents pour répondre aux exigences de la solution :

| Critères        | PlanetHoster | Infomaniak | Ex2   |
|----------------|--------------|------------|-------|
| Engagement écologique (sur 10) | 9 | 8 | 7 |
| Performances (sur 10) | 9 | 7 | 8 |
| Support client (sur 10) | 9 | 8 | 7 |
| Prix (sur 10) | 8 | 7 | 9 |
| Offres et fonctionnalités (sur 10) | 9 | 8 | 7 |
| Flexibilité et évolutivité (sur 10) | 8 | 7 | 6 |
| Garantie satisfait ou remboursé (sur 10) | 9 | 7 | 8 |

Nous avons sélectionnés 2 hébergeurs web qui ont des **datacenters** en France.

**PlanetHoster**

Avec une note globale élevée et un fort engagement écologique, PlanetHoster offre des performances solides, un excellent support client et une large gamme d'offres et de fonctionnalités. De plus, la garantie satisfait ou remboursé de 14 jours offre une certaine tranquillité d'esprit lors de l'essai des services.

**Ex2**

Bien que légèrement inférieur en termes de performances et de support client par rapport à PlanetHoster, Ex2 se distingue par son engagement écologique solide et son prix compétitif. Le client accorde une grande importance à l'aspect écologique et EX2 dispose d'un prix avantageux pour ce plan.

Dans l'optique où le porteur de projet souhaite se diriger vers l'uns des hébergements web que nous avons proposons nous lui conseillons l'adoption de **EX2**.

EX2 dispose des éléments suivant que nous considérons pertinents pour une solution francophone soucieuse de l'environnement :

- Équipes Francophones
- Datacenter en france
- Hébergement Wordpress possible
- Emprunte carbone nulle
- Pour l’achat d’un plan “vert”, Ex2 s’engage à donner 3 lampes solaires à une famille en Afrique au travers de l’association Solar Aid
- Support client très professionnel
- Datacenter en France (ainsi qu’au Canada)
- Installation assistée de nombreux CMS/applications
- Tarifs longues durées abordables

## IV - Planning

| Phase de Conception (2 semaines)         | Durée Estimée |
|------------------------------------------|----------------|
| **Spécifications Techniques**            | 1 semaine      |
| - Définition des fonctionnalités et des besoins techniques de l'application. |
| - Choix des technologies et des frameworks (déjà effectué). |
| - Conception de l'architecture du système. |
| - Définition des APIs et des services web. |
| - Choix de la base de données et du système de stockage. |
| - Définition des exigences de sécurité et de performance. |
| **Cahier des Charges**                   | 1 semaine      |
| - Détail des fonctionnalités et des exigences de l'application. |
| - Définition des interfaces utilisateur (wireframes, prototypes). |
| - Définition des règles de gestion et des workflows. |
| - Planification des tests et de la maintenance. |
| **Initialisation du Projet**             | 1 semaine      |
| - Mise en place des outils de développement et de collaboration (Git, Jira, etc.). |
| - Création du backlog de développement et des sprints. |
| - Définition des jalons et des livrables. |
| - Mise en place des processus de communication et de suivi. |

| Phase de Développement (6 semaines)      | Durée Estimée |
|------------------------------------------|----------------|
| **Développement Back-End (Golang)**      | 4 semaines    |
| - Développement des APIs pour la gestion des utilisateurs, des photos, des récompenses et du système de swipe. |
| - Mise en place de la base de données MongoDB. |
| - Implémentation des tests unitaires et d'intégration. |
| - Optimisation des performances et de la sécurité. |
| **Développement Front-End (React)**      | 4 semaines    |
| - Développement des interfaces utilisateur pour la prise de photos, le système de swipe et la gestion des récompenses. |
| - Optimisation des performances et de l'accessibilité. |
| - Implémentation des tests unitaires et d'intégration. |
| **Intégration et Tests**                 | 2 semaines    |
| - Intégration du Back-End et du Front-End. |
| - Tests fonctionnels et de performance. |
| - Correction des bugs et des anomalies. |
| - Tests de compatibilité sur différents navigateurs et appareils. |

| Phase de Test et de Production (4 semaines)| Durée Estimée |
|-------------------------------------------|----------------|
| **Tests d'utilisabilité**                 | 2 semaines    |
| - Recrutement de testeurs utilisateurs.  |
| - Réalisation de tests d'utilisabilité et de feedback. |
| - Identification des points d'amélioration et correction des anomalies. |
| **Pré-production**                        | 1 semaine     |
| - Déploiement de l'application sur un serveur de test. |
| - Configuration du domaine et des certificats SSL. |
| - Mise en place des outils de monitoring et de sécurité. |
| **Lancement et Production**               | 1 semaine     |
| - Déploiement de l'application en production. |
| - Communication et promotion de l'application. |
| - Acquisition des premiers utilisateurs. |
| - Suivi des performances et de l'engagement. |

## V - Budget

Voici un tableau justifiant les coûts de développement de la solution PWA. Le développement d'une PWA simple en France est entre 10 000€ et 60 000€ pour les PWA complexes. Nous avons décidé d'allouer un budget de 15 000€ au développement de la solution. Ce choix est justifié  :

| Tâche                                | Durée (semaines) | Coût (€)        | Répartition du Coût (%) | Coût Total (€) |
|--------------------------------------|------------------|-----------------|-------------------------|----------------|
| Spécifications Techniques            | 1                | 0               | 0                       | 0              |
| Cahier des Charges                   | 1                | 0               | 0                       | 0              |
| Initialisation du Projet             | 1                | 0               | 0                       | 0              |
| Développement Back-End (Golang)      | 4                | 4,000           | 26.67                   | 4,000          |
| Développement Front-End (React)      | 4                | 4,000           | 26.67                   | 4,000          |
| Intégration et Tests                 | 2                | 2,000           | 13.33                   | 2,000          |
| Tests d'utilisabilité                | 2                | 2,000           | 13.33                   | 2,000          |
| Pré-production                        | 1                | 1,000           | 6.67                    | 1,000          |
| Lancement et Production              | 1                | 1,000           | 6.67                    | 1,000          |
| **Total (sans Solution PWA)**        | -                | -               | -                       | **15,000**     |
| **Coût de la Solution PWA**          | -                | **15,000**      | **100**                 | **15,000**     |
| **Total (avec Solution PWA)**        | -                | -               | -                       | **30,000**     |

## VI - Sources

### PWA

[PWA.fr](https://www.progressive-web-apps.fr/pwa-5-raisons-interesser-infographie)

[Wikipédia](https://fr.wikipedia.org/wiki/Progressive_web_app)

[Google PWA](https://developers.google.com/web/progressive-web-apps/)

[APIMedia Capture](https://developer.mozilla.org/en-US/docs/Web/API/Media_Capture_and_Streams_API)

[Gemini](https://gemini.google.com/)

### Éco-conception web

[Progressive Web App](https://lagrandeourse.design/blog/outils/quels-outils-pour-developper-une-pwa/)

[Éco-conception web](https://www.numendo.com/blog/front/eco-conception-web-pourquoi-et-comment-creer-un-site-eco-responsable/)

[Article sur l'éco-conception](https://alexsoyes.com/eco-conception-web/)

### Comparatif langages

[Calculateur d'emprunte carbon web](https://www.websitecarbon.com/)

[Langages écologiques](https://greenlab.di.uminho.pt/wp-content/uploads/2017/09/paperSLE.pdf)

[Comparatif récent des langages de programmation écologiques](https://www.linkedin.com/pulse/what-greenest-programing-languages-michael-spencer/)

[Golang vs Rust](https://www.pixelcrayons.com/blog/software-development/go-vs-rust/)

### Hébergement Web Green

[Hébergement web vert](https://www.journaldugeek.com/hebergeur/ecologique/)

[De l'hébergement classique à l'hébergement web](https://www.hellocarbo.com/blog/reduire/hebergement-vert-site-web/)

### Base de données

[MongoDB vs PostgreSQL](https://www.bytebase.com/blog/postgres-vs-mongodb/)

### Frameworks Javascript

[React vs Angular vs Vue performances](https://blog.logrocket.com/angular-vs-react-vs-vue-js-comparing-performance/)

[React vs Angular vs Vue](https://www.ambient-it.net/reactjs-vs-angular-vs-vuejs/)

### Budget

[Tarif Développeur Golang](https://www.codeur.com/developpeur/go/tarif)

[Tarifs Développeur ReactJS](https://www.codeur.com/developpeur/react/tarif)
