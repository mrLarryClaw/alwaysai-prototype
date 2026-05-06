# alwaysai.eu — Website Design

> **Designed:** 2026-05-06 · Using designing-beautiful-websites skill
> **Inspired by:** alfatier.io (bold metrics, clean practice areas) + wirkt.ai (problem-first narrative, situation-based journeys)
> **Domain:** alwaysai.eu (NOT alwaysai.io)
> **Languages:** German (primary) + English

---

## 1. Design Brief

**Primary users:**
- German Mittelstand decision-makers (Geschäftsführer, IT-Leiter, Abteilungsleiter) who feel overwhelmed by AI
- Have tried AI and failed or not seen ROI
- Need practical help, not strategy papers

**Primary user goal:** Understand if AlwaysAI can help them — and get in touch for a first conversation.

**Business goal:** Generate qualified leads (Erstgespräch bookings). Position AlwaysAI as the pragmatic, always-current AI partner for Mittelstand.

**Key differentiator:** "We keep up so you don't have to." Unlike consultants who sell one project, AlwaysAI is the ongoing partner that stays current with the breakneck AI pace.

**Success metrics:** Contact form submissions, Erstgespräch bookings, time-on-page for service sections.

**Brand signals:** "Always AI" / "Immer AI" — reliable, ever-present, no-nonsense. Not a hype company. Grounded. Practical.

---

## 2. Core Message & Positioning

**Hero thesis:**
> Die nächste industrielle Revolution passiert gerade. In Rekordgeschwindigkeit.
> Und es ist OK, dass das überwältigend ist.

**Value proposition (sub-headline):**
> Wir verfolgen jeden Tag neue KI-Modelle, Tools und Methoden — damit Sie es nicht müssen.
> KI kann Ihr Business immer verbessern. Die Frage ist nur: die richtige.

**Tagline options:**
- "Always AI. Immer für Sie da."
- "KI, die ankommt. Immer."
- "Immer AI. Immer besser."

---

## 3. Information Architecture

```
alwaysai.eu
├── Hero (Startseite oben)
├── Warum wir? (The "overwhelmed" narrative + credibility)
├── Unsere 3 Schwerpunkte (Productivity / Automation / Security)
├── Schon KI ausprobiert und gescheitert? (Re-engagement section)
├── Wie wir KI nutzen (Social proof → Blog/Social links)
├── KI-Partner die wir nutzen (Tool logos)
├── CTA: Erstgespräch
├── Footer (Kontakt, Impressum, Datenschutz, Social links)
```

---

## 4. Key User Paths

### Path 1: "I'm overwhelmed by AI — help me"
Hero → "Warum wir?" (relatable narrative) → 3 Schwerpunkte → CTA Erstgespräch

### Path 2: "I tried AI and it failed"
Hero → "Schon KI ausprobiert?" section → 3 Schwerpunkte (see relevant one) → CTA

### Path 3: "I know what I need — show me services"
Hero → 3 Schwerpunkte (scan) → specific focus detail → CTA

---

## 5. Page Layout (Wireframe — Section by Section)

### 5.1 HERO SECTION
**Visual:** Dark background (deep navy/charcoal), subtle animated gradient or particle effect suggesting data/AI flow. Clean, bold typography.

**Layout:**
```
[Top bar: Logo "AlwaysAI" left | DE/EN toggle right]

[HERO — full viewport height]

  Die nächste industrielle
  Revolution passiert gerade.

  In Rekordgeschwindigkeit.
  Und es ist OK, dass das überwältigend ist.

  [Subheadline, lighter weight]
  Wir verfolgen jeden Tag neue KI-Modelle, Tools und Methoden —
  damit Sie es nicht müssen.

  [Primary CTA button — bright accent color]
  → Jetzt Erstgespräch vereinbaren

  [Secondary CTA — ghost button]
  Unsere Schwerpunkte ↓

[Scroll indicator — subtle arrow]
```

**Design notes:**
- Inspired by alfatier.io's bold "Enterprise-Qualität. Mittelstands-Budget." — but more emotional, like wirkt.ai's "KI, die ankommt."
- H1: 48-56px on desktop, 32px on mobile
- Two CTAs: primary = Erstgespräch (filled), secondary = scroll hint (outline)
- No navigation links in hero — reduce choice, focus on action

