# Design Proposal: Monica Navascues — MonCoach for Change

## Identidad
Monica is a bilingual (Spanish/English) transformation catalyst who bridges two worlds: 20+ years of corporate HR strategy and deeply personal, human-centered coaching. She immigrated from Spain to Canada and now helps others navigate their own transformations — whether young adults finding direction, executives leading change, or organizations adapting to uncertainty. Her superpower: combining strategic corporate thinking with genuine empathy. "MonCoach" means both "Mon" (my, personal) and "Monica's Coach" — this duality IS her brand.

## Audiencia
1. **Potential coaching clients** — young adults, executives, and organizations seeking transformation coaching
2. **HR/corporate clients** — organizations needing change management and OE consulting
3. **Professional peers & referral partners** — fellow coaches, HR community (HRPA, TRIEC)
4. **LinkedIn visitors** — this is her FIRST web presence beyond LinkedIn

## Metáfora Visual
The feeling of stepping through a threshold into clarity — like emerging from fog into warm light. Her world feels like autumn transformation: things change, but beautifully. Electric blue (clarity, trust) meets emerald green (growth, renewal) on a clean, warm canvas. Professional enough for executives, warm enough for young adults seeking their path.

## Paleta (6 colores)

```typescript
colors: {
  primaryDark: "#0C4A6E",     // Deep ocean blue — authority, depth of experience
  primary: "#0284C7",         // Sky blue — trust, clarity (electric blue family)
  primaryLight: "#38BDF8",    // Bright sky — energy, openness
  accent: "#10B981",          // Emerald green — growth, transformation, her brand
  surface: "#F0FDFA",         // Mint-kissed white — fresh, growth-tinted
  surfaceLight: "#F8FAFC",    // Near-white — clean, breathable
}
```

**Justificación:** Electric blue (solicitado) para confianza/claridad → familia sky blue. Emerald green (solicitado) como accent → transformation/growth. Surface con tinte mint para unificar. Dark ocean blue para autoridad sin ser genérico navy.

## Tipografía

- **Headings:** Plus Jakarta Sans 700 — modern, warm, approachable yet professional
- **Body:** Source Sans 3 400/600 — clean readability, corporate heritage
- **Accent/Quotes:** DM Serif Display — authority for impact quotes and credentials

## Efecto Visual Único: "Transformation Pathways"
Three animated paths that visually diverge from a central point, each leading to a different coaching pillar. On scroll, each path "draws" itself with a connecting line animation, then reveals its destination card. Represents her three coaching journeys: Discover → Lead → Transform. This effect is specific to HER coaching model — can't be swapped.

## Secciones Propuestas (en orden)

### 1. Hero — "The Threshold"
```
┌─────────────────────────────────────────────────┐
│                                                 │
│   [Photo circular     ]    MONICA NAVASCUES     │
│   [with emerald       ]    ─────────────────    │
│   [gradient ring      ]    Coach | HR Leader |  │
│   [warm autumn bg     ]    Change Catalyst      │
│                                                 │
│                  "Empowering People to          │
│                   Grow Through Change"           │
│                                                 │
│           [ICF ACC] [CHRL] [Prosci] [MBA]       │
│                                                 │
│        [ Book a Discovery Call → ]              │
│                                                 │
│     ────── 20+ yrs ── 3 Countries ── ∞ ─────   │
│     Experience    Global Reach    Transformations│
└─────────────────────────────────────────────────┘
```
**Why:** Coach = personal connection. Photo front and center with credential badges for instant credibility. Stats bar builds trust. Single powerful CTA.

