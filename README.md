# App builds

Installable builds of two apps I built, published here because neither is in the
App Store or Google Play yet. They are linked from the products on
[mustafamasood.tech](https://mustafamasood.tech/#work).

| file | app | platform | version | notes |
|---|---|---|---|---|
| `thekurd.apk`  | Kurdistan Barber | Android | 1.0.0 | signed, installs directly |
| `thekurd.ipa`  | Kurdistan Barber | iOS     | 1.0.0 | unsigned, needs sideloading |
| `kurdlink.apk` | KurdLink         | Android | 1.1.2 | signed, installs directly |
| `kurdlink.ipa` | KurdLink         | iOS     | 1.0.0 | unsigned, needs sideloading |

**Android** — download the `.apk` and open it. Your phone will ask you to allow
installs from unknown sources once.

**iPhone** — the `.ipa` files are not signed, so tapping one does nothing. It has
to be re-signed with your own Apple ID using Sideloadly or AltStore.

This repository holds the built packages only. The source for both apps is
private.

## KurdLink 1.1.2

Installs straight over 1.1.1 — same signing key throughout.

- **You can send your link now.** KurdLink is one link for everything, and
  there was no button anywhere on My Page to give that link to anybody. The
  only way left after the first week was Account, scroll down, "Profile link",
  tap, and it copied without telling you. There is a share button on My Page,
  beside Store.
- **Your page says it is live.** Nothing in KurdLink ever publishes — your page
  is public from the moment it exists — so nothing ever told you it was up.
  The handle now carries a lit dot and the word Live.
- **Nothing is locked any more.** Map, Booking, YouTube, Spotify, Apple Music,
  Twitch, embeds, nine of the twelve layouts and two of the profile switches
  all wore a padlock that said "available with KurdLink Pro". There is no Pro,
  there never will be, and there was nowhere to buy it. The padlocks are gone.
- **The app asks before throwing away what you typed.** Swiping back out of
  the profile or link editor used to discard everything, silently, with no
  question — and the X in the corner did the same. Both now ask, and both
  close buttons have a name so a screen reader can read them out.

## KurdLink 1.1.1

Installs straight over 1.1.0 and over 1.0.0 — same signing key throughout.

- Making your page could fail with "Too Many Attempts." A username is
  refused until it happens to be free, so typing over a taken one is the
  normal way this goes — and five refusals locked you out of the account you
  had just created, for an hour. The limit was the wrong shape and is fixed
  on the server, so this part is already better even without updating.
- Errors now appear above the boxes you are filling in, and the page scrolls
  back to them. The create-page sheet used to show nothing at all: the
  attempt failed, and it just sat there.
- Errors are written in the language you picked. The "too many attempts"
  message was always English whatever the app was set to.

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
