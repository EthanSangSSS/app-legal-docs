# Security Policy

`app-legal-docs` hosts public legal, privacy, terms, and support pages for apps. It is not an app source-code repository and must not contain credentials or private account material.

## Supported scope

Security reports are in scope when they involve:

- private identity records, tax records, banking details, Apple account information, certificates, provisioning profiles, API tokens, repository credentials, or other non-public credential material;
- third-party scripts, analytics, trackers, external fonts, or unexpected external network dependencies in public legal pages;
- pages that expose unpublished app information beyond intentionally public support/legal content;
- broken canonical URL routing that could cause App Store Connect or user support links to point to stale or incorrect pages.

## Out of scope

- Legal advice requests.
- App source-code issues in separate private repositories.
- Requests for private app account access, Apple Developer access, certificates, or provisioning profiles.

## Reporting

Open a GitHub issue if no sensitive data is included. If sensitive data is involved, do not paste it into the issue. Open a minimal report with:

- affected path or URL;
- risk category;
- safe reproduction outline;
- whether private account or credential material may be involved.

## Maintainer handling SOP

1. Confirm the affected path or URL.
2. Remove private or unsafe material immediately.
3. Verify canonical GitHub Pages URLs.
4. Document the fix without exposing sensitive details.

## Boundary

These documents are public operational/legal pages and templates. They are not legal advice and do not replace qualified legal review.
