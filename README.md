# Awesome-Unified-Customer-Experience-CX-Suite

# Awesome Unified Customer Experience (CX) Suite

> A curated list of top Unified Customer Experience (CX) Suite platforms — both SaaS/Hosted commercial solutions and open-source alternatives for connecting customer data, feedback, support, and engagement across the entire journey.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Salesforce Customer 360](#salesforce-customer-360)
  - [Adobe Experience Cloud](#adobe-experience-cloud)
  - [Oracle CX](#oracle-cx)
  - [SAP Customer Experience](#sap-customer-experience)
  - [Zoho CRM Plus](#zoho-crm-plus)
  - [Zendesk Suite](#zendesk-suite)
  - [Freshworks Customer Service Suite](#freshworks-customer-service-suite)
  - [Sprinklr](#sprinklr)
  - [Qualtrics XM](#qualtrics-xm)
  - [Pegasystems](#pegasystems)
- [Open-Source Software](#-open-source-software)
  - [Formbricks](#formbricks)
  - [Tracardi](#tracardi)
  - [Chatwoot](#chatwoot)
  - [FreeScout](#freescout)
  - [Znuny](#znuny)
  - [Retentioneering](#retentioneering)
  - [OpenPanel](#openpanel)
  - [CX Impact](#cx-impact)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Unified Customer Experience (CX) Suite platforms. These are not open-source but are included as reference points for feature comparison.

### Salesforce Customer 360
**Type:** Enterprise CRM and CX platform with Agentforce AI  
Salesforce Customer 360 connects sales, service, marketing, commerce, and custom applications on a single platform. The ISG 2026 Buyers Guide rates Salesforce as Exemplary with an A- grade (84.2% performance), praising its metadata-driven architecture and AI capabilities through Einstein and Agentforce . Pricing starts with a Free Suite for basic contact and opportunity management, scaling to enterprise tiers at £440/seat/month for advanced AI features . **Trade-off:** Cost transparency across its broad licensing model is a noted challenge, and platform complexity increases significantly with customization.

### Adobe Experience Cloud
**Type:** Digital experience and marketing platform  
Adobe Experience Cloud provides a suite of applications for customer data management (Real-Time CDP), content management, personalization, and analytics. Suited for enterprises wanting deep integration between marketing content, customer data, and campaign execution. Pricing is quote-based and typically targets large organizations with dedicated marketing technology teams.

### Oracle CX
**Type:** Cloud CX suite (Fusion Cloud CX)  
Oracle CX (Sales, Service, Marketing) is part of Oracle's Fusion Cloud applications. The ISG Buyers Guide rates Oracle as Exemplary with an A- grade, placing it among the top leaders alongside Salesforce and HubSpot . Deeply integrated with Oracle ERP and HCM, making it a natural choice for Oracle-centric enterprises requiring tight back-office integration.

### SAP Customer Experience
**Type:** Enterprise CX suite  
SAP Customer Experience (including SAP Sales Cloud and SAP Service Cloud) integrates with SAP S/4HANA and the broader SAP ecosystem. The ISG Buyers Guide rates SAP as B+ (14.0% performance), indicating solid capability for SAP-standardized organizations . Suited for large enterprises requiring ERP-CRM integration with complex supply chain and manufacturing workflows.

### Zoho CRM Plus
**Type:** Unified customer experience platform within Zoho ecosystem  
Zoho CRM Plus bundles CRM with email marketing, surveys, visitor tracking, social media marketing, project management, and advanced analytics. Zoho CRM itself offers a free edition for 3 users, with paid tiers adding scoring rules, forecasting, Blueprint process design, and anomaly detection. The ISG Buyers Guide rates Zoho CRM as B++ (15.7% performance), placing it above Microsoft and SAP in overall scoring . Strong value for SMBs wanting breadth without multiple vendor relationships.

### Zendesk Suite
**Type:** Customer service and engagement platform  
Zendesk Suite combines ticketing, messaging, help center, voice, and analytics for customer support teams. Known for its mature support ecosystem and extensive integrations. Pricing is per-agent with tiered plans, and AI features (advanced bots, agent assistance) are typically add-ons.

### Freshworks Customer Service Suite
**Type:** Unified customer service and engagement  
Freshworks combines Freshdesk (ticketing), Freshchat (messaging), and Freshsales (CRM) into an integrated suite. The platform emphasizes ease of use and AI assistance (Freddy AI) for agent productivity and self-service. Positioned as an accessible alternative to enterprise suites for mid-market organizations.

### Sprinklr
**Type:** Unified customer experience management (Unified-CXM)  
Sprinklr provides a unified platform for social media management, customer care, marketing, and research across digital channels. Suited for large enterprises managing high-volume social and messaging interactions across multiple brands and regions.

### Qualtrics XM
**Type:** Experience management platform  
Qualtrics XM covers customer experience (CX), employee experience (EX), product experience, and brand experience. Provides survey research, analytics, and action planning across the organization. Often compared with Formbricks, which positions itself as an open-source Qualtrics alternative .

### Pegasystems
**Type:** CRM and business process automation with AI  
Pegasystems provides CRM applications and business process management (BPM) with AI-powered decisioning and automation. Suited for complex enterprise workflows requiring deep process orchestration and real-time decision management.

---

## 🟩 Open-Source Software

Self-hosted, community-driven CX tools. The open-source ecosystem **splits** across feedback/survey platforms, customer data platforms, support inboxes, behavioral analytics, and journey mapping tools rather than unified suites.

### Formbricks
**Stack:** TypeScript / Next.js / React / PostgreSQL | **License:** AGPL-3.0 (core)  
Formbricks is the most direct open-source alternative to Qualtrics, providing a privacy-first experience management platform for gathering feedback at every point in the user journey [citation:9]. Features include in-app, website, link, and email surveys with a no-code editor; best-practice templates; targeting to specific user groups without code changes; shareable link surveys; team collaboration; and integrations with Slack, Notion, Zapier, and n8n . The Formbricks Hub (Apache-2.0) is a Go backend for feedback unification and AI enrichment, creating embeddings and analyzing sentiment at scale [citation:1]. Self-hosting via Docker with AGPLv3 licensing .  
**Best for:** Teams wanting a self-hosted Qualtrics alternative for surveys and feedback with privacy-first design and a growing AI enrichment layer.

### Tracardi
**Stack:** Python / Docker | **License:** MIT with Common Clause  
Tracardi is an API-first, composable open-source Customer Data Platform (CDP) engine, positioned as an alternative to Segment and RudderStack [citation:8]. Features include collecting and aggregating customer data from multiple sources in real time, modeling data with rules, unifying profiles from different sources, personalizing user experience with frontend apps, and integrating internal systems. Designed for building a custom CDP on existing infrastructure. **Note:** MIT with Common Clause licensing restricts certain commercial uses .  
**Best for:** Teams wanting to build their own CDP foundation with full control over customer data collection, unification, and activation.

### Chatwoot
**Stack:** Ruby on Rails / Vue / PostgreSQL | **License:** MIT (Community Edition)  
Chatwoot is an open-source omnichannel support desk covering email, website live chat, WhatsApp, Facebook Messenger, Instagram, SMS, and custom channels in a single queue [citation:6]. The Community Edition is MIT-licensed with assignments, private notes, collision detection, canned responses, and labels. Enterprise features like SSO and audit logs require a paid tier. Positioned as an Intercom/Zendesk alternative for teams wanting a single support inbox.  
**Best for:** Teams needing a unified support inbox across multiple channels with MIT licensing and Docker-friendly deployment.

### FreeScout
**Stack:** PHP / Laravel / MySQL | **License:** AGPL-3.0  
FreeScout is a self-hosted help desk and shared inbox explicitly positioned as a free Zendesk and Help Scout alternative [citation:13]. Features include omnichannel centralization (email, WhatsApp, Telegram, Facebook, Slack, Live Chat), unlimited agents and mailboxes, collision detection, internal notes, auto-replies, and integrations via API. Deployable on shared hosting with PHP/MySQL. Some advanced modules are paid add-ons.  
**Best for:** Technical teams wanting a free-forever shared inbox with help desk features on minimal infrastructure.

### Znuny
**Stack:** Perl / MySQL/PostgreSQL | **License:** GPL-3.0  
Znuny is an open-source ticketing and ITSM platform forked from OTRS, offering help desk and product support workflows with SLAs, customer portal, FAQ/knowledgebase, and third-party integrations [citation:4]. Free and fully customizable, with cloud or on-premises deployment. Vendor support starts at €3,900/year. Production servers need at least 8 GB RAM (16 GB recommended) .  
**Best for:** IT and service teams wanting an OTRS-style service desk with SLAs and knowledge base without license fees.

### Retentioneering
**Stack:** Python (DuckDB) | **License:** Open Source (per project)  
Retentioneering is an open-source Python library for user behavior analysis and customer journey visualization [citation:5]. It reconstructs real user paths through a product — including detours, loops, and dead ends — with interactive Transition Graphs, Step Sankey diagrams, and Step Matrix views. Features include funnel analysis beyond predefined steps, group comparison (A/B arms, channels), and an MCP server for LLM agents to explore eventstreams in plain language. Runs in Jupyter, VS Code, or Colab with exportable interactive HTML reports.  
**Best for:** Product analysts and UX researchers wanting to understand *why* metrics moved by visualizing actual user behavior paths rather than aggregate dashboards.

### OpenPanel
**Stack:** (Check repository) | **License:** AGPL-3.0  
OpenPanel is an open-source product analytics platform positioned as a Mixpanel alternative [citation:15]. Features include cookieless tracking by default, funnels, cohorts, session replay (no session cap), and self-hosting with identical features to the cloud version. Cloud pricing is flat-tiered ($2.50–$90/month) rather than event-volume-based, and self-hosting is free with no event caps.  
**Best for:** Teams wanting Mixpanel-style product analytics with flat pricing or free self-hosting, focused on analytics rather than broad CX suite functionality.

### CX Impact
**Stack:** Node.js / AI Agent Skill | **License:** Open Source (per project)  
CX Impact is an open-source tool for AI agents that turns documents, process descriptions, and numbers into visual maps of customer journeys, service blueprints, process maps, and sales funnels [citation:11]. Features include AS IS / TO BE comparison, source preservation, and standalone HTML output that opens without a server or account. Installed as a skill for Codex, Claude Code, and other AI agents.  
**Best for:** Product managers and analysts wanting AI-assisted customer journey mapping and funnel visualization without a dedicated SaaS platform.

---

## 📊 Comparison at a Glance

| Software | License | Stack | CX Focus | Self-Hosted | Best For |
|----------|---------|-------|----------|-------------|----------|
| **Salesforce** | Proprietary | Cloud | Full suite | ❌ | Enterprise CRM + CX |
| **Adobe Experience Cloud** | Proprietary | Cloud | Marketing + data | ❌ | Digital experience enterprises |
| **Oracle CX** | Proprietary | Cloud | Full suite | ❌ | Oracle-centric enterprises |
| **SAP CX** | Proprietary | Cloud | Full suite | ❌ | SAP S/4HANA integration |
| **Zoho CRM Plus** | Proprietary | Cloud | CRM + marketing + surveys | ❌ | SMB breadth at flat price |
| **Zendesk Suite** | Proprietary | Cloud | Support + engagement | ❌ | Mature support ecosystem |
| **Qualtrics XM** | Proprietary | Cloud | Experience management | ❌ | Enterprise XM research |
| **Formbricks** | AGPL-3.0 | TypeScript/Next.js | Surveys + feedback | ✅ | Qualtrics alternative |
| **Tracardi** | MIT + Clause | Python/Docker | Customer data platform | ✅ | Custom CDP foundation |
| **Chatwoot** | MIT | Ruby/PostgreSQL | Omnichannel support | ✅ | Unified support inbox |
| **FreeScout** | AGPL-3.0 | PHP/MySQL | Shared inbox + help desk | ✅ | Free-forever shared mailbox |
| **Znuny** | GPL-3.0 | Perl | Ticketing + ITSM | ✅ | OTRS-style service desk |
| **Retentioneering** | Open Source | Python/DuckDB | Behavioral journey analysis | ✅ | Why metrics moved |
| **OpenPanel** | AGPL-3.0 | (Check) | Product analytics | ✅ | Mixpanel alternative |
| **CX Impact** | Open Source | Node.js/AI Skill | Journey mapping | ✅ | AI-assisted CX mapping |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Unified CX Suite or CX component that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** across feedback platforms (Formbricks), customer data platforms (Tracardi), support inboxes (Chatwoot, FreeScout), behavioral analytics (Retentioneering, OpenPanel), and journey mapping (CX Impact). No single open-source project replicates the breadth of Salesforce Customer 360 or Adobe Experience Cloud, but combinations can cover most CX needs. Formbricks is currently the most notable open-source CX platform, explicitly targeting the "top 5% of technical CX teams" restricted by Qualtrics and Medallia platform limitations [citation:1].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
