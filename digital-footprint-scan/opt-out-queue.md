# Opt-Out Queue — Darnall Bailey

**Prepared:** 2026-07-19
**Rule:** Nothing here has been submitted. This is a review-first queue. Verify each record actually matches the subject before opting out (the name collides with other people — see Findings Memo), then work top to bottom.

**Verification identity to have on hand for each opt-out:**
- Name: Darnall Bailey
- Cities: Columbia, SC and Atlanta, GA (Virginia-Highland)
- A throwaway/secondary email for confirmation links (avoid feeding your primary email into every broker)
- DOB (PeopleConnect + MyLife ask for it to locate the record)

---

## Tier 1 — High value, fast, free (do first)

### 1. PeopleConnect Suppression Center — removes 4 sites at once
- **Covers:** Intelius, TruthFinder, Instant Checkmate, USSearch
- **Link:** https://suppression.peopleconnect.us/
- **Process:** Enter email → click verification link → enter name + DOB → select your listing(s) → set to *Suppressed*.
- **Verification:** Email + date of birth.
- **Timeline:** ~48h. **No confirmation email is sent** — recheck the four sites manually after 2 days.
- **Note:** PeopleFinders search is Intelius-powered; this usually clears it too, but verify PeopleFinders separately (Tier 2).

### 2. ZoomInfo — already confirmed live (work email + phone)
- **Link:** https://privacy.zoominfo.com/privacy-center
- **Process:** Search name + employer (WDG Real Estate Partners) → select profile → request removal → verify email.
- **Also do:** the "Do Not Sell" opt-out on the same portal.
- **Timeline:** a few business days. Re-indexes from public sources — recheck quarterly.
- **Priority reason:** Confirmed exposing work email pattern + phone; feeds other B2B brokers.

### 3. Radaris — free, no account needed
- **Link:** https://radaris.com/control-privacy
- **Process:** Enter name + city + state + listing URL → confirm it's you → *Start removing* → CAPTCHA → Submit → click link in verification email.
- **Timeline:** reflects in ~24h. If more than one record, email their support to remove all.

### 4. TruePeopleSearch — free
- **Link:** https://www.truepeoplesearch.com/removal
- **Process:** Find your record, copy its URL, submit removal, confirm the code.

### 5. FastPeopleSearch — free (same operator as TruePeopleSearch)
- **Link:** https://www.fastpeoplesearch.com/removal
- **Process:** 3-step form; verify by phone/email code. Do this right after #4.

### 6. ThatsThem — free
- **Link:** https://thatsthem.com/optout
- **Process:** Search listing → submit opt-out. 3–7 days. (Often exposes email/IP — worth doing.)

### 7. Nuwber — free
- **Link:** https://nuwber.com/removal
- **Process:** Search name + city + state → *View Profile* → *Remove My Info* → paste profile URL → enter email → confirm via email link. ~72h.

### 8. ClustrMaps — free, near-instant
- **Link:** https://clustrmaps.com/bl/opt-out
- **Process:** Enter name, email, listing URL, address → check the boxes for data to delete → *Apply*. Clears almost immediately.

---

## Tier 2 — Free but each needs its own verification step

### 9. Spokeo
- **Link:** https://www.spokeo.com/optout
- **Process:** Paste your profile URL + email → click confirmation link in email.

### 10. Whitepages
- **Link:** https://www.whitepages.com/suppression-requests
- **Process:** Find listing → copy URL → submit suppression → **verify via automated phone call** that reads back a code. (Have a phone ready.)

### 11. BeenVerified
- **Link:** https://www.beenverified.com/app/optout/search
- **Process:** Search record → select it → verify via email link.

### 12. PeopleFinders
- **Link:** https://www.peoplefinders.com/opt-out
- **Process:** Search → select record → verify via email. Confirm it's gone after the PeopleConnect suppression too.

---

## Tier 3 — Slow / higher-friction (do last)

### 13. MyLife — slowest, most persistent
- **Links / contacts:** email **privacy@mylife.com** (cc membersupport@mylife.com, customercare@mylife.com); phone **1-888-704-1900** (Mon–Fri 6a–5p PT).
- **Process:** Send full name + current address + profile URL, requesting deletion.
- **Timeline:** 3–14 business days.
- **Watch:** They will pitch a paid "reputation" membership. You don't need it — free removal is your right. Decline and restate the deletion request.

---

## Tier 4 — Blocked pending your input (can't run without old identifiers)

### 14. Have I Been Pwned (breach exposure) — needs OLD email addresses
- **Link:** https://haveibeenpwned.com/
- **Process:** Enter each old email → note which breaches list it → **rotate any still-used passwords and turn on 2FA** for reused ones.
- **Blocker:** Only your current gmail is known. Provide old/college-era emails.

### 15. Wayback Machine + archive.today — needs OLD Facebook / Myspace usernames
- **Wayback:** http://web.archive.org/web/*/facebook.com/<old_username> and .../myspace.com/<old_username>
- **archive.today:** https://archive.ph/ (search each old profile URL)
- **CDX bulk check:** `http://web.archive.org/cdx/search/cdx?url=facebook.com/<old_username>&output=json`
- **If a snapshot exists and you want it gone:** email **info@archive.org** requesting exclusion (Wayback), or use archive.today's removal contact.
- **Blocker:** Need the old FB vanity URL and Myspace handle. (These sites and the Wayback CDX API are also blocked from this sandbox — run in a normal browser.)

---

## Ongoing coverage decision
DIY quarterly reruns of Tiers 1–3 are realistic (~1–2 hrs/quarter). If that's not worth your time, a paid service (**DeleteMe** or **Optery**) covers most of these plus dozens more brokers automatically. Recommendation in the Findings Memo.
