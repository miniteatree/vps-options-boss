# Celectric Blog / Insights - Content Model and CMS Fields

## Purpose
Define the core content structure and CMS fields needed for the blog / insights feature.

## Content Type
### Blog Post
Recommended fields:
- Title
- Slug
- Short excerpt
- Body content
- Featured image
- Category
- Tags
- Author
- Publish status
- Publish date
- Updated date
- SEO title
- Meta description
- OG image
- Canonical URL override if needed
- Featured post toggle
- Related products
- Related brands
- Related solutions
- CTA type
- CTA label
- CTA destination

## Optional Additional Fields
- Reading time
- Summary / key takeaways
- Table of contents toggle
- External source references
- Attachment files if some articles include downloadable PDF guides

## Taxonomy Recommendations
### Categories
Use controlled, limited categories.
Suggested examples:
- Technical Guides
- Product Comparisons
- Applications
- Industry Insights
- Company News
- Case Studies

### Tags
Use tags carefully.
Tag rules:
- do not create too many thin tags
- avoid near-duplicate tags
- use tags mainly for topical grouping, not as a replacement for categories

## Editorial Status Options
- Draft
- In Review
- Scheduled
- Published
- Archived

## Related Content Rules
A post may be linked to:
- one or more products
- one or more brands
- one or more solutions

Recommended behavior:
- related links should be optional
- editors should control them manually at first
- automation can be added later if needed

## SEO Rules
- Each post should have editable SEO title and meta description
- Slugs should stay short and clean
- Category archive pages should be indexable only if they have enough value
- Tag archive pages should be noindex by default unless proven useful
- Articles should include internal links to relevant product, brand, solution, or contact pages

## AI Assistance Guidance
If AI is used in the CMS:
- use it to draft titles, outlines, and meta descriptions
- require human review before publishing
- do not allow AI to invent technical specifications or certifications

## Media Rules
- featured images should follow consistent aspect ratio
- article body images should be optimized for web
- diagrams and spec visuals should remain readable on mobile
