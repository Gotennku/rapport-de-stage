# Rapport de Stage

## Développeur Full Stack
### USTS - Formation IA

---

**Patrick Saint-Laurent NGANE**

Epitech Paris - TEK 2
Promotion 2025-2026

Stage du 1er septembre au 31 décembre 2025

Tuteur entreprise : Lilian Garcia
1 rue Fulton, 75013 Paris

---

<!-- PAGE 1 -->

# Remerciements

Je tiens à exprimer ma gratitude envers l'ensemble des personnes qui ont contribué au bon déroulement de ce stage.

Je remercie tout d'abord **Lilian Garcia**, mon tuteur de stage chez USTS, pour sa confiance, son accompagnement technique et sa patience tout au long de ces quatre mois. Sa disponibilité et ses conseils m'ont permis de progresser significativement dans ma pratique du développement.

Je remercie également l'équipe pédagogique d'**Epitech Paris** pour la formation pratique qui m'a préparé à relever les défis techniques rencontrés durant ce stage.

Enfin, je remercie ma famille pour son soutien constant, particulièrement durant ma période d'arrêt maladie qui a interrompu temporairement mon stage.

---

<!-- PAGE 2 -->

# Résumé

Ce rapport présente mon stage de quatre mois effectué chez **USTS**, une entreprise spécialisée dans la formation à l'intelligence artificielle, située à Paris. En tant que développeur Full Stack, j'ai contribué à deux projets distincts : **Zitelou**, une application de contrôle parental pour smartphones Android, et **Jean-François SAIA**, une plateforme SaaS de création de sites web et de génération de contenu par IA.

Le stage a été marqué par une période d'arrêt maladie du 9 octobre au 20 novembre 2025, ce qui a nécessité une réorganisation des priorités et une intensification du travail sur le second projet.

Sur le projet Zitelou, j'ai développé le backend en Symfony 7.3 avec API Platform, implémentant l'authentification JWT et l'intégration Stripe. Sur le projet Jean-François SAIA, j'ai contribué de manière intensive à une plateforme Next.js 14 intégrant plusieurs services d'IA (Gemini, GPT-4, Veo 3.1, Imagen 3.0), aboutissant à une passation technique notée A-.

**Mots-clés** : Full Stack, Next.js, Symfony, API Platform, Intelligence Artificielle, SaaS, TypeScript, PHP

---

# Abstract

This report presents my four-month internship at **USTS**, a company specializing in artificial intelligence training, located in Paris. As a Full Stack developer, I contributed to two distinct projects: **Zitelou**, a parental control application for Android smartphones, and **Jean-François SAIA**, a SaaS platform for website creation and AI-powered content generation.

The internship was marked by a sick leave period from October 9 to November 20, 2025, which required reorganizing priorities and intensifying work on the second project.

On the Zitelou project, I developed the backend using Symfony 7.3 with API Platform, implementing JWT authentication and Stripe integration. On the Jean-François SAIA project, I contributed intensively to a Next.js 14 platform integrating multiple AI services (Gemini, GPT-4, Veo 3.1, Imagen 3.0), resulting in a technical handover rated A-.

**Keywords**: Full Stack, Next.js, Symfony, API Platform, Artificial Intelligence, SaaS, TypeScript, PHP

---

<!-- PAGE 3 -->

# Table des matières

