# Vikram | Profile README Knowledge Reference

> Internal design and content source of truth for the profile README. This file is not the final README.

## 1. Identity

**Primary positioning**

Software Engineer focused on backend and distributed systems, with 4+ years of production experience building scalable systems, high-throughput event pipelines, cloud data infrastructure, and third-party integrations.

**Core idea**

Build systems that have to actually work in production.

**What should be immediately clear**

- Backend and distributed systems are the professional center of gravity.
- Experience is not theoretical. It includes solo ownership of production systems.
- The work spans fintech, logistics, royalty accounting, messaging/integrations, cloud infrastructure, and data systems.
- Personal products demonstrate continued ownership outside employment.
- AI, ML, systems design, and developer tooling are areas of exploration, not empty branding.

**Identity facts**

- Vikram
- Software Engineer, Backend & Distributed Systems
- Bangalore, India
- B.Tech Computer Science & Engineering, IIITM Gwalior, 2021
- GitHub: https://github.com/vikramiiitm
- LinkedIn: https://linkedin.com/in/vikramchoudhry
- Personal products: https://eonom.com and https://blesshms.com

**Tone**

Direct, technical, confident, understated. No motivational language. No generic developer slogans. No emoji-driven identity. No AI/robot/cyberpunk aesthetic.

---

## 2. What I Build

The profile should communicate a coherent engineering pattern rather than a list of technologies.

**Primary system types**

- Event-driven backend systems
- High-throughput pipelines
- Cloud-native data infrastructure
- Distributed integrations between external platforms
- REST/API services
- Data transformation and ETL systems
- Logistics and compliance systems
- Financial/royalty accounting systems
- Production web applications

**Recurring engineering problems**

- Moving large volumes of data reliably
- Translating between incompatible external APIs and payload models
- Deduplication and idempotency
- Asynchronous processing and event delivery
- Security and secret management
- Rollback and operational safety
- Financial reconciliation and business rules
- Auditability
- Real-time notifications
- Third-party platform reliability

**Engineering pattern**

External systems -> APIs/events -> queues -> processing -> durable storage/data systems -> downstream callbacks/reporting.

This pattern is more important to the profile than naming every framework.

---

## 3. Proof / Experience

### Metromax Group | Software Engineer | Bangalore | Dec 2021 - Present

#### Ferns N Petals | SFMC WhatsApp Middleware | Solo ownership

Strongest proof of production engineering depth.

- Sole engineer for CleverTap-SFMC integration covering real-time WhatsApp delivery, promotional batch campaigns, and ENS delivery reporting across three production flows.
- Batch pipeline: SQS -> Lambda -> S3 -> SFTP.
- In-memory deduplication.
- Dynamic Salesforce Marketing Cloud Data Extension provisioning through SOAP API.
- Millions of records per run.
- Real-time OTT handler: API Gateway -> Lambda -> SFMC.
- Custom payload translation that removed attribute noise causing SFMC message rejection.
- SFMC webhook events consumed through SQS.
- Delivery status callbacks returned to CleverTap with msgId restoration.
- API security using Lambda Authorizer, AWS Secrets Manager, timing-safe key comparison.
- Terraform feature flag for zero-downtime rollback.

**What this proves:** event-driven architecture, distributed integrations, production ownership, throughput, reliability, security, rollback strategy, external API complexity.

#### BMG, Germany | GEMA Royalties Accounting System | Solo ownership

- End-to-end royalty accounting pipeline using Python, dbt and BigQuery on GCP.
- Multi-source ingestion and transformation.
- Automated financial reconciliation.
- Business-rule enforcement.
- Reduced manual reporting effort.
- Improved auditability across global royalty streams.

**What this proves:** data engineering, financial correctness, business-rule modelling, auditability, GCP, ETL, ownership.

#### PrePass / Fleetdrive360 | Logistics & Compliance Platform

- Backend systems processing millions of logistics and FMCSA compliance records.
- Real-time tracking and notification pipelines for supply-chain visibility.
- Stripe and HubSpot integrations.
- Role-based notifications.
- CI/CD pipelines.
- Selenium test suites.
- End-to-end EC2 deployments.

**What this proves:** large operational datasets, logistics domain complexity, integrations, deployment ownership, testing, notifications.

### Leadership and automation

- Managed and mentored interns.
- Led client communication and sprint planning across concurrent engagements.
- Built Selenium-based test automation.
- Automated internal workflows using MS Power Automate and MS Graph API.

---

## 4. What I Build Outside Work

Personal projects should appear as active products, not as a generic project list.

### EONOM

https://eonom.com

An Airbnb-like platform currently being built.

Known product direction includes listings, bookings, wishlists, reviews, messaging, promotions, recommendations, payments, notifications and events.

Known stack/context from project work:

- Next.js / React
- NestJS
- Prisma
- PostgreSQL

**Positioning:** a substantial product being built end-to-end, demonstrating product engineering beyond employment work.

### BLESSHMS

https://blesshms.com

