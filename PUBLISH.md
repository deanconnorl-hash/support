# How to publish this (once)

The App Store Connect listings for Orrery and Tempo already point at these URLs.
App Review will open them, so they need to be live **before** you press Submit.

## The button is "Publish repository", not "Commit"

Everything here is already committed and the working tree is clean, so GitHub
Desktop greys the Commit button out — there is nothing left to commit. What you
want is the blue **Publish repository** button in the top bar. That is the step
that creates the GitHub repo and pushes all four commits at once.

## Steps

1. GitHub Desktop → **File → Add Local Repository** → choose
   `/Users/cld1997/claude code/support-site`
2. **Publish repository** (top bar)
   - Name: `support`   ← must be exactly this
   - Uncheck **Keep this code private** — Pages will not serve a private repo
     on a free account
3. On github.com, open the new repo → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → Save
4. Wait a minute or two, then check that these four load:

   - https://deanconnorl-hash.github.io/support/orrery.html
   - https://deanconnorl-hash.github.io/support/orrery-privacy.html
   - https://deanconnorl-hash.github.io/support/tempo.html
   - https://deanconnorl-hash.github.io/support/tempo-privacy.html

Once those load, Orrery and Tempo are safe to submit.

## Why the name has to be `support`

GitHub Pages serves a project repo at `<user>.github.io/<repo-name>/`, so the
repo name *is* the path segment. Every URL already entered in App Store Connect
says `/support/`. A repo called anything else produces a 404 on all four pages,
and App Review treats a dead support URL as a rejection.

## There is an empty `deanconnorl-hash/support-site` repo on GitHub

It was created by an earlier attempt and holds one file (`.gitattributes`) and
nothing else. It is private, it has none of this content, and it is not what the
App Store URLs point at. Delete it or ignore it — either is fine. Its stray
clone had ended up nested inside this folder and has been removed.

If you would rather reuse that repo than make a new one, say so: it would need
to be renamed to `support` and flipped to public, or I can repoint the four
App Store Connect URLs at `/support-site/` instead.

## Note on Patience

Patience is already live pointing at a different repo
(`deanconnorl-hash.github.io/patience-support/`). Leave that alone — it works.
`index.html` and `privacy.html` here are a spare copy of those pages so the
series cross-links stay complete.
