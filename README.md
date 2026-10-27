# VAROIndustries Browser Extensions

Free browser extensions built by **VARØ Industries**. Install by loading the `.zip` as an unpacked extension in Chrome/Edge, or download from the [Releases](../../releases) page.

---

## GotInfo — Site Intel

**Download:** [GotInfo-SiteIntel-Extension.zip](../../releases/latest)

A lightweight companion to [gotinfo.net](https://gotinfo.net) that gives you instant intelligence about any website you're visiting — without leaving the page.

### What it shows

| Section | Details |
|---------|---------|
| **IP / Network** | Resolved IP address, geolocation (city, region, country), ISP/org, ASN |
| **Domain / WHOIS** | Registrar, registration date, expiry date, last updated, domain status flags, DNSSEC |
| **DNS Records** | A, AAAA, MX, NS, TXT records via DNS-over-HTTPS |
| **TLS Certificate** | HTTPS status with a link to the full cert chain on GotInfo |

Every section links back to the relevant GotInfo tool for deeper analysis.

### How it works

- Uses the **RDAP protocol** (`rdap.org`) for domain registration data — no API key required
- Resolves IPs via **Cloudflare DNS-over-HTTPS** for privacy
- Fetches geolocation data from **ip-api.com** (free tier)
- All requests are made from your browser to public APIs — nothing is sent to GotInfo servers

### Install (unpacked)

1. Download `GotInfo-SiteIntel-Extension.zip` from [Releases](../../releases/latest)
2. Unzip it
3. Open Chrome/Edge → `chrome://extensions` → enable **Developer mode**
4. Click **Load unpacked** → select the unzipped folder

> Source code lives in the [VAROIndustries/technolust](https://github.com/VAROIndustries/technolust) repo under `browser-extension/`.

---

## MakerManifest

**Download:** [MakerManifest-Extension.zip](../../releases/latest)

A browser extension for [MakerManifest](https://makermanifest.co) that lets you add any product from any website directly to your gear lists — without ever leaving the page you're on.

### What it does

- **One-click product saving** — click the extension icon on any product page and add it to a list instantly
- **Smart product detection** — automatically extracts the product title, image, and price from the current page
- **List & section selection** — choose which list and section to save to, with sort preferences remembered
- **Token-based auth** — connects to your MakerManifest account via a secure extension token from your dashboard

### How it works

1. Generate an extension token in your MakerManifest dashboard under **Settings → Browser Extension**
2. Paste the token into the extension popup to connect your account
3. Browse to any product page and click the MakerManifest icon to save it

### Install (unpacked)

1. Download `MakerManifest-Extension.zip` from [Releases](../../releases/latest)
2. Unzip it
3. Open Chrome/Edge → `chrome://extensions` → enable **Developer mode**
4. Click **Load unpacked** → select the unzipped folder

> Source code lives in the [VAROIndustries/makermanifest](https://github.com/VAROIndustries/makermanifest) repo under `browser-extension/`.

---

## NoteSmith — Web Clipper

**Download:** [NoteSmith-WebClipper-Extension.zip](../../releases/latest)

Clip any page — or just the part you selected — straight into a [NoteSmith](https://notesmith.io) note, without leaving the page you're reading.

### What it does

- **Clip the article, not the furniture** — finds the main content and leaves the nav, sidebars, footers and cookie banners behind
- **Clip a selection** — highlight any part of a page and clip only that
- **Right-click to clip** — "Clip selection to NoteSmith" straight from the context menu, no popup needed
- **Keeps the structure** — headings, lists, quotes, code blocks, links, images and inline formatting all survive
- **Pick where it lands** — choose the workspace and folder, and the extension remembers your last choice
- **Every clip is sourced** — each note opens with a link back to the page it came from

### How it works

1. In NoteSmith, go to **Settings → API Keys** and create a key with the **Browser extension (clip only)** scope
2. Paste it into the extension popup once to connect this browser
3. Click the NoteSmith icon on any page, or right-click a selection

A clip-only key can create notes and see your workspace and folder names. It **cannot read, edit or delete anything already in your account**, so a token sitting in a browser profile can't be used to read your notes. Revoking it in Settings disconnects the extension and nothing else.

### Install (unpacked)

1. Download `NoteSmith-WebClipper-Extension.zip` from [Releases](../../releases/latest)
2. Unzip it
3. Open Chrome/Edge → `chrome://extensions` → enable **Developer mode**
4. Click **Load unpacked** → select the unzipped folder

> Source code lives in the [VAROIndustries/notesmith](https://github.com/VAROIndustries/notesmith) repo under `browser-extension/`.

---

## FairKeep — Add Show

**Download:** [FairKeep-AddShow-Extension.zip](../../releases/latest)

On a craft fair or market's web page, one click starts a new [FairKeep](https://fairkeep.app) application with the show's details already filled in.

### What it does

- **Reads the show page for you** — name, dates, city and state, booth fee, application deadline, apply link and organizer contact
- **Fills blanks, you check and save** — nothing is saved until you press Save in FairKeep
- **Puts the show on [FairFinder](https://fairfinder.cc)** — optional checkbox; new shows go in as a suggestion for review
- **Reads only when you click** — only the tab you clicked on, only at that moment; the capture is deleted as soon as FairKeep picks it up

### How it works

1. Sign in to [fairkeep.app](https://fairkeep.app) in the same browser
2. On a show's web page, click the FairKeep icon
3. FairKeep opens in a new tab with a pre-filled application — check it and save

With an Assistant pack, Claude reads the whole page (metered against the pack). Without one, a basic reader uses the page's title and event details. No token to paste — it uses your FairKeep sign-in.

### Install (unpacked)

1. Download `FairKeep-AddShow-Extension.zip` from [Releases](../../releases/latest)
2. Unzip it
3. Open Chrome/Edge → `chrome://extensions` → enable **Developer mode**
4. Click **Load unpacked** → select the unzipped folder

> Source code lives in the VAROIndustries/FairKeep repo under `extension/`.

---

## About

Built by [VARØ Industries](https://varo.industries). All extensions are free and open source.
