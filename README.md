# Hit Your Mark Travel — Brand Toolkit

**Version:** 1.0  
**Date:** May 2026  
**Agent:** Mark Sole, Founder & Travel Director  
**Web:** hymtravel.com  
**Contact:** mark@hymtravel.com · (408) 568-1404

---

## Overview

Hit Your Mark Travel is a single-agent luxury travel firm designing bespoke journeys for time-poor, taste-rich travelers. Household income $400K+, ages 38–65. They've outgrown booking sites. They want someone who already knows which villa on which side of the caldera — and why.

**Tagline:** Dream It. Aim It. Book It.  
**Differentiator:** "Booking engines sell inventory. We design journeys."

**Sources used:**
- Logo: `assets/logo.png` (PNG with transparency, shield + compass rose mark)
- Existing website: https://www.hymtravel.com (pre-rebuild reference only)
- Brand voice document: provided by Mark Sole

---

## File Manifest

```
/
├── README.md                    ← this file
├── SKILL.md                     ← agent skill definition
├── colors_and_type.css          ← all CSS tokens + component base styles
├── assets/
│   └── logo.png                 ← primary brand mark (transparent PNG)
├── preview/
│   ├── 01-brand-colors.html     ← color swatches
│   ├── 02-typography.html       ← type scale specimens
│   ├── 03-logo-usage.html       ← logo on backgrounds
│   ├── 04-voice-tone.html       ← voice pillars + before/after
│   ├── 05-components.html       ← buttons, badges, nav
│   ├── 06-destination-card.html ← trip/destination card
│   ├── 07-business-card.html    ← print card front/back
│   ├── 08-email-signature.html  ← email sig (light bg)
│   └── 09-social-templates.html ← Instagram post, quote, story
└── Brand Toolkit.html           ← full interactive reference hub
```

---

## Content Fundamentals

**Voice in one line:** Warm, confident, editorial. Never salesy.  
Think *Condé Nast Traveller* meets a trusted friend who happens to know the world's best hotels.

### Four Pillars

| Pillar | Definition |
|--------|-----------|
| **Warm** | A person who genuinely loves this work. Copy feels like a conversation with a friend who's been everywhere — not a brochure. |
| **Confident** | World traveler with a lifetime of experience. No pitching, no overselling, no exclamation points. State things plainly. |
| **Editorial** | Long, considered sentences. Specific sensory detail over generic adjectives. Name the reef, the wine, the chef, the view. |
| **Never Salesy** | No "Book now!" No "Don't miss out!" No urgency theater. The only CTA is "Plan My Trip" — an invitation, not a transaction. |

### Writing Rules
- Write like *Condé Nast Traveller*, *Departures*, or *Travel + Leisure* — not like a booking site
- Lead with the experience and the place, not the price or the deal
- Use specific, evocative language: name the reef, the wine, the chef, the view
- Trust the reader's intelligence — luxury travelers don't need to be sold to
- Keep it human — curator and friend, not algorithm

### Words to Avoid
`amazing` `incredible` `stunning` (as filler) · `dream vacation` · `trip of a lifetime` · `paradise` · `Book now!` · `Don't miss out` · `Limited time` · `Rates from` · `Save up to` · `Exclamation points`

### The One CTA
**"Plan My Trip"** — always and only. Never "Book Now," "Contact Us," or "Get a Quote."

### Casing
- Headlines: Title Case
- Eyebrows/labels: ALL CAPS, tracked
- Body copy: Sentence case
- No emoji

---

## Visual Foundations

### Colors
Three signature colors drawn from the logo:

| Role | Color | Hex |
|------|-------|-----|
| Navy Primary (bg) | `--navy-800` | `#0d1b2a` |
| Navy Deep (page bg) | `--navy-900` | `#080f1a` |
| Navy Elevated (cards) | `--navy-600` | `#1a2d45` |
| Gold Primary (accent) | `--gold-500` | `#C9A84C` |
| Gold Light (hover) | `--gold-400` | `#d4b86a` |
| Gold Deep (text on light) | `--gold-700` | `#a8862e` |
| Silver Primary | `--silver-400` | `#8a9bb0` |
| Cream (primary text) | `--cream-100` | `#f5f0e8` |

Full token list in `colors_and_type.css`.

