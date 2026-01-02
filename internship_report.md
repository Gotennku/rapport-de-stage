# Rapport de Stage

**Patrick Saint-Laurent NGANE**

Epitech Paris - TEK 2 | Promotion 2025-2026

Stage du 1er septembre au 31 décembre 2025

**Entreprise** : USTS - Formation IA
**Adresse** : 1 rue Fulton, 75013 Paris
**Tuteur** : Lilian Garcia
**Poste** : Développeur Full Stack

---

<!-- ============================================================ -->
<!-- PARTIE 1 : LE CONTEXTE                                       -->
<!-- ============================================================ -->

# PARTIE 1

# Le Contexte

*L'entreprise, son organisation, ses activités et enjeux business, et ma place dans l'organisation*

---

## 1.1 Présentation de l'entreprise USTS

### Identité et localisation

**USTS** est une entreprise française spécialisée dans la formation professionnelle aux technologies de l'intelligence artificielle. Située au 1 rue Fulton dans le 13ème arrondissement de Paris, à proximité de la Bibliothèque François Mitterrand, l'entreprise bénéficie d'une localisation stratégique dans un quartier numérique en pleine expansion.

### Activité principale : la formation IA

L'activité principale d'USTS consiste à proposer des formations sur les outils et méthodes liés à l'intelligence artificielle, à destination des professionnels souhaitant acquérir ou renforcer leurs compétences dans ce domaine en constante et rapide évolution. Depuis l'émergence de ChatGPT fin 2022 et la démocratisation des grands modèles de langage (LLM), la demande pour ce type de formations a explosé.

L'entreprise se distingue de ses concurrents par son approche résolument pratique. Plutôt que de proposer des cours théoriques sur le fonctionnement des réseaux de neurones, USTS privilégie les cas d'usage concrets et les mises en situation professionnelles. Les participants manipulent directement les outils, créent des projets réels et repartent avec des compétences immédiatement applicables dans leur travail quotidien.

Les formations couvrent un large spectre :
- Utilisation des assistants IA (ChatGPT, Claude, Gemini) en contexte professionnel
- Génération d'images et de vidéos par IA pour le marketing
- Automatisation de tâches répétitives grâce à l'IA
- Intégration d'APIs d'IA dans des applications existantes

### Les produits internes comme supports pédagogiques

En parallèle de son activité de formation, USTS développe des produits internes qui servent un double objectif. D'une part, ces produits constituent des supports pédagogiques concrets pour les formations : les participants peuvent voir comment une application réelle intègre les technologies d'IA enseignées. D'autre part, ces produits ont vocation à être commercialisés, générant ainsi une source de revenus complémentaire.

C'est dans ce cadre que s'inscrivent les deux projets sur lesquels j'ai travaillé durant mon stage : Zitelou, une application de contrôle parental, et Jean-François SAIA, une plateforme de création de sites web par IA. Ces projets représentent la stratégie de diversification d'USTS, qui souhaite ne pas dépendre uniquement de son activité de formation.

## 1.2 Enjeux business et positionnement marché

### Un marché en pleine croissance

Le marché de la formation à l'intelligence artificielle connaît une croissance exponentielle, portée par la prise de conscience des entreprises sur le potentiel de l'IA, la volonté des salariés de rester employables, et les réglementations émergentes comme l'AI Act européen.

### Positionnement concurrentiel d'USTS

Face à des acteurs établis comme les GAFAM (qui proposent leurs propres certifications), les grandes écoles (qui développent des cursus IA) et les plateformes e-learning (Coursera, Udemy), USTS a choisi un positionnement de niche.

L'entreprise cible trois segments principaux :

**Les professionnels en reconversion** : Des personnes issues d'autres secteurs (marketing, RH, finance) qui souhaitent acquérir des compétences IA pour évoluer dans leur carrière ou changer de métier. Pour eux, USTS propose des formations accessibles, sans prérequis techniques.

