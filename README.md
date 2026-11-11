# Mahesh Konar

**Full-stack engineer in Mumbai, strongest on the backend.** I build the systems a business can't afford to get wrong: approvals, access control, money and points.

Nearly 3 years in production. Right now I own the backend of **GlamGuider** at Admobs, a beauty-tech platform on web, Android and iOS, and the admin panel its team runs on every day.

| 350K+ | 82K | 250K+ | 600K+ | 480+ |
| :---: | :---: | :---: | :---: | :---: |
| registered users | monthly actives | loyalty wallets | points transactions | REST endpoints I own |

🌐 **Portfolio & case studies:** [mahesh-portfolio-29e.pages.dev](https://mahesh-portfolio-29e.pages.dev/)

---

### What I've shipped

**GlamGuider** · *Full-time at Admobs · in production*
The Node.js/Express backend and React/Next.js admin panel behind the whole platform.
- **Approval engine** for 45+ content types. A change is a proposal until the final approval; live data is written once, in one transaction, with a full audit trail.
- **Loyalty ledger** with 250K+ wallets and 600K+ transactions. Balances are derived from entries, a redemption is decided exactly once, and a retry or double-click can never pay twice.
- **Exactly-once partner delivery** through an outbox with leased workers and retries from 30 s to 6 h. One broken partner key pauses only that platform.
- **Deny-by-default staff access** down to page, section and action; every ended session records why.
- **Moderation at scale:** 13K+ reviews in resumable batches of up to 500, points credited at most once per review.
- **Performance at peak (~70 RPS):** query rewrites, compound indexes, Redis caching, and media on S3 + CloudFront (1.3M+ CDN requests, 87% cache-hit, 91% of bytes off origin).
- Push to 123K+ devices with caps and cooldowns, 21 end-to-end suites on a throwaway replica set, and a handover manual generated from the code.

**AXM** · *Freelance · live*
A finance and partner portal for an ad network where no single person can move money alone: insertion orders, month close, invoices and payouts, two-person approval on payouts, mandatory 2FA for finance roles, full audit log.

**[DataMint](https://github.com/maheshkonar8/datamint)** · *My own product · [live](https://datamint-web.vercel.app/)*
Reports from your own MongoDB or Postgres without writing SQL or getting production access. Multi-tenant, credentials encrypted with AES-256-GCM, a query allowlist that rejects writes. Code is private; the system design is in the repo.

**Mira3D calibration** · *Samisan Tech*
C#/.NET software for Basler industrial cameras and real-time encoder data. Automated the calibration report people used to write by hand: ~80% less manual effort.

---

### How I work

- **Retries are normal. Paying twice is not.** Anything that moves points or money is safe to repeat.
- **The server decides, not the button.** Checks are re-run server-side before anything is written.
- **Build the engine once, then add adapters.** The next feature should be a small change, not a rewrite.
- **Leave it so the next person can run it.** Runbooks, real tests, honest docs about what still needs fixing.

---

### Open source

- [**loyalty-ledger**](https://github.com/maheshkonar8/loyalty-ledger): the append-only ledger and derived-balance pattern behind the production wallet, in ~150 readable lines with tests.
- [**aes-256-gcm**](https://github.com/maheshkonar8/aes-256-gcm): authenticated encryption for secrets at rest, with tamper detection. DataMint uses it for customer credentials.

---

### Stack

`Node.js` · `TypeScript` · `Express` · `MongoDB` · `PostgreSQL` · `Redis` · `React` · `Next.js` · `Docker` · `Nginx` · `AWS (EC2 / S3 / CloudFront)` · `GitHub Actions` · `Linux` · `Jest` · `System design (HLD / LLD)`

---

### Reach me

Open to **full-time backend / full-stack roles** and a few **freelance projects** (business web apps with admin panels, and backends that handle money, points or approvals).

🌐 [Portfolio](https://mahesh-portfolio-29e.pages.dev/) · 💼 [LinkedIn](https://www.linkedin.com/in/maheshk86000) · ✉️ [konartech@gmail.com](mailto:konartech@gmail.com)
