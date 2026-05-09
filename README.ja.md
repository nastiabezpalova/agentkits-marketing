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
  <strong>Claude Code、Cursor、GitHub Copilot、およびエージェントとスキルをサポートするあらゆるAIアシスタント向けのエンタープライズグレードAIマーケティング自動化。</strong>
</p>

<p align="center">
  SaaS創業者、マーケター、グロースチーム向けに構築された本番環境対応のマーケティングエージェント、スキル、コマンド、ワークフロー。キャンペーン計画、コンテンツ作成、SEO、CRO、メールシーケンス、分析 - すべて専門的なAIエージェントによって強化されています。
</p>

<p align="center">
  <a href="https://www.agentkits.net/marketing">ウェブサイト</a> •
  <a href="https://www.agentkits.net/docs">ドキュメント</a> •
  <a href="#インストール">インストール</a>
</p>

<p align="center">
  🌐 <a href="README.md">English</a> · <a href="README.zh.md">简体中文</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.pt-br.md">Português</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.ru.md">Русский</a> · <a href="README.ar.md">العربية</a>
</p>

---

## Vibe Marketing

<p>
  <img src="https://img.shields.io/badge/Vibe_Coding-Developers-blue?style=for-the-badge&logo=code&logoColor=white" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/→-black?style=for-the-badge" alt="arrow">
  <img src="https://img.shields.io/badge/Vibe_Marketing-Marketers-green?style=for-the-badge&logo=target&logoColor=white" alt="Vibe Marketing">
</p>

> *開発者からの「Vibe Coding」ムーブメントに触発され... 私たちは宇宙を拡大しています: すべてがうまく機能するAI時代のための**Vibe Marketing**。*

| | |
|---|---|
| **AIを使う場合** | AIエージェントにキャンペーンを処理させて、あなたは戦略に集中。ただリラックスして、エージェントに重労働を任せましょう。 |
| **AIを使わない場合** | このリポジトリはマーケティングのベストプラクティス、フレームワーク、テンプレートの**包括的なリファレンスライブラリ**です。スキルドキュメントをマーケティングプレイブックとして使用してください。 |

---

## 内容

**Claude Code**、**Cursor**、**GitHub Copilot**、およびエージェントとスキルをサポートするあらゆるAIアシスタントで動作します。プラグインとしてインストールするか、コンポーネントを手動でコピーします。

```
agentkits-marketing/
|-- .claude-plugin/      # プラグインとマーケットプレイスのマニフェスト
|   |-- plugin.json            # プラグインメタデータとコンポーネントパス
|   |-- marketplace.json       # /plugin marketplace add用マーケットプレイスカタログ
|
|-- .claude/
|   |-- agents/          # 18の専門マーケティングエージェント
|   |   |-- attraction-specialist.md    # リードジェン、SEO、ランディングページ
|   |   |-- lead-qualifier.md           # リードスコアリング、セグメンテーション
|   |   |-- email-wizard.md             # メールシーケンス、自動化
|   |   |-- sales-enabler.md            # セールス資料、バトルカード
|   |   |-- continuity-specialist.md    # リテンション、リエンゲージメント
|   |   |-- upsell-maximizer.md         # 収益拡大
|   |   |-- copywriter.md               # 高コンバージョンのコピー
|   |   |-- conversion-optimizer.md     # CROスペシャリスト
|   |   |-- seo-specialist.md           # SEO最適化
|   |   |-- brand-voice-guardian.md     # ブランド一貫性
|   |   |-- ...その他
|   |
|   |-- commands/        # カテゴリ別93のスラッシュコマンド
|   |   |-- campaign/    # /campaign:plan, /campaign:brief, /campaign:analyze
|   |   |-- content/     # /content:blog, /content:landing, /content:email
|   |   |-- seo/         # /seo:keywords, /seo:audit, /seo:programmatic
|   |   |-- cro/         # /cro:page, /cro:form, /cro:popup, /cro:signup
|   |   |-- growth/      # /growth:launch, /growth:referral, /growth:free-tool
|   |   |-- ...その他
|   |
|   |-- skills/          # 28のマーケティングスキル
|   |   |-- marketing-psychology/       # 70以上のメンタルモデル
|   |   |-- marketing-ideas/            # 140以上のSaaS戦略
|   |   |-- page-cro/                   # ランディングページ最適化
|   |   |-- copywriting/                # マーケティングコピー
|   |   |-- programmatic-seo/           # スケールされたページ生成
|   |   |-- pricing-strategy/           # 価格設定とパッケージング
|   |   |-- ...その他
|   |
|   |-- workflows/       # コアマーケティングワークフロー
|       |-- primary-workflow.md         # キャンペーンライフサイクル
|       |-- sales-workflow.md           # リードから顧客へ
|       |-- crm-workflow.md             # コンタクトライフサイクル
|
|-- docs/                # ドキュメントとガイド
|-- marketplace.json     # セルフホストマーケットプレイス設定
```

