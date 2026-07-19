# Digital Footprint Scan — Darnall Bailey

A public-residue sweep + data-broker opt-out kit. Built to be **rerun quarterly**.

## Files
| File | What it is |
|---|---|
| `findings-memo.md` | Read this first. Narrative of what was found, what's clean, what to do. |
| `opt-out-queue.md` | Prioritized, turnkey removal steps for each broker (nothing submitted yet). |
| `tracker.csv` | The master log: source, URL, data exposed, risk, opt-out link, status, date. Re-run against this. |

## Scope decision (owner, 2026-07-19)
- **KEEP:** LinkedIn, WDG team page, Boyd Foundation page, Instagram, YouTube.
- **DELETE:** all people-search brokers, ZoomInfo, old-archive residue.
- **EVALUATE (accounts you control):** Flickr, Zola, HIBP breach check. (Who's On The Move = likely false positive, verify in browser.)

## Status at a glance (2026-07-19, first automated pass)
- ✅ **Old FB/Myspace content:** no public/indexed residue. (Archive check still pending — needs old usernames.)
- ⏳ **14 people-search brokers + ZoomInfo** — opt-out processes researched & queued; the sites themselves must be checked/submitted in a **browser** (they block automated access).
- 🔒 **Flickr + Zola** confirmed live — flagged, **not touched**; owner handles.
- 📝 **WDG page kept** — optional-only: personal cell on it is the main broker re-scrape source; swap for an office line to make cleanup stick.
- ⛔ **Blocked pending your input:** breach check (old emails) + Wayback/archive check (old usernames).

## Why some checks say "browser required"
This scan runs in a sandbox whose outbound fetches are blocked or 403'd by:
- the people-search brokers (bot protection),
- `web.archive.org` (Wayback CDX API blocked here),
- `boydfoundationcolumbia.org` (403 to automated fetch — content confirmed via search instead).

None of that is a dead end — it just means the *submission/verification* steps happen in a normal browser. The research, links, and exact steps are all captured so it's copy-paste fast.

## How to rerun (quarterly)
1. Open `tracker.csv`. For every row marked a broker, re-search name + `Columbia SC` / `Atlanta GA` in a browser.
2. **Confirm the record is actually Darnall** before acting — the name collides with *Ashley Darnall* and the *Darnall W. Boyd Foundation*. Don't remove strangers' records.
3. If a listing reappeared, follow that row's `opt_out_link` (full steps in `opt-out-queue.md`), then update `status` + `date_checked`.
4. Start with the **PeopleConnect suppression** (clears 4 sites at once) and **ZoomInfo**.
5. Re-run the Wayback/archive + Have-I-Been-Pwned checks once old usernames/emails are provided.

## Open items for Darnall
See the end of `findings-memo.md` — the blocking inputs are old **usernames, emails, phone numbers, and prior addresses**. They're higher-leverage than the name.

## Rules honored
Public sources only. No logins, no auth-gated scraping, no ToS violations. No opt-outs auto-submitted (some require ID/phone verification — queued for review). Flickr and Zola flagged, not touched.
