# CraftVerse Design System

## Colors
- Background: `#FFF9F4`
- Text: `#382A35`
- Muted text: `#756771`
- Primary rose: `#E96F91`
- Soft pink: `#FCE4E8`
- Soft green: `#DDECE0`
- White: `#FFFFFF`

## Typography
- Font: Arial (replace with Poppins in Figma if desired)
- Desktop hero: 66px Bold
- Section headings: 38–39px Bold
- Card titles: 18–23px Bold
- Body: 16–21px Regular
- Mobile hero: 39px Bold

## Components to create in Figma
1. Primary Button — rose background, white text, 26px corner radius; horizontal Auto Layout.
2. Product Card — product image/illustration, product title, price; vertical Auto Layout.
3. Benefit Card — icon, title, description; vertical Auto Layout.
4. Optional Header Nav Item — text with padding; horizontal Auto Layout.

## Spacing
Use an 8px spacing system: 8, 16, 24, 32, 48, 64. Set page and cards to Hug/Fill appropriately.

## Design rationale
Soft rose and botanical green create a welcoming handmade identity. Rounded cards communicate warmth, while a clear hero CTA and four product previews help gift shoppers explore quickly. Mobile design stacks content and uses two-column product cards.


## Tablet and responsive updates
- Tablet design: 768px wide, two-column product grid, compact header.
- Desktop: 1440px; Mobile: 390px.
- Browser demo: `index.html` uses CSS breakpoints at 950px and 600px, flexible grids, mobile navigation, and interactive product/customization dialog.
- Figma: import each SVG and recreate frames with Auto Layout and responsive resizing. SVGs do not preserve native Figma components or prototype links.
