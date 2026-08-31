# App Legal Docs

Public legal documents, privacy policies, terms, and support pages for Ethan Sang's apps.

This repository is only for public App Store / TestFlight legal and support pages. It must not contain app source code, private identity records, tax records, banking details, Apple account information, repository credentials, provisioning profiles, certificates, or any non-public credential material.

## Licensing and reuse

This is a **public legal-content repository**, not an open-source software distribution. Public access to these pages does not by itself grant permission to copy, modify, republish, or reuse the legal text, branding, app-specific wording, or support content.

Unless a file or directory explicitly carries a separate license, all rights in the repository's original legal/support content are reserved by the copyright holder. Third-party material remains subject to its own terms. If reusable site code or templates are introduced later, they should be separated from app-specific legal text and licensed explicitly rather than relying on repository visibility.

## Canonical GitHub Pages Host

Use:

- `https://ethansangsss.github.io/app-legal-docs/`

Do not use any non-canonical GitHub Pages host for App Store Connect, TestFlight, README files, or support materials.

## App Entries

- [今天吃什么 / DishPick](docs/apps/dishpick/index.html)
- [今天穿什么 / OutfitPick](docs/apps/outfitpick/index.html)
- [口袋心探 / Pocket Psy](docs/apps/pocket-psy/index.html)
- [验机侦探 / Device Inspector](docs/apps/device-inspector/index.html)
- [岁月留声 / SYLS](docs/apps/syls/index.html)

## Canonical Public URLs

### DishPick

- `https://ethansangsss.github.io/app-legal-docs/apps/dishpick/privacy.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/dishpick/terms.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/dishpick/support.html`

### OutfitPick

- `https://ethansangsss.github.io/app-legal-docs/apps/outfitpick/privacy.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/outfitpick/terms.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/outfitpick/support.html`

### Pocket Psy

- `https://ethansangsss.github.io/app-legal-docs/apps/pocket-psy/privacy.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/pocket-psy/terms.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/pocket-psy/support.html`

### Device Inspector

- `https://ethansangsss.github.io/app-legal-docs/apps/device-inspector/privacy.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/device-inspector/terms.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/device-inspector/support.html`

### SYLS

- `https://ethansangsss.github.io/app-legal-docs/apps/syls/privacy.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/syls/terms.html`
- `https://ethansangsss.github.io/app-legal-docs/apps/syls/support.html`

## GitHub Pages Settings

Configure GitHub Pages for this repository:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/docs`

The `docs/.nojekyll` marker is present so GitHub Pages serves static files directly.

## Local Preview

```bash
cd docs
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000/`
- `http://localhost:8000/apps/dishpick/privacy.html`

## Safety Rules

- Do not store private identity, tax, banking, Apple account, certificate, provisioning profile, repository credential, or other non-public credential material in this repository.
- Do not add third-party JavaScript, analytics, trackers, or external fonts to these legal pages.
- Placeholder pages for unreleased apps must not be used in App Store Connect until the relevant app is ready.
- Treat any change to app data collection, OCR/image processing, analytics, account systems, cloud sync, payments, third-party APIs, or external-link behavior as requiring a legal-page drift review before release.
