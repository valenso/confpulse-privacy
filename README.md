# confpulse-privacy

Public GitHub Pages site hosting the privacy policy for the
[ConfPulse](https://github.com/valenso/ConfPulse) iOS app.

**Published at:** <https://valenso.github.io/confpulse-privacy/> — this is the URL registered
in App Store Connect.

## Why this is a separate, public repo

`valenso/ConfPulse` is private, and GitHub Pages only publishes from private repos on Pro
plans or above. App Store Connect requires a publicly reachable privacy policy URL, so the
policy lives here instead. Same arrangement as `valenso/ethos-privacy`.

`index.md` is the only copy of the policy — there is deliberately no duplicate in the app
repo to drift out of sync with it.

## Editing

Edit `index.md` and push to `main`; the Pages rebuild takes about 60–90 seconds. The page
title comes from `_config.yml` and is rendered by the theme banner, which is why `index.md`
starts straight into content with no top-level `#` heading.

Note that Jekyll (kramdown) does not turn single newlines into `<br>` the way GitHub's
Markdown does — consecutive `**Label:** value` lines must be a bulleted list or they render
as one run-on paragraph.
