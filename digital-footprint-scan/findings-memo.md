# Digital Footprint Scan — Findings Memo

**Subject:** Darnall Bailey — Columbia, SC native; Atlanta, GA (Virginia-Highland); USC alum; Managing Director, WDG Real Estate Partners
**Date:** 2026-07-19
**Scope:** Public-residue sweep only. No logins, no auth-gated scraping, no ToS violations. No opt-outs submitted — everything is queued for review.

---

## Bottom line

The old personal content you were worried about (college-era Facebook / Myspace) shows **no public residue** — name searches are clean, and the account deletion appears to have stuck. The real, actionable exposure today is the standard swarm of people-search brokers that need per-site opt-outs, plus a **confirmed ZoomInfo listing**. Three checks (Wayback/archive, email breach exposure) are **blocked until you provide old usernames and old email addresses** — those are the highest-leverage things you can hand over.

## Scope decision (owner, 2026-07-19)

**KEEP — no action:** LinkedIn, WDG team page, Boyd Foundation page, Instagram, YouTube.
**DELETE — everything else you never chose to publish:** all people-search brokers + ZoomInfo + old-archive residue.
**EVALUATE — accounts you control, your call to keep / privatize / delete:** Flickr, Zola, and the HIBP breach exposure. (Who's On The Move = likely false positive — see §4.)

Note: your personal **cell number is on the (kept) WDG page** — that's the main thing brokers re-scrape. You've chosen to keep the page; the *optional* source-level fix is swapping the cell for an office line so the broker cleanup stays clean. Entirely your call.

---

## 1. Helpful surprise: your name is naturally buried

Searching "Darnall Bailey" surfaces a lot of **wrong-person noise**, which works in your favor:
- **"Ashley Darnall"** (a different person) appears on Facebook and MyLife — *not you.*
- **"Darnall W. Boyd"** / the **Darnall W. and Susan F. Boyd Foundation** and a **"George Bailey"** leadership article collide with your name — the search engine mixes "Darnall" + "Boyd" + "Bailey" together.

**Implication for opt-outs:** On every broker, *confirm the record is actually you* (Columbia SC / Atlanta GA / correct age / relatives) before submitting a removal. Don't remove Ashley Darnall's records or the Boyd/Bailey conflations by mistake.

---

## 2. Old personal content (the original worry) — CLEAN

**Handles provided (7/19) and swept:** `uscdarnallb`, `dbaileylax`, `dbaileylax21`, `bigbruiserdb86`.
- **Username sweep — CLEAN.** None of the handles return public/indexed residue anywhere — social, forums, photo sites. `bigbruiserdb86` is distinctive enough that its total absence is strong evidence nothing's floating around. The only "dbailey" Myspace hit belongs to a different person (Danielle Bailey).
- **Facebook (deleted account):** no indexed residue under name or handle.
- **Myspace (lost login):** no indexed residue. A live-but-unindexed profile at `myspace.com/dbaileylax` can't be ruled out from here — the site 403s automated reads (bot-block, which is *inconclusive*, not "gone").
- **Still needs a browser (3 quick checks — this sandbox is blocked from all three):**
  1. `myspace.com/dbaileylax` and `/dbaileylax21` — is an old profile still live?
  2. `web.archive.org/web/*/facebook.com/dbaileylax` (+ `/dbaileylax21`, + `myspace.com/dbaileylax`) — any archived snapshot?
  3. If any snapshot exists and you want it gone: request exclusion via `info@archive.org`.
- **Expectation:** near-certainly clean given the sweep. These three checks just close the loop.

---

## 3. Confirmed live — personal (owner will handle, per your instruction — flagged, not touched)

| Item | Exposure | Recommendation |
|---|---|---|
| **Flickr** (joined 2012, 527 public photos, "Morocco to China" bio) | Personal travel photos, publicly visible | **Privatize or delete** in Flickr privacy settings |
| **Zola wedding site** (2021) | Wedding details, names, date, possibly registry/location | **Take down or set to private** in Zola |

Neither was touched. Both are yours to close out directly.

---

## 4. Professional / first-party

**KEEP (owner confirmed — fine for work):**
- **LinkedIn** — active professional profile. No action.
- **WDG team page** — `wdgrep.com/team/darnall-bailey/`. Keep. Optional-only: the personal **cell number** on it is the main thing brokers re-scrape, so swapping it for an office line would make the broker cleanup stick. Your call; the page stays either way.
- **Boyd Foundation "About" page** — `boydfoundationcolumbia.org/about/`. Board-member listing, name + role only. Keep.

**DELETE / EVALUATE (moved out of "keep"):**
- **ZoomInfo** — confirmed listing (work email pattern + phone). **Opt out** (Tier 1) and re-check quarterly; rebuilds from public sources.
- **Who's On The Move** article — **likely a false positive.** Title + URL slug say "**George Bailey**," a different person at the Boyd Foundation; your name only matched via the "Darnall W. Boyd" foundation name + surname "Bailey." Site blocks automated fetch — do a 10-second browser check; if you're not named, drop it entirely.
- **Instagram / YouTube** — **KEEP** (owner confirmed). No action.

---

## 5. Data broker sweep — 14 sites queued

The people-search brokers (Spokeo, Whitepages, BeenVerified, Radaris, TruePeopleSearch, FastPeopleSearch, Intelius, Instant Checkmate, PeopleFinders, MyLife, USSearch, ThatsThem, Nuwber, ClustrMaps) **cannot be queried from this environment** — they sit behind bot protection that returns 403 to automated fetches (the same reason Google doesn't index them, as your brief noted). They must be checked in a normal browser.

What I did instead: **researched and confirmed each site's current (2026) opt-out process and link**, and built the **Opt-Out Queue** so the removal work is turnkey. Two efficiencies worth knowing:
- **PeopleConnect suppression** (`suppression.peopleconnect.us`) removes **Intelius + TruthFinder + Instant Checkmate + USSearch in one request** — do this first.
- **TruePeopleSearch and FastPeopleSearch** share an operator — do them back to back.

Expected exposure on these (typical record): name, age/DOB, current + prior addresses, phone numbers, relatives/associates, sometimes email/IP. All are **repopulating** — see the rerun note.

---

## 6. Identifiers — provided, mostly resolved (7/19)

- **Old usernames** → provided (`uscdarnallb`, `dbaileylax`, `dbaileylax21`, `bigbruiserdb86`) and swept. **Clean** (§2). Three browser-only archive/live-profile checks remain to close the loop.
- **Old emails** → provided: `darnall.bailey@gmail.com`, `william.bailey21@gmail.com`, `bigbruiserdb86@hotmail.com` (confirm domain), plus an old **USC `@email.sc.edu`** (username forgotten). **To do:** run each at **haveibeenpwned.com** (needs an interactive run — can't fetch server-side here), note breaches, and **rotate/2FA any reused passwords**. This is the one item with real residual risk — old breached passwords, not old posts.
- **Still helpful:** old **phone numbers** + **prior street addresses** → sharpen broker record-matching on the opt-outs.

Net: the name/handle residue picture is clean. The meaningful remaining action is the **breach/password check**, not old social content.

---

## 7. Ongoing coverage — recommendation

Brokers repopulate from fresh public records (new address, voter file, court filings) within weeks to months. Two realistic paths:

- **DIY quarterly** — rerun Tiers 1–3 of the queue (~1–2 hrs/quarter). The tracker is built to be re-run. Cheapest, and you control it.
- **Paid service** — **DeleteMe** or **Optery** automate removals across these 14 plus dozens more, continuously. Worth it if quarterly manual work won't realistically happen.

**Suggested:** Do the one-time manual Tier 1–2 sweep now (biggest immediate cleanup), fix the WDG cell-number leak at the source, then decide DIY-quarterly vs. paid for maintenance. Fixing the source (WDG page) first makes every downstream removal stick longer.

---

## Open items for Darnall (blocking a complete scan)
- [ ] Provide **old usernames/handles** (Facebook vanity URL, Myspace handle)
- [ ] Provide **old email addresses**
- [ ] Provide **old phone numbers** and **prior street addresses**
- [ ] Decide: remove cell number from the WDG team page? (recommended)
- [ ] Personally review/privatize the **Flickr** account and **Zola** site
- [ ] Decide: **DIY quarterly** vs. **DeleteMe/Optery**
