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
  <strong>Tự động hóa marketing bằng AI cấp doanh nghiệp cho Claude Code, Cursor, GitHub Copilot và bất kỳ trợ lý AI nào hỗ trợ agents & skills.</strong>
</p>

<p align="center">
  Agents, skills, commands và workflows marketing sẵn sàng cho sản xuất được xây dựng cho các nhà sáng lập SaaS, marketer và đội ngũ tăng trưởng. Lập kế hoạch chiến dịch, tạo nội dung, SEO, CRO, chuỗi email và phân tích - tất cả được hỗ trợ bởi các AI agents chuyên biệt.
</p>

<p align="center">
  <a href="https://www.agentkits.net/marketing">Website</a> •
  <a href="https://www.agentkits.net/docs">Tài liệu</a> •
  <a href="#cài-đặt">Cài đặt</a>
</p>

<p align="center">
  🌐 <a href="README.md">English</a> · <a href="README.zh.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.pt-br.md">Português</a> · <strong>Tiếng Việt</strong> · <a href="README.ru.md">Русский</a> · <a href="README.ar.md">العربية</a>
</p>

---

## Vibe Marketing

<p>
  <img src="https://img.shields.io/badge/Vibe_Coding-Developers-blue?style=for-the-badge&logo=code&logoColor=white" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/→-black?style=for-the-badge" alt="arrow">
  <img src="https://img.shields.io/badge/Vibe_Marketing-Marketers-green?style=for-the-badge&logo=target&logoColor=white" alt="Vibe Marketing">
</p>

> *Lấy cảm hứng từ phong trào "Vibe Coding" của các lập trình viên... chúng tôi đang mở rộng vũ trụ: **Vibe Marketing** cho kỷ nguyên AI nơi mọi thứ hoạt động một cách trơn tru.*

| | |
|---|---|
| **Với AI** | Để AI agents xử lý các chiến dịch của bạn trong khi bạn tập trung vào chiến lược. Chỉ cần thả lỏng và để agents làm những việc nặng nhọc. |
| **Không có AI** | Repo này là **thư viện tham khảo toàn diện** về các best practices, frameworks và templates marketing. Sử dụng tài liệu skills như sổ tay marketing của bạn. |

---

## Có gì bên trong

Hoạt động với **Claude Code**, **Cursor**, **GitHub Copilot** và bất kỳ trợ lý AI nào hỗ trợ agents & skills. Cài đặt dưới dạng plugin hoặc sao chép các thành phần theo cách thủ công.

```
agentkits-marketing/
|-- .claude-plugin/      # Plugin và marketplace manifests
|   |-- plugin.json            # Metadata plugin và đường dẫn components
|   |-- marketplace.json       # Catalog marketplace cho /plugin marketplace add
|
|-- .claude/
|   |-- agents/          # 18 agents marketing chuyên biệt
|   |   |-- attraction-specialist.md    # Tạo lead, SEO, landing pages
|   |   |-- lead-qualifier.md           # Chấm điểm lead, phân khúc
|   |   |-- email-wizard.md             # Chuỗi email, tự động hóa
|   |   |-- sales-enabler.md            # Tài liệu bán hàng, battlecards
|   |   |-- continuity-specialist.md    # Giữ chân, tái kích hoạt
|   |   |-- upsell-maximizer.md         # Mở rộng doanh thu
|   |   |-- copywriter.md               # Copy chuyển đổi cao
|   |   |-- conversion-optimizer.md     # Chuyên gia CRO
|   |   |-- seo-specialist.md           # Tối ưu SEO
|   |   |-- brand-voice-guardian.md     # Nhất quán thương hiệu
|   |   |-- ...và nhiều hơn
|   |
|   |-- commands/        # 93 slash commands theo danh mục
|   |   |-- campaign/    # /campaign:plan, /campaign:brief, /campaign:analyze
|   |   |-- content/     # /content:blog, /content:landing, /content:email
|   |   |-- seo/         # /seo:keywords, /seo:audit, /seo:programmatic
|   |   |-- cro/         # /cro:page, /cro:form, /cro:popup, /cro:signup
|   |   |-- growth/      # /growth:launch, /growth:referral, /growth:free-tool
|   |   |-- ...và nhiều hơn
|   |
|   |-- skills/          # 28 skills marketing
|   |   |-- marketing-psychology/       # 70+ mô hình tâm lý
|   |   |-- marketing-ideas/            # 140+ chiến lược SaaS
|   |   |-- page-cro/                   # Tối ưu landing page
|   |   |-- copywriting/                # Copy marketing
|   |   |-- programmatic-seo/           # Tạo trang quy mô lớn
|   |   |-- pricing-strategy/           # Chiến lược giá & gói
|   |   |-- ...và nhiều hơn
|   |
|   |-- workflows/       # Workflows marketing cốt lõi
|       |-- primary-workflow.md         # Vòng đời chiến dịch
|       |-- sales-workflow.md           # Lead đến khách hàng
|       |-- crm-workflow.md             # Vòng đời contact
|
|-- docs/                # Tài liệu và hướng dẫn
|-- marketplace.json     # Cấu hình marketplace tự host
```

