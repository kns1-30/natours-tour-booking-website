# Natours — Tour Booking Website

A tour booking landing page built with advanced **CSS animations**, Sass, and pure HTML — demonstrating that complex UI effects typically done with JavaScript can be achieved with CSS alone. Developed as part of Jonas Schmedtmann's *Advanced CSS and Sass* course.

## Tech Stack

- HTML5
- Sass (SCSS) compiled via `node-sass`
- Pure CSS animations and transitions (no JavaScript for effects)
- PostCSS Autoprefixer

## Project Structure

```
├── index.html
├── package.json
├── sass/               # SCSS source files
└── css/                # Compiled & minified CSS output
```

## Getting Started

```bash
npm install

# Development (live reload + Sass watch)
npm start

# Production build (compile → autoprefix → minify)
npm run build:css
```

## Key Concepts Demonstrated

- CSS `@keyframes` animations for hero section entrance effects
- Pure-CSS modal popup using `:target` pseudo-class
- CSS-only navigation overlay with checkbox hack
- `clip-path` for geometric section shapes
- Card flip effect using `perspective` and `rotateY` transforms
- Gradient overlays and background `blend-mode`
- BEM naming convention with Sass 7-1 architecture