1. [Introduction](#introduction)
2. [Présentation de l'entreprise](#1-présentation-de-lentreprise)
   - 2.1 [USTS - Formation IA](#11-usts---formation-ia)
   - 2.2 [Contexte et positionnement](#12-contexte-et-positionnement)
   - 2.3 [Organisation et équipe](#13-organisation-et-équipe)
3. [Missions et objectifs](#2-missions-et-objectifs)
   - 3.1 [Contexte global du stage](#21-contexte-global-du-stage)
   - 3.2 [Projet Zitelou](#22-projet-zitelou)
   - 3.3 [Projet Jean-François SAIA](#23-projet-jean-françois-saia)
4. [Analyses techniques et méthodologie](#3-analyses-techniques-et-méthodologie)
   - 4.1 [Architecture du projet Zitelou](#31-architecture-du-projet-zitelou)
   - 4.2 [Architecture du projet SAIA](#32-architecture-du-projet-saia)
   - 4.3 [Intégration des services d'IA](#33-intégration-des-services-dia)
   - 4.4 [Méthodologie de développement](#34-méthodologie-de-développement)
5. [Résultats et difficultés rencontrées](#4-résultats-et-difficultés-rencontrées)
   - 5.1 [Bilan du projet Zitelou](#41-bilan-du-projet-zitelou)
   - 5.2 [Bilan du projet SAIA](#42-bilan-du-projet-saia)
   - 5.3 [Difficultés techniques et humaines](#43-difficultés-techniques-et-humaines)
6. [Conclusion et prise de recul](#5-conclusion-et-prise-de-recul)
7. [Annexes](#annexes)

---

<!-- PAGE 4 -->

# Introduction

Dans le cadre de ma deuxième année à Epitech Paris (TEK 2), j'ai effectué un stage de quatre mois au sein de l'entreprise USTS, spécialisée dans la formation à l'intelligence artificielle. Ce stage, qui s'est déroulé du 1er septembre au 31 décembre 2025, m'a permis d'occuper le poste de développeur Full Stack et de contribuer à deux projets techniquement ambitieux.

L'objectif de ce rapport est de présenter de manière détaillée les missions qui m'ont été confiées, les choix techniques effectués, ainsi que les difficultés rencontrées et les solutions apportées. Ce stage a représenté une opportunité unique de mettre en pratique les compétences acquises durant ma formation, tout en découvrant les réalités du développement logiciel en environnement professionnel.

Le contexte particulier de ce stage mérite d'être mentionné dès l'introduction : une période d'arrêt maladie du 9 octobre au 20 novembre 2025 a interrompu mon travail pendant six semaines. Cette interruption a eu des conséquences sur l'organisation du stage, nécessitant une réaffectation sur un nouveau projet à mon retour et une intensification significative du rythme de travail pour atteindre les objectifs fixés.

Ce rapport s'articule autour de cinq parties principales. Après une présentation de l'entreprise USTS et de son positionnement sur le marché de la formation IA, je détaillerai les deux projets sur lesquels j'ai travaillé : Zitelou, une application de contrôle parental, et Jean-François SAIA, une plateforme SaaS de création de sites web. L'analyse technique approfondie des architectures mises en œuvre précédera un bilan des résultats obtenus et des difficultés surmontées. Enfin, je conclurai par une réflexion sur les apports de ce stage dans mon parcours professionnel.

---

<!-- PAGE 5 -->

# 1. Présentation de l'entreprise

## 1.1 USTS - Formation IA

**USTS** (prononcé "You-S-T-S") est une entreprise française fondée et spécialisée dans la formation professionnelle aux technologies de l'intelligence artificielle. Située au 1 rue Fulton dans le 13ème arrondissement de Paris, à proximité de la Bibliothèque François Mitterrand, l'entreprise occupe une position stratégique dans un quartier en pleine expansion numérique.

L'activité principale d'USTS consiste à proposer des formations sur les outils et méthodes liés à l'intelligence artificielle, à destination des professionnels souhaitant acquérir ou renforcer leurs compétences dans ce domaine en constante évolution. L'entreprise se distingue par son approche pratique, privilégiant les cas d'usage concrets et les mises en situation professionnelles.

En parallèle de son activité de formation, USTS développe des projets internes qui servent à la fois de supports pédagogiques et de produits commercialisables. C'est dans ce cadre que s'inscrivent les deux projets sur lesquels j'ai travaillé durant mon stage.

## 1.2 Contexte et positionnement

Le marché de la formation à l'intelligence artificielle connaît une croissance exponentielle depuis l'émergence des grands modèles de langage (LLM) et des outils de génération de contenu. USTS se positionne comme un acteur agile, capable de s'adapter rapidement aux évolutions technologiques et de proposer des formations actualisées.

L'entreprise cible principalement :
- Les professionnels en reconversion vers les métiers du numérique
- Les entreprises souhaitant former leurs équipes aux outils d'IA
- Les indépendants cherchant à intégrer l'IA dans leur activité

Cette orientation vers la pratique se reflète dans la nature des projets développés en interne, qui doivent être suffisamment aboutis pour servir de démonstrations lors des formations.

## 1.3 Organisation et équipe

Durant mon stage, j'ai travaillé sous la supervision directe de **Lilian Garcia**, qui cumule les fonctions de responsable technique et de formateur. Cette organisation relativement horizontale m'a permis de bénéficier d'un accompagnement personnalisé et d'échanges techniques réguliers.

L'équipe technique reste volontairement restreinte, ce qui favorise la polyvalence et l'autonomie des développeurs. Chaque membre est amené à intervenir sur l'ensemble de la chaîne de développement, du backend au frontend, en passant par le déploiement et la maintenance.

---

<!-- PAGE 6 -->

# 2. Missions et objectifs

## 2.1 Contexte global du stage

Mon stage s'est déroulé en deux phases distinctes, séparées par une période d'arrêt maladie de six semaines :

| Période | Dates | Projet | Durée effective |
|---------|-------|--------|-----------------|
| Phase 1 | 1er sept. - 8 oct. 2025 | Zitelou | ~5 semaines |
| Arrêt maladie | 9 oct. - 20 nov. 2025 | - | 6 semaines |
| Phase 2 | 21 nov. - 31 déc. 2025 | Jean-François SAIA | ~6 semaines |

Cette organisation inhabituelle a profondément influencé la nature de mon travail. La première phase, sur le projet Zitelou, a été interrompue prématurément, ce qui a généré une certaine frustration de ne pas avoir pu mener à bien les fonctionnalités entamées. La seconde phase a nécessité une montée en compétence rapide sur un projet complexe et une forte intensité de travail pour rattraper le temps perdu.

## 2.2 Projet Zitelou

### 2.2.1 Présentation du projet

**Zitelou** est une application mobile destinée à transformer un smartphone Android standard en téléphone sécurisé pour enfants de 5 à 12 ans. Le concept repose sur l'idée de réutiliser les anciens smartphones des parents plutôt que d'acheter des appareils dédiés coûteux.

L'application comprend :
- **Une application Android** installée sur le téléphone de l'enfant, verrouillant l'accès aux applications non autorisées
- **Une application parent** permettant de gérer les autorisations et de localiser l'enfant
- **Un backend API** gérant l'authentification, les abonnements et la synchronisation des données
- **Un back-office administrateur** pour la gestion des utilisateurs et le suivi des métriques

### 2.2.2 Ma mission sur Zitelou

Ma mission consistait à développer le **backend API** du projet, en partant d'une base existante mais incomplète. Les objectifs fixés étaient :

1. **Implémenter l'authentification JWT** pour sécuriser les échanges entre les applications et l'API
2. **Développer les endpoints CRUD** pour la gestion des utilisateurs, enfants et appareils
3. **Intégrer Stripe** pour la gestion des abonnements (checkout, webhooks, portail de facturation)
4. **Mettre en place les tests automatisés** pour garantir la qualité du code
5. **Documenter l'API** via OpenAPI/Swagger

### 2.2.3 Technologies imposées

Le choix technologique pour ce projet avait été fait avant mon arrivée :

| Composant | Technologie | Version |
|-----------|-------------|---------|
| Framework | Symfony | 7.3 |
| API | API Platform | 4.1 |
| Langage | PHP | 8.3 |
| Base de données | MariaDB | 10.11 |
| Authentification | LexikJWTAuthenticationBundle | - |
| Paiements | Stripe PHP SDK | - |

---

<!-- PAGE 7 -->

## 2.3 Projet Jean-François SAIA

### 2.3.1 Présentation du projet

**Jean-François SAIA** (souvent abrégé en "SAIA") est une plateforme SaaS complète destinée à la création de sites web, la génération de vidéos marketing par IA, et la gestion des publications sur les réseaux sociaux. Le nom "Jean-François" fait référence à un personnage fictif représentant l'utilisateur type : un entrepreneur ou marketeur souhaitant créer rapidement du contenu professionnel sans compétences techniques.

La plateforme propose plusieurs modules :

| Module | Description | État |
|--------|-------------|------|
| **Perfect Wizard** | Génération de landing pages par IA avec preview en temps réel | Production |
| **Génération Vidéo** | Création de vidéos marketing via Veo 3.1 et Replicate | Production |
| **Génération Logo** | Création de logos via Google Imagen 3.0 | Production |
| **LinkedIn** | OAuth, publication de posts et vidéos | Production |
| **Campagnes** | Module marketing (réservé aux agences) | Production |
| **Déploiement** | Auto-deploy sur sous-domaines *.usts.ai via Coolify | Production |
| **Paiements** | Intégration Stripe avec 4 plans tarifaires | Production |

### 2.3.2 Ma mission sur SAIA

À mon retour d'arrêt maladie le 21 novembre 2025, j'ai été affecté à ce projet en remplacement de Zitelou. L'équipe avait besoin de renfort pour atteindre les objectifs de fin d'année, notamment :

1. **Enrichir le système de génération de médias** avec l'intégration d'APIs de stock (Unsplash, Pexels) et d'IA (Imagen 3.0)
2. **Améliorer le système de templates** avec des variants adaptés par secteur d'activité
3. **Corriger les bugs** de preview et de génération identifiés
4. **Finaliser la documentation de passation** technique pour permettre la reprise du projet par un autre développeur
5. **Implémenter des fonctionnalités transverses** (génération automatique de logos, analyse d'images pour captions, etc.)

### 2.3.3 Stack technique

La stack technique de SAIA est considérablement plus moderne et complexe que celle de Zitelou :

| Composant | Technologie | Version |
|-----------|-------------|---------|
| Framework | Next.js (App Router) | 14.x |
| Langage | TypeScript | Strict mode |
| UI | React + TailwindCSS + shadcn/ui | 18.x / 3.4 |
| État | Zustand | - |
| ORM | Prisma | 5.x |
| Base de données | PostgreSQL | - |
| Auth | NextAuth.js | - |
| Paiements | Stripe | - |
| Déploiement | Coolify + Docker | - |

### 2.3.4 Services d'IA intégrés

Un aspect particulièrement enrichissant de ce projet fut la manipulation de multiples services d'intelligence artificielle :

| Service | Usage | Modèle |
|---------|-------|--------|
| Google Gemini | Génération de contenu, prompts, captions | gemini-2.0-flash |
| OpenAI GPT-4 | Génération de contenu alternatif | gpt-4 |
| Google Vertex AI Veo | Génération de vidéos marketing | veo-002 / veo-3.1 |
| Replicate | Génération vidéo (alternative) | veo-3.1-fast |
| Google Imagen | Génération de logos et images | imagen-3.0 |
| Unsplash API | Images stock HD | - |
| Pexels API | Images et vidéos stock | - |

---

<!-- PAGE 8 -->

# 3. Analyses techniques et méthodologie

## 3.1 Architecture du projet Zitelou

### 3.1.1 Architecture globale

Le backend Zitelou suit une architecture classique API Platform, structurée autour des concepts de ressources REST :

```
zitelou-backend/
├── src/
│   ├── Controller/          # Contrôleurs personnalisés
│   ├── Entity/              # Entités Doctrine (User, Child, Device)
│   ├── Repository/          # Repositories Doctrine
│   ├── Security/            # Authentification JWT
│   ├── Service/             # Services métier (Stripe, etc.)
│   └── EventSubscriber/     # Webhooks Stripe
├── config/
│   ├── packages/
│   │   ├── api_platform.yaml
│   │   ├── lexik_jwt.yaml
│   │   └── doctrine.yaml
│   └── routes.yaml
└── tests/
    ├── Unit/
    └── Functional/
```

### 3.1.2 Modèle de données

Le schéma de base de données reflète les relations entre les entités principales :

```
┌─────────────┐       ┌─────────────┐       ┌─────────────┐
│    User     │       │    Child    │       │   Device    │
├─────────────┤       ├─────────────┤       ├─────────────┤
│ id          │──┐    │ id          │──┐    │ id          │
│ email       │  │    │ name        │  │    │ device_id   │
│ password    │  └───>│ user_id (FK)│  └───>│ child_id(FK)│
│ stripe_id   │       │ age         │       │ model       │
│ plan        │       │ avatar      │       │ os_version  │
└─────────────┘       └─────────────┘       └─────────────┘
```

### 3.1.3 Authentification JWT

L'authentification repose sur le bundle LexikJWTAuthenticationBundle. Le flux d'authentification implémenté est le suivant :

1. L'utilisateur envoie ses credentials (email/password) à `/api/login_check`
2. Le serveur valide les credentials et génère un token JWT signé
3. Le client stocke le token et l'inclut dans le header `Authorization: Bearer <token>` pour chaque requête
4. Les routes protégées vérifient la validité du token avant traitement

```php
// config/packages/lexik_jwt.yaml
lexik_jwt_authentication:
    secret_key: '%env(resolve:JWT_SECRET_KEY)%'
    public_key: '%env(resolve:JWT_PUBLIC_KEY)%'
    pass_phrase: '%env(JWT_PASSPHRASE)%'
    token_ttl: 3600
```

### 3.1.4 Intégration Stripe

L'intégration Stripe couvre trois cas d'usage principaux :

1. **Checkout Session** : Création d'une session de paiement pour l'abonnement initial
2. **Webhooks** : Réception des événements Stripe (paiement réussi, échec, annulation)
3. **Billing Portal** : Redirection vers le portail Stripe pour la gestion de l'abonnement

```php
// Exemple simplifié du service Stripe
class StripeService
{
    public function createCheckoutSession(User $user, string $priceId): Session
    {
        return Session::create([
            'customer' => $user->getStripeCustomerId(),
            'payment_method_types' => ['card'],
            'line_items' => [[
                'price' => $priceId,
                'quantity' => 1,
            ]],
            'mode' => 'subscription',
            'success_url' => $this->successUrl,
            'cancel_url' => $this->cancelUrl,
        ]);
    }
}
```

### 3.1.5 Qualité du code

À la fin de ma période sur Zitelou, les métriques de qualité étaient les suivantes :

| Métrique | Valeur |
|----------|--------|
| Tests | 49 tests, 129 assertions |
| Couverture classes | 75% |
| Couverture méthodes | 93.22% |
| Couverture lignes | 84.77% |
| PHPStan | Niveau 4, 0 erreurs |

---

<!-- PAGE 9 -->

## 3.2 Architecture du projet SAIA

### 3.2.1 Architecture Next.js App Router

Le projet SAIA utilise l'architecture App Router de Next.js 14, qui diffère significativement de l'ancien Pages Router :

```
jean-francois-saia/
├── app/                         # Next.js App Router
│   ├── dashboard/               # Routes dashboard (15+ pages)
│   │   ├── sites/              # Gestion des sites
│   │   ├── videos/             # Génération vidéos IA
│   │   ├── social/             # Réseaux sociaux (LinkedIn)
│   │   ├── campaigns/          # Campagnes marketing
│   │   ├── calendar/           # Calendrier éditorial
│   │   ├── analytics/          # Analytics
│   │   ├── team/               # Gestion équipe
│   │   ├── adn/                # Identité de marque
│   │   └── settings/           # Paramètres
│   ├── perfect/                 # Wizard création sites
│   │   ├── wizard/             # Étapes du wizard
│   │   └── preview/            # Preview WebContainer
│   ├── api/                     # Routes API
│   │   ├── auth/               # NextAuth
│   │   ├── sites/              # CRUD sites
│   │   ├── videos/             # Génération vidéos
│   │   ├── social/             # LinkedIn OAuth
│   │   ├── media/              # Génération médias
│   │   └── stripe/             # Webhooks Stripe
│   └── plans/                   # Page tarifs
├── components/
│   ├── ui/                      # shadcn/ui primitives
│   ├── dashboard/               # Composants dashboard
│   ├── organisms/               # Composants complexes
│   │   ├── media/              # VideoBackground, etc.
│   │   └── sites/              # MediaOptionsPanel, etc.
│   └── magic-ui/                # Effets visuels
├── lib/
│   ├── auth.ts                  # Config NextAuth
│   ├── prisma.ts                # Client Prisma
│   ├── ai/                      # Clients IA (Gemini, OpenAI)
│   ├── services/                # Services métier
│   │   ├── stock-images.service.ts
│   │   ├── ai-images.service.ts
│   │   └── media-generation.service.ts
│   └── social/                  # LinkedIn API
├── hooks/                       # React hooks custom
└── prisma/
    └── schema.prisma            # Schema BDD
```

### 3.2.2 Gestion d'état avec Zustand

Contrairement à Redux, Zustand offre une approche minimaliste de la gestion d'état :

```typescript
// Exemple de store Zustand
import { create } from 'zustand';

interface SiteStore {
  currentSite: Site | null;
  isGenerating: boolean;
  setCurrentSite: (site: Site) => void;
  setGenerating: (status: boolean) => void;
}

export const useSiteStore = create<SiteStore>((set) => ({
  currentSite: null,
  isGenerating: false,
  setCurrentSite: (site) => set({ currentSite: site }),
  setGenerating: (status) => set({ isGenerating: status }),
}));
```

### 3.2.3 Schéma Prisma

Le modèle de données de SAIA est plus complexe, gérant utilisateurs, sites, médias, posts sociaux et abonnements :

```prisma
model User {
  id            String    @id @default(cuid())
  email         String    @unique
  name          String?
  image         String?
  stripeCustomerId String?
  plan          Plan      @default(STARTER)
  credits       Int       @default(100)
  sites         Site[]
  socialAccounts SocialAccount[]
  videos        Video[]

  @@map("users")
}

model Site {
  id          String   @id @default(cuid())
  name        String
  subdomain   String   @unique
  content     Json
  deployed    Boolean  @default(false)
  deployedUrl String?
  userId      String
  user        User     @relation(fields: [userId], references: [id])

  @@map("sites")
}
```

---

<!-- PAGE 10 -->

## 3.3 Intégration des services d'IA

### 3.3.1 Architecture du système de génération de médias

L'une de mes contributions majeures sur SAIA fut le développement du système de génération de médias. Ce système orchestre plusieurs sources (stock et IA) selon une stratégie configurable :

```
┌─────────────────────────────────────────────────────────────────┐
│                    Media Generation System                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  Sources                                                        │
│  ├── Unsplash API (images HD libres de droits)                  │
│  ├── Pexels API (images + vidéos stock)                         │
│  ├── Google Imagen 3.0 (génération images IA)                   │
│  └── Google Veo 3.1 (génération vidéos IA)                      │
│                                                                 │
│  Stratégies                                                     │
│  ├── 'stock' : Libre de droit uniquement                        │
│  ├── 'ai' : Génération IA uniquement                            │
│  ├── 'mixed' : Stock prioritaire + IA si nécessaire             │
│  └── 'none' : Pas de médias automatiques                        │
│                                                                 │
│  Composants React                                               │
│  ├── VideoBackground (overlay configurable)                     │
│  └── ImageBackground (overlay configurable)                     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 3.3.2 Service d'images stock

Le service d'images stock agrège les résultats d'Unsplash et Pexels :

```typescript
// lib/services/stock-images.service.ts
export class StockImagesService {
  private unsplashClient: ReturnType<typeof createApi>;
  private pexelsClient: typeof createClient;

  async searchImages(query: string, count: number = 5): Promise<StockImage[]> {
    const [unsplashResults, pexelsResults] = await Promise.all([
      this.searchUnsplash(query, count),
      this.searchPexels(query, count),
    ]);

    return this.mergeAndRank([...unsplashResults, ...pexelsResults]);
  }

  private mergeAndRank(images: StockImage[]): StockImage[] {
    // Algorithme de ranking basé sur la pertinence et la qualité
    return images
      .sort((a, b) => b.relevanceScore - a.relevanceScore)
      .slice(0, 10);
  }
}
```

### 3.3.3 Service de génération IA

Le service d'images IA utilise Google Imagen 3.0 :

```typescript
// lib/services/ai-images.service.ts
export class AIImagesService {
  async generateImage(prompt: string, style?: string): Promise<GeneratedImage> {
    const enhancedPrompt = this.enhancePrompt(prompt, style);

    const response = await this.vertexClient.generateImage({
      model: 'imagen-3.0',
      prompt: enhancedPrompt,
      aspectRatio: '16:9',
      numberOfImages: 1,
    });

    return {
      url: response.images[0].url,
      prompt: enhancedPrompt,
      source: 'imagen-3.0',
    };
  }

  private enhancePrompt(prompt: string, style?: string): string {
    const stylePrefix = style ? `${style} style, ` : '';
    return `${stylePrefix}${prompt}, professional photography, high quality, 4K`;
  }
}
```

### 3.3.4 Orchestrateur de médias

L'orchestrateur centralise la logique de sélection de source :

```typescript
// lib/services/media-generation.service.ts
export class MediaGenerationService {
  async generateMedias(
    config: MediaConfig,
    strategy: 'stock' | 'ai' | 'mixed' | 'none'
  ): Promise<MediaResult> {
    if (strategy === 'none') return { images: [], videos: [] };

    if (strategy === 'stock') {
      return this.generateStockOnly(config);
    }

    if (strategy === 'ai') {
      return this.generateAIOnly(config);
    }

    // Mixed: essayer stock d'abord, fallback sur IA
    const stockResults = await this.generateStockOnly(config);
    if (stockResults.images.length >= config.minImages) {
      return stockResults;
    }

    const aiResults = await this.generateAIOnly({
      ...config,
      count: config.minImages - stockResults.images.length,
    });

    return {
      images: [...stockResults.images, ...aiResults.images],
      videos: [...stockResults.videos, ...aiResults.videos],
    };
  }
}
```

---

<!-- PAGE 11 -->

## 3.4 Méthodologie de développement

### 3.4.1 Workflow Git

Les deux projets suivent un workflow Git similaire, basé sur des branches de feature :

```bash
# Création d'une feature
git checkout -b feat/media-generation
# ... développement ...
npm run build    # Vérification build
npm run test     # Tests unitaires
git add . && git commit -m "feat(media): add rich media generation"
git push -u origin feat/media-generation
# Création de Pull Request
```

#### Conventions de commits

Les messages de commit suivent la convention Conventional Commits :

| Préfixe | Usage |
|---------|-------|
| `feat:` | Nouvelle fonctionnalité |
| `fix:` | Correction de bug |
| `refactor:` | Refactoring sans changement fonctionnel |
| `docs:` | Documentation |
| `test:` | Ajout/modification de tests |
| `chore:` | Maintenance |

### 3.4.2 Stratégie de tests

#### Sur Zitelou (PHP/Symfony)

```bash
# Tests unitaires et fonctionnels
./vendor/bin/phpunit

# Analyse statique
./vendor/bin/phpstan analyse src --level 4

# Tests de mutation
./vendor/bin/infection
```

#### Sur SAIA (TypeScript/Next.js)

```bash
# Tests unitaires
npm test

# Tests d'intégration
npm run test:integration

# Tests E2E
npm run test:e2e

# Tests de sécurité OWASP
npm run test:security
```

### 3.4.3 Déploiement continu

Le projet SAIA utilise Coolify pour le déploiement automatisé :

1. Push sur la branche `main`
2. Coolify détecte le changement et clone le repo
3. Build Docker via Nixpacks
4. Déploiement sur l'infrastructure USTS
5. Configuration automatique du reverse proxy Traefik
6. Disponibilité sur `jean-francois.usts.ai`

Pour les sites générés par les utilisateurs, un mécanisme similaire déploie sur des sous-domaines `*.usts.ai`.

### 3.4.4 Documentation

La documentation technique a été un aspect important de mon travail, particulièrement en fin de stage pour préparer la passation :

| Document | Description |
|----------|-------------|
| `README.md` | Quick start et vue d'ensemble |
| `PASSATION-TECHNIQUE.md` | Architecture détaillée (~800 lignes) |
| `ARCHITECTURE-FEATURES.md` | Design des 6 features majeures |
| `LISTE-BUGS-ET-CAUSES.md` | Bugs connus et solutions |
| `SPECS-ANNOTEES-V2.md` | État d'implémentation vs spécifications |
| `ACCES-SERVICES.md` | Credentials et accès |
| `AUDIT-PASSATION.md` | Audit exhaustif de la passation |

---

<!-- PAGE 12 -->

# 4. Résultats et difficultés rencontrées

## 4.1 Bilan du projet Zitelou

### 4.1.1 Réalisations

Malgré une période de travail raccourcie (environ 5 semaines), j'ai pu accomplir une partie significative des objectifs :

| Objectif | Statut | Commentaire |
|----------|--------|-------------|
| Authentification JWT | ✅ Terminé | Fonctionnel et testé |
| Endpoints CRUD | ✅ Terminé | User, Child, Device |
| Intégration Stripe Checkout | ✅ Terminé | Session de paiement fonctionnelle |
| Webhooks Stripe | ⚠️ Partiel | Événements principaux implémentés |
| Billing Portal | ✅ Terminé | Redirection fonctionnelle |
| Tests automatisés | ✅ Terminé | 49 tests, 84.77% couverture |
| Documentation API | ⚠️ Partiel | OpenAPI généré mais non complété |

### 4.1.2 Métriques finales

À la date de mon arrêt maladie (8 octobre 2025), le projet présentait les métriques suivantes :

- **6 commits** sur la période
- **49 tests** passant avec 129 assertions
- **84.77%** de couverture de code
- **0 erreur** PHPStan niveau 4
- **Backend fonctionnel** pour le MVP

### 4.1.3 Points non terminés

L'interruption prématurée a laissé plusieurs éléments en suspens :

1. Documentation OpenAPI incomplète
2. Webhooks Stripe partiellement implémentés (manque gestion des échecs de paiement)
3. Tests E2E non démarrés
4. Optimisation des performances non abordée

## 4.2 Bilan du projet SAIA

### 4.2.1 Réalisations

La seconde phase du stage a été particulièrement intensive et productive. En 6 semaines, j'ai contribué à :

#### Système de génération de médias (nouveau)

| Livrable | Fichiers | Lignes |
|----------|----------|--------|
| Service Stock Images | `lib/services/stock-images.service.ts` | ~200 |
| Service AI Images | `lib/services/ai-images.service.ts` | ~150 |
| Media Orchestrator | `lib/services/media-generation.service.ts` | ~300 |
| Composant VideoBackground | `components/organisms/media/VideoBackground.tsx` | ~100 |
| Composant MediaOptionsPanel | `components/organisms/sites/MediaOptionsPanel.tsx` | ~250 |
| Endpoint API | `app/api/media/generate/route.ts` | ~150 |

#### Templates par secteur

- Variants de hero adaptés par secteur d'activité
- Amélioration UX du wizard de génération
- Amélioration de l'IA caption/hashtags avec analyse d'image

#### Corrections de bugs

| Commit | Description |
|--------|-------------|
| `75053f3` | Retry mechanism pour icônes Lucide |
| `90bd366` | Ajout icônes Lucide manquantes |
| `002dc2a` | Fallback framer-motion, shadcn, magic-ui |
| `b503e63` | Interdire logos/icônes placeholder |
| `6cd053a` | Fix preview + composants UI |
| `3c7942d` | Auto-repair + timeout preview |

#### Génération automatique de logos

- Génération logo automatique lors de la création de site
- Intégration dans le template header
- Support Google Imagen 3.0

#### Documentation de passation

- 7 documents techniques créés
- Note globale de passation : **A-**
- Temps d'onboarding estimé : 30 min (quick start) à 3h (compréhension complète)

---

<!-- PAGE 13 -->

### 4.2.2 Métriques finales

Les métriques de la période sur SAIA sont éloquentes :

| Métrique | Valeur |
|----------|--------|
| Nombre de commits | ~100+ |
| Fichiers modifiés | ~130 (dernière semaine) |
| Lignes ajoutées | +22,126 (dernière semaine) |
| Lignes supprimées | -2,491 (dernière semaine) |
| Nouveaux services/composants | 8 |
| Documents de passation | 7 |
| Note de passation | A- |

### 4.2.3 Points d'attention identifiés

Le travail de passation a permis d'identifier les points nécessitant une attention future :

#### Priorité haute
1. **Cron worker** pour posts planifiés (non déployé)
2. Connecter MediaOptionsPanel au wizard de génération

#### Priorité moyenne
3. Nettoyer les ~290 `console.log` dans `app/lib`
4. Augmenter la couverture de tests

#### Priorité basse
5. Implémenter autres réseaux sociaux (Twitter, Facebook, Instagram)
6. Analytics avancées

## 4.3 Difficultés techniques et humaines

### 4.3.1 Difficultés techniques sur Zitelou

#### Configuration API Platform

API Platform, bien que puissant, présente une courbe d'apprentissage significative. La configuration des serialization groups et des opérations personnalisées a nécessité plusieurs itérations :

```php
// Exemple de configuration complexe
#[ApiResource(
    operations: [
        new GetCollection(),
        new Post(
            security: "is_granted('ROLE_USER')",
            validationContext: ['groups' => ['child:create']],
        ),
    ],
    normalizationContext: ['groups' => ['child:read']],
    denormalizationContext: ['groups' => ['child:write']],
)]
class Child
{
    // ...
}
```

#### Webhooks Stripe

La gestion des webhooks Stripe en environnement de développement local s'est avérée complexe, nécessitant l'utilisation de Stripe CLI pour le forwarding :

```bash
stripe listen --forward-to localhost:8000/webhook/stripe
```

### 4.3.2 Difficultés techniques sur SAIA

#### Preview WebContainer

Le système de preview utilise WebContainer, une technologie permettant d'exécuter Node.js dans le navigateur. Les problèmes rencontrés incluaient :

- Imports de composants non résolus
- Timeouts sur la génération
- Incohérences entre preview et déploiement

Solution : Implémentation d'un système d'auto-repair et augmentation des timeouts.

#### Gestion des URLs blob

Un bug subtil concernait les URLs `blob:` générées côté client qui ne pouvaient être fetchées côté serveur :

```typescript
// Problème : fetch() échoue sur les URLs blob côté serveur
const response = await fetch(blobUrl); // TypeError: invalid method

// Solution : Détection du type d'URL
if (url.startsWith('blob:')) {
  throw new Error('Blob URLs cannot be fetched server-side');
}
if (url.startsWith('data:')) {
  return decodeDataUrl(url);
}
return fetch(url);
```

---

<!-- PAGE 14 -->

### 4.3.3 Difficultés humaines et organisationnelles

#### L'arrêt maladie

L'arrêt maladie du 9 octobre au 20 novembre 2025 a constitué la difficulté majeure de ce stage. Au-delà de l'aspect médical, cette interruption a eu plusieurs conséquences :

1. **Frustration de ne pas terminer Zitelou** : Quitter un projet en cours génère un sentiment d'inachevé
2. **Anxiété du retour** : Incertitude sur l'accueil et les attentes après 6 semaines d'absence
3. **Pression temporelle** : Nécessité de rattraper le temps perdu en un temps réduit

#### La réaffectation sur un nouveau projet

Être affecté à un projet différent au retour présentait des avantages et inconvénients :

| Avantages | Inconvénients |
|-----------|---------------|
| Nouveau départ, sans le poids de l'échec | Courbe d'apprentissage sur une nouvelle stack |
| Projet plus stimulant techniquement | Perte de la connaissance métier Zitelou |
| Équipe motivée et accueillante | Pression de performance accrue |

#### Le rythme intensif

La dernière semaine de décembre 2025 illustre bien l'intensité du travail fourni :

- 14 commits en une journée (31 décembre)
- ~22,000 lignes ajoutées
- 7 documents de passation rédigés
- Travail jusqu'à la deadline

Ce rythme, s'il a permis d'atteindre les objectifs, n'est pas soutenable sur le long terme et reflète une gestion du temps perturbée par l'arrêt maladie.

### 4.3.4 Leçons tirées

Cette expérience m'a enseigné plusieurs leçons importantes :

1. **La communication est essentielle** : Tenir informé son tuteur de l'avancement, même (surtout) quand ça ne va pas
2. **Documenter au fil de l'eau** : Ne pas attendre la fin pour rédiger la documentation
3. **Anticiper les imprévus** : Garder une marge dans les estimations pour les aléas
4. **Accepter l'imperfection** : Un projet livré imparfait vaut mieux qu'un projet parfait non livré

---

<!-- PAGE 15 -->

# 5. Conclusion et prise de recul

## 5.1 Bilan des compétences acquises

Ce stage de quatre mois chez USTS m'a permis de développer et consolider de nombreuses compétences techniques et transversales.

### Compétences techniques

| Domaine | Compétences acquises |
|---------|---------------------|
| **Backend PHP** | Symfony 7.3, API Platform, Doctrine ORM, JWT |
| **Frontend TypeScript** | Next.js 14, React 18, TailwindCSS, Zustand |
| **Bases de données** | PostgreSQL, MariaDB, Prisma ORM |
| **IA/ML** | Intégration APIs (Gemini, GPT-4, Imagen, Veo) |
| **DevOps** | Docker, Coolify, Traefik, CI/CD |
| **Paiements** | Stripe (Checkout, Webhooks, Billing Portal) |
| **Tests** | PHPUnit, Jest, Playwright, PHPStan |

### Compétences transversales

| Compétence | Contexte d'acquisition |
|------------|----------------------|
| **Autonomie** | Travail sur des features complètes de bout en bout |
| **Documentation** | Rédaction de 7 documents de passation |
| **Gestion de crise** | Reprise après arrêt maladie |
| **Communication** | Échanges techniques avec le tuteur |
| **Priorisation** | Arbitrage entre dette technique et features |

## 5.2 Apport du stage dans mon parcours

### Confirmation de mon orientation

Ce stage a confirmé mon intérêt pour le développement Full Stack. La variété des technologies manipulées (PHP/Symfony d'un côté, TypeScript/Next.js de l'autre) m'a permis de comparer deux écosystèmes et d'affiner mes préférences.

Le projet SAIA, en particulier, m'a fait découvrir le potentiel des services d'IA en tant que briques logicielles intégrables. Cette expérience influence mon projet professionnel vers des postes combinant développement classique et intégration d'IA.

### Confrontation aux réalités professionnelles

Au-delà des aspects techniques, ce stage m'a confronté aux réalités du monde professionnel :

- **Les deadlines sont réelles** : Contrairement aux projets scolaires, les retards ont des conséquences business
- **Le code legacy existe** : Reprendre le code d'un autre développeur fait partie du quotidien
- **La documentation compte** : Un code bien documenté facilite la vie de tous
- **L'imprévu fait partie du jeu** : Maladie, bugs bloquants, changements de priorités

### Points d'amélioration personnels

Cette expérience a également mis en lumière des axes de progression :

1. **Meilleure estimation du temps** : Tendance à sous-estimer la complexité des tâches
2. **Tests plus systématiques** : Prendre l'habitude d'écrire les tests en même temps que le code
3. **Documentation continue** : Ne pas attendre la fin du projet pour documenter
4. **Gestion du stress** : Apprendre à gérer la pression des deadlines serrées

## 5.3 Perspectives

### Court terme

À l'issue de ce stage, je poursuis ma formation à Epitech avec une vision plus claire de mes objectifs. Les compétences acquises me permettront d'aborder les projets suivants avec plus d'assurance, notamment sur les aspects d'architecture et d'intégration d'APIs.

### Moyen terme

Mon objectif à moyen terme est de développer une expertise sur les technologies d'IA intégrées au développement web. Le marché du travail évolue rapidement vers des applications "AI-first", et les développeurs capables de maîtriser ces intégrations seront particulièrement recherchés.

### Contribution au projet SAIA

Bien que mon stage soit terminé, la documentation de passation rédigée permettra au prochain développeur de reprendre le projet dans de bonnes conditions. La note A- obtenue à l'audit de passation témoigne de la qualité du travail de transfert de connaissances.

---

<!-- PAGE 16 -->

# Annexes

## Annexe A : Chronologie détaillée du stage

| Date | Événement |
|------|-----------|
| 1er sept. 2025 | Début du stage, affectation au projet Zitelou |
| 4 sept. 2025 | Revue backend Zitelou : 49 tests, 84.77% couverture |
| 8 oct. 2025 | Dernier jour avant arrêt maladie |
| 9 oct. 2025 | Début arrêt maladie |
| 20 nov. 2025 | Fin arrêt maladie |
| 21 nov. 2025 | Reprise, affectation au projet SAIA |
| 22 nov. 2025 | Premiers commits sur SAIA |
| 19 déc. 2025 | Mise à jour documentation README |
| 31 déc. 2025 | Finalisation passation, 14 commits |
| 31 déc. 2025 | Fin du stage |

## Annexe B : Liste des commits significatifs

### Projet Zitelou (6 commits)

| Date | Description |
|------|-------------|
| Oct. 2025 | Configuration initiale API Platform |
| Oct. 2025 | Authentification JWT |
| Oct. 2025 | Endpoints CRUD User/Child/Device |
| Oct. 2025 | Intégration Stripe Checkout |
| Oct. 2025 | Tests unitaires |
| Oct. 2025 | Webhooks Stripe |

### Projet SAIA (sélection, ~100+ commits au total)

| Hash | Date | Description |
|------|------|-------------|
| `01c199d` | 31 déc. | feat(media): add rich media generation |
| `a5e71fe` | 31 déc. | feat(templates): add sector-based variants |
| `4ff3a3d` | 31 déc. | feat(sites): add automatic logo generation |
| `6cd053a` | 31 déc. | fix: preview + composants UI |
| `e9ad7a6` | 31 déc. | docs(passation): add technical handover |
| `ebcdd93` | 31 déc. | docs(passation): reorganize documentation |

## Annexe C : Variables d'environnement configurées

### Zitelou

```env
DATABASE_URL=mysql://user:pass@localhost:3306/zitelou
JWT_SECRET_KEY=%kernel.project_dir%/config/jwt/private.pem
JWT_PUBLIC_KEY=%kernel.project_dir%/config/jwt/public.pem
STRIPE_SECRET_KEY=sk_test_...
STRIPE_WEBHOOK_SECRET=whsec_...
```

### SAIA

```env
DATABASE_URL=postgresql://user:pass@host:5432/saia
NEXTAUTH_SECRET=...
OPENAI_API_KEY=sk-...
GOOGLE_API_KEY=...
GEMINI_API_KEY=...
REPLICATE_API_TOKEN=r8_...
LINKEDIN_CLIENT_ID=...
LINKEDIN_CLIENT_SECRET=...
STRIPE_SECRET_KEY=sk_...
UNSPLASH_ACCESS_KEY=...
PEXELS_API_KEY=...
COOLIFY_BASE_URL=...
COOLIFY_API_TOKEN=...
```

## Annexe D : Glossaire

| Terme | Définition |
|-------|------------|
| **API Platform** | Framework PHP pour créer des APIs REST/GraphQL |
| **App Router** | Nouvelle architecture de routing Next.js 13+ |
| **Coolify** | Plateforme de déploiement self-hosted (alternative Vercel) |
| **JWT** | JSON Web Token, standard d'authentification |
| **LLM** | Large Language Model (GPT-4, Gemini, etc.) |
| **ORM** | Object-Relational Mapping (Prisma, Doctrine) |
| **SaaS** | Software as a Service |
| **Webhook** | Callback HTTP déclenché par un événement externe |
| **Zustand** | Bibliothèque de gestion d'état React minimaliste |

---

**Rapport rédigé par** : Patrick Saint-Laurent NGANE
**Date** : Janvier 2026
**Stage effectué** : Septembre - Décembre 2025
**Entreprise** : USTS - Formation IA
**Poste** : Développeur Full Stack

---

*Ce rapport a été rédigé dans le cadre du stage de deuxième année (TEK 2) à Epitech Paris, promotion 2025-2026.*
