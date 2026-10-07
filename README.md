## Chi Nguyen

Ecommerce systems engineer in Darwin, Australia (UTC+9:30). I build the
plumbing between suppliers, point-of-sale systems and online stores — the part
that is nobody's favourite job and quietly decides whether a catalogue is
trustworthy.

Founder and engineer of **[Sonic Invoices](https://sonicinvoices.com)**, which
turns a supplier PDF into live Shopify products with every variant, instead of
someone retyping it.

### What I actually work on

- **Catalogue pipelines.** Supplier invoice in, verified products out. Document
  extraction with an LLM, enrichment from the brand's own site, then a human
  approves before anything is written.
- **Feeds and compliance.** Google Merchant Center disapprovals, taxonomy and
  category metafields, GTIN check digits, duty and incoterm handling.
- **POS and store integration.** Lightspeed X-Series to Shopify, inventory
  parity, barcode and SKU reconciliation across systems that disagree.

Recent work, as counts a client could check at handover: a 3,181-product and
1,991-collection catalogue loaded from supplier invoices across 40+ wholesale
brands, a 3,857-product Google Shopping feed cleared of disapprovals, and a
~2,700-product POS migration with GTIN validation.

### How I work

**Prefer evidence of the effect over evidence of the intent.** A migration file,
a merged pull request, a green CI tick and an agent's own report are all intent.
The object existing in the database and the endpoint answering are effect. Most
confidently wrong engineering calls I have seen, including my own, are someone
reading intent and reporting it as effect.

I use agentic coding tools daily and keep a written contract file at the root of
each codebase — the specific ways that repo has made capable people confidently
wrong, measured, with the command that proves each one. Guardrails travel
further than review.

### Here

- **[shopify-store-audit](https://github.com/thanhchi4695-afk/shopify-store-audit)**
  — audit any public Shopify store from outside. No login, no API key, no app
  install. Node 18+, no dependencies. Its "things learned the hard way" section
  is the honest part.

Most of my work is in private client and product repositories, so this profile
is the smaller half of it. Happy to walk through the rest live.

**Stack:** TypeScript · React · Vite · Node · Deno · Postgres · Supabase ·
Shopify GraphQL Admin API · Cloudflare · Capacitor
