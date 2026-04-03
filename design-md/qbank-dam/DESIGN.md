# Design System: QBank DAM

## 1. Visual Theme & Atmosphere

QBank DAM's website embodies the restrained confidence of Nordic SaaS design -- a system that communicates enterprise-grade capability through visual simplicity rather than ornament. The page opens on a pure white canvas (`#ffffff`) with deep indigo body text (`#01005f`) and a signature sky blue (`#1DABE2`) that functions as the primary brand anchor. This isn't the oversaturated blue of American tech; it's a crisp, clear Scandinavian blue that reads as trustworthy and modern without demanding attention.

The Outfit variable font is the typographic backbone -- a geometric sans-serif that runs from weight 100 to 900, giving the system extraordinary range from whisper-light captions to bold, authoritative headlines at weight 700-800. At display sizes (47px), headlines sit at weight 800 with a tight line-height of 1.0, creating dense, impactful text blocks. The body text at 22.5px (1.25rem) with weight 400 and a generous 1.6 line-height creates comfortable, Scandinavian-style reading rhythm.

What defines QBank's visual language is its deliberate flatness. There are no decorative drop shadows, no blue-tinted depth layers, no parallax illusions. Elevation is communicated through color contrast and spacing rather than shadows. Cards use generous border-radius (up to 2rem) and color-filled backgrounds from a warm, Nordic-inspired palette -- cream (`#F2F0ED`), light blue (`#F2FBFF`), soft purple (`#E4E4F9`), and pale green (`#DCFBEC`). The result is a design that feels open, breathable, and unhurried.

**Key Characteristics:**
- Outfit variable font (100-900) as the sole typeface -- geometric, clean, Nordic
- Weight 700-800 for headlines, 400 for body -- conventional hierarchy done with precision
- Deep indigo (`#01005f`) body text instead of black or gray -- a distinctive, branded reading color
- Sky blue (`#1DABE2`) as brand anchor, electric blue (`#3c61ef`) as CTA -- two blues with distinct roles
- Pill-shaped buttons (35px radius) -- the signature interactive element
- Flat design philosophy: no decorative shadows, elevation through color and spacing
- Warm Nordic surface palette: cream, light blue, soft purple, pale green
- Dark navy (`#023E58`) as the brand's "black" -- never true black

## 2. Color Palette & Roles

### Primary
- **Sky Blue** (`#1DABE2`): Primary brand color, logo accent, interactive highlights. A crisp, clear blue that anchors the identity.
- **Dark Navy** (`#023E58`): Brand black. Headers in dark sections, footer background, secondary buttons. Not true black -- a warm, deep navy.
- **Deep Indigo** (`#01005f`): Body text color. A rich, near-navy indigo that adds warmth and distinctiveness to reading text.
- **Pure White** (`#ffffff`): Page background, card surfaces, button text on dark backgrounds.

### CTA & Action
- **Electric Blue** (`#3c61ef`): Primary CTA button background. A brighter, more saturated blue than the brand blue -- designed to draw the eye.
- **Dark Blue** (`#1980AA`): Darker brand blue for hover states and secondary emphasis.
- **Drive Blue** (`#2A66FF`): Vivid action blue for high-emphasis links and special CTAs.
- **Deep Lead** (`#030067`): Deep indigo-black for maximum contrast text on light surfaces.

### Accent Colors
- **Purple** (`#737FEC`): Secondary accent for features, badges, decorative elements.
- **Dark Purple** (`#4A5BA5`): Muted purple for hover states and secondary purple elements.
- **Green** (`#299778`): Success states, positive actions, secondary CTAs ("Book a Demo").
- **Yellow/Amber** (`#F9AF49`): Warning states, highlight accents.
- **Orange Push** (`#E8560D`): Urgent accents, attention-grabbing elements.

