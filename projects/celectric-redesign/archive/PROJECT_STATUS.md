# Celectric Redesign - Internal Project Status

## Objective
Create a clearer structure to plan, track, and execute the Celectric website redesign.

## Current Direction
Reference structure is based on Instrumart.
Working recommendation is to position Celectric as an industrial product catalog plus enquiry platform.

## Current Status
- Initial recommendation shared
- Direction leaning toward catalog + RFQ rather than full e-commerce
- User requested a dedicated folder with separate internal and external markdown files
- Blog / insights feature added into planning scope

## Folder Structure
- `external/CLIENT_DISCUSSION.md`
  - Client-safe discussion points
  - Scope confirmation
  - Proposed directions
  - Open questions
- `internal/PROJECT_STATUS.md`
  - Progress tracking
  - Internal decisions
  - Next actions
  - Risks and assumptions

## Internal Working Assumptions
- Celectric is better suited to enquiry-first conversion in phase 1
- Product discovery, specifications, and product detail pages are key
- Search, brand pages, category structure, and blog / insights content will be important parts of the redesign

## Work Completed
- Framed redesign direction using Instrumart as structural reference
- Recommended quote cart / RFQ approach
- Created project documentation structure for external and internal use
- Added blog / insights feature into planning documents and scope
- Added blog page module breakdown
- Added blog content model and CMS field recommendations
- Added blog relation rules for products, brands, and solutions
- Added a single client-facing version document with clearer UI/UX intent
- Added Cloudflare R2 roughly 30GB storage note for documents and downloadable assets
- Split planning into client version, development requirements, and phase plan documents

## Next Recommended Actions
1. Confirm business model
   - RFQ only
   - mixed RFQ + direct purchase
   - full e-commerce
2. Define sitemap
3. Define page list and modules
4. Define product data structure
5. Define blog content model and editorial flow
6. Decide phase 1 scope
7. Define SEO strategy for product options / variants
8. Define product document attachment model

## Risks / Unknowns
- Unknown number of products and brands
- Unknown quality of existing product data
- Unknown whether pricing is fixed or enquiry-based
- Unknown internal quotation workflow
- Unknown whether existing CMS / backend must be reused
- Unknown variant complexity across products
- Unknown number and types of downloadable product documents

## Suggested Deliverables Next
- Sitemap
- RFQ flow
- Database / content model suggestion
- Phase-based roadmap
- Variant URL and SEO rules
- Product documents management rules
- Search indexing and autocomplete rules for product variants
- SEO architecture and sitemap examples
- Client confirmation items for product option SEO handling
- Implementation-ready functional spec for blog + resources relationship if needed
- Client review presentation workflow from markdown
- Cloudflare R2 storage and secure document delivery planning
- Dedicated client, development, and phase planning documents
- Client version simplified into one better presentation-ready document

## Decision Log
- 2026-04-18: Start project docs with separate external and internal markdown files.
- 2026-04-20: Add blog / insights feature into planning scope for SEO, authority building, and top-of-funnel traffic.
- 2026-04-20: Add blog module breakdown, content model, editorial workflow, and relationship rules.

## Notes
Keep external file clean and client-facing.
Keep internal file honest about risks, assumptions, and implementation direction.
