# NitPath Privacy Policy Website

Responsive static privacy policy for NitPath, built with React, Vite, TypeScript, and Lucide.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## GitHub Pages deployment

1. Create a public repository named `nitpath-privacy-policy`.
2. Push this project to its `main` branch.
3. `vite.config.ts` is configured with `base: '/nitpath-privacy-policy/'`. Change it if your repository name differs; use `/` for a root site/custom domain.
4. In repository Settings → Pages, select GitHub Actions as the source.
5. Commit the included `.github/workflows/deploy.yml` workflow and push to `main`.
6. Wait for the Actions deployment to succeed and verify the public HTTPS page.
7. Add the URL in Play Console and link it inside the app.

The policy deliberately includes a draft publication notice because Firebase status, backup behavior, provider terms, deletion controls, target-age details, and effective date need confirmation. Resolve the developer checklist and finalize the text before public use.
