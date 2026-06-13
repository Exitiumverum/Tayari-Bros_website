# Tayari-Bros_website (legacy / old domain)

Static single-page site for the **old** domain `tayari.co.il`.

The brand now lives on the **new** canonical domain:
**https://www.tayaribrothers.co.il**

This page is kept for the old domain, which **301-redirects** to the new domain
at the host/Vercel level. The HTML still carries correct, brand-consistent SEO so
that any crawler fetching the old domain resolves it to the one entity at the new
canonical URL:

- `lang="he" dir="rtl"`, real Hebrew `<title>` + meta description
- `<link rel="canonical">` → `https://www.tayaribrothers.co.il/`
- Open Graph + Twitter tags pointing at the new domain
- `Organization` + `WebSite` JSON-LD (alternateName: `אחים טיירי` / `טיירי` /
  `Tayari Brothers` / `Tayari`) `@id`-anchored to the new domain
- Favicon (`favicon.png`) — the same brand logo as the new site
- About copy mirrors the new site's claims-safe "מי אנחנו / מה אנחנו עושים /
  למי אנחנו מתאימים" answer blocks (no unproven importer/exclusive claims)

> Entity target: `אחים טיירי` = `אחים טיירי עסקי מזון בע"מ` = `Tayari Brothers`
> = `https://www.tayaribrothers.co.il`.
