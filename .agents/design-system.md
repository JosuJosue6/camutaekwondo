# Design System

## Colors

- Background: `#101110`
- Soft background: `#171918`
- Panel: `#1d201e`
- Warm text: `#f2f1ec`
- Muted text: `#a3a6a1`
- Accent lime: `#d9fa49`

## Typography

- Display: Barlow Condensed, weights 500–900.
- Body: DM Sans, weights 400–700.
- Main display headings: fluid `clamp()` sizing; compact uppercase editorial treatment.

## Spacing and shape

- Page gutter: `clamp(22px, 6.1vw, 96px)`, reduced to 22px on mobile.
- Section spacing: `clamp(88px, 11vw, 156px)`, reduced to 92px on mobile.
- Cards are square cornered with fine low contrast borders; buttons are square cornered.

## Buttons

Lime fill, dark text, uppercase compact label, arrow detail. Hover changes to outlined transparent treatment. Light variant is used over the training image.

## Breakpoints

- Mobile: `max-width: 700px`
- Narrow mobile: `max-width: 380px`
- Tablet / compact desktop: `max-width: 900px`
- Desktop: above 900px

## Motion

Reveal transitions use opacity and vertical movement. Image hover is a gentle zoom. All motion is reduced under `prefers-reduced-motion`.
