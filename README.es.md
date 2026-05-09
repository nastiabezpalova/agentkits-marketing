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
  <strong>Automatización de marketing con IA de nivel empresarial para Claude Code, Cursor, GitHub Copilot y cualquier asistente de IA que soporte agentes y habilidades.</strong>
</p>

<p align="center">
  Agentes de marketing, habilidades, comandos y flujos de trabajo listos para producción, creados para fundadores de SaaS, marketers y equipos de crecimiento. Planificación de campañas, creación de contenido, SEO, CRO, secuencias de email y analíticas - todo impulsado por agentes de IA especializados.
</p>

<p align="center">
  <a href="https://www.agentkits.net/marketing">Sitio Web</a> •
  <a href="https://www.agentkits.net/docs">Documentación</a> •
  <a href="#instalación">Instalar</a>
</p>

<p align="center">
  🌐 <a href="README.md">English</a> · <a href="README.zh.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <strong>Español</strong> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.pt-br.md">Português</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.ru.md">Русский</a> · <a href="README.ar.md">العربية</a>
</p>

---

## Vibe Marketing

<p>
  <img src="https://img.shields.io/badge/Vibe_Coding-Developers-blue?style=for-the-badge&logo=code&logoColor=white" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/→-black?style=for-the-badge" alt="arrow">
  <img src="https://img.shields.io/badge/Vibe_Marketing-Marketers-green?style=for-the-badge&logo=target&logoColor=white" alt="Vibe Marketing">
</p>

> *Inspirado en el movimiento "Vibe Coding" de los desarrolladores... estamos expandiendo el universo: **Vibe Marketing** para la era de la IA donde todo simplemente funciona.*

| | |
|---|---|
| **Con IA** | Deja que los agentes de IA manejen tus campañas mientras te enfocas en la estrategia. Solo mantén la vibra y deja que los agentes hagan el trabajo pesado. |
| **Sin IA** | Este repositorio es una **biblioteca de referencia integral** de mejores prácticas de marketing, frameworks y plantillas. Usa la documentación de habilidades como tu manual de marketing. |

---

## Qué Contiene

Funciona con **Claude Code**, **Cursor**, **GitHub Copilot** y cualquier asistente de IA que soporte agentes y habilidades. Instala como plugin o copia componentes manualmente.

```
agentkits-marketing/
|-- .claude-plugin/      # Manifiestos de plugin y marketplace
|   |-- plugin.json            # Metadatos del plugin y rutas de componentes
|   |-- marketplace.json       # Catálogo del marketplace para /plugin marketplace add
|
|-- .claude/
|   |-- agents/          # 18 agentes de marketing especializados
|   |   |-- attraction-specialist.md    # Generación de leads, SEO, páginas de destino
|   |   |-- lead-qualifier.md           # Puntuación de leads, segmentación
|   |   |-- email-wizard.md             # Secuencias de email, automatización
|   |   |-- sales-enabler.md            # Material de ventas, battlecards
|   |   |-- continuity-specialist.md    # Retención, re-engagement
|   |   |-- upsell-maximizer.md         # Expansión de ingresos
|   |   |-- copywriter.md               # Copy de alta conversión
|   |   |-- conversion-optimizer.md     # Especialista en CRO
|   |   |-- seo-specialist.md           # Optimización SEO
|   |   |-- brand-voice-guardian.md     # Consistencia de marca
|   |   |-- ...y más
|   |
|   |-- commands/        # 93 comandos slash por categoría
|   |   |-- campaign/    # /campaign:plan, /campaign:brief, /campaign:analyze
|   |   |-- content/     # /content:blog, /content:landing, /content:email
|   |   |-- seo/         # /seo:keywords, /seo:audit, /seo:programmatic
|   |   |-- cro/         # /cro:page, /cro:form, /cro:popup, /cro:signup
|   |   |-- growth/      # /growth:launch, /growth:referral, /growth:free-tool
|   |   |-- ...y más
|   |
|   |-- skills/          # 28 habilidades de marketing
|   |   |-- marketing-psychology/       # Más de 70 modelos mentales
|   |   |-- marketing-ideas/            # Más de 140 estrategias SaaS
|   |   |-- page-cro/                   # Optimización de landing pages
|   |   |-- copywriting/                # Copy de marketing
|   |   |-- programmatic-seo/           # Generación escalada de páginas
|   |   |-- pricing-strategy/           # Pricing y packaging
|   |   |-- ...y más
|   |
|   |-- workflows/       # Flujos de trabajo de marketing principales
|       |-- primary-workflow.md         # Ciclo de vida de campaña
|       |-- sales-workflow.md           # De lead a cliente
|       |-- crm-workflow.md             # Ciclo de vida de contacto
|
|-- docs/                # Documentación y guías
|-- marketplace.json     # Configuración de marketplace auto-alojado
```