---

### 5.2 "WARUM WIR?" — The Overwhelm Narrative
**Visual:** White/light background. Clean text column, max 65ch line length.

**Layout:**
```
[Section padding: 96px top/bottom]

  Warum AlwaysAI?

  KI verändert alles — schneller als je zuvor in der
  Menschheitsgeschichte. Neue Modelle. Neue Tools.
  Neue Paradigmen. Jeden Tag.

  Sie haben ein Unternehmen zu führen.
  Dafür sind wir da.

  [3 stat cards in a row — inspired by alfatier.io's metric boxes]

  ┌────────────────┐  ┌────────────────┐  ┌────────────────┐
  │   Immer aktuell │  │  Praxisnah     │  │  Neutral       │
  │                │  │                │  │                │
  │ Wir testen      │  │ Keine           │  │ Wir verkaufen   │
  │ täglich neue    │  │ Strategie-      │  │ keine Tools —   │
  │ Tools & Modelle │  │ papier,         │  │ wir finden das  │
  │                 │  │ sondern Impact  │  │ passende für Sie│
  └────────────────┘  └────────────────┘  └────────────────┘
```

**Design notes:**
- Cards: subtle shadow (elevation 1), rounded corners (8px), hover lift effect
- Icons above each card title (clock/target/scale or similar)
- Background: slight off-white (#F7F8FA) to differentiate from hero

---

### 5.3 DIE 3 SCHWERPUNKTE — Services
**Visual:** Three-column layout. Each column has an icon, headline, description bullets, and a mini-CTA.

**Layout:**
```
[Section padding: 96px]

  Unsere 3 Schwerpunkte

  ┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐
  │   ⚡             │ │   🔄             │ │   🔒             │
  │                  │ │                  │ │                  │
  │  Produktivität   │ │  Automatisierung │ │  Sicherheit      │
  │                  │ │                  │ │                  │
  │  Nie genug       │ │  Keine Lust auf  │ │  Angst vor       │
  │  IT-Ressourcen?  │ │  spreadsheets?   │ │  Datenklau?      │
  │                  │ │                  │ │                  │
  │  • KI-Monitoring │ │  • Social Media  │ │  • Eigene KI     │
  │    wichtiger     │ │    automatisch   │ │    Modelle hosten│
  │    Ressourcen    │ │  • Marketing     │ │  • Mit Ihren     │
  │  • Audit &       │ │    verbessern    │ │    Daten trainieren│
  │    Recherche     │ │  • Kommunikation │ │  • Vertrauliche  │
  │    für Sie       │ │    automatisieren │ │    Daten schützen│
  │  • Developer-    │ │                  │ │                  │
  │    Produktivität │ │                  │ │                  │
  │    vervielfachen │ │                  │ │                  │
  │                  │ │                  │ │                  │
  │  [Mehr erfahren→]│ │  [Mehr erfahren→]│ │  [Mehr erfahren→]│
  └──────────────────┘ └──────────────────┘ └──────────────────┘
```

**Design notes:**
- Each card uses a problem-question headline (wirkt.ai style) rather than a dry feature list
- Hover: card background shifts slightly, arrow animates right
- On mobile: stack vertically, full width
- Accent color per section: Productivity = blue, Automation = green, Security = amber

---

### 5.4 "SCHON KI AUSPROBIERT?" — Re-engagement
**Visual:** Full-width section, dark background (matching hero), centered content.

**Layout:**
```
[Full-width dark section, padding 96px]

  Schon KI ausprobiert und gescheitert?

  Das passiert den meisten Unternehmen.
  Falsches Tool. Keine Strategie. Keine Adoption.

  Wir helfen Ihnen, das Potential zu heben —
  pragmatisch, ohne Hype, mit Ergebnissen.

  [CTA button — accent color]
  → Lassen Sie uns reden
```

**Design notes:**
- Mirrors wirkt.ai's "Warum jetzt?" urgency section
- Emotional hook — validates the reader's experience
- Single CTA, centered, high contrast

---

### 5.5 "WIE WIR KI NUTZEN" — Social Proof
**Visual:** Light background. Blog/social media teaser area.

**Layout:**
```
[Section padding: 64px]

  Wie wir KI nutzen

  Wir essen unser eigenes Hundefutter.
  Folgen Sie uns auf Social Media oder lesen Sie unseren Blog,
  um zu sehen, wie wir KI im Alltag einsetzen.

  [Social media icons row: LinkedIn, X/Twitter, etc.]
  [Blog preview — 3 latest posts as cards]
```

---

### 5.6 KI-PARTNER — Tool Logos
**Visual:** Clean logo grid, grayscale logos that color on hover.

**Layout:**
```
[Section padding: 48px, light gray background]

  Wir arbeiten mit den besten KI-Plattformen:

  [Logo row — centered, equal spacing]
  ChatGPT   Claude   Anthropic   Gemini   Deepseek   Mistral

  (6 logos, responsive: 3 per row on tablet, 2 on mobile)
```

**Design notes:**
- Logo lockup: monochrome by default, brand color on hover
- Subtle divider line above and below
- No endorsements implied — just "we work with these"

---

### 5.7 FOOTER CTA + FOOTER
**Visual:** Dark background, clean two-column layout.

**Layout:**
```
[CTA strip — accent color background]
  Bereit für den nächsten Schritt?
  [Button: Erstgespräch vereinbaren]  [Button: E-Mail schreiben]

[Footer — dark]
  AlwaysAI                     Kontakt           Rechtliches
  "Immer AI."                  kontakt@          Impressum
  alwaysai.eu                  alwaysai.eu       Datenschutz
                                                   AGB

  [Social icons: LinkedIn, X]
  © 2026 AlwaysAI. Alle Rechte vorbehalten.
```

---

## 6. Design Tokens

### Color Palette
```css
:root {
  /* Primary — deep navy (trust, professionalism) */
  --color-primary-900: #0A1628;    /* Hero/footer bg */
  --color-primary-800: #0F2341;    /* Dark section bg */
  --color-primary-700: #1A365D;    /* Card hover */
  --color-primary-600: #2B5797;    /* Links, secondary text */

  /* Accent — electric blue/teal (AI, modernity, action) */
  --color-accent-500: #00B4D8;     /* Primary buttons, highlights */
  --color-accent-400: #48CAE4;     /* Hover states */
  --color-accent-600: #0096B7;     /* Active states */

  /* Neutrals */
  --color-white: #FFFFFF;
  --color-gray-50: #F7F8FA;        /* Light section bg */
  --color-gray-100: #E8EBF0;       /* Borders, dividers */
  --color-gray-400: #9CA3AF;       /* Secondary text */
  --color-gray-600: #4B5563;       /* Body text on light */
  --color-gray-900: #111827;       /* Headings on light */

  /* Section accents */
  --color-productivity: #3B82F6;   /* Blue */
  --color-automation: #10B981;     /* Green */
  --color-security: #F59E0B;       /* Amber */

  /* Semantic */
  --color-error: #EF4444;
  --color-success: #10B981;
}
```

### Typography
```css
/* Headings: Inter (clean, modern, highly legible) */
/* Body: Inter (same family for consistency) */

--font-family: 'Inter', system-ui, -apple-system, sans-serif;

/* Type scale */
--text-xs:   12px;   /* captions, fine print */
--text-sm:   14px;   /* secondary text, labels */
--text-base: 16px;   /* body text, line-height 1.6 */
--text-lg:   20px;   /* subheadings */
--text-xl:   24px;   /* h3, card titles */
--text-2xl:  30px;   /* h2, section headers */
--text-4xl:  40px;   /* h1 on mobile */
--text-5xl:  48px;   /* h1 on desktop */
--text-hero: 56px;   /* hero headline on large screens */

/* Weights */
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
```

### Spacing Scale
```
0, 4, 8, 12, 16, 24, 32, 48, 64, 96, 128  (px)
```

### Border Radius
```
--radius-sm:  4px;   /* buttons, inputs */
--radius-md:  8px;   /* cards */
--radius-lg:  12px;  /* hero elements */
--radius-xl:  16px;  /* large containers */
```

### Shadows
```
--shadow-1: 0 1px 3px rgba(0,0,0,0.08), 0 1px 2px rgba(0,0,0,0.06);   /* cards */
--shadow-2: 0 4px 6px rgba(0,0,0,0.07), 0 2px 4px rgba(0,0,0,0.06);   /* card hover */
--shadow-3: 0 10px 15px rgba(0,0,0,0.1), 0 4px 6px rgba(0,0,0,0.05);  /* modals */
```

---

## 7. Responsive Rules

| Element | Mobile (<640px) | Tablet (640-1024px) | Desktop (>1024px) |
|---------|-----------------|---------------------|-------------------|
| Hero H1 | 32px, stacked | 40px | 48-56px |
| CTAs | Stacked, full width | Side by side | Side by side |
| 3 Schwerpunkte cards | Stacked | 2 columns | 3 columns |
| Logo grid | 2 per row | 3 per row | 6 in a row |
| Stat cards (Warum wir) | Stacked | 2 columns | 3 columns |
| Nav | Hamburger menu | Hamburger | Top bar |

---

## 8. Component Inventory

| Component | Variants | States |
|-----------|----------|--------|
| Button (primary) | Filled accent | default/hover/active/focus/disabled |
| Button (secondary) | Ghost/outline | default/hover/active/focus |
| Card (service) | With icon, bullets | default/hover |
| Card (stat) | Number + label | default |
| Logo badge | Grayscale → color | default/hover |
| Section header | H2 + optional subtitle | — |
| CTA strip | Dark bg, centered text + buttons | — |
| Footer | Multi-column links | default/hover on links |
| Language toggle | DE / EN | active/inactive |
| Scroll indicator | Animated arrow | auto-scrolling |

---

## 9. States & Edge Cases

- **Empty blog section:** "Blog kommt bald. Folgen Sie uns auf Social Media in der Zwischenzeit."
- **Loading:** Minimal — this is a marketing site, pre-render. Skeleton for blog cards if dynamically loaded.
- **Form errors:** Inline red text below field, clear German error messages.
- **Long text:** Card headlines truncate at 2 lines with ellipsis. Body text never truncates.
- **No-JS fallback:** All content visible, CTAs are links not JS actions.

---

## 10. Accessibility Notes

- Contrast: All text meets WCAG AA (4.5:1 for normal, 3:1 for large)
- Focus states: Visible 2px outline ring on all interactive elements (--color-accent-400)
- Keyboard nav: Full tab order through all CTAs and links
- Language toggle: `lang` attribute switches between `de` and `en`
- Images: All decorative images have `alt=""`, meaningful images get descriptive alt text
- Reduced motion: Particle/animation effects respect `prefers-reduced-motion`
- Mobile tap targets: Minimum 44×44px

---

## 11. Implementation Notes

**Recommended approach:**
- **Framework:** Static site (Astro, Hugo, or plain HTML/CSS) — fast, secure, no backend
- **Hosting:** Cloudflare Pages, Netlify, or Vercel (free tier works fine)
- **CMS (optional):** Decap CMS for blog posts, or just Markdown files
- **Analytics:** Plausible or Umami (privacy-friendly, no cookie banner needed)
- **Contact form:** Formspree, Netlify Forms, or link to Calendly for Erstgespräch

**Structure:**
```
/
├── index.html          (single-page, all sections)
├── /css
│   └── style.css       (tokens + styles)
├── /js
│   └── main.js         (language toggle, smooth scroll, mobile nav)
├── /images
│   ├── logos/          (partner logos)
│   └── hero-bg.svg     (optional hero background)
├── /en                 (English version)
│   └── index.html
└── /blog               (future)
```

---

## 12. Next Steps

1. **Review this design** — approve structure, messaging, visual direction
2. **Refine German copy** — translate and polish all content (I can draft German versions)
3. **Wireframe in Figma or code** — build actual HTML/CSS prototype
4. **Implement** — deploy to hosting
5. **Test** — mobile, accessibility, performance

---

## 13. Glance Test (Self-Validation)

| Question | Answer |
|----------|--------|
| What is this page? | AI consulting for Mittelstand that stays current so you don't have to |
| Who is it for? | German business owners/managers overwhelmed by AI |
| Top 3 things to do? | 1) Understand services 2) See why AlwaysAI 3) Book Erstgespräch |
| Primary action? | Book Erstgespräch (CTA repeated 3x on page) |
| Navigation? | Single page scroll + language toggle |

**Passes.** Structure is clear, hierarchy flows from emotional hook → credibility → services → CTA.
