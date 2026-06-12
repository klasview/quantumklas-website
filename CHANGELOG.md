# Quantum KLAS LLC Website — Changelog

## v1.0-website — June 11, 2026

### Initial Release
- 5-page professional website built (Mercury-style)
- Home, Product (Diamond AI), About, Privacy, Terms
- Deployed to GitHub Pages with custom domain
- HTTPS/SSL via Let's Encrypt (auto-renews)
- DNS configured via Cloudflare

### Design System
- Monochrome black/white/grey palette
- Matches QuickSnap app design system (v0.2.1)
- Professional SVG line icons (Tabler-style)
- Gradient text on headings (white to grey)
- Fully responsive (mobile, tablet, desktop)

### Content
- Product name: Diamond AI (placeholder — may change)
- Patent Pending badge on every page
- Coming Soon CTAs for App Store and Google Play
- Generic AI/tech descriptions (proprietary details
  hidden until launch)
- Location references genericized to "United States"

### Security
- CSP, X-Frame-Options, X-Content-Type-Options headers
- Canonical URLs on all pages
- .gitignore for env files and secrets

### Infrastructure
- GitHub repo: klasview/quantumklas-website (public)
- GitHub Pages with custom domain
- Cloudflare DNS (5 records — 4x A + CNAME www)
- Domain: quantumklas.com

### Known TODOs for v2
- Update app name when finalized (currently "Diamond AI")
- Add real screenshots once app store assets ready
- Add team section when ready to go public
- Update App Store / Google Play buttons when live
- Consider adding logo (5 concepts created, awaiting
  selection)