---

## Instalación

### Opción 1: Marketplace de Plugins de Claude Code (Recomendado para Claude Code)

Instala directamente a través del sistema de plugins de Claude Code — sin configuración manual:

```bash
# Añadir el marketplace
/plugin marketplace add aitytech/agentkits-marketing

# Instalar la suite completa (18 agentes, 28 habilidades, 93 comandos)
/plugin install agentkits-marketing@agentkits-marketing
```

También puedes instalar componentes individuales:

```bash
/plugin install agentkits-marketing-skills@agentkits-marketing    # Solo Skills
/plugin install agentkits-marketing-agents@agentkits-marketing    # Solo Agentes
/plugin install agentkits-marketing-commands@agentkits-marketing  # Solo Comandos
```

Reinicia Claude Code después de la instalación.

---

### Opción 2: Instalar vía npx (Todas las Plataformas)

Un comando para instalar 18 agentes, 28 habilidades, 93 comandos:

```bash
npx @aitytech/agentkits-marketing install
```

**Instalación específica por plataforma:**

```bash
npx @aitytech/agentkits-marketing install --platform claude    # Claude Code
npx @aitytech/agentkits-marketing install --platform cursor    # Cursor IDE
npx @aitytech/agentkits-marketing install --platform windsurf  # Windsurf
npx @aitytech/agentkits-marketing install --platform cline     # Cline
npx @aitytech/agentkits-marketing install --platform copilot   # GitHub Copilot
npx @aitytech/agentkits-marketing install --platform all       # Todas las plataformas
```

**Otros comandos CLI:**

```bash
npx @aitytech/agentkits-marketing --help        # Mostrar todos los comandos
npx @aitytech/agentkits-marketing list-ides     # Listar IDEs soportados
npx @aitytech/agentkits-marketing list-modules  # Listar módulos disponibles
npx @aitytech/agentkits-marketing update        # Actualizar instalación existente
```

---

### Opción 3: Clonar y Usar

Clona el repositorio y trabaja dentro de él:

```bash
git clone https://github.com/aitytech/agentkits-marketing.git
cd agentkits-marketing
claude
```

---

### Opción 4: Instalación Manual

Copia componentes individuales a tu configuración de Claude:

```bash
# Clona el repo
git clone https://github.com/aitytech/agentkits-marketing.git

# Copia agentes
cp agentkits-marketing/.claude/agents/*.md ~/.claude/agents/

# Copia comandos
cp -r agentkits-marketing/.claude/commands/* ~/.claude/commands/

# Copia habilidades
cp -r agentkits-marketing/.claude/skills/* ~/.claude/skills/

# Copia flujos de trabajo
cp -r agentkits-marketing/.claude/workflows/* ~/.claude/workflows/
```

---

## Inicio Rápido

### Lanzamiento de Campaña

```bash
# Investigar y planificar
/research:market "SaaS productivity tools"
/competitor:deep "competitor.com"
/campaign:plan "Q1 Product Launch"

# Generar contenido
/content:landing "new feature" "target audience"
/content:email "product launch" "trial users"
/content:blog "feature announcement" "primary keyword"

# Optimizar
/cro:page "landing page for conversion"
/seo:optimize "content.md" "target keyword"
```

