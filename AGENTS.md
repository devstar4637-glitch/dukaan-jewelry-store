# AGENTS.md — Project Instructions for Jules

## Project: Dukaan Jewelry Store
A premium Indian jewelry dropship e-commerce store built as a modern, responsive web application.

## Tech Stack
- **Framework**: Next.js 14+ (App Router)
- **Styling**: Vanilla CSS with CSS custom properties (NO TailwindCSS)
- **Font**: Inter from Google Fonts
- **Language**: TypeScript

## Design Requirements
- **Aesthetic**: Premium, dark-mode-first with gold (#D4AF37) and rose-gold (#B76E79) accent colors
- **Style**: Glassmorphism cards, subtle micro-animations, sophisticated color palette
- **Target**: ₹100k-agency-quality presentation — NOT a basic template
- **Mobile-first**: 9:16 vertical layout must work beautifully (Instagram shoppers)

## Product Catalog (3 Products)
1. **Temple Choker** — ₹999 — Premium matte gold temple-style necklace
2. **Evil-Eye Bracelet** — ₹999 — Handcrafted evil-eye protection bracelet  
3. **Pearl Pendant** — ₹999 — Elegant freshwater pearl pendant necklace

## Pages Required
1. **Home/Landing** — Hero banner, featured products grid, trust badges, Instagram-style gallery
2. **Product Detail** — Image carousel, size guide, "Add to Cart" with quantity, related products
3. **Cart** — Line items, quantity controls, COD option highlighted, order summary
4. **Checkout** — Name, phone, address, pincode, COD vs Prepaid toggle
5. **About** — Brand story, craftsmanship promise, return policy

## Business Rules
- All prices are ₹999 (₹799-1,499 validated price band)
- Free shipping above ₹999 (i.e., always free for single items)
- COD available (highlight this — Indian customers expect it)
- Currency: INR (₹) only
- Trust signals: "Handcrafted", "Quality Assured", "Easy Returns"

## Code Style
- Use semantic HTML5 elements
- Every interactive element needs a unique, descriptive ID
- Proper heading hierarchy (single H1 per page)
- Add meta descriptions and Open Graph tags for SEO
- Components should be modular and reusable
