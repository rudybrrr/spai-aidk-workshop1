# AI Don't Know - Workshop 1

Static HTML/CSS/JavaScript presentation deck for SPAI's first AI Don't Know workshop.

## Run locally

From this directory, run:

```sh
npm run dev
```

Open the local URL printed by the server. No install or build step is required. If you already have another static file server, serve this directory and open `index.html` through it.

## Deploy to Vercel

Import this project directory as a new Vercel project. Select **Other** as the framework preset and leave the build command empty. The site is served directly from the project root.

With the Vercel CLI, run this command from the same directory:

```sh
vercel
```

## Edit slide content

Slide content and ordering live in `index.html`. Each slide is a `<section class="slide">` inside `<main class="deck">`. Keep the existing class names and `data-footer` attributes when editing content so navigation, fitting, and footer labels continue to work.

Styles are separated by responsibility:

- `src/styles/globals.css`: theme variables, base styles, typography, and page background
- `src/styles/slides.css`: layouts, controls, progress, footer, dots, transitions, and responsive behavior
- `src/styles/code.css`: code windows, copy buttons, and syntax colours

Scripts are also separated by responsibility:

- `src/scripts/navigation.js`: navigation, keyboard controls, dots, footer, and progress
- `src/scripts/fitSlides.js`: slide staging and viewport fitting
- `src/scripts/copyCode.js`: code-copy buttons

## Add images

Place assets in the matching public directory:

- Event photos: `public/images/events/`
- Background images: `public/images/backgrounds/`
- SPAI or partner logos: `public/images/logos/`

Reference public assets from HTML with paths such as `/images/events/pixels-to-perception-01.webp`.

For optional event images, use the provided image class and hide a missing asset so it cannot reserve space or show a broken-image icon:

```html
<div class="event-image-slot">
  <img
    class="event-image"
    src="/images/events/pixels-to-perception-01.webp"
    alt="Participants at Pixels to Perception"
    onerror="this.hidden = true"
  />
</div>
```

An empty `.event-image-slot`, an image without a source, or an image hidden after a load error does not affect the slide layout.

## Recommended asset naming

Use lowercase kebab-case names with a descriptive subject and optional sequence number:

```txt
pixels-to-perception-01.webp
graphing-impact-group-photo-01.webp
n8n-workshop-banner.webp
spai-logo-light.svg
workshop-background-grid.webp
```

Prefer WebP or AVIF for photos, SVG for logos and simple graphics, and include meaningful `alt` text for content images.
