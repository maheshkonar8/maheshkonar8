# Mahesh Konar

Backend & systems engineer. I build products that scale and I think about them like a business owner, not just an engineer.

Currently a Backend Engineer at Admobs, leading backend and system design on GlamGuider, a consumer beauty-tech platform serving 90K+ registered users and 22K monthly actives across web, Android, and iOS - 70K+ API requests/day at ~70 RPS peak. I own API design, system architecture, infrastructure, and cross-team execution.

📊 Live production metrics, queried from the system I run: [mahesh-portfolio-29e.pages.dev](https://mahesh-portfolio-29e.pages.dev)

### What I work with

`Node.js` · `TypeScript` · `Express` · `MongoDB` · `Redis` · `PostgreSQL` · `Docker` · `GitHub Actions CI/CD` · `Nginx` · `AWS (S3 / CloudFront)` · `Linux` · `System Design (HLD/LLD)`

### How I work

- I design APIs around how the product and the business actually use data, not just CRUD.
- Balances are derived, never trusted - I reach for ledgers, audit logs, and deny-by-default before I reach for quick fixes.
- I care about cost, scalability, and shipping things that move the product.

### Systems I've shipped in production

- Loyalty wallet & reward engine - 80K+ user wallets on an append-only transaction ledger with country-specific reward rules and a streak/milestone engine. Balances derived, never stored.
- Infrastructure migration - single server → Dockerized services + MongoDB Atlas behind Nginx, GitHub Actions CI/CD, zero-downtime deploys. Media on S3 + CloudFront: 1.3M+ CDN requests at 87% cache-hit, 91% of media bytes offloaded from origin.
- Product comparison & intelligence pipeline - queue-driven ingestion (collect → normalize → enrich → serve) separating heavy offline work from low-latency APIs. Authored the HLD.
- Review moderation pipeline - 13.7K+ reviews through an approval workflow with RBAC, audit logs, and bulk actions.

### Selected repos

- [loyalty-ledger](https://github.com/maheshkonar8/loyalty-ledger) - the append-only ledger + derived-balance pattern behind the production loyalty wallet, extracted into ~150 readable lines with tests.
- [aes-256-gcm](https://github.com/maheshkonar8/aes-256-gcm) - authenticated encryption of secrets at rest with tamper detection; the pattern datamint uses to store customer DB credentials.
- [datamint](https://github.com/maheshkonar8/datamint) - self-serve MongoDB reporting SaaS ([live](https://datamint-web.vercel.app/)). Multi-tenant RBAC, encrypted credentials at rest. Code private; full system design in the repo.

### Reach me

- 📁 Portfolio: <https://mahesh-portfolio-29e.pages.dev>
- 💼 LinkedIn: <https://www.linkedin.com/in/maheshk86000>
- ✉️ Email: <konartech@gmail.com>

Open to backend engineering roles and serious freelance work.
