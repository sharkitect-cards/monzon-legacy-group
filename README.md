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
- **Type:** Playfair Display for the name (matches the serif on their printed
  card); Montserrat for UI.
- **Card standard:** one button only, opens the QR. No `saveContact()`,
  no `.vcf` anchor, no `qr-btn`. Verified at runtime, not just by grep.
- **QR:** rounded modules, deep-green vertical gradient `#0E2016` to `#224F33`,
  seal disc at 22.5% width, ECC-H. Decode-verified at 100 / 50 / 25 / 15 % scale.

- **Website link is the personal agent page**, not the root domain:
  `https://www.theiln.agency/inez-angelica-monzon` (client-specified, 2026-08-27).
  Do NOT "simplify" it to ilnagency.com — that drops his page.

## Open items

- `hero.jpg` is upscaled from a low-resolution screenshot of their printed
  card. **Replace with the original photo file** when available.
- CA licence number not printed — could not be read cleanly from the source
  image and was not guessed. Add once confirmed.
- Social links and a booking link are pending Christian's answer.

Built by Sharkitect Digital.
