# EXEL — VISUAL TOKENS

Status: ACTIVE WORKING CANON
Purpose: implementation tokens for website, presentations, social, reports, dashboards and visual production

## Color tokens

```yaml
color:
  midnight_navy: "#0A1E3F"
  deep_blue: "#123A78"
  action_blue: "#0B74FF"
  intelligence_blue: "#4D8DF7"
  white: "#FFFFFF"
  architectural_mist: "#F4F6F9"
  platinum_line: "#D7DEE8"
  graphite: "#1F2937"
  slate: "#6B7280"
  soft_champagne: "#D8C9B8"
```

## Usage ratio

```yaml
ratio:
  navy: 28
  white: 32
  mist: 20
  graphite: 10
  blues: 8
  champagne: 2
```

Higher-level: 70% calm / 20% authority / 10% action-information.

## Typography tokens

```yaml
typography:
  primary_family: "Heebo"
  headline_weight: "700-800"
  subhead_weight: "500-700"
  body_weight: "400-500"
  data_weight: "500-600"
  rtl: true
```

Website scale:

- Hero desktop: 56–72px
- Hero mobile: 38–48px
- H2: 38–48px
- H3: 24–30px
- Body: 17–19px
- Body Large: 20–22px
- Label: 13–15px
- KPI: 40–64px

Presentation principle:

Headlines are conclusion-first and visibly dominant. Text density is intentionally low.

## Grid tokens

```yaml
grid:
  desktop_container_min: 1200
  desktop_container_max: 1320
  columns: 12
  section_spacing_desktop_min: 96
  section_spacing_desktop_max: 140
  section_spacing_mobile_min: 64
  section_spacing_mobile_max: 88
```

## Component tokens

```yaml
component:
  card_radius_min: 20
  card_radius_max: 28
  border_width: 1
  border_color: "#D7DEE8"
  shadow: "very-subtle"
  icon_style: "line"
  icon_stroke_min: 1.5
  icon_stroke_max: 2.0
```

## State colors

Action Blue is reserved for primary CTA and active states.
Intelligence Blue is for KPI, secondary data, hover and analytical emphasis.
Soft Champagne is for founder, trust and quote accents only.

Do not create traffic-light investment scoring by default.
Do not use aggressive red/green to imply investment approval.

## Visual anchor rule

Every screen / slide must have one dominant anchor:

- person
- project
- number
- process
- map
- CTA

## Image rules

- real assets first
- real founder photography
- no AI face/body for founder
- no generic stock real-estate imagery when project assets exist
- every image must explain something about the opportunity, market, transaction or people

## X symbol rules

X is a secondary brand primitive.
Allowed: favicon, app icon, watermark, pattern, social avatar, methodological cue.
Forbidden: repeated decorative X on every card or treating X as the master narrative without explicit approval.

## Signature component family

- Evidence Card
- Risk Card
- Scenario Card
- Money Map
- Payment Timeline
- Deal Flow
- Investor Path Timeline
- Open Questions Panel
- Market Map
- Unit Plan
- Verification State
- Smart Buy / Deal Architecture Route

## Forbidden visual language

- shiny gold
- neon
- metallic effects
- strong gradients
- full black as main brand background
- cold SaaS dashboard look
- generic bank look
- generic Canva real-estate template
- excessive icons
- heavy shadows
- decorative complexity without decision value
