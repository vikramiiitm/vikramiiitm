<div align="center">

<img src="./hero.svg" alt="Vikram profile hero" width="100%" />

</div>

<br>

<table>
<tr>
<td width="58%" valign="top">

## `whoami`

**Software Engineer · Backend & Distributed Systems**

I build production systems where APIs, data, events and infrastructure have to work together — and I keep a parallel habit of building things just because the idea is interesting.

My work spans **backend architecture, cloud systems, web applications, AI tooling and product experiments**.

</td>
<td width="42%" valign="top">

### `signal`

```text
backend / distributed   ████████████████
AI / agents             ██████████████░░
web / product           █████████████░░░
cloud / infrastructure  █████████████░░░
experiments             ███████████████░
```

<sub>Not a skill ranking. Just where I spend my time.</sub>

</td>
</tr>
</table>

<br>

## `what i actually build`

<table>
<tr>
<td width="50%" valign="top">

### `EONOM`

A personal product built as a **separate web + application architecture**.

The UI is a Next.js / React application; the application layer is a NestJS service with Prisma/PostgreSQL, authentication, listings, bookings, wishlists, reviews, messaging, promotions, recommendations, payments, notifications and event-driven modules.

**The interesting part:** treating a product as a system, not just a screen.

</td>
<td width="50%" valign="top">

### `BLESSHMS`

A full hospital-management system split across **frontend + backend repositories**.

The frontend is a Next.js / React application covering patients, appointments, prescriptions, billing, inventory, labs, optics, analytics and administration. The backend provides NestJS APIs, PostgreSQL persistence, JWT/RBAC, audit trails, backups, licensing and offline/cloud synchronization.

**The interesting part:** real workflows meeting real infrastructure.

</td>
</tr>
</table>

```text
                    PRODUCT
                       │
          ┌────────────┴────────────┐
          │                         │
        EONOM                  BLESSHMS
          │                         │
     ┌────┴────┐              ┌─────┴─────┐
     │         │              │           │
     UI       API            UI          API
     │         │              │           │
   Next.js   NestJS         Next.js     NestJS
                │                         │
             Prisma /                  TypeORM /
             PostgreSQL                PostgreSQL
```

<sub>These are the kinds of systems I enjoy: multiple moving parts, clear boundaries, and enough complexity to make the architecture matter.</sub>

<br>

## `the engineering side`

<table>
<tr>
<td width="33%" align="center">

**BACKEND**

Python · Django · DRF  
Node.js · NestJS  
REST · GraphQL

</td>
<td width="33%" align="center">

**SYSTEMS**

AWS · GCP · Terraform  
SQS · Lambda · BigQuery  
Event-driven architecture

</td>
<td width="33%" align="center">

**DATA**

PostgreSQL · MongoDB  
Prisma · TypeORM · DBT  
ETL · APIs · SFTP

</td>
</tr>
</table>

<br>

## `production taught me`

```text
millions of records
        │
        ▼
   event pipelines ────────→ APIs ────────→ external systems
        │                     │                    │
        ▼                     ▼                    ▼
     queues                auth / RBAC          webhooks
        │                     │                    │
        └──────────────→ observability ←──────────┘
                              │
                              ▼
                         failure happens
                              │
                              ▼
                         design for it
```

I've worked on high-throughput event pipelines, third-party integrations, cloud infrastructure, data/ETL systems and backend platforms across production environments. My resume describes 4+ years of experience across fintech, logistics and royalty-accounting domains, including ownership of production systems end-to-end. fileciteturn42file0L5-L8

<br>

## `the pattern`

<table>
<tr>
<td align="center" width="33%">

### 01
**QUESTION**

Start with *why*.

</td>
<td align="center" width="33%">

### 02
**BUILD**

Make the idea real.

</td>
<td align="center" width="33%">

### 03
**PULL IT APART**

Understand what is actually happening.

</td>
</tr>
</table>

```text
                         ┌───────────────┐
                         │     IDEA      │
                         └───────┬───────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │        PROTOTYPE       │
                    └────────────┬───────────┘
                                 │
                       ┌─────────┴─────────┐
                       │                   │
                       ▼                   ▼
                 ┌───────────┐       ┌───────────┐
                 │   WORKS   │       │   BREAKS  │
                 └─────┬─────┘       └─────┬─────┘
                       │                   │
                       └─────────┬─────────┘
                                 ▼
                         ┌───────────────┐
                         │ UNDERSTANDING │
                         └───────┬───────┘
                                 │
                                 └──────────→ build again
```

<br>

## `currently`

**AI agents** · **LLM systems** · **developer tooling**  
**backend architecture** · **automation** · **web interfaces**  
**data + APIs** · **distributed systems** · **product experiments**

<br>

> ### **I don't want software that merely looks finished.**
> 
> I want to understand the machinery underneath it.

<br>

<div align="center">

`BUILD` &nbsp;→&nbsp; `BREAK` &nbsp;→&nbsp; `UNDERSTAND` &nbsp;→&nbsp; `REPEAT`

<br><br>

<sub>still building.</sub>

</div>
