# Darman GitHub Pages

The gh-pages branch serves the site at `https://mobinseven.github.io/Darman/`.
Edit the HTML and site styles directly. The clinic guide lives at `guide/`.
Preserve the four guide fragments because the former Vitarish site links to them.

The site uses native HTML with HeroUI v3 component styles and local Vazirmatn. The font and style licenses are adjacent to their assets.

To refresh `heroui.css`, compile `heroui.source.css` using Tailwind CSS v4 and `@heroui/styles@3.2.7`. The stylesheet is generated and should be replaced as a whole.
From a disposable directory with those packages, use `npx @tailwindcss/cli@4 -i heroui.source.css -o heroui.css --minify`.

The Vitarish repository owns Darman's app journeys and plans. This site summarizes them for a public audience.
