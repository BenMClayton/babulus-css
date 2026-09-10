# Babulus CSS

A small Sass-generated colour utility library. It provides predictable
background classes for 12 colour families, each with ten lighter tints and ten
darker shades.

## Usage

Include the compiled stylesheet:

```html
<link rel="stylesheet" href="src/babulus-v0.1.css">
```

Then apply a utility class:

```html
<section class="bg-blue-4">Light blue</section>
<section class="bg-blue">Base blue</section>
<section class="bg-blue-16">Dark blue</section>
```

Available families are `red`, `orange`, `yellow`, `lime`, `green`, `cyan`,
`blue`, `magenta`, `purple`, `pink`, `brown`, and `grey`.

## Build

The compiled CSS and source map are committed so the library can be used
without a build step. To regenerate them with Dart Sass:

```sh
npx sass src/babulus-v0.1.scss src/babulus-v0.1.css
```

Open [`demo/index.html`](demo/index.html) to inspect the complete palette.

## Project status

This is a focused utility experiment rather than a full framework. It is useful
when a project needs a compact, human-readable background palette without
bringing in a larger CSS dependency.