### Creación de Contenido

```bash
/content:good "Blog post about AI marketing"
/content:editing "polish this draft"
/seo:keywords "ai marketing automation"
```

### Optimización de Conversión

```bash
/cro:page "homepage conversion audit"
/cro:form "lead capture optimization"
/cro:signup "registration flow"
/test:ab-setup "headline variations"
```

### Crecimiento y Estrategia

```bash
/marketing:ideas "SaaS product"
/marketing:psychology "pricing objections"
/growth:launch "Product Hunt strategy"
/pricing:strategy "tier structure"
```

---

## Habilidades Disponibles

| Habilidad | Descripción | Usar Cuando |
|-------|-------------|----------|
| **Marketing Principal** |
| `marketing-psychology` | Más de 70 modelos mentales para marketing | Persuasión, pricing, objeciones |
| `marketing-ideas` | 140 estrategias SaaS probadas | Necesitas ideas de marketing |
| `marketing-fundamentals` | Funnel, journey, posicionamiento | Conceptos fundamentales |
| **Optimización de Conversión** |
| `page-cro` | Landing page, homepage, pricing | La página no convierte |
| `form-cro` | Captura de leads, formularios de contacto | Optimización de formularios |
| `popup-cro` | Modales, overlays, exit intent | Creación de popups |
| `signup-flow-cro` | Registro, signup de prueba | Fricción en signup |
| `onboarding-cro` | Activación post-signup | Activación de usuarios |
| `paywall-upgrade-cro` | Paywalls in-app, pantallas de upgrade | Conversión freemium |
| `ab-test-setup` | Diseño de experimentos | Testing A/B |
| **Contenido y Copy** |
| `copywriting` | Copy para páginas de marketing | Escribir copy nuevo |
| `copy-editing` | Editar y pulir | Mejorar copy existente |
| `email-sequence` | Campañas drip, nurture | Automatización de email |
| **SEO y Crecimiento** |
| `seo-mastery` | Keywords, técnico, on-page | Optimización SEO |
| `programmatic-seo` | Páginas de plantilla a escala | SEO escalado |
| `schema-markup` | Datos estructurados, rich snippets | Implementación de schema |
| `competitor-alternatives` | Páginas vs, alternativas | Contenido de comparación |
| `launch-strategy` | Lanzamientos de producto, anuncios | Go-to-market |
| `pricing-strategy` | Pricing, packaging, niveles | Decisiones de pricing |
| `referral-program` | Referidos, afiliados | Crecimiento viral |
| `free-tool-strategy` | Engineering-as-marketing | Planificación de herramienta gratuita |

---

## Agentes de Marketing

### Agentes Principales
| Agente | Enfoque |
|-------|-------|
| `attraction-specialist` | Generación de leads, SEO, landing pages |
| `lead-qualifier` | Puntuación de leads, segmentación |
| `email-wizard` | Secuencias de email, automatización |
| `sales-enabler` | Material de ventas, battlecards |
| `continuity-specialist` | Retención, re-engagement |
| `upsell-maximizer` | Expansión de ingresos, cross-sell |

### Agentes de Soporte
| Agente | Enfoque |
|-------|-------|
| `researcher` | Investigación de mercado, inteligencia competitiva |
| `brainstormer` | Ideación de campañas, conceptos creativos |
| `planner` | Planificación de campañas, calendarios |
| `copywriter` | Copy de alta conversión |
| `project-manager` | Coordinación de campañas |
| `docs-manager` | Documentación de marketing |

### Agentes Revisores
| Agente | Perspectiva |
|-------|-------------|
| `brand-voice-guardian` | Consistencia de marca |
| `conversion-optimizer` | Mejores prácticas de CRO |
| `seo-specialist` | Optimización SEO |
| `solopreneur` | Freelancer/pequeño negocio |
| `startup-founder` | Startup en etapa temprana |

---

## Categorías de Comandos