A hospital management system spanning frontend and backend applications.

Known areas include patients, appointments, prescriptions, billing, inventory, labs, optics, analytics, administration, RBAC, audit trails, backups and cloud synchronization.

Known stack/context from project work:

- Next.js / React
- NestJS
- PostgreSQL

**Positioning:** complex domain software with operational workflows, permissions, auditability and multiple interconnected modules.

**Important:** Do not present either product as employment work. Do not reduce them to a project-card grid.

---

## 5. Exploration / Research

Exploration should show intellectual range without making the profile look like an AI portfolio.

### Machine learning research

Violence Detection in Smart Cities, B.Tech final-year research, Jan-May 2021.

- CNN-based deep learning model for automated violence detection in smart-city CCTV feeds.
- Benchmarked multiple architectures for real-time inference.
- Presented as final-year research at IIITM Gwalior.

### Current technical exploration

Repository activity indicates exploration across:

- AI agents and LLM systems
- Developer tooling
- Generative UI
- Model orchestration
- Code intelligence / code graphs
- Systems design and low-level design
- Backend and web frameworks

These should be framed as **exploration and curiosity**, not as claims of production expertise unless supported by professional or project evidence.

**Fork rule**

Forked repositories must never be represented as original projects. Source-repository stars must never be attributed to Vikram. Forks can be evidence of interest or experimentation only when useful.

---

## 6. Technical Foundation + Design Direction

### Technical foundation

**Languages**

Python, JavaScript, C/C++

**Backend / Web**

Django, Django REST Framework, NestJS, React, Next.js, REST APIs

**Cloud / Infrastructure**

AWS: SQS, Lambda, EC2, S3, IAM, API Gateway, Secrets Manager

GCP: BigQuery

Terraform, CI/CD, GitHub, Linux

**Data / Integration**

dbt, BigQuery, ETL pipelines, SFTP, SOAP, REST, Stripe, HubSpot, CleverTap, Salesforce Marketing Cloud, MS Graph API

**Architecture**

Backend systems, distributed systems, event-driven architecture, system design

### README design constraints

- Maximum visual/content footprint: approximately 1.5 GitHub profile pages.
- Build one section at a time. Do not implement the next section until explicitly approved.
- The README should feel authored, not template-generated.
- Avoid a conventional portfolio dashboard.
- Avoid generic hero banners, skill clouds, badge walls, contribution widgets, neon gradients, terminal screens, cyberpunk grids, robots, AI brains, server racks, fake system-status displays, or decorative graphs without meaning.
- Avoid giant SVG illustrations that consume space without communicating information.
- Use SVG where it creates a real visual system or interaction, not because SVG is technically possible.
- Every visual should communicate either identity, engineering depth, product ownership, or structure.
- The final result should feel technically sophisticated while remaining professional enough for a hiring manager.
- No fluff.
- No AI-style em dashes.

### Proposed visual language to explore

**Concept:** engineered editorial interface.

Not a dashboard. Not a magazine. Not a futuristic terminal.

Think of a carefully designed technical artifact where typography, spacing, diagrams and small pieces of system notation create the identity.

**Color direction**

Primary background: near-black graphite or warm off-white depending on final theme strategy.

Primary text: high-contrast neutral.

Secondary text: muted graphite.

Accent: one distinctive engineering color, likely oxidized orange / signal red / electric cobalt. Use sparingly.

Potential palette to prototype:

- Ink: #111111
- Paper: #F4F1EA
- Muted: #74716B
- Signal: #E05A3F
- Deep Signal: #8E3024
- Technical Blue: #355CFF

Do not commit to this palette until the hero prototype is visually tested.

**Typography direction**

Use a strong display face for the main statement, a highly legible sans for body copy, and monospace only for technical metadata.

Possible hierarchy:

- Display: high-contrast serif or distinctive grotesk
- Body: neutral sans
- Metadata: monospace

Do not turn the entire page into monospace.

**Layout direction**

- Strong asymmetry.
- Large whitespace around a small number of high-value statements.
- Thin rules and precise alignment.
- Small technical annotations used as visual anchors.
- Selective diagrams rather than decorative illustrations.
- Section transitions should feel like the same visual system, not six unrelated cards.

### Technical complexity we can exploit

GitHub profile READMEs support GitHub Flavored Markdown plus HTML and images. Relative paths can point to files in the profile repository. A `<picture>` element can also provide theme-specific images. This means the profile can behave more like a small static interface than a plain Markdown document while staying within GitHub's rendering constraints.

Potential architecture:

README.md
knowledge.md
assets/
  hero.svg
  experience.svg
  systems.svg
  products.svg
  exploration.svg
  foundation.svg

However, assets should only be created after the visual concept for that section is approved.

### Design objective

The finished profile should make a technically strong visitor think:

"This person has actually operated complex systems, understands how they fit together, and builds substantial things outside work."

The visual response should be:

**That is unusually well designed for a GitHub README.**

Not:

**That is a flashy GitHub README.**