### Surface & Tint Palette
- **White Blue** (`#F2FBFF`): Very light blue tint for alternating sections and subtle emphasis.
- **Warm Base** (`#F2F0ED`): Nordic cream for warm surface backgrounds and content blocks.
- **Light Purple** (`#B9BEF6`): Soft purple surface for feature cards and badges.
- **Lightest Purple** (`#E4E4F9`): Barely-there purple for subtle tinted sections.
- **Light Green** (`#DCFBEC`): Soft green for success surfaces and positive-context cards.
- **Light Yellow** (`#FFF4E7`): Warm yellow tint for highlight and warning surfaces.
- **Light Blue** (`#BFDCF6`): Soft blue for informational surfaces.
- **Pulse Pink** (`#FEE2EC`): Light pink for decorative and marketing surfaces.
- **Focus Blue** (`#C3D9FF`): Soft blue for focus-related and attention surfaces.

### Neutral Scale
- **Gray 100** (`#f8f9fa`): Lightest background.
- **Gray 200** (`#e9ecef`): Disabled backgrounds, soft dividers.
- **Gray 300** (`#dee2e6`): Default borders.
- **Gray 400** (`#ced4da`): Form borders, input outlines.
- **Gray 500** (`#adb5bd`): Placeholder text.
- **Gray 600** (`#6c757d`): Secondary text, captions, muted labels.
- **Gray 700** (`#495057`): Strong secondary text.
- **Gray 800** (`#343a40`): Dark secondary.
- **Gray 900** (`#212529`): Near-black.
- **Light** (`#F1F2F4`): Light section background.
- **Dark** (`#25292A`): Dark UI elements, near-black.
- **Gray** (`#5a585a`): Mid-tone gray for tertiary text.

### Shadow Colors
- **Focus Primary** (`rgba(13,110,253,0.25)`): Standard focus ring.
- **Focus Navy** (`rgba(2,62,88,0.5)`): Navy-themed focus ring.
- **Focus Purple** (`rgba(115,127,236,0.5)`): Purple-themed focus ring.
- **Focus Green** (`rgba(187,213,201,0.5)`): Green-themed focus ring.

## 3. Typography Rules

### Font Family
- **Primary**: `Outfit`, with fallback: `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`
- **Monospace**: `SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace`
- **Variable weight**: 100-900 range via Google Fonts

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display Hero | Outfit | 47.25px (2.625rem) | 800 | 1.0 | normal | Maximum impact, fluid responsive scaling |
| Section Heading | Outfit | 40.5px (2.25rem) | 700 | 1.0 | normal | Feature section titles |
| Sub-heading Large | Outfit | 28.8px (1.6rem) | 700 | 1.2 | normal | Card headings, sub-sections |
| Sub-heading | Outfit | 25.2px (1.4rem) | 700 | 1.2 | normal | Smaller section heads |
| Sub-heading Small | Outfit | 22.5px (1.25rem) | 700 | 1.2 | normal | Tertiary headings |
| Body Label | Outfit | 19.8px (1.1rem) | 700 | 1.2 | normal | Form labels, strong captions |
| Body Large | Outfit | 22.5px (1.25rem) | 400 | 1.6 | normal | Default reading text, descriptions |
| Body | Outfit | 18px (1rem) | 400 | 1.6 | normal | Secondary reading text |
| Button | Outfit | 20.7px (1.15rem) | 700 | 1.5 | normal | Button labels |
| Form Input | Outfit | 19.8px (1.1rem) | 400 | 1.5 | normal | Form field text |
| Small | Outfit | 15.75px (0.875em) | 400 | 1.5 | normal | Captions, fine print |
| Code | Monospace | 15.75px (0.875em) | 400 | 1.5 | normal | Code snippets, technical labels |

### Principles
- **Single font, maximum range**: Outfit at variable 100-900 means the entire typographic system uses one family. No font-loading complexity, no pairing decisions.
- **Bold headlines, regular body**: Unlike systems that use light-weight headlines for luxury, QBank uses 700-800 for authority and 400 for comfortable reading. This is enterprise SaaS typography -- clear, direct, functional.
- **Generous body size**: 22.5px default body text is notably large for SaaS, reflecting a Scandinavian commitment to readability and accessibility.
- **Tight headline rhythm**: Line-height 1.0 on display sizes creates dense, impactful headline blocks. Body opens to 1.6 for reading comfort.
- **Deep indigo reading color**: `#01005f` body text is more distinctive than gray or black, adding a branded quality to every paragraph.

