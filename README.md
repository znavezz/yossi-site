# Yossi site

Help and privacy pages for the Yossi app, served by GitHub Pages at
https://znavezz.github.io/yossi-site/.

| Page | Used as |
|---|---|
| `index.html` | How to join a home, and short answers. The App Store's **Support URL**. |
| `privacy.html` | The privacy policy. The App Store's **Privacy Policy URL**. |

Plain HTML and one stylesheet: no build step, nothing to install. `icon.png` and `favicon.png`
are the app icon, resized from the app repo's `ios-1024.png` (drawn by `scripts/make-icons.swift`
there).

## Preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000. Check it at phone width first.

## When Yossi is on the App Store

The join steps describe TestFlight. Once the unlisted App Store link exists, replace steps 1 to 3
in `index.html` with that link, and drop the TestFlight answer.
