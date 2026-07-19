# Digital Footprint Scan — Findings Memo

**Subject:** Darnall Bailey — Columbia, SC native; Atlanta, GA (Virginia-Highland); USC alum; Managing Director, WDG Real Estate Partners
**Date:** 2026-07-19
**Scope:** Public-residue sweep only. No logins, no auth-gated scraping, no ToS violations. No opt-outs submitted — everything is queued for review.

---

## Bottom line

The old personal content you were worried about (college-era Facebook / Myspace) shows **no public residue** — name searches are clean, and the account deletion appears to have stuck. The real, actionable exposure today is (1) a **direct cell number published on the WDG team page** that seeds the broker ecosystem, (2) a **confirmed ZoomInfo listing**, and (3) the standard swarm of people-search brokers that need per-site opt-outs. Three checks (Wayback/archive, email breach exposure) are **blocked until you provide old usernames and old email addresses** — those are the highest-leverage things you can hand over.

---

## 1. Helpful surprise: your name is naturally buried

Searching "Darnall Bailey" surfaces a lot of **wrong-person noise**, which works in your favor:
- **"Ashley Darnall"** (a different person) appears on Facebook and MyLife — *not you.*
- **"Darnall W. Boyd"** / the **Darnall W. and Susan F. Boyd Foundation** and a **"George Bailey"** leadership article collide with your name — the search engine mixes "Darnall" + "Boyd" + "Bailey" together.

**Implication for opt-outs:** On every broker, *confirm the record is actually you* (Columbia SC / Atlanta GA / correct age / relatives) before submitting a removal. Don't remove Ashley Darnall's records or the Boyd/Bailey conflations by mistake.

---

## 2. Old personal content (the original worry) — CLEAN

- **Facebook (deleted account):** No indexed residue under the name. Cannot check the **Wayback Machine / archive.today** for an old profile snapshot **without the old FB vanity username** — that's an open item for you. Deleted ≠ un-archived, so this check still matters.
- **Myspace (lost login):** No indexed residue under the name. Same blocker — need the old Myspace handle to check archives.
- **Recommendation:** Provide old usernames so the archive check can actually run. If a snapshot exists, we request exclusion via `info@archive.org` (Wayback) or archive.today's removal contact. If none exists (likely), close this out.

---

## 3. Confirmed live — personal (owner will handle, per your instruction — flagged, not touched)

| Item | Exposure | Recommendation |
|---|---|---|
| **Flickr** (joined 2012, 527 public photos, "Morocco to China" bio) | Personal travel photos, publicly visible | **Privatize or delete** in Flickr privacy settings |
| **Zola wedding site** (2021) | Wedding details, names, date, possibly registry/location | **Take down or set to private** in Zola |

Neither was touched. Both are yours to close out directly.

---

## 4. Confirmed live — professional / first-party (decision needed)

- **WDG team page** — `wdgrep.com/team/darnall-bailey/` — publishes your **direct work email and cell number**. This is the single biggest *feeder* for data brokers (scrapers pull cell numbers straight off corporate bio pages). **Recommendation: remove the cell number** (or swap it for a main office line). Highest-leverage single fix in this whole report because it's under your control and stops re-population at the source.
- **ZoomInfo** — confirmed listing exposing your work email pattern + phone. **Recommendation: opt out** (Tier 1 in the queue) and re-check quarterly; it rebuilds from public sources.
- **Boyd Foundation "About" page** — `boydfoundationcolumbia.org/about/` — lists you as a board member. Name + role only, no PII. **Low risk; likely intentional. Leave** unless you specifically want it down.
- **Who's On The Move** article — PR/announcement naming you re: the Boyd Foundation. Low risk. Leave.
- **Instagram / LinkedIn / YouTube** — active, intentional. No action (per brief).

---

## 5. Data broker sweep — 14 sites queued

The people-search brokers (Spokeo, Whitepages, BeenVerified, Radaris, TruePeopleSearch, FastPeopleSearch, Intelius, Instant Checkmate, PeopleFinders, MyLife, USSearch, ThatsThem, Nuwber, ClustrMaps) **cannot be queried from this environment** — they sit behind bot protection that returns 403 to automated fetches (the same reason Google doesn't index them, as your brief noted). They must be checked in a normal browser.

What I did instead: **researched and confirmed each site's current (2026) opt-out process and link**, and built the **Opt-Out Queue** so the removal work is turnkey. Two efficiencies worth knowing:
- **PeopleConnect suppression** (`suppression.peopleconnect.us`) removes **Intelius + TruthFinder + Instant Checkmate + USSearch in one request** — do this first.
- **TruePeopleSearch and FastPeopleSearch** share an operator — do them back to back.

Expected exposure on these (typical record): name, age/DOB, current + prior addresses, phone numbers, relatives/associates, sometimes email/IP. All are **repopulating** — see the rerun note.

---

## 6. Blocked — need your input (highest leverage)

1. **Old email addresses** → run each through **haveibeenpwned.com**, note breaches, rotate/2FA any reused passwords. *(Only your current gmail is known.)*
2. **Old Facebook + Myspace usernames** → run the Wayback + archive.today checks that are currently impossible without them.
3. **Old phone numbers + prior street addresses** → sharpen broker record-matching and catch listings that don't surface under the current name.

Per your brief: "these matter more than the name — brokers and archives key off them." Confirmed. The name-only pass is largely exhausted; identifiers are the unlock.

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
