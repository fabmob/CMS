# Gouvervance du GT " Compte Mobilité Standardisé" (CMS) 

## Préambule
### Historique et contexte
Le développement de systèmes de MaaS ces 10 dernières années, c’est à dire l’intégration de différents modes de transports ou systèmes de transport gérés par des acteurs hétérogènes, a conduit à la mise en oeuvre de solutions ad-hoc pour gérer l’identité d’un usager, son authentification, la gestion de ses comptes multiples, entre ces différents systèmes.

Le Gart a animé en 2020 et 2021 des groupes de travail “Architecture & Interfaces MaaS”, restitués dans un [rapport publié en décembre 2021](https://www.gart.org/wp-content/uploads/2021/12/Rapport-de-restitution-des-travaux-du-groupe-de-travail-MaaS-Architecture-et-Interfaces_Decembre-2021.pdf). Ces travaux incluent une expression de besoin partagée par les contributeurs de ces travaux quant aux attendus du compte mobilité standardisé.

La Fabrique des Mobilités conçoit et développe depuis 2019, avec Capgemini Invent, l’outil “MOB - Mon Compte Mobilité” dans le cadre d’un programme CEE sous l’égide de l’AIT, du Gart et de l’Ademe. Cet outil de compte unifié pour la gestion d’aides à la mobilité a une vocation nationale et sera expérimenté sur l’année 2022 en Ile de France et à Mulhouse. Cet outil national et Open Source a vocation à mettre en oeuvre l’intégralité du standard pour les comptes mobilité et à offrir des fonctionnalités de référence à l’écosystème pour la mise en œuvre de ce standard.

Les acteurs de l’écosystème français et le Gart ont fixé comme feuille de route la disponibilité d’un premier standard complet et éprouvé d’ici fin 2022. Cela signifie que la publication d’une première version du standard est attendue d’ici juin 2022 afin de pouvoir le tester, l’implémenter et obtenir des retours d’expérience, notamment à travers le programme “Mon Compte Mobilité”.


### Le standard compte mobilité standardisé : définition et objectifs
Tout opérateur de mobilité et opérateur de MaaS gère des comptes utilisateurs indispensables au fonctionnement des services proposés. Dans ce contexte chacun de ces comptes utilisateur constitue un “compte mobilité” puisqu’il contient des données personnelles génériques, des données de profil propres au contexte mobilité (préférences de déplacement, abonnements, droits d’accès, caractéristiques de déplacement et de véhicules par exemple) et éventuellement des données d’usage des services et/ou de déplacement de l’utilisateur.

Dans le cadre de systèmes “Mobility as a Service” plusieurs comptes mobilité qui concernent le même usager final interagissent. Plusieurs fonctionnalités clef attendues ont d’ores et déjà été identifiées, pour lesquelles une standardisation des méthodes ou des pratiques de mise en œuvre est requise. Sont citées ici 9 fonctionnalités clef identifiées dans le cadre des travaux du Gart, qui devront être complétées et approfondies au cours du processus d’élaboration du standard : 
* CM01 - Créer, modifier ou supprimer un compte mobilité
* CM02 - Permettre la connexion à un compte mobilité et l’authentification unique
* CM03 - Gérer et accéder aux informations du compte
* CM04 - Créer (enrôlement) et modifier un compte chez un partenaire
* CM05 - S’assurer de la protection des données personnelles
* CM06 - Gérer les préférences de voyage
* CM07 - Contrôler les comptes frauduleux
* CM08 - Permettre le lien des comptes porteur / payeur
* CM09 - Recueillir et traiter les pièces justificatives

Pour rendre disponibles de manière standardisée ces différentes fonctionnalités, les travaux de standardisation du Groupe de Travail “Compte Mobilité Standardisé” pourront notamment standardiser :
* La description des informations présentes ou disponibles dans un “Compte Mobilité”, leur représentation technique, ainsi que la qualification de leur source ou de leur qualité ;
* La gestion des consentements et des droits associés, pour chaque utilisateur et chaque contexte ;
* Des interfaces pour la création de compte à partir d’un autre compte mobilité standardisé, l’appariement de comptes existants, l’échange de données standards entre ces comptes, ainsi que l’échange de justificatifs ou preuves de validation ;
* Le choix des standards pour le SSO et la manière de les configurer, afin que différents systèmes les mettent en œuvre de manière similaire, ce qui réduira la complexité technique et ouvrira la voie à des comptes unifiés territoriaux ou nationaux à moindres frais.

Le standard est référé sous les termes “Compte Mobilité Standardisé” ou “CMS” et fera l’objet d’adaptations dans d’autres langues dont l’anglais.


### Un standard ouvert
#### Les principes 
Le « compte mobilité standardisé » et sa gouvernance préservent les intérêts des parties prenantes de la communauté de manière non-discriminante. A cet effet ils respectent des principes fondamentaux des « standards ouverts » tels que [définis par OpenStand](https://open-stand.org/about-us/principles/) et pratiqués par des organisations de référence de standardisation pour le numérique (Internet Society, W3C, IETF, IEEE, Fondation OASIS), et en particulier :
* Un processus transparent basé sur le consensus. Ce processus garantit que toutes les parties prenantes concernées peuvent contribuer et sont sollicitées, et qu’aucune organisation ou aucun groupe particulier ne domine le processus, au détriment des autres
* Un standard qui sert les intérêts collectifs de l’écosystème du MaaS : qualité technique, stabilité, compétition équitable, possibilité de développer des innovations sur la fondation que constitue le standard
* Accessibilité et gratuité. Le standard est disponible pour toutes les parties prenantes, sans frais, sur un dépôt commun, et la communauté travaille à toute documentation, outil ou implémentation de référence qui facilite l’accès et l’implémentation effective du standard. Cet accès répond à la définition de « standard ouvert » au sens de [l’article 4 de la loi pour la confiance dans l’économie numérique](https://www.legifrance.gouv.fr/loda/article_lc/LEGIARTI000006421544)
* L’adoption et la mise en œuvre de ce standard par les parties prenantes de l’écosystème est volontaire

#### La licence
Le standard CMS est publié sous licence ouverte [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0), licence couramment utilisée (ex : format GTFS).
La licence répond au besoin de libre accès au standard, de protection des réutilisateurs en matière de propriété intellectuelle et ouvre la possibilité d’innover par enrichissement du standard à titre expérimental (dans ce cas de figure il n’est pas permis de faire usage de la marque « Compte Mobilité Standardisé » ou “CMS”).


## Les rôles
### La communauté CMS
#### Contributeur
Toute personne physique ou morale peut participer et contribuer aux groupes de travail sur une base volontaire et bénévole. Les outils de travail collaboratif mis en place par la communauté sont accessibles aux contributeurs de manière libre ou sur simple demande.

#### Membre délibérant
Toute personne morale qui met en œuvre le standard dans le cadre de ses activités (opérateur, intégrateur ou éditeur de solution, AOM, organismes de recherches développant des innovations autour du MaaS) peut participer à la gouvernance avec le statut de membre délibérant. Un membre délibérant peut participer à toutes les décisions et dispose du droit de veto chaque fois que cela est prévu par les règles de gouvernance. 

Le statut de membre délibérant et l’accès aux droits attachés est gratuit, il ne repose sur aucune contribution financière. Il nécessite une inscription avec une description de l’organisation et la désignation d’au moins un représentant. Le membre délibérant doit pouvoir justifier de sa qualité de partie prenante qui met en œuvre le standard dans le cadre de ses activités, ou bien sera amené à le faire.

Tout membre délibérant apparaît dans une liste officielle des acteurs soutenant et promouvant le standard. Tout membre délibérant peut demander à ne plus figurer sur cette liste, et renonce alors aux droits attachés au statut de membre délibérant.

### Groupe de travail
Lorsque des contributeurs souhaitent développer et expérimenter de nouvelles fonctionnalités, ils peuvent constituer un groupe de travail sur une base volontaire. Le groupe de travail est constitué librement par ceux qui souhaitent coopérer ensemble sur une extension du standard qui sera publiée dans la partie informative du standard.
Des groupes de travail peuvent aussi être créés par la communauté pour traiter tout sujet qui a trait à l'amélioration ou la promotion du standard.
Pour être reconnu officiellement par la communauté, un groupe de travail est validé par la réunion d’orientation ([cf III.e](https://docs.google.com/document/d/1e18C6_dy8dQJWfLs3vqCdpRhutIdxOW2frGGtWwcIF8/edit#heading=h.uozgst5wful1)), sur la base d’une présentation des objectifs poursuivis par celui-ci. Le groupe de travail est ouvert à tout contributeur de la communauté.

### Facilitateur
Le facilitateur est une personne ou une organisation qui accompagne la communauté dans le maintien, la promotion et le développement du standard. Ses missions évoluent en accord avec la communauté, et couvrent a minima :
* La gestion des outils de la communauté (Github, outils de communication et collaboration, documentation)
* La coordination et la facilitation des groupes de travail (qui peut être partagée ou déléguée à d’autres contributeurs de la communauté)
* La représentation du standard et de la communauté qui le soutient auprès de toute partie prenante externe, en coordination avec les contributeurs de la communauté
* Organiser la prise de décision et faire respecter les principes de gouvernance. Elaborer et soumettre à la communauté des décisions relatives à la gouvernance et au développement du standard (en particulier tous les sujets listés ci-dessus)
Le facilitateur ne prend pas part aux votes de la communauté, pendant toute la durée de son mandat.

Le facilitateur de la communauté est choisi chaque année par la communauté par un vote majoritaire. Le mandat est annuel.

Pour l’année 2022 le rôle de facilitateur est tenu par La Fabrique des Mobilités, qui soutient cette activité dans le cadre du programme CEE « Mon compte mobilité » qui prévoit un soutien à l’écosystème MaaS dans le développement et la promotion de standards.

## Le standard


### Publication
Un dépôt de référence (Github) hébergera la version de référence validée par la communauté, les versions élaborées par les groupes de travail, et toute évolution proposée par une partie prenante à la communauté, en vue d’une validation. Ce dépôt accueillera aussi toute la documentation disponible relative au standard et aux travaux des groupes de travail. Les décisions, les débats qui l’entourent, et la justification des votes (en particulier des vétos) font partie de la documentation librement accessible.
Le dépôt est géré et administré par le facilitateur.

### Langue
La version initiale du standard est publiée en anglais, sauf la documentation de présentation du standard qui elle est disponible en français et en anglais. Au démarrage, les comptes-rendus de réunion des groupes de travail sont en français. Le présent document de gouvernance fait l’objet d’une traduction officielle en anglais, adoptée en même temps que la version française.
Des langues additionnelles, notamment l’anglais, peuvent être développées par la communauté, selon les besoins identifiés.

### Structure du standard
#### Les versions
La communauté approuve le standard et ses évolutions périodiquement. La version du standard approuvée par la communauté selon les règles de gouvernance de ce document est la version canonique, qui fait référence. Toute utilisation de la marque « Compte Mobilité Standardisé » comporte l’obligation de se conformer à l’une des versions canoniques publiées sur le Git de référence de la communauté. Une version du standard qui ne correspond à l’une des versions canoniques dûment approuvée par la communauté ne peut pas faire usage de la marque « Compte Mobilité Standardisé ».
Une gestion sémantique des versions est mise en place selon le standard [SemVer](https://semver.org/lang/fr/).

#### La partie normative
La partie normative est le tronc commun du “Compte Mobilité Standardisé” dont la mise en œuvre a été approuvée selon les procédures prévues à la gouvernance.

Des outils peuvent être approuvés par la communauté pour valider la conformité d’une implémentation du standard. 

Chaque implémentation doit faire l'objet d’une phase de consultation (voir III.B) et de vote pour intégrer la partie normative. Les critères objectifs permettant de caractériser si une implémentation relève de la partie normative du standard sont : 
* L’**adhésion** : les fonctionnalités proposées sont promues par l’ensemble des “membres délibérants”
* L’**engagement** : engagement de tous les opérateurs de MaaS et de services de mobilité à se conformer aux spécifications s’ils mettent en œuvre toute fonctionnalité décrite par le standard dans la partie normative. A minima une telle fonctionnalité doit être rendue disponible selon le standard de compte mobilité
* Le **fonctionnement** : fonctionnement validé en production avec des implémentations
* La **garantie de pérennité, de performance et de respect des règlementations en vigueur**

#### La partie informative
La partie informative contient des extensions et des évolutions structurantes du standard, publiées à part sur le dépôt de référence. Chaque extension est publiée sous la responsabilité d’un groupe de travail approuvé par la communauté selon les règles définies dans la gouvernance. La partie informative, comme la partie normative, constitue un socle commun. Par conséquent une fonctionnalité n’est décrite qu’une seule fois : la partie informative permet d’accorder toutes les parties prenantes sur une manière commune de réaliser une fonctionnalité.

Les extensions concernent des évolutions fonctionnelles du standard que des parties prenantes souhaitent expérimenter dans un cadre de concertation commun. La communauté ne s'engage pas sur le respect des 4 critères formulés pour la partie normative.

L’objectif de la partie informative est de permettre l’expérimentation et approuver des évolutions de la partie normative sur la base d’expériences concrètes et d’un processus d’élaboration ouvert. Elle décrit des évolutions de fonctionnalités qui sont rétrocompatibles avec la partie normative. Cela signifie qu’une implémentation d’extension contenue dans la partie informative doit pouvoir se faire dans le respect de l’ensemble de la partie normative. C’est le principal critère de publication d’une extension dans le cadre de la partie informative.

Le passage de la partie informative à la partie normative peut entraîner des évolutions du standard rendues nécessaires par la prise en compte des retours d’expérience.

#### Les versions non officielles du standard

La licence Apache 2.0 autorise toute partie prenante à faire évoluer et adapter le standard librement. Ces évolutions se font alors sans approbation ni concertation particulière de la communauté. Par conséquent, ces versions du standard ne doivent pas utiliser la marque « Compte Mobilité Standardisé » ou ses dérivés.
Le facilitateur est mandaté par la communauté pour faire respecter le bon usage de la marque.


## Processus d'élaboration du standard
### Elabiration de la version 1.0.0
Les contributeurs de la communauté adoptent à l’unanimité une version 0.2.0 du standard composée uniquement du présent document de gouvernance. 

A partir de ce moment, les signataires ayant apporté leur soutien seront ajoutés dans la partie IV et deviennent membres délibérants de droit. Les règles de la gouvernance sont dès lors appliquées pour faire évoluer le document de gouvernance et publier des premières versions des travaux dans les volets informatifs puis normatifs.

Le développement du standard est itératif. Un ensemble cohérent de fonctionnalités utiles à l’écosystème sera publié dans une version 1.0.0 en juin 2022. Au moins une version ultérieure sera publiée en deuxième partie de 2022 avec des correctifs et mises à jour sur les fonctionnalités déjà publiées, si nécessaire, ainsi que de nouvelles fonctionnalités. Ce travail itératif est amené à se poursuivre en 2023 et au-delà pour répondre aux besoins de l’écosystème en France et en Europe. 

### Evolutions de la partie normative
#### Rythme d'évolution
L’évolution de la partie normative est un processus continu qui vise à répondre aux exigences de performance et stabilité de standard d’une part, aux besoins d’évolution d’autre part.

Tous les deux mois la communauté passe en revue des évolutions proposées pour la partie normative. Ces évolutions peuvent être proposées directement par la communauté (évolutions mineures, correctifs), être le résultat d’un groupe de travail dédié ou bien être une extension informative candidate à la partie normative. Le facilitateur organise le partage, le tri et le vote sur ces évolutions du standard, si nécessaire.

Les évolutions proposées font l’objet de discussions sur les outils de la communauté afin d’en comprendre les objectifs et les modalités.

#### Processus de validation
Les votes se déroulent de la manière suivante :
* Les évolutions font l’objet d’une revue et d’une discussion lors d’une réunion d’orientation du standard à laquelle sont conviés tous les membres délibérants
* Chaque évolution discutée en réunion d’orientation fait l’objet d’une publication 5 jours ouvrés au préalable
* Des échanges en ligne sont organisés de la publication de l’évolution jusqu’à 5 jours ouvrés au-delà de la réunion d’orientation
* À l’issue de ce délai un vote en ligne est organisé. Les votes possibles sont POUR, NEUTRE et CONTRE
* Le quorum est fixé à 10 membres délibérants, y compris les votes NEUTRES
* Chaque évolution qui recueille ⅔ de votes positifs est validée (le calcul se fait sur le votes exprimés POUR ou CONTRE uniquement, les votes NEUTRE sont uniquement comptabilisés pour l’atteinte du quorum)
* Tout membre délibérant dispose d’un délai de 5 jours ouvrés pour émettre, seul ou à plusieurs, un veto motivé et publié sur les outils de la communauté. En cas de veto la proposition est soumise de nouveau à consultation ou à de nouveaux travaux.

#### Exercice du droit de veto et limitations
L’exercice du droit de veto permet à des membres délibérants de préserver leurs intérêts et ceux de la communauté, même en position minoritaire. Cela doit conduire à un niveau de consensus et d’exigence de qualité plus importants pour le standard, et éviter des décisions précipitées. Ce droit de veto ne doit pas servir à des manœuvres dilatoires ou être utilisé de mauvaise foi pour bloquer le processus de standardisation au détriment des autres parties prenantes. C’est la raison pour laquelle les décisions, et en particulier l’usage des vetos, sont documentées et publiques.

De plus, tout membre délibérant ne peut exercer son droit de veto que deux fois au cours d’une période de 12 mois glissants. Lorsqu’il a utilisé son droit de veto par deux fois au cours des 12 derniers mois, un membre délibérant ne peut plus exercer de veto sur une décision tant que la condition “moins de deux veto au cours des douze derniers mois” n’est pas remplie.

### Revue des extentions informatives candidates au volet normatif
Lorsqu’une extension du volet informatif a été mise en œuvre dans des projets, le groupe de travail qui soutient cette extension peut la soumettre à la communauté en vue d’une adoption dans la partie normative du standard. Le processus est le suivant :
* Le groupe de travail fournit une version révisée de l’extension ;
* Le groupe de travail fournit un rapport évaluant les conditions de mise en œuvre de l’extension dans des projets et en dresse un bilan. Le rapport doit montrer que l'extension respecte les 4 critères de la partie normative (voir II.C.ii)
* La phase de concertation et vote décrite au III.B est mise en oeuvre en vue d’adopter l’évolution de la partie normative

### Evolution de la partie informative
Chaque groupe de travail informatif a la responsabilité de faire évoluer l’extension dont il a la charge, par consensus au sein du groupe de travail (absence de veto de l’un des membres du groupe). Le groupe de travail doit assurer la transparence de ses travaux (publication au sein de la communauté) et consulte la communauté autant que nécessaire pour définir son extension.

Chaque nouvelle version publiée doit faire l’objet d’une période d’information et consultation de la communauté d’une durée de 10 jours ouvrés, à l’issue de laquelle le groupe de travail décide par consensus de publier l’extension informative révisée. 

Chaque groupe de travail a la responsabilité de maintenir la rétrocompatibilité de son extension avec la dernière version canonique de la partie normative du standard.

Chaque année le groupe de travail soumet un rapport à la communauté décrivant les évolutions apportées à l’extension, les implémentations réalisées et leur bilan, ainsi que les perspectives pour l’année suivante (évolutions fonctionnelles envisagées, processus éventuel d’adoption dans la partie normative). A cette occasion la communauté peut prendre une décision de désinscription de l’extension de la partie informative. Cette décision à la majorité qualifiée des 2/3, sera motivée par des critères d’intérêt de la communauté pour l’extension ou de difficultés techniques constatées avec la partie normative du standard.

Lorsqu’une extension n’est plus soutenue par la communauté, cette extension et la documentation ne sont plus inscrites dans la partie informative du standard, et sont archivées dans une section dédiée des outils de la communauté, pour référence.


### Réunion d'orientation du standard
Tous les deux mois, les membres délibérants organisent une réunion d’orientation du standard. Ces réunions permettent de traiter de différentes missions :
* Revue et discussion des évolutions normatives proposées
* Le lancement d’un nouveau groupe de travail, à la demande d’un groupe de contributeurs.
* Proposer à la communauté un facilitateur et les modalités de son intervention
* Adopter des motions ou lancer des actions d’intérêt pour la promotion et l’évolution du standard


## Liste des membres délibérants ayant approuvé le standard dans version actuelle
