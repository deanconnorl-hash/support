# How to publish this (once)

The App Store Connect listings for Orrery and Tempo already point at these URLs.
App Review will open them, so they need to be live **before** you press Submit.

The repository name matters. Every URL already entered in App Store Connect is
`deanconnorl-hash.github.io/support/...`, and GitHub Pages takes that path
segment from the repo name — so the repo has to be called exactly **`support`**.

## Steps

1. GitHub Desktop → **File → Add Local Repository** → choose
   `/Users/cld1997/claude code/support-site`
2. **Publish repository**
   - Name: `support`   ← must be exactly this
   - Uncheck **Keep this code private** (Pages needs it public on a free account)
3. On github.com, open the new repo → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → Save
4. Wait a minute or two, then check that these four load:

   - https://deanconnorl-hash.github.io/support/orrery.html
   - https://deanconnorl-hash.github.io/support/orrery-privacy.html
   - https://deanconnorl-hash.github.io/support/tempo.html
   - https://deanconnorl-hash.github.io/support/tempo-privacy.html

Once those load, Orrery and Tempo are safe to submit.

## Note on Patience

Patience is already live pointing at a different repo
(`deanconnorl-hash.github.io/patience-support/`). Leave that alone — it works.
`index.html` and `privacy.html` here are a spare copy of those pages so the
series cross-links stay complete.
