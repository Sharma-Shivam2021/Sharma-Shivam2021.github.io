# /\*

1.  # TYPOGRAPHY

Font Sizes (px → rem @ 62.5% root):

- Small Text: 12 / 14
- Base: 16
- Body / Paragraphs: 18
- Subheading: 20
- Headings: h1 → 52 / 62 / 74 / 86 / 98 h2 → 44 / 52 h3 → 30 / 36 h4 → 24
- Scale follows modular increments

Font Weights:

- Default: 400
- Medium: 500
- Semi-bold: 600
- Bold: 700

Line Heights:

- Base: 1
- Paragraph: 1.6
- Headings: 1.05 (tight), 1.2 (looser)

Typeface:

- Primary: "Rubik", sans-serif
- Fallback: system fonts

---

2.  # COLORS

Primary Brand:

- Orange: #e67e22

Tints:

- #fdf2e9
- #fae5d3

Shades:

- #cf711f (dark orange)

Accents:

- Green: #51cf66 (success)
- Red: #ff0000 (error/attention)

Greys:

- #555 (default body text)
- #333 (dark headings)
- #6f6f6f (secondary text)
- #ddd (borders)
- #888 (muted text)

Utility:

- White: #fff
- Black: #000

---

3.  # SHADOWS

- Card Shadow: 0 2.4rem 4.8rem rgba(0, 0, 0, 0.075)
- CTA Shadow: 0 2.4rem 4.8rem rgba(0, 0, 0, 0.15)
- Hover/Focus: 0 1rem 2rem rgba(0, 0, 0, 0.15)

---

4.  # BORDER RADIUS

- Small Elements (icons): 9px
- Buttons: 11px
- Images / Cards: 12px
- Pill Buttons: 100px
- Circle Containers: 50%

---

5.  # SPACING SYSTEM

Scale (px → rem): 2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

Section Padding:

- Standard section: 9.6rem top & bottom
- Hero section: 4.8rem / 9.6rem
- CTA section: extra-large (4.8rem 6.4rem)

Gaps:

- Small grids: 1.6rem
- Default grids: 3.2rem
- Large grids: 4.8rem
- XL grids: 6.4rem

---

6.  # LAYOUT UTILITIES

Containers:

- Max width: 120rem (1200px)
- Centered with auto margins
- Horizontal padding: 3.2rem

Grids:

- 2-col / 3-col / 4-col / 5-col options
- Column gap: responsive (3.2rem / 4.8rem / 6.4rem)
- Supports vertical alignment

Utility Classes:

- `.margin-right-sm` → 1.6rem
- `.margin-bottom-md` → 4.8rem
- `.center-text` → text-align: center
- `.strong` → bold highlight

---

7.  # COMPONENTS

🔹 Header

- Flex container: space-between, padding 0 4.8rem
- Logo fixed height: 2.2rem

🔹 Navigation

- Horizontal list with 4.8rem gap
- Links styled with hover/focus transitions
- CTA link (button style with pill radius)

🔹 Hero Section

- Grid layout (2 cols, 1fr 1fr)
- Hero image: responsive, box-shadow
- Delivered meals flex box (avatars + text)

🔹 How It Works

- Numbered steps with large faint numbers
- Step images in circular gradient backgrounds

🔹 Meals

- Meal card with hover transform + shadow
- Tags: pill-style, green/red/blue variations
- Attributes list with icons

🔹 Pricing

- Two plans: starter (outlined), complete (filled background)
- Plan cards: rounded, padding, shadow
- Features list with check icons

🔹 CTA (Call To Action)

- Split layout: text + image
- Form inputs styled with custom focus states
- CTA button inherits global `.btn`

🔹 Featured Section

- Logo strip: grayscale filter, reduced opacity

🔹 Features

- Icon container: 6.4rem, colored background
- Title + description text stack

🔹 Testimonials

- 2-col grid of customer quotes
- Avatar + name below each text
- Dark-on-light scheme

🔹 Gallery

- Responsive auto-fit grid (min 30rem)
- Images with hover scale & shadow

🔹 Footer

- 5-col grid
- Social links, nav links
- Copyright with small text

---

8.  # ACCESSIBILITY & INTERACTIONS

- Focus outline: always visible (color #e67e22, offset 8px)
- Buttons: hover + active states with transform
- Links: smooth color transitions
- Images: responsive, rounded corners for friendliness
- Typography: high contrast against backgrounds
- Forms: custom focus with background tint \*/