**Les entreprises en transformation** : Des PME et ETI qui veulent former leurs équipes aux outils d'IA pour améliorer leur productivité. USTS propose des formations sur mesure, dispensées dans les locaux de l'entreprise cliente.

**Les indépendants et entrepreneurs** : Des freelances, consultants et créateurs d'entreprise qui veulent intégrer l'IA dans leur offre de services. Pour eux, USTS met l'accent sur les applications concrètes et le retour sur investissement rapide.

Ce positionnement permet à USTS d'éviter la confrontation directe avec les géants du secteur tout en adressant une demande réelle et croissante.

### Défis et opportunités

Les principaux défis sont la rapidité d'évolution des technologies et la concurrence croissante. Les opportunités résident dans l'expansion géographique et la commercialisation des produits internes.

## 1.3 Organisation et structure de l'équipe

### Une structure volontairement légère

USTS a fait le choix d'une structure organisationnelle légère et agile. L'équipe permanente reste volontairement restreinte, ce qui présente plusieurs avantages : flexibilité, rapidité de décision, et capacité à pivoter rapidement si nécessaire.

La structure se compose de :
- La direction, qui assure la stratégie et les relations commerciales
- L'équipe technique (développeurs), responsable des produits internes
- Les formateurs, souvent des intervenants externes spécialisés

Cette organisation favorise la polyvalence. Chaque membre de l'équipe technique est amené à intervenir sur l'ensemble de la chaîne de développement : conception, développement backend et frontend, tests, déploiement et maintenance. Il n'y a pas de silos entre "développeurs backend" et "développeurs frontend" comme dans les grandes structures.

### Mon tuteur : Lilian Garcia

Durant mon stage, j'ai travaillé sous la supervision directe de Lilian Garcia, qui cumule les fonctions de responsable technique et de formateur. Sa méthode de management repose sur l'autonomie progressive : accompagnement rapproché au début, puis autonomie croissante au fil des semaines.

## 1.4 Ma place dans l'organisation

### Intégration comme développeur Full Stack

En tant que développeur Full Stack stagiaire, j'ai été intégré comme membre à part entière de l'équipe technique. Mon rôle consistait à contribuer au développement des produits internes, avec une autonomie croissante au fil du stage.

Concrètement, cela signifiait que je participais :
- Aux réunions techniques hebdomadaires où l'équipe discute des priorités et des problèmes rencontrés
- Aux revues de code, où chaque développeur présente son travail et reçoit des retours
- Aux sessions de pair programming occasionnelles avec mon tuteur
- À la documentation des fonctionnalités développées

### Responsabilités confiées

Dès les premières semaines, des responsabilités réelles m'ont été confiées : j'ai développé des fonctionnalités utilisées en production. Cette immersion m'a permis de comprendre les enjeux business derrière chaque décision technique.

---

<!-- ============================================================ -->
<!-- PARTIE 2 : LA MISSION                                        -->
<!-- ============================================================ -->

# PARTIE 2

# La Mission

*Les missions définies par mon tuteur, replacées dans leur contexte plus général*

---

## 2.1 Contexte particulier du stage

### Une organisation en deux phases

Mon stage s'est déroulé de manière inhabituelle, en deux phases distinctes séparées par une période d'arrêt maladie de six semaines. Cette circonstance a profondément influencé la nature et l'organisation de mes missions.

| Période | Dates | Projet assigné | Durée effective |
|---------|-------|----------------|-----------------|
| Phase 1 | 1er sept. - 8 oct. 2025 | Zitelou | ~5 semaines |
| Arrêt maladie | 9 oct. - 20 nov. 2025 | - | 6 semaines |
| Phase 2 | 21 nov. - 31 déc. 2025 | Jean-François SAIA | ~6 semaines |

La première phase, sur le projet Zitelou, correspondait à la mission initialement prévue pour mon stage. L'arrêt maladie a interrompu ce travail de manière inattendue. À mon retour, les priorités de l'entreprise avaient évolué et j'ai été réaffecté sur un projet différent, Jean-François SAIA, avec de nouveaux objectifs.