---

## インストール

### オプション1: Claude Codeプラグインマーケットプレイス（Claude Code推奨）

Claude Codeのプラグインシステム経由で直接インストール — 手動設定不要:

```bash
# マーケットプレイスを追加
/plugin marketplace add aitytech/agentkits-marketing

# フルスイートをインストール（18エージェント、28スキル、93コマンド）
/plugin install agentkits-marketing@agentkits-marketing
```

個別コンポーネントもインストール可能:

```bash
/plugin install agentkits-marketing-skills@agentkits-marketing    # スキルのみ
/plugin install agentkits-marketing-agents@agentkits-marketing    # エージェントのみ
/plugin install agentkits-marketing-commands@agentkits-marketing  # コマンドのみ
```

インストール後、Claude Codeを再起動してください。

---

### オプション2: npx経由でインストール（全プラットフォーム）

1つのコマンドで18エージェント、28スキル、93コマンドをインストール:

```bash
npx @aitytech/agentkits-marketing install
```

**プラットフォーム固有のインストール:**

```bash
npx @aitytech/agentkits-marketing install --platform claude    # Claude Code
npx @aitytech/agentkits-marketing install --platform cursor    # Cursor IDE
npx @aitytech/agentkits-marketing install --platform windsurf  # Windsurf
npx @aitytech/agentkits-marketing install --platform cline     # Cline
npx @aitytech/agentkits-marketing install --platform copilot   # GitHub Copilot
npx @aitytech/agentkits-marketing install --platform all       # すべてのプラットフォーム
```

**その他のCLIコマンド:**

```bash
npx @aitytech/agentkits-marketing --help        # すべてのコマンドを表示
npx @aitytech/agentkits-marketing list-ides     # サポートされているIDEをリスト
npx @aitytech/agentkits-marketing list-modules  # 利用可能なモジュールをリスト
npx @aitytech/agentkits-marketing update        # 既存のインストールを更新
```

---

### オプション3: クローンして使用

リポジトリをクローンしてその中で作業:

```bash
git clone https://github.com/aitytech/agentkits-marketing.git
cd agentkits-marketing
claude
```

---

### オプション4: 手動インストール

個々のコンポーネントをClaude設定にコピー:

```bash
# リポジトリをクローン
git clone https://github.com/aitytech/agentkits-marketing.git

# エージェントをコピー
cp agentkits-marketing/.claude/agents/*.md ~/.claude/agents/

# コマンドをコピー
cp -r agentkits-marketing/.claude/commands/* ~/.claude/commands/

# スキルをコピー
cp -r agentkits-marketing/.claude/skills/* ~/.claude/skills/

# ワークフローをコピー
cp -r agentkits-marketing/.claude/workflows/* ~/.claude/workflows/
```

---

## クイックスタート

### キャンペーンローンチ

