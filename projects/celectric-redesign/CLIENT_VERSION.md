# Celectric Client Review

## Goal
Present the recommended direction in a clean, easy-to-review format.

## Recommended Direction
Celectric should be positioned as an industrial product catalog plus enquiry platform.

## What the client needs to know
- The site should help buyers find products quickly.
- RFQ / enquiry should be the main conversion path.
- Blog / Insights should be included for SEO and trust.
- Product documents should be delivered through secure download links.
- Cloudflare R2 should be used for document storage, about 30GB.

## Main Navigation
- Products
- Brands
- Industries / Solutions
- Resources
- Blog / Insights
- About
- Contact / Request Quote

## Homepage
- search bar
- category entry points
- brand highlights
- featured products
- solutions section
- latest blog section
- clear enquiry CTA

## Product Page
- title and model
- brand
- images
- key specs
- downloads
- related products
- FAQ / Q&A
- RFQ button

## Product Option Rule
- minor options stay on one main product page
- query param states can be used for variant selection
- only distinct model-level variants should get separate pages

## Documents Rule
- use secure download links
- links should be time-limited and non-guessable
- email should contain links, not attachments

## Hosting Summary
- Mock / preview, Cloudflare Pages, RM0
- Production, Hetzner VPS + Cloudflare, RM30 to RM80 per month
- Storage, Cloudflare R2 about 30GB
- Domain, RM60 to RM120 per year

## Phase Summary
### Short term
- confirm direction
- finalise sitemap
- confirm page list
- confirm approval points

### Mid term
- build homepage
- build products
- build brands
- build blog
- build RFQ flow
- build document delivery flow

### Long term
- better search
- Odoo sync
- user accounts
- checkout if needed
- CRM integration

## Client Checklist
- [ ] industrial catalog + enquiry platform direction
- [ ] RFQ first, not full checkout
- [ ] brand pages included
- [ ] resources/document pages included
- [ ] blog / insights included
- [ ] minor options stay on one main product page
- [ ] secure document links instead of attachments
- [ ] Cloudflare R2 for about 30GB of documents
