# High-Converting WebGL Ecommerce Template

**Single-file, production-ready HTML store** following the MASTER PROMPT for high-converting WebGL websites.

## How to use (only upload company identity & details)

1. Clone or download this repository.
2. Open `index.html` in a code editor.
3. Edit the **CONFIG** object near the top (clearly marked `/* ========== BRAND INPUTS — EDIT ONLY THIS SECTION ========== */`).
4. Replace the placeholder base64 logo with your real logo (convert PNG/SVG to base64 online and paste).
5. Update the products array, pricing tiers, events, and any copy to match your store.
6. Double-click `index.html` — it opens in any modern browser. No build step, no server, no npm.

### Required fields you change

```js
const CONFIG = {
  businessName: "Your Brand Name",
  tagline: "Your short powerful tagline",
  primaryColor: "#c9a227",          // primary brand hex
  accentColor: "#f5f5f5",
  background: "#0a0a0a",            // dark recommended for luxury
  logoBase64: "data:image/png;base64,iVBORw0KGgo...",  // your logo
  aesthetic: "dark luxury",
  priceRange: "R150 – R4 500",
  contact: {
    phone: "+27 11 123 4567",
    email: "orders@yourbrand.co.za",
    address: "12 Design District, Johannesburg",
    mapLink: "https://maps.google.com/?q=..."
  },
  hours: {
    0: "Closed",                    // Sunday
    1: "09:00 – 18:00",
    // ... Mon-Sat
  },
  socials: {
    instagram: "https://instagram.com/yourbrand",
    facebook: "https://facebook.com/yourbrand",
    whatsapp: "https://wa.me/27111234567"
  }
};
```

Everything else (Three.js scene, 16 conversion sections, auth gate, cart modal, toasts, mobile rules, anti-epilepsy lighting, syntax integrity) is already built according to the master prompt.

## What’s included

- Loader with logo ring + progress
- 3-step Auth Gate (Register → OTP demo → Welcome) + Guest + localStorage
- Sticky nav that blurs on scroll + full-screen mobile menu
- Full-viewport WebGL hero (Three.js r134) that fades on scroll
- Parallax layers, ticker, animated counters
- 6 Experience cards, Events schedule, filterable Products grid
- CSS-only atmospheric gallery (no external images)
- 3 Pricing packages (featured card uses border + shadow only)
- Location + live “today” highlight
- Lead-capture form
- Footer + social buttons (44×44)
- Checkout / Booking modal (bottom sheet on mobile, live total)
- Social-proof toast notifications cycling every 14 s
- Scroll progress bar, prefers-reduced-motion support

## Technical compliance (master prompt)

- Two separate IIFEs (Three.js + App)
- MeshPhysicalMaterial glass shells + procedural DataTextures
- No particle systems
- Max rotation/orbit speed ≤ 0.12
- if (PRM) return; first line of animate
- All interactive elements min-height: 44px
- Inputs font-size: max(16px, 1em)
- #gate overflow-y: auto
- Featured pricing card never uses transform: scale()

## License

MIT. Free for commercial use.

---

**Fill company identity → attach logo → open index.html → sell.**
