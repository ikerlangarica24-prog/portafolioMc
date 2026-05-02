---
name: Overworld Professional
colors:
  surface: '#121412'
  surface-dim: '#121412'
  surface-bright: '#383a38'
  surface-container-lowest: '#0d0f0d'
  surface-container-low: '#1a1c1a'
  surface-container: '#1e201e'
  surface-container-high: '#292a29'
  surface-container-highest: '#333533'
  on-surface: '#e3e3df'
  on-surface-variant: '#c2c8c1'
  inverse-surface: '#e3e3df'
  inverse-on-surface: '#2f312f'
  outline: '#8c928c'
  outline-variant: '#424843'
  surface-tint: '#accfb8'
  primary: '#accfb8'
  on-primary: '#173627'
  primary-container: '#2d4c3b'
  on-primary-container: '#99bca6'
  inverse-primary: '#466553'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#f0b9bb'
  on-tertiary: '#492628'
  tertiary-container: '#623b3d'
  on-tertiary-container: '#dba6a8'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c7ebd4'
  primary-fixed-dim: '#accfb8'
  on-primary-fixed: '#012113'
  on-primary-fixed-variant: '#2e4d3c'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffdada'
  tertiary-fixed-dim: '#f0b9bb'
  on-tertiary-fixed: '#311214'
  on-tertiary-fixed-variant: '#633c3e'
  background: '#121412'
  on-background: '#e3e3df'
  surface-variant: '#333533'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style

The brand personality for this design system is rooted in "Technical Craftsmanship." It bridges the gap between high-level architectural design and the gritty, voxel-based reality of server configuration. The target audience includes server owners, network administrators, and gaming communities looking for premium, bespoke environments.

The design style is a hybrid of **Modern Minimalism** and **Glassmorphism**, accented by "Low-Poly Geometric" influences. The aesthetic response should be one of stability and immersion—evoking the feeling of a high-end workstation used to build vast digital worlds. We utilize sharp verticality, pixel-aligned borders, and a sophisticated dark mode to ensure the portfolio showcases (the maps and builds) remain the focal point.

## Colors

The palette is anchored by "Deep Forest Green" and "Stone Grey," reflecting the organic and structural foundation of the game world. 

- **Primary:** The forest green is used for key action areas and brand identifiers, providing a grounded, earthy tone.
- **Secondary/Accents:** "Diamond Blue" is reserved for technical callouts, links, and high-priority data visualizations. "Gold" is used sparingly for premium tiers, achievements, or featured map highlights.
- **Background:** A multi-layered dark theme. The base layer is a near-black neutral to maximize contrast, while "Stone Grey" is utilized for structural elements like borders and dividers to maintain a rigid, architectural feel.

## Typography

This design system employs a tiered typography strategy to balance readability with a technical edge. 

- **Headlines:** We use **Inter** for its neutral, systematic clarity. Tight letter spacing and heavy weights create an authoritative presence for section headers.
- **Body:** **Manrope** provides a refined, modern reading experience for long-form descriptions of technical configurations and build processes.
- **Technical Labels:** **Space Grotesk** is introduced for small labels, coordinates, or version numbers, leaning into its geometric and futuristic character to signal technical precision.

## Layout & Spacing

The layout philosophy is based on a **Fixed Grid** model to ensure a high-end, editorial portfolio feel. We utilize a 12-column grid with a 1280px maximum container width. 

The spacing rhythm follows a strict 4px "voxel" increment. All components, margins, and gutters must align to this 4px baseline to maintain a "pixel-perfect" aesthetic. Sections are separated by large vertical gaps (xl) to allow the high-quality imagery to breathe, while functional UI elements use tighter spacing (sm, md) to imply a compact, efficient dashboard environment.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layers** rather than traditional drop shadows. This maintains the clean, modern aesthetic while hinting at the layered nature of world-building.

- **Surface Levels:** The background is the lowest level. Cards and containers sit on "Surface 1" (a slightly lighter grey). Modals or active flyouts sit on "Surface 2."
- **Glass Effects:** Top-level navigation and primary feature cards use a backdrop-blur (12px to 20px) with a semi-transparent fill. 
- **Borders:** Every elevated element must have a 1px solid border. This border should use a high-contrast "Stone Grey" or a subtle "Diamond Blue" glow to mimic the sharp edges of a block-based universe.

## Shapes

The shape language is predominantly **geometric and rigid**. While a pure 0px radius can feel overly "retro-gaming," this design system uses a subtle **0.25rem (Soft)** radius to provide a modern, premium finish. This slight rounding prevents the UI from feeling aggressive while still honoring the cubic nature of the subject matter. 

Interactive elements like buttons or input fields follow this same "Soft" rule, ensuring a cohesive look across the entire interface.

## Components

### Buttons
Primary buttons use the "Deep Forest Green" with white text. They should have a 1px inner top-border (highlight) to give a subtle tactile "block" feel. Secondary buttons use a "Stone Grey" outline.

### Cards
Portfolio cards are the centerpiece. They feature a fixed 16:9 aspect ratio for map showcases, topped with a glassmorphic overlay for titles. Borders are 1px Stone Grey at 30% opacity.

### Chips & Tags
Used for technical tags (e.g., "PaperMC", "1.20.1", "WorldEdit"). These should use the "Space Grotesk" label font and have a background of "Surface 2" with "Diamond Blue" text.

### Input Fields
Dark backgrounds with a 1px border that glows "Diamond Blue" upon focus. Use monospaced fonts for coordinate or configuration inputs to emphasize the technical nature of the work.

### Icons
Use thin-stroke, modern geometric icons. Avoid illustrative or playful styles; icons should look like blueprints or technical schematics.