---

## Cài đặt

### Tùy chọn 1: Chợ Plugin Claude Code (Khuyến nghị cho Claude Code)

Cài đặt trực tiếp qua hệ thống plugin của Claude Code — không cần cấu hình thủ công:

```bash
# Thêm marketplace
/plugin marketplace add aitytech/agentkits-marketing

# Cài đặt bộ đầy đủ (18 agents, 28 skills, 93 commands)
/plugin install agentkits-marketing@agentkits-marketing
```

Bạn cũng có thể cài đặt từng thành phần riêng lẻ:

```bash
/plugin install agentkits-marketing-skills@agentkits-marketing    # Chỉ Skills
/plugin install agentkits-marketing-agents@agentkits-marketing    # Chỉ Agents
/plugin install agentkits-marketing-commands@agentkits-marketing  # Chỉ Commands
```

Khởi động lại Claude Code sau khi cài đặt.

---

### Tùy chọn 2: Cài đặt qua npx (Tất cả Nền tảng)

Một lệnh để cài đặt 18 agents, 28 skills, 93 commands:

```bash
npx @aitytech/agentkits-marketing install
```

**Cài đặt theo nền tảng cụ thể:**

```bash
npx @aitytech/agentkits-marketing install --platform claude    # Claude Code
npx @aitytech/agentkits-marketing install --platform cursor    # Cursor IDE
npx @aitytech/agentkits-marketing install --platform windsurf  # Windsurf
npx @aitytech/agentkits-marketing install --platform cline     # Cline
npx @aitytech/agentkits-marketing install --platform copilot   # GitHub Copilot
npx @aitytech/agentkits-marketing install --platform all       # Tất cả nền tảng
```

**Các lệnh CLI khác:**

```bash
npx @aitytech/agentkits-marketing --help        # Hiển thị tất cả lệnh
npx @aitytech/agentkits-marketing list-ides     # Liệt kê các IDE được hỗ trợ
npx @aitytech/agentkits-marketing list-modules  # Liệt kê các modules có sẵn
npx @aitytech/agentkits-marketing update        # Cập nhật cài đặt hiện tại
```

---

### Tùy chọn 3: Clone và Sử dụng

Clone repository và làm việc trong đó:

```bash
git clone https://github.com/aitytech/agentkits-marketing.git
cd agentkits-marketing
claude
```

---

### Tùy chọn 4: Cài đặt Thủ công

Sao chép các thành phần riêng lẻ vào cấu hình Claude của bạn:

```bash
# Clone repo
git clone https://github.com/aitytech/agentkits-marketing.git

# Sao chép agents
cp agentkits-marketing/.claude/agents/*.md ~/.claude/agents/

# Sao chép commands
cp -r agentkits-marketing/.claude/commands/* ~/.claude/commands/

# Sao chép skills
cp -r agentkits-marketing/.claude/skills/* ~/.claude/skills/

# Sao chép workflows
cp -r agentkits-marketing/.claude/workflows/* ~/.claude/workflows/
```

---

## Bắt đầu nhanh

### Ra mắt Chiến dịch