### Impact sur les attentes

Cette situation a modifié les attentes de mon tuteur. Plutôt que de pouvoir me former progressivement sur un seul projet pendant quatre mois, il a dû gérer deux montées en compétence distinctes et des objectifs réajustés en cours de route.

De mon côté, j'ai dû faire preuve d'adaptabilité pour rebondir après l'arrêt maladie et me montrer rapidement productif sur un nouveau projet.

## 2.2 Première mission : Projet Zitelou

### Présentation générale du projet

**Zitelou** est une application mobile destinée à transformer un smartphone Android standard en téléphone sécurisé pour enfants de 5 à 12 ans. Le concept repose sur une idée simple mais pertinente : plutôt que d'acheter un téléphone dédié coûteux pour son enfant, le parent peut recycler un ancien smartphone en le configurant avec Zitelou.

L'application verrouille l'accès aux applications non autorisées, permet de définir des plages horaires d'utilisation, offre une géolocalisation de l'enfant et facilite la communication entre parents et enfants via des fonctions d'appel et de messagerie simplifiées.

Ce projet s'inscrit dans le marché du contrôle parental numérique, un secteur en croissance avec la multiplication des écrans et l'abaissement de l'âge d'équipement des enfants. Les solutions existantes sont souvent complexes, coûteuses ou intrusives. Zitelou vise à proposer une alternative simple et abordable.

### Architecture de l'écosystème Zitelou

L'écosystème comprend : une application Android enfant (verrouillage et synchronisation), une application Android parent (gestion et localisation), un backend API (authentification, abonnements), et un back-office administrateur.

### Ma mission définie sur Zitelou

Ma mission consistait à développer le **backend API** du projet. À mon arrivée, une base existait mais restait incomplète. Les objectifs fixés par mon tuteur étaient les suivants :

**Objectif 1 : Implémenter l'authentification sécurisée**
Le système devait permettre aux utilisateurs de se connecter de manière sécurisée via un mécanisme de tokens JWT (JSON Web Tokens). Cette technologie standard permet une authentification sans état, particulièrement adaptée aux applications mobiles.

**Objectif 2 : Développer les endpoints de gestion**
L'API devait exposer des interfaces pour créer, lire, modifier et supprimer les différentes entités : utilisateurs (parents), enfants rattachés et appareils associés. Ces endpoints devaient respecter les conventions REST et être correctement documentés.

**Objectif 3 : Intégrer le système de paiement Stripe**
Zitelou fonctionne sur un modèle d'abonnement mensuel. L'intégration Stripe devait permettre la création de sessions de paiement, la gestion des abonnements récurrents et la réception des notifications de paiement (webhooks).

**Objectif 4 : Mettre en place les tests automatisés**
Pour garantir la qualité et la maintenabilité du code, une suite de tests automatisés devait être développée, couvrant les scénarios critiques.

**Objectif 5 : Documenter l'API**
Une documentation technique devait permettre aux développeurs des applications mobiles de comprendre et d'utiliser l'API.

### Contexte plus large de la mission

Cette mission s'inscrivait dans l'objectif plus large de livrer une première version fonctionnelle de Zitelou aux beta-testeurs avant la fin de l'année. Mon travail sur le backend devait permettre aux développeurs mobiles d'avancer sur les applications Android en parallèle.

## 2.3 Seconde mission : Projet Jean-François SAIA

### Présentation générale du projet

**Jean-François SAIA** (souvent abrégé en "SAIA") est une plateforme SaaS complète destinée à la création de sites web, la génération de vidéos marketing par IA, et la gestion des publications sur les réseaux sociaux.

Le nom "Jean-François" fait référence à un personnage fictif représentant l'utilisateur type : un entrepreneur, artisan ou professionnel libéral qui souhaite créer rapidement du contenu web professionnel sans disposer de compétences techniques ni de budget conséquent pour un prestataire.

