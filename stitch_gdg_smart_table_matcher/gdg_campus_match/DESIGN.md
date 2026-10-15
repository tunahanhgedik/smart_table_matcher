---
name: GDG Campus Match
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#424753'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#727785'
  outline-variant: '#c2c6d5'
  surface-tint: '#005ac1'
  primary: '#0058bd'
  on-primary: '#ffffff'
  primary-container: '#2771df'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#006e2c'
  on-secondary: '#ffffff'
  secondary-container: '#86f898'
  on-secondary-container: '#00722f'
  tertiary: '#b51b15'
  on-tertiary: '#ffffff'
  tertiary-container: '#d9372b'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004494'
  secondary-fixed: '#89fa9b'
  secondary-fixed-dim: '#6ddd81'
  on-secondary-fixed: '#002108'
  on-secondary-fixed-variant: '#005320'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#930004'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system embodies the welcoming, inventive, and collaborative ethos of Google Developer Groups (GDG) On Campus. It bridges student curiosity with peer connection during orientation and info sessions, transforming what can feel like an intimidating networking event into an intuitive, gamified matching experience.

The design movement is **Material You / Modern Community Tech**:
- **Tactile Softness meets Precision:** Friendly, rounded surfaces paired with purposeful, expressive Google signature accents.
- **Empathetic & Inclusive Tone:** Relieving social anxiety through clear categorization (e.g., communicative traits, technical interests) without heavy academic or corporate stiffness.
- **Micro-Delight:** Lively, interactive micro-states across badges and cards that provide real-time tactile validation during live round-robin or table allocations.

## Colors

The palette embraces the iconic Google quad-color harmony, anchored by slate neutrals and airy container surfaces:
- **Primary (`#4285F4` - Google Blue):** Central brand action, navigation emphasis, primary table identifiers, and major interactive touch targets.
- **Secondary (`#34A853` - Google Green):** Validation, successful team matches, open seats, and growth/learning status tags.
- **Tertiary (`#EA4335` - Google Red):** Urgent callouts, high-energy alerts, spotlight roles, and live session updates.
- **Accent Quad (`#FBBC04` - Google Yellow):** Icebreaker achievements, featured session highlights, and creative social-style chips.
- **Neutral Core (`#1E293B` - Dark Slate):** High-legibility typography, iconography, and structured outline accents.
- **Background System (`#F8FAFC` to `#FFFFFF`):** High-clarity off-white foundational canvas paired with pure white cards to generate crisp, natural elevation without muddy grey tones.

## Typography

The type scale combines the warmth and geometric approachability of Plus Jakarta Sans for headers with the high-density legibility of Inter for system data, participant rosters, and personality badges.

- **Headlines:** Use Plus Jakarta Sans to evoke Google Sans-style community friendliness. Tighter letter-spacing on headline scales prevents optical drift on fluid mobile screens.
- **Body & Metadata:** Use Inter for high screen legibility across small chips, table numbers, and dense participant profiles.
- **Responsive Handling:** `headline-xl` and `headline-lg` automatically downgrade to their designated `-mobile` variants below 640px viewport widths to prevent badge overlapping and unwanted line-wrapping.

## Layout & Spacing

The layout utilizes a fluid, single-column priority model tailored for handheld mobile devices, scaling up to structured multi-column grids on tablets and host display dashboards:
- **Mobile Handheld (360px – 639px):** 4-column fluid layout with `margin-mobile` (16px) and `gutter-mobile` (12px). Full-bleed cards with safe touch targets of at least 48px height.
- **Tablet / Large Mobile (640px – 1023px):** 8-column layout with 24px margins, allowing side-by-side matching queues and interactive floor maps.
- **Desktop / Session Host Display (1024px+):** 12-column layout max-width capped at 1200px centered canvas, dividing viewports between live matching controls and real-time floor occupancy visualizations.
- **Vertical Rhythm:** Strict adherence to an 8px modular baseline (interpolated by `space-xs` 4px for micro-adjustments within chips and avatar rings).

