# App builds

Installable builds of two apps I built, published here because neither is in the
App Store or Google Play yet. They are linked from the products on
[mustafamasood.tech](https://mustafamasood.tech/#work).

| file | app | platform | version | notes |
|---|---|---|---|---|
| `thekurd.apk`  | Kurdistan Barber | Android | 1.0.0 | signed, installs directly |
| `thekurd.ipa`  | Kurdistan Barber | iOS     | 1.0.0 | unsigned, needs sideloading |
| `kurdlink.apk` | KurdLink         | Android | 1.1.0 | signed, installs directly |
| `kurdlink.ipa` | KurdLink         | iOS     | 1.0.0 | unsigned, needs sideloading |

**Android** — download the `.apk` and open it. Your phone will ask you to allow
installs from unknown sources once.

**iPhone** — the `.ipa` files are not signed, so tapping one does nothing. It has
to be re-signed with your own Apple ID using Sideloadly or AltStore.

This repository holds the built packages only. The source for both apps is
private.

## KurdLink 1.1.0

Installs straight over 1.0.0 — same signing key, so nothing has to be removed
first and nothing signed in is lost.

- Music on your page: pick a song, and visitors can play it while they read.
- Twenty motion button styles, and they now look the same in the app as they do
  on your public page — the two had drifted apart in ways that were easy to see
  and hard to describe.
- A bell beside each link on My Page, to notify the people following you about
  that one link.
- QR codes with frames, and the picture you get out is the one on screen.
- Occasion packs — Newroz, Blossom, Winter, Aurora — dress the whole page.
- Prices are shown in dinars only. They used to read "$1 · 1500 IQD", two prices
  for one thing, in a currency the checkout cannot take.
- Buy something on the web and come back, and the app now notices. It used to
  still say "Buy" after you had paid, which is a good way to pay twice.

The iPhone build is still numbered 1.0.0 because it was built before this
version bump. Same app.
