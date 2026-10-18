# Jouhara NK — Professional Portfolio

Responsive Angular portfolio with selected work, experience, technical skills, certifications, and contact links.

## Local development

```sh
npm ci
npm start
```

Open http://localhost:4200.

## Production build

```sh
npm run build
```

Static output is generated in `dist/jouhara/browser`.

For GitHub Pages under this repository's project path, build with:

```sh
npm run build -- --base-href /my-portfolio/
```

## Content and branding

- Portfolio structure: `src/app/app.html`
- Career, skills, and certifications: `src/app/app.ts`
- Styles and responsive layouts: `src/app/app.scss`, `src/app/responsive.scss`
- Project enquiry link: `src/app/contact.config.ts`
- Browser icons: `public/`

The project enquiry section and its Google Forms links are commented out for public portfolio sharing.
