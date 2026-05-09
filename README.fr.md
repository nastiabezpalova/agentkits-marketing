<p align="center">
  <img src="https://raw.githubusercontent.com/aitytech/agentkits-marketing/main/assets/logo.svg" alt="AgentKits Logo" width="80" height="80">
</p>

<h1 align="center">AgentKits Marketing</h1>

<p align="center">
  <a href="https://github.com/aitytech/agentkits-marketing/stargazers"><img src="https://img.shields.io/github/stars/aitytech/agentkits-marketing?style=flat" alt="Stars"></a>
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Claude_Code%20|%20Cursor%20|%20Copilot-Compatible-blueviolet" alt="AI Assistants">
  <br>
  <img src="https://img.shields.io/badge/Agents-18-green" alt="Agents">
  <img src="https://img.shields.io/badge/Commands-93-orange" alt="Commands">
  <img src="https://img.shields.io/badge/Skills-28-blue" alt="Skills">
</p>

<p align="center">
  <strong>Automation marketing IA de niveau entreprise pour Claude Code, Cursor, GitHub Copilot et tout assistant IA prenant en charge les agents et compétences.</strong>
</p>

<p align="center">
  Agents marketing, compétences, commandes et workflows prêts pour la production, conçus pour les fondateurs SaaS, les marketeurs et les équipes de croissance. Planification de campagnes, création de contenu, SEO, CRO, séquences d'emails et analyses - le tout alimenté par des agents IA spécialisés.
</p>

<p align="center">
  <a href="https://www.agentkits.net/marketing">Site web</a> •
  <a href="https://www.agentkits.net/docs">Documentation</a> •
  <a href="#installation">Installer</a>
</p>

<p align="center">
  🌐 <a href="README.md">English</a> · <a href="README.zh.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <strong>Français</strong> · <a href="README.pt-br.md">Português</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.ru.md">Русский</a> · <a href="README.ar.md">العربية</a>
</p>

---

## Vibe Marketing

<p>
  <img src="https://img.shields.io/badge/Vibe_Coding-Developers-blue?style=for-the-badge&logo=code&logoColor=white" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/→-black?style=for-the-badge" alt="arrow">
  <img src="https://img.shields.io/badge/Vibe_Marketing-Marketers-green?style=for-the-badge&logo=target&logoColor=white" alt="Vibe Marketing">
</p>

> *Inspiré par le mouvement "Vibe Coding" des développeurs... nous élargissons l'univers : **Vibe Marketing** pour l'ère de l'IA où tout fonctionne simplement.*

| | |
|---|---|
| **Avec l'IA** | Laissez les agents IA gérer vos campagnes pendant que vous vous concentrez sur la stratégie. Restez zen et laissez les agents faire le gros du travail. |
| **Sans IA** | Ce dépôt est une **bibliothèque de référence complète** des meilleures pratiques marketing, frameworks et modèles. Utilisez la documentation des compétences comme votre manuel de marketing. |

---

## Contenu

Fonctionne avec **Claude Code**, **Cursor**, **GitHub Copilot** et tout assistant IA prenant en charge les agents et compétences. Installez comme plugin ou copiez les composants manuellement.

