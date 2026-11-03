# Birtukan M Ayalew

**Founder & Full-Stack Builder — I ship products that solve real problems and power better decisions**

Law-trained (LL.M., Business Law). Building across fintech, compliance, health, and faith tech.

## About Me

The clearest way to describe me is by what I build. My work solves real problems and helps people make better, faster decisions — investment risk (FRMQuant), trading mornings (SignalDesk), compliance readiness (ComplianceOS), and what to do in the gym today (ActiveUp). I'm a full-stack founder who takes products from 0 to 1 and ships them to real users.

My legal training (LL.M. in Business Law) is the foundation, not the headline — it's why the products I build in regulated spaces are compliant, credible, and strategically sound. But my fruits are the products themselves: tools that solve a problem and help people decide and act.

- **Location:** Santa Clara, California
- **Website:** [frmquant.com](https://www.frmquant.com)
- **LinkedIn:** [birtukan-m-ayalew](https://www.linkedin.com/in/birtukan-m-ayalew-861112a1)

---

## Current Projects

### 🏦 FRMQuant — Institutional Portfolio Analytics
**70+ institutional-grade quantitative tools** in one platform — the risk models used on hedge-fund and trading desks, built for RIAs, family offices, and serious individual investors. Not another portfolio tracker.

**This is rigorous mathematics, not AI.** Every model is grounded in peer-reviewed financial research and runs on deterministic, transparent calculation engines — the formulas, assumptions, and data sources are all shown, no black boxes. (An optional AI assistant adds plain-language insights, but the quant math stands entirely on its own.)

**Live Platform:** [frmquant.com](https://www.frmquant.com) · 70+ tools · live market data (Polygon.io) · free tools, no account · SOC 2-compliant infrastructure

**Risk & Quant Models**
- Value at Risk — Parametric, Historical, Monte Carlo, and Liquidity-Adjusted
- EVT tail risk — Peaks-Over-Threshold / Generalized Pareto
- CDaR — Conditional Drawdown at Risk
- Copula tail-dependence modeling
- Sharpe confidence intervals — Probabilistic & Deflated Sharpe (PSR/DSR)
- Hierarchical Risk Parity (HRP) & Black-Litterman allocation
- Factor decomposition — Fama-French, momentum, and quality

**Analytics Suite**
- Stress testing (2008, COVID, tech bubble, custom), backtesting, portfolio optimization (efficient frontier, Sharpe max, rebalancing, what-if), correlation & drawdown analysis, transaction-cost/fee analysis, multi-asset coverage (stocks, ETFs, crypto)
- **Tax Center** — lot tracking (FIFO/LIFO/HIFO), wash-sale detection, one-click Form 8949 export
- **Free tools (no account):** Market Risk Today, Correlation Checker, Cost Calculator

**Enterprise:** SSO (SAML, OAuth, Microsoft & Google) · role-based team management · audit logs · RESTful API

**Tech Stack:** React, TypeScript · Node.js, Firebase · Google Cloud Platform · Polygon.io market data · optional AI assistant (Claude)

**Business Model:** Professional $49/mo · Advisor $149/mo · Enterprise $999/mo · 7-day free trial
**Status:** Live in production with active paying customers

**Why I Built This:** Institutional investors have always had sophisticated risk tools — Bloomberg, FactSet, Axioma — but they cost $20,000–$50,000 a year. Every serious investor deserves real quantitative analysis, not just pretty charts. FRMQuant brings 70+ hedge-fund-grade tools to the browser at a fraction of the cost, with transparent methodology and no black boxes. My background in securities law and compliance ensures it meets SEC and FINRA expectations.

### 🛡️ ComplianceOS — Multi-Framework Compliance Platform
Full-stack compliance automation that gets startups audit-ready in weeks, not months — across SOC 2, ISO 27001, GDPR, HIPAA, PCI-DSS, NIST CSF, and CCPA.

**Live Platform:** [soc2iso.com](https://www.soc2iso.com)

**Features**
- Sourced Controls — 450+ controls across 7 frameworks, each cited to its public basis (GDPR articles, CFR sections, PCI requirements, AICPA criteria) for audit-grade transparency
- Gap Assessment — Know exactly where you stand against every control
- Policy Generator — 16 audit-grade security policies generated and customized instantly
- Evidence Management — Upload, organize, and track evidence with expiry alerts and audit trails
- Auto Integrations — Auto-collect evidence from AWS, GitHub, Google Workspace, Okta, Azure & Slack
- Security Scanner — Proprietary scan of HTTPS, security headers, and DNS; grades posture A+ to F and auto-fills controls
- Compliance Monitoring — Real-time score with trend charts and daily Slack alerts
- Risk Register — Track and manage risks with severity scoring and ownership
- Trust Center — Public page to share your security posture with customers
- Audit Reports — One-click professional PDF export for your auditor

**Tech Stack:** Next.js 14, TypeScript, Tailwind CSS · Next.js API Routes · Supabase (PostgreSQL, Auth, Storage) · Resend · jsPDF + autoTable · Recharts

**Status:** Live in production

**Why I Built This — compliance shouldn't cost you your runway.** I didn't set out to build a compliance company; I was building my own products. When enterprise customers and partners started requiring SOC 2 and other certifications, I hit the wall that stops so many founders cold: getting audit-ready traditionally means tens of thousands in tooling, consultants, and hidden fees — before you've closed a single deal that requires it. The most capable teams miss opportunities not because their security is weak, but because they can't afford to *document* that it's strong. That's backwards. So I built the tool I needed for my own products and opened it to every founder facing the same wall — a flat subscription, no hidden fees, with the controls, evidence, and policies **you own** and hand straight to your own auditor. My LL.M. in Business Law and compliance background let me ground all 450+ controls in their public source, so it's audit-grade, not guesswork. Compliance should be a starting cost, not a scaling reward.

### 📡 SignalDesk — AI Morning Briefing for Traders
An AI morning-briefing agent for traders, built on Meta's Muse Spark for the Meta Global AI Developer Hackathon.

**Repository:** [github.com/frmquant/signaldesk](https://github.com/frmquant/signaldesk)

**Features**
- Runs the universal trader morning ritual — key levels, event windows, and an if/then game plan — on any instrument (stocks, futures, FX, crypto)
- Live data and today's economic calendar via Muse Spark web-search grounding, with source citations to verify every number
- Chart reading via Muse Spark vision (multimodal)
- Honest by design — marks unknown data "n/a" instead of fabricating it

**Tech Stack:** Single-page HTML/CSS/JS · Meta Model API (Muse Spark, grounding, vision)
**Status:** Built during the Meta Global AI Developer Hackathon (2026)

### 💪 ActiveUp — Smart Workout Tracking
The fitness app that tells you exactly what to do every workout — so you stop planning and start lifting. Pre-built progressive programs, smart auto-progression, one-tap logging.

**Website:** [activeup.app](https://activeup.app) · **Download:** iOS App Store ·  

**Features**
- 72-session periodized programs — fat loss, complete beginner, muscular endurance, powerlifting, balanced development, or a custom-built plan
- One-tap logging — pre-filled weights, just tap "Complete Set"
- Auto progression — suggests +5 lbs when you're ready, no guessing
- Weekly volume tracking — shows which muscle groups are optimal, low, or neglected
- Rest timer + voice coach — auto-starts and counts down with audio cues
- Works offline

**Tech Stack:** iOS native · Swift/SwiftUI · Stripe (subscriptions)
**Model:** $12.99/mo or $99.99/yr (save 36%)
**Status:** Live on the iOS App Store

**Why I Built This:** Most people don't skip the gym because they're lazy — they skip because deciding *what to do* takes 30 minutes and kills momentum. ActiveUp removes that decision: open the app, see today's workout, start lifting. A decision-making tool disguised as a fitness app — the same thread that runs through everything I build.

### 📖 Thy Word Lamp — Sacred Scripture Study
Free Bible study platform for immersive engagement with Scripture.

**Website:** [thywordlamp.com](https://thywordlamp.com/)

> *"Your word is a lamp to my feet and a light on my path" — Psalm 119:105*

**Features**
- Multiple translations (KJV, ESV, Hebrew text)
- Immersive study experience and deep scripture-engagement tools

**Model:** Free (ministry / service project)
**Status:** Live and freely available

**Why I Built This:** Technology should serve multiple purposes — not just profit, but purpose. Thy Word Lamp reflects my commitment to using technical skills for service and spiritual growth.

---

## Legal Education & Expertise

**Master of Laws (LL.M.), United States Law** — Santa Clara University | 2013–2015
Specializations: Business Law & Corporate Transactions, M&A, Business Organization Formation (LLCs, Corporations, Partnerships), Corporate Taxation & Tax Planning, Contract Law & Legal Remedies, Business Property Law, Startup Legal Issues, Securities Law & Financial Regulation. *LL.M. Student Association — promoted student interests and collaborated with administration on policy matters.*

**Bachelor of Laws (LL.B.) — Juris Doctor Equivalent** — Bahir Dar University, Ethiopia | 2005–2009
*Law Students Union — led advocacy initiatives, coordinated cross-stakeholder policy work, provided legal aid.*

### Why My Legal Background Matters for Tech

- ✅ **Building Compliant Products** — regulatory requirements (SEC, FINRA, data governance), SaaS agreements and terms of service, compliance frameworks for regulated industries
- ✅ **Enterprise Sales & Negotiations** — credible engagement with General Counsels and Compliance Officers, corporate procurement, enterprise contract review
- ✅ **Strategic Partnerships & M&A** — partnership agreements, acquisition processes and due diligence, valuation and deal structures
- ✅ **Corporate Tax & Structure** — tax-efficient business models, enterprise tax implications of software, R&D tax credits and financial planning

This legal foundation makes me uniquely valuable in roles requiring both technical credibility and business/legal acumen — particularly in regulated industries like fintech, compliance, and enterprise SaaS.

---

## Technical Skills

**Languages & Frameworks:** JavaScript, TypeScript, React, Next.js · Swift, SwiftUI (iOS native) · Node.js, Python · Firebase, SQL, Supabase (PostgreSQL)
**Cloud & Infrastructure:** Google Cloud Platform, Firebase, Supabase, CI/CD pipelines, production deployment & scaling
**AI & Machine Learning:** Claude (optional AI assistant in FRMQuant), Meta Model API / Muse Spark — reasoning, web-search grounding, and vision (SignalDesk), prompt engineering for financial and compliance analysis
**Domain Expertise:** Fintech & quantitative finance · Security & privacy compliance (SOC 2, ISO 27001, GDPR, HIPAA, PCI-DSS, NIST CSF, CCPA) · Regulatory compliance (SEC, FINRA) · Mobile development (iOS)
**Development Practices:** Full-stack product development (0 to 1), agile/iterative development, user research, production operations and monitoring

---

## Philosophy: Building Across Domains

### 💼 Commercial (FRMQuant)
Building sustainable, revenue-generating businesses that solve real problems while remaining compliant with regulatory requirements.

### 🛡️ Legal Tech / Compliance (ComplianceOS)
Turning regulatory expertise into software — automating SOC 2, ISO 27001, GDPR, HIPAA and more so startups get audit-ready in weeks. Where my legal training and technical execution combine most directly.

### 📱 Consumer (ActiveUp)
Creating accessible tools that improve people's daily lives through intuitive, well-designed experiences.

### 🙏 Ministry ([Thy Word Lamp](https://thywordlamp.com/))
Using technical skills for service and spiritual growth, freely giving to build community and faith.

This range reflects my belief that technology should serve multiple purposes: **commercial viability, user wellbeing, and meaningful impact.**

---

## What I'm Looking For

I'm currently exploring opportunities that leverage my unique combination of:
- **Legal expertise** (Business Law, M&A, Corporate Structure, Compliance)
- **Technical execution** (Full-stack development, AI integration, Product development)
- **Domain knowledge** (Fintech, Compliance, Regulated Industries, Enterprise SaaS)

**Ideal roles:**
- Technical Account Executive / Solutions Engineer (combining sales with technical depth)
- Product roles at the intersection of AI, fintech, and compliance
- Strategic partnerships requiring legal + technical expertise
- Developer advocacy / evangelism in regulated industries

---

## Code Privacy Note

The source code for FRMQuant, ComplianceOS, ActiveUp, and Thy Word Lamp is kept private for security and competitive reasons. These are live, production applications serving real users and customers.

**This public profile serves as a showcase of my work and capabilities.** My GitHub contribution graph reflects consistent, active development — the private repositories hold proprietary business logic, but the activity speaks to the technical work behind these products.

---

## Connect With Me

- 🌐 **Website:** [frmquant.com](https://www.frmquant.com)
- 🛡️ **ComplianceOS:** [soc2iso.com](https://www.soc2iso.com)
- 💼 **LinkedIn:** [birtukan-m-ayalew](https://www.linkedin.com/in/birtukan-m-ayalew-861112a1)

---

## At a Glance

**Products Live:** 4 (FRMQuant, ComplianceOS, ActiveUp, Thy Word Lamp)
**Users Served:** Active customers across financial services and startup compliance
**Tech Stack Breadth:** Web (React/Next.js/TypeScript) + Mobile (iOS/Swift) + Quant (VaR, EVT, HRP, Black-Litterman) + AI (Claude / Meta Muse Spark)

*(My contribution graph above reflects day-to-day development activity.)*

---

*Currently working on legal technology in relation to AI product development, compliance automation, fintech partnerships, and portfolio management — and roles combining legal expertise with technical execution.*

**Last updated:** November 2026