### 2. About — "The Story"
```
┌─────────────────────────────────────────────────┐
│                                                 │
│  "Change is constant.                           │
│   Growth is a choice."                          │
│                      — Monica Navascues         │
│                                                 │
│  ┌─────────────────────────────────────────┐    │
│  │ [Her story as narrative paragraphs]     │    │
│  │                                         │    │
│  │ From Spain to Latin America to Canada,  │    │
│  │ Monica has spent 20+ years helping      │    │
│  │ people and organizations navigate       │    │
│  │ growth and change...                    │    │
│  │                                         │    │
│  │ Her approach: empathy + strategy        │    │
│  └─────────────────────────────────────────┘    │
│                                                 │
└─────────────────────────────────────────────────┘
```
**Why:** Lead with her philosophy quote (it's powerful), then the narrative. Not a CV dump — a human story.

### 3. Transformation Pathways — "Three Journeys" ★ UNIQUE SECTION
```
┌─────────────────────────────────────────────────┐
│                                                 │
│           WHO I HELP                            │
│                                                 │
│    ┌──────────┐ ┌──────────┐ ┌──────────┐     │
│    │ 🌱       │ │ ⚡       │ │ 🔄       │     │
│    │ DISCOVER │ │ LEAD     │ │ TRANSFORM│     │
│    │          │ │          │ │          │     │
│    │ Young    │ │Executive │ │ Change   │     │
│    │ Adults & │ │&Leader-  │ │ Coaching │     │
│    │ Emerging │ │ship      │ │          │     │
│    │ Talent   │ │Coaching  │ │          │     │
│    │          │ │          │ │          │     │
│    │ [items]  │ │ [items]  │ │ [items]  │     │
│    └──────────┘ └──────────┘ └──────────┘     │
│                                                 │
│    ┌────────────────────────────────────┐       │
│    │ 💼 CONSULTING                      │       │
│    │ OE, HR & Change Management        │       │
│    │ [items in horizontal list]         │       │
│    └────────────────────────────────────┘       │
│                                                 │
└─────────────────────────────────────────────────┘
```
**Why:** NOT generic "services cards". Three journeys that reflect her coaching model. Each has a transformation verb (Discover/Lead/Transform). The consulting service is separate below as a full-width card.

### 4. Approach — "The Method"
```
┌─────────────────────────────────────────────────┐
│  (dark section — primaryDark bg)                │
│                                                 │
│           MY APPROACH                           │
│                                                 │
│  "Coaching isn't about fixing people — it's     │
│   about creating space for discovery, growth,   │
│   and confidence to move forward with           │
│   intention."                                   │
│                                                 │
│  ┌────┐  ┌────┐  ┌────┐  ┌────┐               │
│  │ 🔍 │  │ 💡 │  │ 🎯 │  │ 🚀 │               │
│  │    │  │    │  │    │  │    │               │
│  │Self│  │Build│  │Take│  │Move│               │
│  │Awa-│  │Awa-│  │Int-│  │For-│               │
│  │rene│  │rene│  │ent-│  │ward│               │
│  │ss  │  │ss  │  │ional│ │    │               │
│  │    │  │    │  │Steps│  │    │               │
│  └────┘  └────┘  └────┘  └────┘               │
│     Reflect    Discover    Act      Grow        │
│                                                 │
└─────────────────────────────────────────────────┘
```
**Why:** Dark contrast section breaks the page rhythm. Her philosophy in her own words + 4-step methodology icons (Reflect → Discover → Act → Grow). Creates visual framework unique to her approach.

### 5. Credibility — "The Journey"
```
┌─────────────────────────────────────────────────┐
│                                                 │
│           PROFESSIONAL JOURNEY                  │
│                                                 │
│  Spain ──→ Latin America ──→ Canada             │
│  🇪🇸           🌎              🇨🇦               │
│                                                 │
│  ┌──────────────────────────────────────┐       │
│  │ Avanade (Accenture/Microsoft)       │       │
│  │ Group Manager, Business HR          │       │
│  ├──────────────────────────────────────┤       │
│  │ Wrigley Canada (Mars)               │       │
│  │ Sr. Training & Development          │       │
│  ├──────────────────────────────────────┤       │
│  │ Global HR Leadership                │       │
│  │ Multiple Latin American countries   │       │
│  └──────────────────────────────────────┘       │
│                                                 │
│  Volunteer: TRIEC • HRPA                        │
│  Helping newcomers to Canada succeed            │
│                                                 │
└─────────────────────────────────────────────────┘
```
**Why:** Not a generic timeline. A geographic journey that tells her immigration story + career arc. Volunteer work included because it's core to her identity.

### 6. Testimonial
```
┌─────────────────────────────────────────────────┐
│  (surface bg)                                   │
│                                                 │
│          ❝                                      │
│  "Monica possesses a profound understanding     │
│   of both organizational dynamics and           │
│   individual motivations..."                    │
│                                                 │
│                  — LinkedIn Colleague            │
│                                                 │
└─────────────────────────────────────────────────┘
```

### 7. CTA — "Let's Connect"
```
┌─────────────────────────────────────────────────┐
│  (accent/emerald bg)                            │
│                                                 │
│    Let's Start the Conversation                 │
│                                                 │
│    Whether you're exploring what's next,        │
│    leading through change, or seeking           │
│    guidance — I'd love to hear from you.        │
│                                                 │
│    [ Book a Discovery Call → ]                  │
│    [ Email Me ]                                 │
│                                                 │
└─────────────────────────────────────────────────┘
```

### 8. Footer — Contact + Social

## Secciones que NO incluir
- **Skills pills** — she's a coach, not a developer. Credentials are in the hero.
- **Projects section** — she doesn't have "projects" in the traditional sense
- **Education standalone** — credentials fold into hero badges + about section
- **Generic experience timeline with dots** — replaced by geographic journey

## Mobile Layout Notes
- Hero: photo stacks above text, CTA full-width
- Transformation Pathways: cards stack vertically
- Approach: 4 icons in 2x2 grid
- Journey: geographic path becomes vertical flow
- All touch targets 44px+, no horizontal scroll