```
agentkits-marketing/
|-- .claude-plugin/      # Manifestes plugin et marketplace
|   |-- plugin.json            # Métadonnées du plugin et chemins des composants
|   |-- marketplace.json       # Catalogue marketplace pour /plugin marketplace add
|
|-- .claude/
|   |-- agents/          # 18 agents marketing spécialisés
|   |   |-- attraction-specialist.md    # Génération de leads, SEO, pages de destination
|   |   |-- lead-qualifier.md           # Scoring de leads, segmentation
|   |   |-- email-wizard.md             # Séquences d'emails, automation
|   |   |-- sales-enabler.md            # Supports de vente, battlecards
|   |   |-- continuity-specialist.md    # Rétention, réengagement
|   |   |-- upsell-maximizer.md         # Expansion des revenus
|   |   |-- copywriter.md               # Textes à forte conversion
|   |   |-- conversion-optimizer.md     # Spécialiste CRO
|   |   |-- seo-specialist.md           # Optimisation SEO
|   |   |-- brand-voice-guardian.md     # Cohérence de marque
|   |   |-- ...et plus
|   |
|   |-- commands/        # 93 commandes slash par catégorie
|   |   |-- campaign/    # /campaign:plan, /campaign:brief, /campaign:analyze
|   |   |-- content/     # /content:blog, /content:landing, /content:email
|   |   |-- seo/         # /seo:keywords, /seo:audit, /seo:programmatic
|   |   |-- cro/         # /cro:page, /cro:form, /cro:popup, /cro:signup
|   |   |-- growth/      # /growth:launch, /growth:referral, /growth:free-tool
|   |   |-- ...et plus
|   |
|   |-- skills/          # 28 compétences marketing
|   |   |-- marketing-psychology/       # 70+ modèles mentaux
|   |   |-- marketing-ideas/            # 140+ stratégies SaaS
|   |   |-- page-cro/                   # Optimisation de pages de destination
|   |   |-- copywriting/                # Rédaction marketing
|   |   |-- programmatic-seo/           # Génération de pages à grande échelle
|   |   |-- pricing-strategy/           # Tarification et packaging
|   |   |-- ...et plus
|   |
|   |-- workflows/       # Workflows marketing principaux
|       |-- primary-workflow.md         # Cycle de vie des campagnes
|       |-- sales-workflow.md           # Du lead au client
|       |-- crm-workflow.md             # Cycle de vie des contacts
|
|-- docs/                # Documentation et guides
|-- marketplace.json     # Configuration marketplace auto-hébergée
```

---

## Installation

### Option 1 : Marketplace de Plugins Claude Code (Recommandé pour Claude Code)

Installez directement via le système de plugins de Claude Code — aucune configuration manuelle nécessaire :

```bash
# Ajouter le marketplace
/plugin marketplace add aitytech/agentkits-marketing

# Installer la suite complète (18 agents, 28 compétences, 93 commandes)
/plugin install agentkits-marketing@agentkits-marketing
```

Vous pouvez également installer des composants individuels :

```bash
/plugin install agentkits-marketing-skills@agentkits-marketing    # Compétences uniquement
/plugin install agentkits-marketing-agents@agentkits-marketing    # Agents uniquement
/plugin install agentkits-marketing-commands@agentkits-marketing  # Commandes uniquement
```

Redémarrez Claude Code après l'installation.

---

### Option 2 : Installation via npx (Toutes les plateformes)

Une seule commande pour installer 18 agents, 28 compétences, 93 commandes :

```bash
npx @aitytech/agentkits-marketing install
```

**Installation spécifique par plateforme :**

```bash
npx @aitytech/agentkits-marketing install --platform claude    # Claude Code
npx @aitytech/agentkits-marketing install --platform cursor    # Cursor IDE
npx @aitytech/agentkits-marketing install --platform windsurf  # Windsurf
npx @aitytech/agentkits-marketing install --platform cline     # Cline
npx @aitytech/agentkits-marketing install --platform copilot   # GitHub Copilot
npx @aitytech/agentkits-marketing install --platform all       # Toutes les plateformes
```

**Autres commandes CLI :**

```bash
npx @aitytech/agentkits-marketing --help        # Afficher toutes les commandes
npx @aitytech/agentkits-marketing list-ides     # Lister les IDE supportés
npx @aitytech/agentkits-marketing list-modules  # Lister les modules disponibles
npx @aitytech/agentkits-marketing update        # Mettre à jour l'installation existante
```

---

### Option 3 : Cloner et utiliser

Clonez le dépôt et travaillez directement dedans :

```bash
git clone https://github.com/aitytech/agentkits-marketing.git
cd agentkits-marketing
claude
```

---

### Option 4 : Installation manuelle

Copiez les composants individuels dans votre configuration Claude :

```bash
# Cloner le dépôt
git clone https://github.com/aitytech/agentkits-marketing.git

# Copier les agents
cp agentkits-marketing/.claude/agents/*.md ~/.claude/agents/

# Copier les commandes
cp -r agentkits-marketing/.claude/commands/* ~/.claude/commands/

# Copier les compétences
cp -r agentkits-marketing/.claude/skills/* ~/.claude/skills/

# Copier les workflows
cp -r agentkits-marketing/.claude/workflows/* ~/.claude/workflows/
```

---