Cette plateforme illustre parfaitement la stratégie d'USTS : créer un produit utilisant massivement l'IA, qui peut être commercialisé mais aussi servir de démonstration lors des formations.

### Fonctionnalités de la plateforme

La plateforme SAIA propose plusieurs modules complémentaires :

**Perfect Wizard** : Un assistant de création de landing pages guidé par l'IA. L'utilisateur répond à quelques questions sur son activité, et l'IA génère automatiquement une page web complète avec textes, images et mise en page professionnelle. Un système de preview permet de visualiser le résultat en temps réel.

**Génération de vidéos** : L'utilisateur peut créer des vidéos marketing courtes (30 secondes à 2 minutes) en décrivant simplement ce qu'il souhaite. L'IA génère le script, les visuels et assemble le tout en vidéo.

**Génération de logos** : Un module permet de créer un logo professionnel par IA, en quelques clics.

**Publication LinkedIn** : La plateforme peut publier directement du contenu sur le compte LinkedIn de l'utilisateur, avec des suggestions de posts générés par IA.

**Déploiement automatique** : Les sites créés sont automatiquement déployés sur des sous-domaines et accessibles publiquement en quelques minutes.

### Ma mission définie sur SAIA

À mon retour d'arrêt maladie le 21 novembre 2025, j'ai été affecté à ce projet. L'équipe avait besoin de renfort pour atteindre les objectifs de fin d'année. Les missions fixées étaient :

**Objectif 1 : Enrichir le système de génération de médias**
La plateforme permettait de générer des textes par IA, mais les médias (images, vidéos) restaient limités. Ma mission était d'intégrer plusieurs sources : des banques d'images gratuites (Unsplash, Pexels) et de la génération d'images par IA (Google Imagen).

**Objectif 2 : Améliorer le système de templates par secteur**
Les templates de sites étaient trop génériques. Je devais créer des variantes adaptées par secteur d'activité (restaurant, immobilier, coach, artisan) pour des résultats plus pertinents.

**Objectif 3 : Corriger les bugs de preview et génération**
Le système de preview présentait de nombreux bugs affectant l'expérience utilisateur. Leur correction était prioritaire.

**Objectif 4 : Finaliser la documentation de passation**
L'entreprise anticipait que je ne serais pas disponible indéfiniment sur ce projet. Une documentation technique complète devait permettre à un autre développeur de reprendre mon travail.

### Contexte plus large de la mission

Cette mission s'inscrivait dans un double objectif : d'une part, livrer une version complète et stable de la plateforme avant la fin de l'année 2025 ; d'autre part, assurer la continuité du projet après mon départ en préparant une passation technique de qualité.

---

<!-- ============================================================ -->
<!-- PARTIE 3 : L'ACCOMPLISSEMENT                                 -->
<!-- ============================================================ -->

# PARTIE 3

# L'Accomplissement de la Mission

*Ce que j'ai produit, les facilités et difficultés rencontrées*

---

## 3.1 Réalisations sur le projet Zitelou

### Bilan des objectifs

Malgré une période de travail raccourcie à environ cinq semaines, j'ai pu accomplir une partie significative des objectifs fixés.

| Objectif | Statut | Commentaire |
|----------|--------|-------------|
| Authentification JWT | Terminé | Système fonctionnel et testé |
| Endpoints de gestion | Terminé | Utilisateurs, enfants, appareils |
| Intégration Stripe Checkout | Terminé | Session de paiement fonctionnelle |
| Webhooks Stripe | Partiel | Événements principaux, certains manquants |
| Tests automatisés | Terminé | 49 tests, 85% couverture |
| Documentation API | Partiel | Structure créée, contenu incomplet |

### Détail des réalisations techniques

**Authentification JWT**
J'ai implémenté un système complet d'authentification basé sur les tokens JWT. L'utilisateur envoie ses identifiants (email et mot de passe), le serveur vérifie ces informations et renvoie un token signé. Ce token, inclus dans chaque requête suivante, permet d'identifier l'utilisateur sans avoir à retransmettre ses identifiants.

