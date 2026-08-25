# Salamanca: Sushi & Pasta

Salamanca is a small coastal restaurant concept in Boqueron, Cabo Rojo, Puerto Rico. The site presents a fictional family restaurant that brings together two culinary traditions: west-coast sushi and handmade Italian pasta. Its signature dish is sushi pizza, a crisp rice base treated like an Italian pizza and topped with local seafood and seasonal ingredients.

## What the site contains

- **Hero:** A storefront image, the Salamanca name, the Boqueron location, and quick links to the menu and phone number.
- **Our story:** The restaurant's family history, coastal setting, and approach to combining Japanese and Italian cooking.
- **The kitchen:** A chef profile for Marisol Esposito, whose background connects Ponce, Osaka, and the restaurant's two cuisines.
- **Menu:** Interactive tabs for appetizers, sushi, sushi pizza, pasta, and desserts. The menu includes descriptions, prices in US dollars, and notes about daily seafood and fresh pasta.
- **Instagram gallery:** Four image slots for social photography and restaurant updates.
- **Visit us:** Address, storefront image, phone link, map link, and opening hours.

## Visual direction

The page uses an editorial, book-inspired style with Cormorant Garamond headings, Lora body text, warm ivory surfaces, charcoal text, thin rules, and brass accents. Photography is treated like a printed image plate, pairing the restaurant's coastal setting with its food and craft.

## Project structure

- `index.html` - The standalone production page.
- `Salamanca.dc.html` - The design-canvas source with data-driven menu and image slots.
- `assets/` - Hero, chef, storefront, and gallery imagery.
- `support.js` - Support code used by the design-canvas source.
- `image-slot.js` - Image-slot behavior used by the design-canvas source.
- `_ds/` - The bundled Classical design system, including tokens, components, and styles.

## Run locally

This is a static HTML site with no build step or package installation required. From the project directory, start any local static server, for example:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Status

This is an early restaurant site concept. The current imagery is representative and can be replaced with final restaurant photography or a generated hero image later.