## 4. Component Stylings

### Buttons

**Primary CTA**
- Background: `#3c61ef`
- Text: `#ffffff`
- Padding: 1.5rem 2.0rem
- Radius: 35px (pill)
- Font: 1.15rem Outfit weight 700
- Border: none
- Hover: darker shade, standard transition
- Use: Primary CTA ("Book a Demo", "Get Started")

**Secondary / Navy**
- Background: `#023E58`
- Text: `#ffffff`
- Padding: 1.5rem 2.0rem
- Radius: 35px (pill)
- Font: 1.15rem Outfit weight 700
- Use: Secondary actions, navigation CTA

**Green CTA**
- Background: `#299778`
- Text: `#ffffff`
- Padding: 1.5rem 2.0rem
- Radius: 35px (pill)
- Font: 1.15rem Outfit weight 700
- Use: Positive actions ("Book a Demo" alternate)

**Light / Surface**
- Background: `#F2F0ED`
- Text: `#030067`
- Padding: 1.5rem 2.0rem
- Radius: 35px (pill)
- Font: 1.15rem Outfit weight 700
- Use: Tertiary actions on dark backgrounds

**Ghost / Outlined**
- Background: transparent
- Text: `#023E58`
- Padding: 1.5rem 2.0rem
- Radius: 35px (pill)
- Border: 1px solid `#023E58`
- Font: 1.15rem Outfit weight 700
- Use: Secondary on white backgrounds

### Cards & Containers
- Background: `#ffffff` or tinted surface colors (`#F2FBFF`, `#F2F0ED`, `#E4E4F9`)
- Border: none (cards use background color for separation) or `1px solid #dee2e6`
- Radius: 0.5rem (compact), 1rem (standard), 1.5rem (comfortable), 2rem (featured)
- Shadow: none (flat design -- elevation through color contrast)
- Hover: subtle background shift or border change

### Badges / Tags
**Feature Badge**
- Background: tinted surface (`#E4E4F9`, `#DCFBEC`, `#F2FBFF`)
- Text: corresponding dark variant (`#4A5BA5`, `#299778`, `#1980AA`)
- Padding: 0.25rem 0.75rem
- Radius: 1.25rem (pill)
- Font: 0.875rem weight 700

### Inputs & Forms
- Border: `1px solid #ced4da`
- Radius: 0.25rem
- Padding: 0.5rem 1rem
- Focus border: `#86b7fe`
- Focus shadow: `0 0 0 0.25rem rgba(13,110,253,0.25)`
- Label: `#030067`, 1.1rem Outfit weight 700
- Text: `#030067`
- Placeholder: `#6c757d`
- Disabled: `#e9ecef` background

### Navigation
- Clean horizontal nav on white, sticky
- Brand logo left-aligned
- Links: Outfit weight 400, `#023E58` text
- CTA: pill button right-aligned ("Book a Demo")
- Mobile: hamburger toggle

## 5. Layout Principles

### Spacing System
- Base unit: 0.5rem (8px)
- Scale: 0, 0.5rem, 1rem, 1.5rem, 2rem, 2.5rem, 3rem, 3.5rem, 4rem, 4.5rem, 5rem, 5.5rem, 6rem, 7.5rem, 10rem, 12.5rem
- Extended scale goes up to 12.5rem (200px) for generous Nordic-style section spacing

### Grid & Container
- Max content widths: 720px (sm), 960px (md), 1240px (lg), 1560px (xl)
- Bootstrap 5 grid with custom gutter scale
- Hero: centered single-column with generous padding
- Feature sections: alternating text/image blocks, 2-3 column grids for feature cards
- Full-width colored sections using surface tints for visual rhythm