```bash
# Nghiên cứu và lập kế hoạch
/research:market "SaaS productivity tools"
/competitor:deep "competitor.com"
/campaign:plan "Q1 Product Launch"

# Tạo nội dung
/content:landing "new feature" "target audience"
/content:email "product launch" "trial users"
/content:blog "feature announcement" "primary keyword"

# Tối ưu
/cro:page "landing page for conversion"
/seo:optimize "content.md" "target keyword"
```

### Tạo Nội dung

```bash
/content:good "Blog post about AI marketing"
/content:editing "polish this draft"
/seo:keywords "ai marketing automation"
```

### Tối ưu Chuyển đổi

```bash
/cro:page "homepage conversion audit"
/cro:form "lead capture optimization"
/cro:signup "registration flow"
/test:ab-setup "headline variations"
```

### Tăng trưởng & Chiến lược

```bash
/marketing:ideas "SaaS product"
/marketing:psychology "pricing objections"
/growth:launch "Product Hunt strategy"
/pricing:strategy "tier structure"
```

---

## Các Skills Có Sẵn

| Skill | Mô tả | Sử dụng Khi |
|-------|-------------|----------|
| **Marketing Cốt lõi** |
| `marketing-psychology` | 70+ mô hình tâm lý cho marketing | Thuyết phục, định giá, phản đối |
| `marketing-ideas` | 140 chiến lược SaaS đã chứng minh | Cần ý tưởng marketing |
| `marketing-fundamentals` | Funnel, journey, positioning | Khái niệm nền tảng |
| **Tối ưu Chuyển đổi** |
| `page-cro` | Landing page, homepage, pricing | Trang không chuyển đổi |
| `form-cro` | Biểu mẫu thu thập lead, contact | Tối ưu biểu mẫu |
| `popup-cro` | Modals, overlays, exit intent | Tạo popup |
| `signup-flow-cro` | Đăng ký, trial signup | Ma sát đăng ký |
| `onboarding-cro` | Kích hoạt sau đăng ký | Kích hoạt người dùng |
| `paywall-upgrade-cro` | Paywalls trong app, màn hình nâng cấp | Chuyển đổi freemium |
| `ab-test-setup` | Thiết kế thử nghiệm | A/B testing |
| **Nội dung & Copy** |
| `copywriting` | Copy trang marketing | Viết copy mới |
| `copy-editing` | Chỉnh sửa và hoàn thiện | Cải thiện copy hiện có |
| `email-sequence` | Chiến dịch drip, nurture | Tự động hóa email |
| **SEO & Tăng trưởng** |
| `seo-mastery` | Từ khóa, kỹ thuật, on-page | Tối ưu SEO |
| `programmatic-seo` | Trang template quy mô lớn | SEO có quy mô |
| `schema-markup` | Dữ liệu có cấu trúc, rich snippets | Triển khai schema |
| `competitor-alternatives` | Trang vs, alternatives | Nội dung so sánh |
| `launch-strategy` | Ra mắt sản phẩm, thông báo | Go-to-market |
| `pricing-strategy` | Định giá, gói, tiers | Quyết định giá |
| `referral-program` | Referral, affiliate | Tăng trưởng viral |
| `free-tool-strategy` | Engineering-as-marketing | Lập kế hoạch công cụ miễn phí |

---

## Agents Marketing

### Agents Cốt lõi
| Agent | Tập trung |
|-------|-------|
| `attraction-specialist` | Tạo lead, SEO, landing pages |
| `lead-qualifier` | Chấm điểm lead, phân khúc |
| `email-wizard` | Chuỗi email, tự động hóa |
| `sales-enabler` | Tài liệu bán hàng, battlecards |
| `continuity-specialist` | Giữ chân, tái kích hoạt |
| `upsell-maximizer` | Mở rộng doanh thu, cross-sell |

### Agents Hỗ trợ
| Agent | Tập trung |
|-------|-------|
| `researcher` | Nghiên cứu thị trường, thông tin cạnh tranh |
| `brainstormer` | Ý tưởng chiến dịch, khái niệm sáng tạo |
| `planner` | Lập kế hoạch chiến dịch, calendars |
| `copywriter` | Copy chuyển đổi cao |
| `project-manager` | Điều phối chiến dịch |
| `docs-manager` | Tài liệu marketing |

