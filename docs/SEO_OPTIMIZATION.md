# SEO Optimization for Portfolio Sites

## Essential Meta Tags
```html
<meta name="description" content="[Your Name] - [Role]. Portfolio showcasing [skills]">
<meta name="keywords" content="developer, portfolio, [your skills]">
<meta property="og:title" content="[Your Name] - Portfolio">
<meta property="og:description" content="[Brief description]">
<meta property="og:image" content="[screenshot URL]">
<meta name="robots" content="index, follow">
```

## Performance Checklist
- [ ] Optimize images (WebP format, lazy loading)
- [ ] Minify CSS and JavaScript
- [ ] Enable GZIP compression
- [ ] Add `rel="preload"` for critical resources
- [ ] Score 90+ on Lighthouse

## Structured Data
```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "[Your Name]",
  "jobTitle": "[Your Title]",
  "url": "[Portfolio URL]",
  "sameAs": ["[GitHub]", "[LinkedIn]"]
}
```

## Free Deployment with Custom Domain
| Platform | Free Tier | Custom Domain | SSL |
|----------|-----------|---------------|-----|
| Vercel | Unlimited | Yes | Yes |
| Netlify | 100GB/mo | Yes | Yes |
| GitHub Pages | Unlimited | Yes | Yes |
| Cloudflare Pages | Unlimited | Yes | Yes |