## Démarrage rapide

### Lancement de campagne

```bash
# Recherche et planification
/research:market "SaaS productivity tools"
/competitor:deep "competitor.com"
/campaign:plan "Q1 Product Launch"

# Générer du contenu
/content:landing "new feature" "target audience"
/content:email "product launch" "trial users"
/content:blog "feature announcement" "primary keyword"

# Optimiser
/cro:page "landing page for conversion"
/seo:optimize "content.md" "target keyword"
```

### Création de contenu

```bash
/content:good "Blog post about AI marketing"
/content:editing "polish this draft"
/seo:keywords "ai marketing automation"
```

### Optimisation de conversion

```bash
/cro:page "homepage conversion audit"
/cro:form "lead capture optimization"
/cro:signup "registration flow"
/test:ab-setup "headline variations"
```

### Croissance et stratégie

```bash
/marketing:ideas "SaaS product"
/marketing:psychology "pricing objections"
/growth:launch "Product Hunt strategy"
/pricing:strategy "tier structure"
```

---

## Compétences disponibles

| Compétence | Description | Utiliser quand |
|-------|-------------|----------|
| **Marketing principal** |
| `marketing-psychology` | 70+ modèles mentaux pour le marketing | Persuasion, tarification, objections |
| `marketing-ideas` | 140 stratégies SaaS éprouvées | Besoin d'idées marketing |
| `marketing-fundamentals` | Funnel, parcours, positionnement | Concepts fondamentaux |
| **Optimisation de conversion** |
| `page-cro` | Page de destination, page d'accueil, tarification | Page qui ne convertit pas |
| `form-cro` | Capture de leads, formulaires de contact | Optimisation de formulaire |
| `popup-cro` | Modales, overlays, exit intent | Création de popup |
| `signup-flow-cro` | Inscription, inscription à l'essai | Friction d'inscription |
| `onboarding-cro` | Activation post-inscription | Activation utilisateur |
| `paywall-upgrade-cro` | Paywalls in-app, écrans de mise à niveau | Conversion freemium |
| `ab-test-setup` | Conception d'expériences | Tests A/B |
| **Contenu et rédaction** |
| `copywriting` | Textes de pages marketing | Rédiger un nouveau texte |
| `copy-editing` | Édition et polissage | Améliorer un texte existant |
| `email-sequence` | Campagnes drip, nurture | Automation d'emails |
| **SEO et croissance** |
| `seo-mastery` | Mots-clés, technique, on-page | Optimisation SEO |
| `programmatic-seo` | Pages template à grande échelle | SEO à grande échelle |
| `schema-markup` | Données structurées, rich snippets | Implémentation de schema |
| `competitor-alternatives` | Pages vs, alternatives | Contenu de comparaison |
| `launch-strategy` | Lancements de produits, annonces | Go-to-market |
| `pricing-strategy` | Tarification, packaging, niveaux | Décisions de tarification |
| `referral-program` | Parrainage, affiliation | Croissance virale |
| `free-tool-strategy` | Engineering-as-marketing | Planification d'outil gratuit |

---

## Agents marketing

### Agents principaux
| Agent | Focus |
|-------|-------|
| `attraction-specialist` | Génération de leads, SEO, pages de destination |
| `lead-qualifier` | Scoring de leads, segmentation |
| `email-wizard` | Séquences d'emails, automation |
| `sales-enabler` | Supports de vente, battlecards |
| `continuity-specialist` | Rétention, réengagement |
| `upsell-maximizer` | Expansion des revenus, vente croisée |

### Agents de support
| Agent | Focus |
|-------|-------|
| `researcher` | Recherche de marché, veille concurrentielle |
| `brainstormer` | Idéation de campagnes, concepts créatifs |
| `planner` | Planification de campagnes, calendriers |
| `copywriter` | Textes à forte conversion |
| `project-manager` | Coordination de campagnes |
| `docs-manager` | Documentation marketing |

### Agents réviseurs
| Agent | Perspective |
|-------|-------------|
| `brand-voice-guardian` | Cohérence de marque |
| `conversion-optimizer` | Meilleures pratiques CRO |
| `seo-specialist` | Optimisation SEO |
| `solopreneur` | Freelance/petite entreprise |
| `startup-founder` | Startup en phase initiale |