### Agents Đánh giá
| Agent | Quan điểm |
|-------|-------------|
| `brand-voice-guardian` | Nhất quán thương hiệu |
| `conversion-optimizer` | Best practices CRO |
| `seo-specialist` | Tối ưu SEO |
| `solopreneur` | Freelancer/doanh nghiệp nhỏ |
| `startup-founder` | Startup giai đoạn đầu |

---

## Danh mục Commands

| Danh mục | Commands | Ví dụ |
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
| ...nhiều hơn | 45+ | Xem tài liệu tham khảo command đầy đủ |

---

## Lộ trình Học tập

### Lộ trình 1: Bắt đầu Nhanh (30 phút)
Dành cho marketers có kinh nghiệm - nhảy thẳng vào sản xuất:
```bash
/campaign:plan "Your campaign"
/content:good "Your content"
/cro:page "Your landing page"
```

### Lộ trình 2: Theo Skill Cụ thể (15-30 phút mỗi)
Học các skills cụ thể khi cần:

| Mục tiêu | Commands |
|------|----------|
| **Cải thiện chuyển đổi** | `/cro:page`, `/cro:form`, `/marketing:psychology` |
| **Viết copy tốt hơn** | `/content:good`, `/content:editing` |
| **Ra mắt sản phẩm** | `/growth:launch`, `/campaign:plan` |
| **Tối ưu định giá** | `/pricing:strategy` |
| **Scale SEO** | `/seo:programmatic`, `/seo:schema` |
| **Thiết kế referral** | `/growth:referral` |
| **A/B testing** | `/test:ab-setup` |

---

## Tích hợp MCP

Dữ liệu thực từ các dịch vụ được kết nối (xem `data-reliability-rules.md`):

| Server | Sử dụng Cho |
|--------|---------|
| `sensortower` | Phân tích app, ASO |
| `google-search-console` | Hiệu suất tìm kiếm |
| `google-analytics` | Phân tích web |
| `semrush` | Từ khóa, backlinks |
| `dataforseo` | Dữ liệu SERP |
| `meta-ads` | Quảng cáo Facebook/Instagram |
| `hubspot` | CRM, tự động hóa |

---

## Đóng góp

Chào đón các đóng góp! Nếu bạn có:
- Agents hoặc skills được cải thiện
- Commands marketing mới
- Workflows tốt hơn
- Sửa lỗi

Xem [CONTRIBUTING.md](CONTRIBUTING.md) để biết hướng dẫn.

### Ý tưởng Đóng góp
- Skills theo ngành cụ thể (B2B, e-commerce, SaaS)
- Agents theo nền tảng cụ thể (TikTok, YouTube, Reddit)
- Marketing khu vực (APAC, EMEA, LATAM)
- Tích hợp Analytics

---

## Tài nguyên

### AgentKits
- [Trang chủ AgentKits](https://agentkits.net)
- [Trang Marketing Kit](https://www.agentkits.net/marketing)
- [Tài liệu](https://www.agentkits.net/docs)
- [AgentKits CLI](https://github.com/aitytech/agentkits-cli)

### Trợ lý AI
- [Claude Code Docs](https://docs.claude.com/en/docs/claude-code/overview)
- [Cursor Docs](https://docs.cursor.com)
- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [Model Context Protocol](https://modelcontextprotocol.io)

### Cộng đồng
- [GitHub Issues](https://github.com/aitytech/agentkits-marketing/issues)
- [GitHub Discussions](https://github.com/aitytech/agentkits-marketing/discussions)

---

## Lịch sử Star

<a href="https://star-history.com/#aitytech/agentkits-marketing&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=aitytech/agentkits-marketing&type=Date" />
 </picture>
</a>

---

## Giấy phép

MIT - Sử dụng tự do, chỉnh sửa khi cần, đóng góp lại nếu có thể.

---

**Star repo này nếu nó hữu ích. Bắt đầu xây dựng các chiến dịch marketing hỗ trợ AI ngay hôm nay.**