```bash
# リサーチと計画
/research:market "SaaS productivity tools"
/competitor:deep "competitor.com"
/campaign:plan "Q1 Product Launch"

# コンテンツ生成
/content:landing "new feature" "target audience"
/content:email "product launch" "trial users"
/content:blog "feature announcement" "primary keyword"

# 最適化
/cro:page "landing page for conversion"
/seo:optimize "content.md" "target keyword"
```

### コンテンツ作成

```bash
/content:good "Blog post about AI marketing"
/content:editing "polish this draft"
/seo:keywords "ai marketing automation"
```

### コンバージョン最適化

```bash
/cro:page "homepage conversion audit"
/cro:form "lead capture optimization"
/cro:signup "registration flow"
/test:ab-setup "headline variations"
```

### グロースと戦略

```bash
/marketing:ideas "SaaS product"
/marketing:psychology "pricing objections"
/growth:launch "Product Hunt strategy"
/pricing:strategy "tier structure"
```

---

## 利用可能なスキル

| スキル | 説明 | 使用タイミング |
|-------|-------------|----------|
| **コアマーケティング** |
| `marketing-psychology` | マーケティング向けの70以上のメンタルモデル | 説得、価格設定、異議 |
| `marketing-ideas` | 140の実証済みSaaS戦略 | マーケティングアイデアが必要な時 |
| `marketing-fundamentals` | ファネル、ジャーニー、ポジショニング | 基礎概念 |
| **コンバージョン最適化** |
| `page-cro` | ランディングページ、ホームページ、価格ページ | ページがコンバージョンしない時 |
| `form-cro` | リードキャプチャ、コンタクトフォーム | フォーム最適化 |
| `popup-cro` | モーダル、オーバーレイ、離脱インテント | ポップアップ作成 |
| `signup-flow-cro` | 登録、トライアルサインアップ | サインアップの摩擦 |
| `onboarding-cro` | サインアップ後のアクティベーション | ユーザーアクティベーション |
| `paywall-upgrade-cro` | アプリ内ペイウォール、アップグレード画面 | フリーミアムコンバージョン |
| `ab-test-setup` | 実験設計 | A/Bテスト |
| **コンテンツとコピー** |
| `copywriting` | マーケティングページのコピー | 新しいコピーを書く時 |
| `copy-editing` | 編集と洗練 | 既存のコピーを改善 |
| `email-sequence` | ドリップキャンペーン、ナーチャリング | メール自動化 |
| **SEOとグロース** |
| `seo-mastery` | キーワード、技術的、オンページ | SEO最適化 |
| `programmatic-seo` | スケールでのテンプレートページ | スケールされたSEO |
| `schema-markup` | 構造化データ、リッチスニペット | スキーマ実装 |
| `competitor-alternatives` | vsページ、代替 | 比較コンテンツ |
| `launch-strategy` | プロダクトローンチ、発表 | Go-to-market |
| `pricing-strategy` | 価格設定、パッケージング、階層 | 価格設定の決定 |
| `referral-program` | リファラル、アフィリエイト | バイラルグロース |
| `free-tool-strategy` | Engineering-as-marketing | 無料ツールの計画 |

---

## マーケティングエージェント

### コアエージェント
| エージェント | 焦点 |
|-------|-------|
| `attraction-specialist` | リードジェン、SEO、ランディングページ |
| `lead-qualifier` | リードスコアリング、セグメンテーション |
| `email-wizard` | メールシーケンス、自動化 |
| `sales-enabler` | セールス資料、バトルカード |
| `continuity-specialist` | リテンション、リエンゲージメント |
| `upsell-maximizer` | 収益拡大、クロスセル |

### サポートエージェント
| エージェント | 焦点 |
|-------|-------|
| `researcher` | 市場調査、競合インテリジェンス |
| `brainstormer` | キャンペーンアイデア、クリエイティブコンセプト |
| `planner` | キャンペーン計画、カレンダー |
| `copywriter` | 高コンバージョンのコピー |
| `project-manager` | キャンペーン調整 |
| `docs-manager` | マーケティングドキュメンテーション |