| Categoría | Comandos | Ejemplos |
|----------|----------|----------|
| Campaign | 4 | `/campaign:plan`, `/campaign:brief` |
| Content | 10 | `/content:blog`, `/content:landing`, `/content:editing` |
| SEO | 6 | `/seo:keywords`, `/seo:audit`, `/seo:programmatic` |
| CRO | 6 | `/cro:page`, `/cro:form`, `/cro:signup` |
| Growth | 3 | `/growth:launch`, `/growth:referral` |
| Email | 4 | `/sequence:welcome`, `/sequence:nurture` |
| Analytics | 5 | `/analytics:roi`, `/analytics:funnel` |
| Sales | 4 | `/sales:pitch`, `/sales:battlecard` |
| Research | 3 | `/research:market`, `/research:persona` |
| Marketing | 2 | `/marketing:psychology`, `/marketing:ideas` |
| Testing | 1 | `/test:ab-setup` |
| ...más | 45+ | Ver referencia completa de comandos |

---

## Rutas de Aprendizaje

### Ruta 1: Inicio Rápido (30 min)
Para marketers experimentados - salta directo a producción:
```bash
/campaign:plan "Your campaign"
/content:good "Your content"
/cro:page "Your landing page"
```

### Ruta 2: Específica por Habilidad (15-30 min cada una)
Aprende habilidades específicas según sea necesario:

| Objetivo | Comandos |
|------|----------|
| **Mejorar conversiones** | `/cro:page`, `/cro:form`, `/marketing:psychology` |
| **Escribir mejor copy** | `/content:good`, `/content:editing` |
| **Lanzar un producto** | `/growth:launch`, `/campaign:plan` |
| **Optimizar pricing** | `/pricing:strategy` |
| **Escalar SEO** | `/seo:programmatic`, `/seo:schema` |
| **Diseñar referidos** | `/growth:referral` |
| **Testing A/B** | `/test:ab-setup` |

---

## Integraciones MCP

Datos reales de servicios conectados (ver `data-reliability-rules.md`):

| Servidor | Usar Para |
|--------|---------|
| `sensortower` | Analíticas de app, ASO |
| `google-search-console` | Rendimiento de búsqueda |
| `google-analytics` | Analíticas web |
| `semrush` | Keywords, backlinks |
| `dataforseo` | Datos SERP |
| `meta-ads` | Anuncios Facebook/Instagram |
| `hubspot` | CRM, automatización |

---

## Contribuir

¡Las contribuciones son bienvenidas! Si tienes:
- Agentes o habilidades mejorados
- Nuevos comandos de marketing
- Mejores flujos de trabajo
- Correcciones de bugs

Ver [CONTRIBUTING.md](CONTRIBUTING.md) para directrices.

### Ideas para Contribuciones
- Habilidades específicas por industria (B2B, e-commerce, SaaS)
- Agentes específicos por plataforma (TikTok, YouTube, Reddit)
- Marketing regional (APAC, EMEA, LATAM)
- Integraciones de analíticas

---

## Recursos

### AgentKits
- [Página Principal de AgentKits](https://agentkits.net)
- [Página del Kit de Marketing](https://www.agentkits.net/marketing)
- [Documentación](https://www.agentkits.net/docs)
- [AgentKits CLI](https://github.com/aitytech/agentkits-cli)

### Asistentes de IA
- [Documentación de Claude Code](https://docs.claude.com/en/docs/claude-code/overview)
- [Documentación de Cursor](https://docs.cursor.com)
- [Documentación de GitHub Copilot](https://docs.github.com/en/copilot)
- [Model Context Protocol](https://modelcontextprotocol.io)

### Comunidad
- [GitHub Issues](https://github.com/aitytech/agentkits-marketing/issues)
- [GitHub Discussions](https://github.com/aitytech/agentkits-marketing/discussions)

---

## Historial de Estrellas

<a href="https://star-history.com/#aitytech/agentkits-marketing&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
 </picture>
</a>

---

## Licencia

MIT - Usa libremente, modifica según sea necesario, contribuye de vuelta si puedes.

---

**Dale una estrella a este repo si te ayuda. Comienza a construir campañas de marketing impulsadas por IA hoy.**