### Whitespace Philosophy
- **Scandinavian generosity**: QBank uses notably generous spacing -- 10rem (160px) and 12.5rem (200px) section padding is common. The design breathes.
- **Color as separation**: Rather than borders or shadows, sections are separated by background color changes (white -> cream -> light blue -> white).
- **Content-led density**: Text content areas use comfortable line-height (1.6) and body sizes (22.5px), while UI chrome remains compact.

### Border Radius Scale
- Tight (0.25rem / 4px): Form inputs, small elements
- Compact (0.5rem / 8px): Small cards, inline elements
- Standard (1rem / 16px): Medium containers
- Comfortable (1.5rem / 24px): Feature cards
- Large (2rem / 32px): Hero cards, featured containers
- Pill (35px): Buttons -- the signature shape
- Circle (50%): Avatars, icons

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat (Level 0) | No shadow, white bg | Default page surface |
| Tinted (Level 1) | No shadow, tinted bg (`#F2FBFF`, `#F2F0ED`, `#E4E4F9`) | Section differentiation, card backgrounds |
| Bordered (Level 2) | `1px solid #dee2e6`, no shadow | Explicit container boundaries, form groups |
| Focus (Level 3) | `0 0 0 0.25rem rgba(13,110,253,0.25)` | Keyboard focus, active input states |
| Navy Focus | `0 0 0 0.25rem rgba(2,62,88,0.5)` | Focus on navy-themed elements |
| Purple Focus | `0 0 0 0.25rem rgba(115,127,236,0.5)` | Focus on purple-themed elements |

**Elevation Philosophy**: QBank's design system is deliberately flat. There are no decorative shadows, no ambient elevation layers, no depth illusions. This is a conscious design choice rooted in the Nordic tradition of functional minimalism. Hierarchy is communicated through three mechanisms: color contrast (dark text on light surfaces), surface tinting (cream, blue, purple, green backgrounds), and generous spacing. This flatness gives the design a clean, printed-page quality that feels premium without the visual noise of shadow systems.

## 7. Do's and Don'ts

### Do
- Use Outfit as the only typeface -- never introduce a second font family
- Use `#01005f` (deep indigo) for body text -- this branded reading color is intentional
- Keep buttons pill-shaped with 35px radius -- it's the signature interactive element
- Use tinted surface colors (`#F2FBFF`, `#F2F0ED`, `#E4E4F9`, `#DCFBEC`) for section variety
- Keep the design flat -- use color and spacing for hierarchy, not shadows
- Use `#3c61ef` for primary CTAs and `#023E58` for secondary actions
- Maintain generous section spacing (5rem+) -- the Nordic breathing room is essential
- Use weight 700-800 for headlines and weight 400 for body -- the contrast is deliberate

### Don't
- Don't add decorative box-shadows to cards or containers -- QBank is flat by design
- Don't use true black (`#000000`) for text -- always use `#01005f` (body) or `#023E58` (headings in dark mode)
- Don't use square or small-radius buttons -- the 35px pill shape is non-negotiable
- Don't reduce body text below 18px -- the generous sizing is a readability commitment
- Don't use light font weights (100-300) for headlines -- QBank is bold and direct, not whisper-light
- Don't introduce warm accent colors (red, orange) for primary CTAs -- blue is the action color
- Don't use tight line-height for body text -- 1.6 is the reading rhythm
- Don't add gradients to backgrounds -- QBank uses solid, flat surface colors

## 8. Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile | <576px | Single column, fluid type scaling, stacked cards |
| Small Tablet | 576-767px | Slight layout adjustments, 720px container |
| Tablet | 768-991px | 2-column layouts begin, 960px container |
| Desktop | 992-1279px | Full feature grids, 1240px container |
| Large Desktop | 1280-1599px | Generous margins, full typography scale |
| Extra Large | 1600px+ | 1560px container, maximum whitespace |

