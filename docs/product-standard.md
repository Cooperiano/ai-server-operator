# Product standard

Every product uses the same four-layer structure.

| Surface | Purpose | Authentication | Indexing |
| --- | --- | --- | --- |
| Public site | Explain, educate, convert | No | Yes |
| Documentation | Teach and answer questions | No | Yes |
| App console | Deliver the service | Required | No |
| API | Stable machine interface | Token/OAuth | No |

## Navigation contract

The public site always shows Product, Use cases, Docs, Open source, Pricing, and **Open console**. The console keeps the same logo and provides an obvious **Back to website** link. A persistent environment label distinguishes public content from the authenticated console.

## URL contract

- `https://product.example/`
- `https://product.example/docs/`
- `https://app.product.example/`
- `https://api.product.example/v1/`
- `https://status.product.example/`

## Release contract

Community source and the free self-hosted edition ship together. Hosted convenience and enterprise controls may be paid, but core safety behavior remains inspectable.

## Search and answer-engine contract

- One search intent and one canonical URL per page
- Descriptive titles, summaries, headings, and internal links
- `SoftwareApplication`, `Organization`, `WebSite`, and `FAQPage` structured data where accurate
- Human-readable comparisons, definitions, limitations, and cited technical claims
- `robots.txt`, XML sitemap, canonical URLs, Open Graph metadata, and fast static rendering
- No authenticated console page is indexable
