# FONTLOG — Gloss Manuscript

## 1.005 — 2026-07-18

- Applied a uniform -28-unit-per-em reduction to every alphabetic advance in Regular, Italic, and Bold.
- Tightened base spacing throughout unkerned Word text, including `h–i` in “This,” `f–a` and `a–l` in “fall,” and the overall texture of “Article I will say.”
- Removed the earlier Gloss-specific pair compensations; the compactness now comes from the alphabetic spacing model rather than isolated pairs.
- Left word-space and figure widths unchanged.

## 1.004 — 2026-07-18

- Replaced the overly broad Garamond-advance model with outline-aware spacing for the directly traced alphabet and figures.
- Preserved each Gloss glyph's original traced ink width while matching both its left and right optical sidebearings to Garamond 2.40.
- Corrected excessive unkerned gaps after narrow traced forms, including `f` in “funds transfers,” and recurring openness after `h`, `u`, `n`, `i`, `l`, `m`, and `o`.
- Recalibrated the residual pair corrections and made base spacing work when applications such as Word do not apply pair kerning.

## 1.003 — 2026-07-18

- Added targeted optical kerning corrections for `h–i`, `a–i`, `a–n`, `i–c`, and `c–i` after in-context review of “This,” “The Claimant’s,” and “Official.”
- Retained the Garamond 2.40 per-glyph advances, left sidebearings, and word-space width.
- Rebuilt and revalidated the desktop fonts, webfonts, and PDF specimens.

## 1.002 — 2026-07-17

- Matched horizontal metrics to the installed Windows Garamond 2.40 family (`GARA.TTF`, `GARAIT.TTF`, and `GARABD.TTF`).
- Matched per-glyph advances, left sidebearings, word-space width, and every applicable style-specific kerning pair.
- Preserved the Gloss Manuscript outlines; no Garamond contour, hinting program, bitmap, or font program is included.
- Kept ligature substitutions width-compatible with the corresponding Garamond character sequences.
- Rebuilt and revalidated the desktop fonts, webfonts, and PDF specimens.

## 1.001 — 2026-07-17

- Tightened the core uppercase, lowercase, and figure sidebearings in Regular, Italic, and Bold.
- Applied additional optical spacing corrections to narrow letters such as `i`, `l`, and `j`.
- Preserved the corrected period baseline and all OpenType behavior.
- Rebuilt and revalidated the desktop fonts, webfonts, and PDF specimens.

## 1.000 — 2026-07-17

- Released Regular, Italic, and Bold in TTF and WOFF2 formats.
- Added extended Latin coverage and combining-mark positioning.
- Added small caps, ligatures, kerning, oldstyle and lining figures, superior and inferior figures, and fractions.
- Added long-reading and family specimen PDFs.
- Corrected the optical baseline position of the period in all three styles.
- Passed structural, cmap, composite, serialization, FreeType, and OpenType shaping checks.