J'ai également implémenté le renouvellement automatique des tokens et la gestion des tokens révoqués pour la déconnexion.

**Endpoints REST**
J'ai développé les interfaces permettant de gérer les trois entités principales :
- Les utilisateurs (inscription, connexion, modification du profil)
- Les enfants rattachés (création, modification, suppression)
- Les appareils (association d'un téléphone à un enfant)

Chaque endpoint respecte les conventions REST et inclut la validation des données entrantes.

**Intégration Stripe**
L'intégration du système de paiement Stripe permet de créer des sessions de paiement sécurisées. Quand un utilisateur souhaite s'abonner, l'application le redirige vers une page Stripe où il saisit ses informations bancaires. Une fois le paiement validé, Stripe notifie notre serveur via un webhook.

**Tests automatisés**
J'ai développé une suite de 49 tests couvrant les scénarios critiques : authentification, gestion des entités, cas d'erreur. La couverture de code atteint 85%, ce qui garantit que la majorité du code est effectivement testée.

### Métriques finales sur Zitelou

À la date de mon arrêt maladie (8 octobre 2025), le projet présentait les métriques suivantes :
- 6 commits sur le repository
- 49 tests passant avec 129 assertions
- 85% de couverture de code
- 0 erreur d'analyse statique
- Backend fonctionnel pour le MVP

## 3.2 Réalisations sur le projet SAIA

### Bilan des objectifs

La seconde phase du stage, sur le projet SAIA, a été particulièrement intensive et productive. En six semaines, j'ai contribué de manière significative à l'enrichissement de la plateforme.

| Objectif | Statut | Commentaire |
|----------|--------|-------------|
| Système de médias | Terminé | Stock + IA intégrés |
| Templates par secteur | Terminé | Variants implémentés |
| Correction bugs preview | Terminé | ~15 bugs résolus |
| Documentation passation | Terminé | 7 documents, note A- |

### Système de génération de médias

La réalisation majeure de cette période fut le développement d'un système complet de génération de médias. Ce système permet d'enrichir automatiquement les sites web créés avec des images et vidéos pertinentes.

**Architecture du système**
J'ai conçu une architecture modulaire permettant d'utiliser plusieurs sources de médias :
- Unsplash : banque d'images HD gratuites, excellente qualité
- Pexels : banque d'images et vidéos gratuites
- Google Imagen : génération d'images par IA

L'utilisateur peut choisir sa stratégie préférée : uniquement des images stock (gratuites), uniquement de l'IA (plus personnalisé mais consomme des crédits), ou un mix des deux.

**Services développés**
J'ai créé trois services distincts :
- Un service d'images stock qui interroge Unsplash et Pexels
- Un service d'images IA qui utilise Google Imagen
- Un orchestrateur qui coordonne ces services selon la stratégie choisie

**Composants visuels**
J'ai également développé des composants permettant d'afficher ces médias de manière attractive : arrière-plans vidéo avec overlay configurable, galeries d'images responsives.

### Templates par secteur d'activité

Les templates de sites générés étaient auparavant génériques. J'ai développé des variantes adaptées à différents secteurs d'activité.

Chaque secteur dispose maintenant de visuels, de textes d'exemple et d'une mise en page adaptés. Un restaurateur verra des suggestions différentes d'un coach sportif ou d'un agent immobilier.

Cette personnalisation améliore significativement la pertinence des sites générés et réduit le travail de personnalisation nécessaire pour l'utilisateur.

### Corrections de bugs

J'ai résolu une quinzaine de bugs affectant le système de preview et la génération de sites. Ces bugs dégradaient l'expérience utilisateur et pouvaient bloquer complètement la création de sites dans certains cas.

Les corrections ont notamment porté sur :
- Des problèmes de chargement de composants visuels
- Des timeouts lors de la génération
- Des incohérences entre le preview et le site final
- Des erreurs de gestion des images uploadées

### Documentation de passation

Conformément à l'objectif fixé, j'ai rédigé une documentation technique complète de passation. Cette documentation comprend sept documents distincts :

1. Un index de la passation présentant l'ensemble des documents
2. Une documentation technique détaillant l'architecture
3. Une présentation des fonctionnalités majeures
4. Une liste des bugs connus et leurs solutions
5. Un état d'avancement des spécifications
6. Un document listant les accès aux services externes
7. Un audit de qualité de la passation

Cette documentation a été évaluée et a obtenu la note A- (très bon), avec un temps d'onboarding estimé à 30 minutes pour être opérationnel et 3 heures pour une compréhension complète.

### Métriques finales sur SAIA

Les métriques de ma période sur SAIA témoignent de l'intensité du travail fourni :
- Environ 100 commits sur le repository
- Plus de 130 fichiers modifiés
- Plus de 22 000 lignes de code ajoutées
- 8 nouveaux services et composants créés
- 7 documents de passation rédigés
- Note de passation : A-

## 3.3 Facilités rencontrées

### Autonomie et confiance accordées

Mon tuteur m'a accordé une grande autonomie dans mes choix d'implémentation. Cette confiance m'a permis de proposer des solutions créatives et de les mettre en oeuvre sans validation préalable systématique.

Par exemple, pour le système de génération de médias, j'ai pu concevoir l'architecture de bout en bout, en justifiant mes choix a posteriori lors des revues de code. Cette responsabilisation a été très motivante.

### Qualité de la documentation existante

Sur le projet SAIA, la documentation existante était de bonne qualité. Les cahiers des charges et spécifications m'ont permis de comprendre rapidement le contexte et les attentes, sans avoir à déranger constamment mon tuteur pour des clarifications.

### Technologies bien documentées

Les technologies utilisées disposent d'excellentes documentations officielles et de communautés actives. Que ce soit Next.js, TypeScript, Prisma ou les APIs des services d'IA, j'ai pu trouver rapidement des réponses à mes questions techniques.

### Environnement de développement mature

L'environnement de développement était bien configuré : scripts automatisés, linter, formateur de code, tests automatisés. Ces outils m'ont permis de me concentrer sur le code métier plutôt que sur la configuration.

## 3.4 Difficultés rencontrées

### L'arrêt maladie : impact humain et organisationnel

La difficulté majeure de ce stage fut l'arrêt maladie de six semaines, du 9 octobre au 20 novembre 2025. Au-delà de l'aspect médical, cette interruption a eu plusieurs conséquences importantes.

**La frustration de l'inachevé**
Quitter le projet Zitelou alors que le travail était en cours a généré un sentiment d'inachèvement. J'avais développé une compréhension du métier, une connaissance du code, et tout cela a dû être mis de côté.

**L'anxiété du retour**
Pendant mon arrêt, je me suis interrogé sur l'accueil qui me serait réservé à mon retour. Est-ce que l'entreprise voudrait encore de moi ? Est-ce que mes collègues m'en voudraient d'avoir été absent si longtemps ?

**La pression temporelle**
À mon retour, il restait six semaines avant la fin du stage. Il fallait rattraper le temps perdu tout en se formant à un nouveau projet. Cette pression a été difficile à gérer psychologiquement.

### Le changement de projet

Être affecté à un projet différent au retour présentait des avantages et des inconvénients.

L'avantage principal était de repartir de zéro, sans le poids du travail inachevé sur Zitelou. Le projet SAIA était aussi techniquement plus stimulant et correspondait davantage à mes intérêts.

L'inconvénient majeur était la nécessité d'une nouvelle montée en compétence. J'ai dû apprendre une stack technique différente (Next.js et TypeScript au lieu de Symfony et PHP) tout en étant immédiatement productif.

### Complexité technique du système de preview

Le système de preview de SAIA utilise WebContainer, une technologie permettant d'exécuter du code Node.js directement dans le navigateur. Cette technologie, bien qu'innovante, génère de nombreux bugs difficiles à diagnostiquer.

Les problèmes rencontrés incluaient :
- Des composants qui ne se chargeaient pas correctement
- Des timeouts aléatoires lors de la génération
- Des différences inexplicables entre le preview et le site final déployé

La résolution de ces problèmes m'a demandé beaucoup de temps, de persévérance et de lectures de documentation technique pointue.

### Gestion des URLs et des images

Un bug particulièrement subtil m'a occupé plusieurs jours. Les images uploadées par les utilisateurs généraient des URLs de type "blob:", qui fonctionnent côté navigateur mais pas côté serveur. J'ai dû implémenter une détection du type d'URL et des traitements différenciés.

### Le rythme de fin de stage

La dernière semaine de décembre a été exceptionnellement intense : 14 commits en une seule journée (le 31 décembre), près de 22 000 lignes de code ajoutées, 7 documents de passation rédigés.

Ce rythme, s'il a permis d'atteindre tous les objectifs fixés, n'est pas soutenable sur le long terme. Il reflète la pression ressentie pour compenser l'absence due à l'arrêt maladie.

---

<!-- ============================================================ -->
<!-- PARTIE 4 : CONCLUSION                                        -->
<!-- ============================================================ -->

# PARTIE 4

# Conclusion

*Ce que ce stage m'a appris sur l'industrie, le business, mes connaissances organisationnelles et techniques, et ce que ma mission a apporté à l'entreprise*

---

## 4.1 Apprentissages sur l'industrie et le business

### Le marché de l'IA : opportunités et défis

Ce stage m'a permis de découvrir de l'intérieur le marché de la formation et des outils d'intelligence artificielle. Plusieurs constats ont marqué ma réflexion.

Premièrement, la demande pour les compétences IA est réelle et croissante. Les entreprises de toutes tailles cherchent à intégrer ces technologies, mais manquent souvent de ressources humaines qualifiées.

Deuxièmement, les clients recherchent des solutions pratiques et immédiates, pas des gadgets technologiques. Une fonctionnalité doit apporter une valeur concrète pour être adoptée.

Troisièmement, la capacité à intégrer plusieurs services d'IA différents est un avantage compétitif. Les plateformes qui savent orchestrer GPT, Gemini, Imagen et d'autres services offrent une expérience plus riche que celles qui se limitent à une seule technologie.

### Les réalités du développement professionnel

Au-delà des aspects techniques, j'ai découvert plusieurs réalités du monde professionnel.

**Les deadlines sont réelles** : contrairement aux projets scolaires où un retard se traduit par une mauvaise note, en entreprise les retards ont des conséquences business. Un client qui attend, un lancement reporté, une démonstration ratée.

**Le code legacy existe** : reprendre le code écrit par quelqu'un d'autre fait partie du quotidien. Il faut savoir comprendre la logique d'un autre développeur, s'adapter à ses conventions, et parfois accepter des choix qu'on n'aurait pas faits.

**L'imprévu fait partie du jeu** : maladie, bugs bloquants, changements de priorités, évolutions technologiques. La capacité à s'adapter est au moins aussi importante que les compétences techniques pures.

## 4.2 Connaissances organisationnelles acquises

### Gestion de projet et priorisation

J'ai appris à prioriser les tâches selon leur impact business. Toutes les fonctionnalités ne se valent pas : certaines sont critiques pour le lancement, d'autres peuvent attendre.

Cette priorisation implique de savoir dire non ou "plus tard" à certaines demandes, et de se concentrer sur ce qui apporte le plus de valeur.

### Communication et transparence

J'ai compris l'importance de communiquer régulièrement sur l'avancement, surtout quand les choses ne vont pas comme prévu. Un problème signalé tôt peut être résolu ; un problème caché devient une crise.

La transparence sur les difficultés n'est pas un aveu de faiblesse mais une marque de professionnalisme.

### Documentation continue

L'expérience de rédaction de la documentation de passation m'a convaincu de l'importance de documenter au fil de l'eau. Attendre la fin d'un projet pour documenter est une erreur : on oublie les détails, on manque de temps, et le résultat est de moindre qualité.

## 4.3 Connaissances techniques acquises

### Compétences backend

J'ai approfondi mes compétences en développement backend avec deux technologies différentes :

En PHP avec Symfony et API Platform, j'ai appris à structurer une API REST professionnelle, à gérer l'authentification JWT et à intégrer des services de paiement.

En TypeScript avec Next.js et Prisma, j'ai découvert une approche différente, plus orientée full-stack, avec une gestion élégante des types et une intégration base de données simplifiée.

### Compétences frontend

J'ai développé mes compétences en React et en styling avec TailwindCSS. La création de composants réutilisables, la gestion de l'état avec Zustand, et l'intégration de bibliothèques de composants comme shadcn/ui font maintenant partie de mon arsenal technique.

### Intégration de services d'IA

L'aspect le plus formateur techniquement fut l'intégration de multiples services d'IA. J'ai appris à utiliser les APIs de Google (Gemini pour le texte, Imagen pour les images, Veo pour les vidéos), d'OpenAI, et de services de stock media.

Cette expérience me positionne favorablement pour les évolutions du marché, où l'intégration d'IA dans les applications devient la norme.

## 4.4 Apport de ma mission à l'entreprise

### Sur le projet Zitelou

Mon travail sur Zitelou, bien qu'interrompu, a posé des bases solides :
- Une architecture backend propre et testée
- Une intégration Stripe fonctionnelle
- Une couverture de tests de 85%

Ces fondations permettront une reprise plus rapide du développement, avec moins de dette technique à gérer.

### Sur le projet SAIA

Mon apport sur SAIA a été plus conséquent et visible :

**Le système de génération de médias** constitue une fonctionnalité majeure qui enrichit significativement les sites créés par les utilisateurs. Cette valeur ajoutée peut justifier une tarification plus élevée.

**Les templates par secteur** améliorent la pertinence des sites générés, réduisant le temps de personnalisation pour l'utilisateur final.

**La correction des bugs** a stabilisé la plateforme et amélioré l'expérience utilisateur, réduisant potentiellement le taux d'abandon.

**La documentation de passation** représente un investissement important pour l'entreprise. Elle permettra à un nouveau développeur d'être opérationnel en quelques heures plutôt qu'en plusieurs jours. La note A- obtenue à l'audit valide la qualité de ce travail.

## 4.5 Bilan personnel et perspectives

Ce stage a confirmé mon intérêt pour le développement Full Stack. La variété des technologies manipulées m'a permis d'affiner mes préférences : j'apprécie particulièrement l'écosystème TypeScript/Next.js pour sa cohérence et sa productivité.

L'expérience de l'arrêt maladie, bien que difficile, m'a appris l'importance de la résilience. J'ai su rebondir, me réadapter à un nouveau contexte, et finalement atteindre tous les objectifs fixés. Cette capacité d'adaptation sera un atout pour ma carrière.

Les axes d'amélioration que j'ai identifiés pour moi-même :
- Mieux estimer le temps nécessaire aux tâches (tendance à sous-estimer)
- Écrire les tests en parallèle du code plutôt qu'après
- Documenter de manière continue plutôt qu'en fin de projet
- Mieux gérer le stress des deadlines serrées

Ce stage représente une étape importante dans mon parcours. Il m'a donné confiance en mes capacités techniques et m'a montré que je pouvais apporter une vraie valeur à une entreprise, même en tant que stagiaire et malgré des circonstances difficiles.

---

*Rapport rédigé par Patrick Saint-Laurent NGANE*
*Stage effectué du 1er septembre au 31 décembre 2025*
*USTS - Formation IA, Paris*
*Epitech Paris - TEK 2, Promotion 2025-2026*