### レビュアーエージェント
| エージェント | 視点 |
|-------|-------------|
| `brand-voice-guardian` | ブランド一貫性 |
| `conversion-optimizer` | CROベストプラクティス |
| `seo-specialist` | SEO最適化 |
| `solopreneur` | フリーランサー/小規模ビジネス |
| `startup-founder` | 初期段階のスタートアップ |

---

## コマンドカテゴリ

| カテゴリ | コマンド数 | 例 |
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
| ...その他 | 45以上 | 完全なコマンドリファレンスを参照 |

---

## 学習パス

### パス1: クイックスタート（30分）
経験豊富なマーケター向け - 本番環境に直接ジャンプ:
```bash
/campaign:plan "Your campaign"
/content:good "Your content"
/cro:page "Your landing page"
```

### パス2: スキル特化（各15-30分）
必要に応じて特定のスキルを学習:

| 目標 | コマンド |
|------|----------|
| **コンバージョンを改善** | `/cro:page`, `/cro:form`, `/marketing:psychology` |
| **より良いコピーを書く** | `/content:good`, `/content:editing` |
| **プロダクトをローンチ** | `/growth:launch`, `/campaign:plan` |
| **価格設定を最適化** | `/pricing:strategy` |
| **SEOをスケール** | `/seo:programmatic`, `/seo:schema` |
| **リファラルを設計** | `/growth:referral` |
| **A/Bテスト** | `/test:ab-setup` |

---

## MCP統合

接続されたサービスからの実データ（`data-reliability-rules.md`を参照）:

| サーバー | 用途 |
|--------|---------|
| `sensortower` | アプリ分析、ASO |
| `google-search-console` | 検索パフォーマンス |
| `google-analytics` | ウェブ分析 |
| `semrush` | キーワード、バックリンク |
| `dataforseo` | SERPデータ |
| `meta-ads` | Facebook/Instagram広告 |
| `hubspot` | CRM、自動化 |

---

## 貢献

貢献を歓迎します！以下をお持ちの場合:
- 改善されたエージェントまたはスキル
- 新しいマーケティングコマンド
- より良いワークフロー
- バグ修正

ガイドラインについては[CONTRIBUTING.md](CONTRIBUTING.md)を参照してください。

### 貢献のアイデア
- 業界特化スキル（B2B、eコマース、SaaS）
- プラットフォーム特化エージェント（TikTok、YouTube、Reddit）
- 地域別マーケティング（APAC、EMEA、LATAM）
- 分析統合

---

## リソース

### AgentKits
- [AgentKitsホームページ](https://agentkits.net)
- [マーケティングキットページ](https://www.agentkits.net/marketing)
- [ドキュメント](https://www.agentkits.net/docs)
- [AgentKits CLI](https://github.com/aitytech/agentkits-cli)

### AIアシスタント
- [Claude Codeドキュメント](https://docs.claude.com/en/docs/claude-code/overview)
- [Cursorドキュメント](https://docs.cursor.com)
- [GitHub Copilotドキュメント](https://docs.github.com/en/copilot)
- [Model Context Protocol](https://modelcontextprotocol.io)

### コミュニティ
- [GitHub Issues](https://github.com/aitytech/agentkits-marketing/issues)
- [GitHub Discussions](https://github.com/aitytech/agentkits-marketing/discussions)

---

## スター履歴

<a href="https://star-history.com/#aitytech/agentkits-marketing&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
 </picture>
</a>

---

## ライセンス

MIT - 自由に使用し、必要に応じて修正し、可能であれば貢献してください。

---

**役立つ場合はこのリポジトリにスターを付けてください。今日からAIを活用したマーケティングキャンペーンの構築を始めましょう。**