# Celectric Blog / Insights - Relationship Rules

## Purpose
Define how blog content should connect with products, brands, and solutions so the feature strengthens discovery and conversion instead of becoming isolated content.

## Core Principle
Blog content should support the commercial journey.
It should attract informational traffic, educate visitors, and guide them into relevant product, brand, solution, or enquiry pages.

## 1. Blog to Product Relationships
Use when:
- an article explains how to choose a product type
- an article compares product options
- an article discusses use cases or specifications

Recommended behavior:
- show related product cards inside or below the article
- link to relevant product categories or product detail pages
- use CTA wording such as View Product, Compare Options, or Request Quote

## 2. Blog to Brand Relationships
Use when:
- an article discusses brand strengths
- an article features a manufacturer or technology partner
- an article compares brands or product lines

Recommended behavior:
- link to brand overview pages
- allow articles to be attached to one or more brands

## 3. Blog to Solution Relationships
Use when:
- an article addresses an industry workflow or application
- an article explains how products solve a specific problem

Recommended behavior:
- connect the article to relevant solutions pages
- use clear contextual CTAs such as Explore This Solution

## 4. Manual First, Automation Later
Recommended phase approach:
- Phase 1: editors manually assign related products, brands, and solutions
- Phase 2: optionally suggest related items automatically based on tags, category, or keyword matching

## 5. Display Rules
### On article pages
Recommended order:
1. in-article contextual links
2. related product / brand / solution section
3. related posts section
4. final conversion CTA

### On product pages
Optional later enhancement:
- show related articles such as guides, comparisons, and use-case content

### On brand pages
Optional later enhancement:
- show latest related articles about that brand

### On solution pages
Optional later enhancement:
- show articles relevant to that application area

## 6. SEO and UX Rules
- related links must be genuinely relevant, not stuffed
- avoid excessive cross-linking that looks spammy
- use descriptive anchor text
- prioritize helpful reading paths over raw link count

## 7. Conversion Rules
Each article should have at least one meaningful next step:
- view a relevant product
- browse a related brand
- explore a solution page
- request a quote
- contact sales

## 8. Data Model Summary
Recommended relation fields on blog posts:
- relatedProducts[]
- relatedBrands[]
- relatedSolutions[]

Recommended future reverse-display behavior:
- products can optionally surface relatedPosts[]
- brands can optionally surface relatedPosts[]
- solutions can optionally surface relatedPosts[]
