# NineSixTwo — Legal Pages

This repository hosts the Privacy Policy and Terms & Conditions for the NineSixTwo iOS app.

## Pages

- **Landing page:** `index.html`
- **Privacy Policy:** `privacy.html`
- **Terms & Conditions:** `terms.html`

## Where These Live

If added to your existing `treanthonyguerrero-rgb.github.io` repository under a `ninesixtwo/` folder, the live URLs will be:

- `https://treanthonyguerrero-rgb.github.io/ninesixtwo/` (landing page)
- `https://treanthonyguerrero-rgb.github.io/ninesixtwo/privacy.html`
- `https://treanthonyguerrero-rgb.github.io/ninesixtwo/terms.html`

## Updating the App

When you rebrand the app in Xcode, update these locations to point at the new URLs:

- **OnboardingView.swift** — search for any hardcoded `macromeals/privacy` or `macromeals/terms` URLs and replace with the new `ninesixtwo/` URLs.
- **SettingsView.swift** — same search and replace.

Then rebuild and your app will link to the updated NineSixTwo pages.

## Updating the Pages

To update content later:
1. Go to your repository on GitHub
2. Click the file you want to edit (e.g. `privacy.html`)
3. Click the pencil icon to edit
4. Make your changes and click **Commit changes**
5. Changes go live automatically within a minute or two

When you make changes, update the **Last Updated** date at the top of the file.

## Notes

- The old `macromeals/` folder should remain in place until your rebranded v2 is approved by Apple, since the live v1 app still points there.
- Brand color is `#F97316` (warm orange) matching the app's design system.
- Contact email is `macromealsplan@gmail.com` — update this throughout the files if you ever switch to a NineSixTwo-branded email.
- Governing law is set to Texas. Update if your legal entity moves to another state.
