# Verification record — 3 November 2026

These are classroom checks, not accessibility or clinical certification.

## PRD acceptance checks

| ID | Result | Evidence / limit |
| --- | --- | --- |
| R1: EN/KY/RU | Implemented; interaction checked | All 104 main translation keys exist in every language. All five pages rendered in all three languages. KY selected on Home, then Medical Services followed; KY persisted. Translation-review labels present. |
| R2: consultation fields → WhatsApp | Prototype implemented and checked | Missing fields show an error. Fictional sample creates name/DOB/phone/service/team preference text and a percent-encoded `wa.me/00000000000?text=...` link. Future DOB rejected. Escape closes the dialog and clears draft. No real booking or message sent. |
| R3: staff names/photos/role/two-sentence bio | Partial, pending client materials | Three source-supported staff summaries with role and two sentences. Photo placeholders and complete-team pending notice are explicit. Real photos, approved full roster and final bios remain open. |
| R4: brand / readable hierarchy | Implemented; selected pairs checked | Light background, orange/yellow accents, grey text, limited red, Manrope/Noto Sans stack. Selected primary text/button contrast pairs exceed 4.5:1. |
| R5: Instagram | Placeholder only | Media block explains the pending official profile URL. No fake integration, account or post. |

## Browser checks performed

- All five pages in English, Kyrgyz and Russian: 15 desktop renders, 1,348 CSS-pixel content viewport. No horizontal overflow detected.
- All five pages in all three languages: 15 narrow responsive iframe renders, 320-pixel outer width / 305-pixel content viewport with scrollbar. `scrollWidth == clientWidth` in all 15 cases.
- Visual inspection of English desktop Home, Russian desktop Contact and Russian mobile Home (390-pixel outer iframe / 375-pixel content viewport). No visible clipping in inspected views.
- Mobile Menu click expands the translated navigation.
- Keyboard Escape closes booking dialog; native dialog manages modal focus; focus is restored to the initiating control. Visible focus styles are defined. A complete manual screen-reader audit was not performed.
- English form: blank submit rejected; fictional sample generates a correctly encoded WhatsApp draft and visibly states no appointment is booked.
- Russian form: future date rejected; valid fictional sample produces Russian field labels; Escape clears the temporary message.
- The external WhatsApp page was not opened or submitted. The recipient is intentionally invalid. Actual message delivery is outside scope.

## Static checks performed

- `node --check hw6/script.js`: passed.
- All three language dictionaries have the same 104 keys; all 15 render combinations produced content without undefined values.
- Five generated HTML pages have one H1 each and unique IDs.
- Local link, script, stylesheet and image targets in all five pages exist.
- ZIP integrity and required-file presence checked after packaging.

| Foreground / background | Contrast |
| --- | --- |
| `#303330` / `#ffffff` | 12.79:1 |
| `#555b57` / `#ffffff` | 6.95:1 |
| `#95500b` / `#fcf8ef` | 5.78:1 |
| `#2f3028` / `#f7a124` | 6.40:1 |
| `#6a6d65` / `#ffffff` | 5.27:1 |

## Not run / pending

Lighthouse and slow-network profiling, real-device touch testing, exhaustive contrast and screen-reader audits, clinic medical/translation review, approved photos, real contact confirmation and GitHub Pages deployment. No performance score is invented. These files are ready to upload; publication must be checked after uploading to the student's repository.
