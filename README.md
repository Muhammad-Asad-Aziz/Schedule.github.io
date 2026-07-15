# Schedule Maker

A responsive class schedule builder that works on desktop and mobile. It is hosted as a static site on GitHub Pages:

**https://muhammad-asad-aziz.github.io/Schedule.github.io/**

## Features

- Multiple schedule profiles with custom class colors
- Desktop timetable and mobile agenda layouts
- Drag and drop classes to change their day/time
- JSON import and export for backups and sharing
- Installable Progressive Web App (PWA) with offline support
- Dark mode, 12/24-hour times, and optional weekends
- Keyboard shortcuts: `A` add, `E` export, `I` import, `?` help, and `Esc` close
- Data stays in the browser's local storage

## Development

The maintainable source files are `index.html`, `styles.css`, and `app.js`. GitHub Pages serves the generated `styles.min.css` and `app.min.js` files for faster loading.

```bash
npm install
npm run check
npm run build
```

After changing `styles.css` or `app.js`, run `npm run build` and include the regenerated minified files. No server-side components or special GitHub Pages configuration are required.

## Install and offline use

Open the site in a supported browser and choose **Install app** when it appears (or use the browser's “Add to Home Screen” action). Once the first visit finishes, the application shell is cached for offline use. Schedule data remains local to that browser unless exported.
