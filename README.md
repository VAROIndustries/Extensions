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

## About

Built by [VARØ Industries](https://varo.industries). All extensions are free and open source.