### Touch Targets
- Buttons use generous padding (1.5rem 2.0rem) for comfortable touch targets
- Navigation links spaced for mobile tap accuracy
- Form inputs at 1.1rem font size with adequate padding
- Pill buttons naturally create tall touch targets due to padding + radius

### Collapsing Strategy
- Hero: 47.25px display -> `calc(1.3875rem + 1.65vw)` fluid scaling on mobile
- Section headings: 40.5px -> `calc(1.35rem + 1.2vw)` fluid scaling
- Navigation: horizontal + CTA -> hamburger toggle
- Feature cards: multi-column -> single column stacked
- Section spacing compresses but maintains generous rhythm
- Container widths step down: 1560px -> 1240px -> 960px -> 720px -> fluid

### Image Behavior
- Product screenshots and UI mockups maintain aspect ratio
- Full-width sections maintain edge-to-edge color fills
- Icon grids reflow from multi-column to 2-column to single
- Integration logos grid adapts to available width

## 9. Agent Prompt Guide

### Quick Color Reference
- Primary CTA: Electric Blue (`#3c61ef`)
- Brand blue: Sky Blue (`#1DABE2`)
- Brand navy: Dark Navy (`#023E58`)
- Background: White (`#ffffff`)
- Body text: Deep Indigo (`#01005f`)
- Secondary text: Gray 600 (`#6c757d`)
- Heading on dark: White (`#ffffff`)
- Border: Gray 400 (`#ced4da`)
- Surface cream: Warm Base (`#F2F0ED`)
- Surface blue: White Blue (`#F2FBFF`)
- Surface purple: Lightest Purple (`#E4E4F9`)
- Surface green: Light Green (`#DCFBEC`)
- Success: Green (`#299778`)
- Accent: Purple (`#737FEC`)

### Example Component Prompts
- "Create a hero section on white background. Headline at 2.625rem Outfit weight 800, line-height 1.0, color #01005f. Subtitle at 1.25rem weight 400, line-height 1.6, color #6c757d. Primary CTA pill button (#3c61ef, 35px radius, 1.5rem 2.0rem padding, white text, weight 700) and ghost button (transparent, 1px solid #023E58, #023E58 text, 35px radius)."
- "Design a feature card: #F2FBFF background, no shadow, 1.5rem radius. Title at 1.4rem Outfit weight 700, color #01005f. Body at 1.25rem weight 400, color #6c757d. Purple badge (#E4E4F9 bg, #4A5BA5 text, 1.25rem radius pill)."
- "Build a dark section: #023E58 background, white text. Headline 2.25rem Outfit weight 700, line-height 1.0. Body 1.25rem weight 400, rgba(255,255,255,0.8). CTA pill button on light surface (#F2F0ED bg, #030067 text, 35px radius)."
- "Create navigation: white sticky header. Outfit weight 400 for links, #023E58 text. Green CTA 'Book a Demo' right-aligned (#299778 bg, white text, 35px pill radius, 1.15rem weight 700). Brand logo left."
- "Design a pricing card: white background, 1px solid #dee2e6 border, 2rem radius. Plan name 1.6rem weight 700, #01005f. Price 2.625rem weight 800, #3c61ef. Feature list 1rem weight 400, #6c757d. CTA pill button full-width."

### Iteration Guide
1. Outfit is the only font -- variable weight 100-900, no companion typeface needed
2. Headlines at 700-800, body at 400 -- never invert this hierarchy
3. Body text color is `#01005f` (deep indigo), not black or gray -- this is the brand's reading identity
4. All buttons are pill-shaped (35px radius) -- no square or slightly-rounded buttons
5. No decorative shadows -- elevation is communicated through surface color and spacing
6. Surface tints rotate between `#F2FBFF` (blue), `#F2F0ED` (cream), `#E4E4F9` (purple), `#DCFBEC` (green)
7. Primary CTA is `#3c61ef`, brand blue is `#1DABE2`, brand navy is `#023E58` -- three distinct blues with distinct roles
8. Section spacing is generous (5rem+) -- resist the urge to tighten; the breathing room is the Nordic signature