## Elevation & Depth

Visual hierarchy leverages **Tonal Layers paired with Soft Ambient Diffusion**:
- **Layer 0 (Canvas):** Soft neutral tint `#F8FAFC`.
- **Layer 1 (Cards & Static Containers):** Crisp pure white `#FFFFFF` paired with an ultra-subtle border stroke (`rgba(30, 41, 59, 0.08)`) and a feathered drop shadow: `0 2px 8px rgba(30, 41, 59, 0.04)`.
- **Layer 2 (Floating Pickers, Active Tables, Focus Cards):** Elevated with a dual shadow model: `0 4px 6px -1px rgba(30, 41, 59, 0.06), 0 10px 15px -3px rgba(66, 133, 244, 0.08)`. The faint blue undertone gives interactive tables a vibrant, responsive presence.
- **Layer 3 (Modals, Match Sheets, Bottom Drawers):** Backdrop blur of `12px` over an 80% opacity veil, grounded by a high-diffusion elevation shadow: `0 20px 25px -5px rgba(30, 41, 59, 0.12)`.

## Shapes

The design uses a high-radii shape language (`roundedness: 3` / pill-shaped expressions) reflecting modern Material You mobile design:
- **Pill Elements:** Buttons, social trait chips, and badge capsules use full stadium/capsule rounding (`rounded-full`).
- **Cards & Sheet Surfaces:** Structural surfaces employ `rounded-xl` (1.5rem to 2rem) for an organic, tactile aesthetic that sits comfortably in thumb-driven mobile ergonomics.
- **Micro-Indicators:** Avatar clusters, table slot indicators, and seat availability rings use pure circles with 2px separation rings matching the background tone.

## Components

### Buttons
- **Primary:** Full stadium shape (`rounded-full`), Google Blue background (`#4285F4`), white label (`#FFFFFF`), `label-lg` typography. 48px minimum touch height with a 12px horizontal inset.
- **Secondary / Outlined:** Transparent fill with a 1.5px border in Slate (`#1E293B` at 20% opacity) or Google Blue, scaling with a subtle background wash (`rgba(66, 133, 244, 0.06)`) on tap.
- **Tonal (Quick Actions):** Pastel container fill (e.g., `#E8F0FE` for Blue, `#E6F4EA` for Green) with saturated brand text.

### Chips & Social Style Badges
- **Social Role Chips:** Pill-shaped, composed of `label-md` typography with an icon or emoji prefix:
  - *Talkative / Storyteller:* Google Yellow tonal base (`#FEF7E0`), text `#B06000`, warning amber accent dot.
  - *Active Listener:* Google Blue tonal base (`#E8F0FE`), text `#1A73E8`, soft blue accent ring.
  - *Balanced Connector:* Google Green tonal base (`#E6F4EA`), text `#137333`, emerald accent check.
- **Interactive Selectors:** Tap-to-toggle chips with a 200ms ease-out spring animation, shifting from muted white/neutral borders to full vibrant brand fills.

### Cards & Table Containers
- **Table Assignment Card:** Rounded surface (`rounded-2xl`), pure white, enclosed by subtle 1px border. Includes an absolute-positioned colored corner badge indicating Table ID (e.g., Table 04 - AI/Cloud Focus), an occupancy meter (e.g., "5/6 Seats Filled"), and an avatar row.
- **Active Participant Card:** Compact tile displaying name, tech domain badge, social style chip, and a prominent swap or check-in trigger.

### Form Inputs & Filters
- **Text Inputs:** Large rounded containers (`rounded-xl`), `#FFFFFF` surface with `#F1F5F9` background when unfocused. Transforms to a crisp 2px Google Blue outline upon focus, retaining placeholder text in `#94A3B8`.
- **Selection Controls:** Circular radio indicators and squircle checkboxes with animated scale-in Google Blue fills and white check paths.

### Live Match Progress Indicator
- Segmented linear bar at the top of the mobile viewport, alternating Google's four brand colors to reflect table balance metrics across social styles and technical domains.