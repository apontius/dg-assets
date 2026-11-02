# MailerLite Custom HTML Blocks

Version-controlled backups of every custom HTML block used on DisappointingGrace.com.

## Naming Convention

Files are named by page and block number:

```
<page>-block-<number>-<description>.html
```

### Main Landing Page Blocks

| File | Description | Char Count |
|------|-------------|------------|
| `main-block-1-hero.html` | Hero section with book cover and CTA |  |
| `main-block-2-audio.html` | Audio player with Chapter 1 sample |  |
| `main-block-3a-storm-quote.html` | "Caught in a storm" narrative section |  |
| `main-block-reviews-social.html` | Sliding hero carousel (5 review quotes) |  |
| `main-block-3b-discover.html` | "What You'll Discover" section |  |
| `main-block-reviews-main.html` | 6-card testimonials grid (mobile carousel) |  |
| `main-block-4a-author-formats.html` | Author bio + book formats |  |
| `main-block-reviews-closing.html` | Single closing quote on dark background |  |
| `main-block-4b-mission.html` | Mission / Pay It Forward CTA |  |
| `main-block-5-footer.html` | Footer with links and copyright |  |

### Terms of Service Page

| File | Description |
|------|-------------|
| `tos-block-1-header.html` | TOS header |
| `tos-block-2-body.html` | TOS content |
| `tos-block-3-footer.html` | TOS footer |

## Notes

- MailerLite has a **5,000 character limit** per custom HTML block
- MailerLite strips inline SVG; use SVG data URIs in `<img>` tags instead
- Inline styles are more reliable than class-based CSS in MailerLite
- `<style>` blocks with `@keyframes` and `@media` queries DO work