---

## Catégories de commandes

| Catégorie | Commandes | Exemples |
|----------|----------|----------|
| Campagne | 4 | `/campaign:plan`, `/campaign:brief` |
| Contenu | 10 | `/content:blog`, `/content:landing`, `/content:editing` |
| SEO | 6 | `/seo:keywords`, `/seo:audit`, `/seo:programmatic` |
| CRO | 6 | `/cro:page`, `/cro:form`, `/cro:signup` |
| Croissance | 3 | `/growth:launch`, `/growth:referral` |
| Email | 4 | `/sequence:welcome`, `/sequence:nurture` |
| Analyses | 5 | `/analytics:roi`, `/analytics:funnel` |
| Ventes | 4 | `/sales:pitch`, `/sales:battlecard` |
| Recherche | 3 | `/research:market`, `/research:persona` |
| Marketing | 2 | `/marketing:psychology`, `/marketing:ideas` |
| Tests | 1 | `/test:ab-setup` |
| ...plus | 45+ | Voir la référence complète des commandes |

---

## Parcours d'apprentissage

### Parcours 1 : Démarrage rapide (30 min)
Pour les marketeurs expérimentés - passez directement à la production :
```bash
/campaign:plan "Your campaign"
/content:good "Your content"
/cro:page "Your landing page"
```

### Parcours 2 : Compétences spécifiques (15-30 min chacune)
Apprenez des compétences spécifiques selon les besoins :

| Objectif | Commandes |
|------|----------|
| **Améliorer les conversions** | `/cro:page`, `/cro:form`, `/marketing:psychology` |
| **Rédiger de meilleurs textes** | `/content:good`, `/content:editing` |
| **Lancer un produit** | `/growth:launch`, `/campaign:plan` |
| **Optimiser la tarification** | `/pricing:strategy` |
| **Évoluer le SEO** | `/seo:programmatic`, `/seo:schema` |
| **Concevoir des parrainages** | `/growth:referral` |
| **Tests A/B** | `/test:ab-setup` |

---

## Intégrations MCP

Données réelles provenant de services connectés (voir `data-reliability-rules.md`) :

| Serveur | Utiliser pour |
|--------|---------|
| `sensortower` | Analytics d'applications, ASO |
| `google-search-console` | Performance de recherche |
| `google-analytics` | Analytics web |
| `semrush` | Mots-clés, backlinks |
| `dataforseo` | Données SERP |
| `meta-ads` | Publicités Facebook/Instagram |
| `hubspot` | CRM, automation |

---

## Contribuer

Les contributions sont les bienvenues ! Si vous avez :
- Des agents ou compétences améliorés
- De nouvelles commandes marketing
- De meilleurs workflows
- Des corrections de bugs

Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour les directives.

### Idées de contributions
- Compétences spécifiques à l'industrie (B2B, e-commerce, SaaS)
- Agents spécifiques à la plateforme (TikTok, YouTube, Reddit)
- Marketing régional (APAC, EMEA, LATAM)
- Intégrations d'analytics

---

## Ressources

### AgentKits
- [Page d'accueil AgentKits](https://agentkits.net)
- [Page Marketing Kit](https://www.agentkits.net/marketing)
- [Documentation](https://www.agentkits.net/docs)
- [AgentKits CLI](https://github.com/aitytech/agentkits-cli)

### Assistants IA
- [Documentation Claude Code](https://docs.claude.com/en/docs/claude-code/overview)
- [Documentation Cursor](https://docs.cursor.com)
- [Documentation GitHub Copilot](https://docs.github.com/en/copilot)
- [Model Context Protocol](https://modelcontextprotocol.io)

### Communauté
- [GitHub Issues](https://github.com/aitytech/agentkits-marketing/issues)
- [GitHub Discussions](https://github.com/aitytech/agentkits-marketing/discussions)

---

## Historique des étoiles

<a href="https://star-history.com/#aitytech/agentkits-marketing&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
 </picture>
</a>

---

## Licence

MIT - Utilisez librement, modifiez selon vos besoins, contribuez si vous le pouvez.

---

**Mettez une étoile à ce dépôt s'il vous aide. Commencez à créer des campagnes marketing alimentées par l'IA dès aujourd'hui.**