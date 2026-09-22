# App builds

Installable builds of two apps I built, published here because neither is in the
App Store or Google Play yet. They are linked from the products on
[mustafamasood.tech](https://mustafamasood.tech/#work).

| file | app | platform | version | notes |
|---|---|---|---|---|
| `thekurd.apk`  | Kurdistan Barber | Android | 1.0.0 | signed, installs directly |
| `thekurd.ipa`  | Kurdistan Barber | iOS     | 1.0.0 | unsigned, needs sideloading |
| `kurdlink.apk` | KurdLink         | Android | 1.1.3 | signed, installs directly |
| `kurdlink.ipa` | KurdLink         | iOS     | 1.0.0 | unsigned, needs sideloading |

**Android** — download the `.apk` and open it. Your phone will ask you to allow
installs from unknown sources once.

**iPhone** — the `.ipa` files are not signed, so tapping one does nothing. It has
to be re-signed with your own Apple ID using Sideloadly or AltStore.

This repository holds the built packages only. The source for both apps is
private.

## KurdLink 1.1.3

Installs straight over 1.1.2 — same signing key throughout.

- **The app opens on your page now.** It used to open on Explore, a list of
  other people's pages, with yours one tab away every single time. If you have
  no page of your own yet you still land on Explore, because your page would
  be an empty screen.
- **Arrows point the right way in Kurdish and Arabic.** Ten of them did not,
  including the Continue button on the first screen after you sign in, which
  wore an arrow that looked like Back.
- **No more "Pro" badge.** Every page in the app wore one, for a plan that does
  not exist. Your public page never showed it.
- **Failures say what went wrong.** The music screen and the store used to
  swallow them: an add that failed simply did not happen. The store also used
  to answer a dead connection with a blank gap and a spinner that never
  stopped; it now says what happened and offers to try again.
- **Edit profile is readable.** Your page's font used to be filed under
  "Search and appearance" between two search boxes. It is under its own
  heading now, and the sixteen social account boxes are folded away unless you
  have some filled in.
- **Smaller things:** three buttons were too small to hit reliably; the QR
  colour swatches are the worst of them and are fixed. Three animations
  ignored the phone's Reduce Motion setting. Long lists no longer blur their
  background, which is easier on a cheap phone's battery.
- Under the hood: the app used to carry a second, older layout and would drop
  you into it if your sign-in token went stale — every tab in a different
  place. There is one layout now.

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
