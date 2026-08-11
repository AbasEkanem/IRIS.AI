# IRIS.ai

This repository hosts the public homepage, privacy policy, and terms of
service for **IRIS**, an AI agent that connects to Google Workspace
(Gmail, Calendar, Docs, Slides, Drive) to help complete user-requested tasks.

This site is served via GitHub Pages and is used to satisfy Google Cloud's
OAuth consent screen branding requirements (homepage URL, privacy policy
URL, and terms of service URL).

## Live site

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from
branch → `main` / root), the site will be available at:

```
https://<your-github-username>.github.io/iris-app/
```

Use that URL in the Google Cloud Console OAuth consent screen under:
- Application home page
- Application privacy policy link
- Application Terms of Service link

And use `github.io` as the Authorised domain.

## Files

- `index.html` — the single-page site containing the app description,
  privacy policy, and terms of service.

## Editing

Before deploying, update the placeholder contact email inside `index.html`
(`emryzekanem@gmail.com`) with a real contact address.