### Typography
- **Display/Headings:** Raleway (Google Fonts) — weights 300/400/500/600/700/800
- **Body/UI:** DM Sans (Google Fonts) — weights 300/400/500/600
- Headers: letter-spacing `-0.02em`, tight line-height `1.1`
- Labels/eyebrows: ALL CAPS, `letter-spacing: 0.20–0.22em`
- Body: `line-height: 1.7`, DM Sans 400

### Backgrounds
- Default: dark navy surfaces (`--navy-800`, `--navy-900`)
- Cards: slightly elevated navy (`--navy-600`, `--navy-700`)
- Light variant: cream/white for email, print, proposals
- No gradients as backgrounds — use flat navy
- Photography: full-bleed with dark overlay (gradient from bottom)

### Imagery / Photography
- Style: Aspirational & moody — dramatic landscapes, golden hour, rich contrast
- Color grade: slightly cool/desaturated highlights, deep shadows
- Approach: Lead with place, not people. Name-specific locations, not generic "beach at sunset"
- Placeholder treatment: navy `#1a2d45` with uppercase label text in silver

### Cards
- Background: `--navy-700` (`#132234`)
- Border: `1px solid rgba(138,155,176,0.18)` (subtle silver)
- Hover: border transitions to gold `rgba(201,168,76,0.3)` + subtle gold glow shadow
- No left-border-only accent — full border system
- Image area: 55–60% of card height, full-bleed photo or placeholder

### Buttons
- Primary: gold fill `#C9A84C`, navy text — zero border-radius
- Outline: gold stroke, transparent fill
- Ghost: silver stroke, cream text
- All: Raleway 700, tracked uppercase, 14px
- Hover: primary lightens to `--gold-400`, adds gold glow shadow

### Borders & Radius
- Standard radius: `0` (sharp — precision aesthetic)
- Cards: `0` sharp
- Badge pill: `0` (stays rectangular — consistent with precision mark identity)
- Dividers: `1px solid rgba(138,155,176,0.18)` (subtle) or gold `rgba(201,168,76,0.3)` (emphasis)

### Shadows
- Cards: none at rest; `0 0 24px rgba(201,168,76,0.12)` on hover
- Logo on dark: `drop-shadow(0 8px 32px rgba(201,168,76,0.25))`
- Business card: `0 16px 48px rgba(0,0,0,0.5)`

### Animation
- Transitions: `all 150ms cubic-bezier(0.16,1,0.3,1)` (fast ease-out)
- Hover states: color + border-color transitions only; no scale/bounce
- Page loads: no animated entrance; content appears instantly

### Iconography
- No icon system currently defined
- Brand mark (compass rose within shield) is the primary visual icon
- Text-based navigation preferred over icon-based
- Arrow `→` used as inline CTA indicator (text, not SVG)
- Recommend: Lucide Icons (stroke, weight `1.5`) if icons are needed in future

---

## Customer Profiles

**The Milestone Couple** (35–55) — Honeymoon, anniversary, big birthday. Avg trip: $25K–60K.  
**The Established Family** (40–60, kids 8–22) — Multi-gen luxury, zero logistics. Avg trip: $40K–100K+.  
**The Connoisseur** (50–70, empty-nester) — Has been everywhere obvious. Wants Bhutan, private chef Provence. Avg trip: $30K–150K.

**Where they live:** Manhattan, Greenwich, Miami/Palm Beach, LA, Bay Area, Aspen, Nashville, Austin, Charleston, Naples FL.  
**How they find HYM:** Almost always referral. Secondary: organic search, Instagram, editorial features. Not Google Ads.

---

## Trip Categories

All-inclusive resorts · River & ocean cruises · International adventure / bucket list · Family luxury vacations · Honeymoons & romance · Group travel · Safari & wildlife · Corporate / incentive travel

---

## Next Steps for Website Rebuild

1. Provide destination photography (aspirational, moody, location-specific)
2. Define category pages — recommend: Honeymoons, Safaris, Cruises & Yachts, Family, Hidden Gems
3. Confirm if a blog/journal section is desired ("The Journal" fits brand voice perfectly)
4. Confirm if client testimonials / case studies are available
5. Decide on inquiry form vs. direct email/phone CTA
