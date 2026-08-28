# Monzon Legacy Group — Digital Business Card

Christian & Angelica Monzon, Executive Partners, Monzon Legacy Group
(Impact Leadership Network). Insurance-licensed; no securities activity
represented on this card.

**Live:** https://cards.sharkitectdigital.com/monzon-legacy-group/
**vCard / NFC target:** https://cards.sharkitectdigital.com/monzon-legacy-group/contact.vcf

## Build notes

- **Brand green `#12291D`** sampled directly from their printed business card
  (dominant colour, 77,625 px). Not guessed.
- **Seal** rebuilt as a clean raster from their existing circular MLG mark —
  same double ring, same two diagonal breaks with the clasp step, same bold
  letterforms. Their logo, built true; not a redesign.
- **Layout:** medallion — full-bleed photo banner, seal in a white disc
  straddling the lower edge. The same disc repeats in the QR centre.
- **Hero** is `MLG - Christian and Angelica.png` (client-supplied, 2026-08-27),
  cropped 95 px off the left edge because the source has a **cut-off MLG badge**
  bleeding off the top-left corner (measured: x 0–83, y 32–190). The card already
  carries the full seal in the medallion, so the partial one is dropped, not kept.
  Frame is 1272×978 (1.30) to keep the suit and blazer in shot.
- **Saved-contact photo** is the circular `MLG - Headshots.png`, flattened onto
  white (the PNG corners are transparent) and embedded in the vCard at 800×800.
  Phones mask contact photos to a circle, so the corners never show; on any app
  that renders square it reads as a white-background studio portrait.
- **Type:** Playfair Display for the name (matches the serif on their printed
  card); Montserrat for UI.
- **Card standard:** one button only, opens the QR. No `saveContact()`,
  no `.vcf` anchor, no `qr-btn`. Verified at runtime, not just by grep.
- **QR:** rounded modules, deep-green vertical gradient `#0E2016` to `#224F33`,
  seal disc at 22.5% width, ECC-H. Decode-verified at 100 / 50 / 25 / 15 % scale.

- **Website link is the personal agent page**, not the root domain:
  `https://www.theiln.agency/inez-angelica-monzon` (client-specified, 2026-08-27).
  Do NOT "simplify" it to ilnagency.com — that drops his page.

- **Tagline provenance:** "Protect who you love most." is OURS, not theirs.
  Their site has the phrase inside a sentence — "Providing you the guidance
  through life's most important choices, so you can protect what you love most."
  — as body copy, once, never as a tagline; their printed card has no tagline at
  all. We lifted the tail and changed *what* to *who* (2026-08-27, CEO): in life
  insurance the subject is people, and "what" reads as possessions. **Christian
  has not approved this line** — present it as a suggestion, not as his own words.

## Open items

- CA licence number not printed — could not be read cleanly from the source
  image and was not guessed. Add once confirmed.
- Social links and a booking link are pending Christian's answer.

Built by Sharkitect Digital.
