# NuvoraMind Learning — website project

React + Vite website updated with the supplied NuvoraMind Private Limited logo reference and a blue / cyan / orange / silver brand palette.

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (configured for port 3000). Production build:

```bash
npm run build
npm run preview
```

## Included

- Updated supplied logo assets in `public/identity/`.
- Brand palette and theme styling in `source/aurora-theme.css`.
- React website routes and interactions in `source/NuvoraSite.jsx`.
- Updated NuvoraMind Learning naming and product route slug.
- Existing service, academic, pricing, contact, project, legal and resources sections retained.
- Vite deployment configuration and existing content catalog retained.

## Important verification limits

The source archive was inspected and updated. The production build could not be completed in this environment because `npm install` timed out while retrieving dependencies. Therefore, do not treat this archive as a browser-tested production release. Run `npm install` and `npm run build` on a connected machine, then test each route and interactive control. Existing contact form, assistant, and portal behaviours remain as described in the original source; they are not upgraded into live backend services by this visual/branding pass.

The supplied logo includes a white background. It is preserved intact to avoid damaging the silver/white parts of the emblem. It is placed in white-backed logo containers for contrast.
