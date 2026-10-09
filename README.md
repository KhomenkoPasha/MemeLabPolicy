# MemeLab Policy

Private source repository for MemeLab's public privacy policy, terms and account deletion pages. Developer: Pavlo Khomenko; contact: hompavlik@gmail.com. Android package: `com.khom.memelab`.

Public website: https://memelab-khom.web.app/

- Russian: `/`, `/terms.html`, `/delete-account.html`
- Ukrainian: `/uk.html`, `/terms-uk.html`, `/delete-account-uk.html`
- English: `/en.html`, `/terms-en.html`, `/delete-account-en.html`

The static website uses no analytics scripts, cookies or external assets. Firebase Hosting may process ordinary server request information. Source access remains private; the deployed policy pages are public.

```sh
firebase deploy --only hosting --project memelab-khom
```

Generation and in-app account deletion depend on the separate backend deployment. The public deletion page provides an email request route while in-app deletion is unavailable. Keep this documentation synchronized with actual app behavior before a public release.
