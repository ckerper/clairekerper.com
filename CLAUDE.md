# Claire Kerper Portfolio Website

This is the portfolio website for Claire Kerper, an artist specializing in custom hand-drawn pet portraits in colored charcoal.

## Brand Vibe

- **Elegant and artistic** - sophisticated without being pretentious
- **Warm and personal** - approachable and trustworthy
- **Professional yet creative** - balancing business needs with artistic sensibility
- **Timeless and classic** - emphasizes the enduring quality of the work

## Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Blue | `#1F466D` | Header, footer, primary headings, nav background |
| Secondary Olive | `#77806D` | Buttons, portfolio titles, taglines, active nav states |
| Accent Sage | `#BCC6B1` | Process badges, decorative elements, borders |
| Forest Green | `#434A39` | Button hover states, process card headings |
| Dark Text | `#333333` | Body text, default text color |
| Light Gray | `#EBE8E5` | Process boxes, portfolio page background |
| Lighter Gray | `#F1F0ED` | Secondary backgrounds |
| Lightest Gray | `#F8F7F6` | Body background |
| White | `#FFFFFF` | Card backgrounds, text on dark backgrounds |
| Border Gray | `#DDDDDD` | Card borders, dividers |

## Typography

### Dancing Script (Cursive)
- **Usage:** h1 page titles, site title in header
- **Weight:** 600
- **Style:** lowercase
- **Character:** Elegant, handwritten script for artistic branding

### Josefin Sans (Sans-Serif)
- **Usage:** h2, h3, h4 headings, section headers
- **Weights:** 300-500
- **Character:** Modern, clean, geometric for clear hierarchy

### Crimson Pro (Serif)
- **Usage:** Body text, paragraphs, testimonials
- **Weights:** 300-600 (regular and italic)
- **Size:** 1.4rem base
- **Line Height:** 1.6
- **Character:** Classic, elegant serif for readability

## Design Patterns

### Spacing
- Max content width: 1100px (1400px outer container)
- Base unit: 1rem
- Common padding: 1rem, 1.5rem, 2rem, 3rem

### Border Radius
- Standard (buttons, images): 4px
- Cards: 6-8px
- Circular badges: 50%

### Shadows
- Subtle: `0 2px 8px rgba(0,0,0,0.08)`
- Dropdown: `0 8px 16px rgba(0,0,0,0.2)`
- Hover enhanced: `0 4px 12px rgba(0,0,0,0.08)`

### Transitions
- Standard: `0.3s ease` for all interactive elements

### Interactive States
- Button hover: Forest green (`#434A39`) + `translateY(-2px)` lift
- Card hover: `translateY(-3px)` + enhanced shadow (only for clickable cards)
- Link hover: Remove underline, slight opacity change

**Important:** Only interactive/clickable elements should have hover animations (lift effects, enhanced shadows). Static content like testimonials, process boxes, or informational cards should not lift on hover—if clicking it doesn't do anything, it shouldn't animate.

## Component Styles

### Buttons
- Background: Secondary olive (`#77806D`)
- Text: White
- Padding: 1rem 2rem
- Hover: Forest green with lift effect
- Outline variant: Transparent with 2px border

### Cards
- Background: White
- Border: 1px solid `#DDDDDD`
- Border-radius: 6-8px
- Subtle shadow with hover lift

### Process Boxes
- Background: Light gray (`#EBE8E5`)
- Left border: 4px solid accent sage (`#BCC6B1`)
- Headings: Forest green (`#434A39`)

### Testimonials
- White background
- Left border: 4px solid secondary olive (`#77806D`)
- Border-radius: 8px

## Responsive Breakpoints

### Tablet (max-width: 768px)
- **Body:** Line height reduced to 1.4
- **h1:** 3.1rem → 2.5rem
- **h2:** 2.5rem → 2rem
- **Site title:** 2.25rem → 1.75rem
- **Nav links:** Font 1.1rem, padding 0.5rem 0.75rem, gap 0.25rem
- **Portfolio grid:** Single column
- **Homepage hero h1:** 4rem → 3rem
- **Hero description:** 1.2rem
- **Main links grid:** Single column, max-width 280px
- **Featured grid:** Stacks vertically
- **Process overview:** Single column

### Mobile (max-width: 480px)
- **Body:** Line height reduced to 1.35
- **Container:** Padding 1rem 0.5rem
- **h1:** 2.5rem → 2rem
- **Nav links:** Font 1rem, padding 0.4rem 0.6rem
- **Footer:** Font 1rem
- **Pricing table:** Font 1.1rem, reduced cell padding
- **Homepage hero h1:** 3rem → 2.5rem
- **Hero CTA buttons:** Stack vertically, full width

### Short Screens (max-height: 500px)
- **Site title:** Hidden
- **Header:** Reduced padding (0.5rem)

## File Structure

- `/css/styles.css` - Main stylesheet with CSS custom properties
- `/index.html` - Homepage
- `/portfolio.html` - Portfolio gallery
- `/process.html` - Commission process info
- `/about.html` - About page
- `/testimonials.html` - Client testimonials
- `/faq.html` - FAQ page
