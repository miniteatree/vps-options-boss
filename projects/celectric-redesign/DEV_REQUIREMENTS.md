# Celectric Development Requirements

## Purpose
Internal development reference for structure, rules, and implementation guidance.

## Core Product Direction
Industrial catalog + enquiry platform.

## Required Content Areas
- homepage
- products listing
- product detail
- brands
- solutions
- resources
- blog / insights
- contact / request quote
- presentation / review page

## URL Structure
- `/`
- `/products`
- `/products/{category}`
- `/products/{subcategory}`
- `/brands`
- `/brands/{brand}`
- `/products/{product-slug}`
- `/blog`
- `/blog/{category}`
- `/blog/{post-slug}`
- `/resources`
- `/about`
- `/contact`
- `/request-quote`

## Product Data Model
Minimum fields:
- name
- slug
- model code
- brand
- category
- summary specs
- full specs
- variant options
- related documents
- related products
- SEO title
- meta description
- canonical URL
- FAQ items

## Variant Rules
- minor options stay on parent page
- option state can be query-based
- distinct model-level variant may get separate page only if justified
- autocomplete should still surface variant phrases such as `product-a-10nm`

## Document Rules
- support product-level and variant-level files
- file groups: datasheet, manual, drawing, certificate, brochure
- use secure download links
- links should expire after a short window
- restrict internal-only documents

## Blog Requirements
- listing page
- article page
- categories
- tags
- related products / brands / solutions
- CTA blocks
- SEO fields
- author
- publish date
- featured article support

## Presentation Requirements
- presentation must be generated from markdown
- presentation should use a slide-like layout
- presentation style should not reuse the website theme directly
- presentation should be easy to scan by client

## Storage / Hosting
- mock preview: Cloudflare Pages
- production app: VPS + Cloudflare
- file storage: Cloudflare R2, about 30GB

## Development Phases
### Short term
- confirm IA
- confirm sitemap
- confirm content model
- define presentation pages

### Mid term
- implement main pages
- implement blog
- implement docs flow
- implement RFQ flow

### Long term
- search engine
- Odoo sync
- CRM integration
- user accounts / checkout if required

## Dev Notes
- keep client docs separate from dev docs
- keep markdown as source of truth for review materials
- keep file URLs secure and short-lived
