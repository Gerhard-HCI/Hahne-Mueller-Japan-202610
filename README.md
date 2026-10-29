# R.Hahne-A.Mueller-Japan-2026-10

## Changelog

Changes to `index.html`, newest first. Source of truth: the Google Sheet
"HCI Canvas/Program for Richard HAHNE 2026/10" (CANVAS and Confirmation tabs).

### 2026-10-29
- **Taxi card.** Stop cards now carry four buttons — Maps / Nav / Taxi / Copy.
  Taxi opens a full-screen card in Japanese (venue name, address and
  「ここまでお願いします」) to show a driver. Backed by a new `JA_DIR` directory of
  31 venues; each address cross-checked against Google's romanised address and
  postcode. Stops without an entry show a disabled Taxi button rather than a
  guess — currently Yakitori Kouun and Tachigui Sushi Yusho, whose town
  readings could not be confirmed. No `q:` value was altered.
- **Utilities · Dining Etiquette** extended with a new "At the counter" card:
  chopsticks, photography, the chef's pace, soy and wasabi, pouring, phones,
  the oshibori, and finishing a course.
- **Utilities · new "Getting Around" section** after the etiquette cards:
  the stop buttons, the taxi card, shinkansen, luggage transfers, IC cards,
  taxis, private cars, train manners, escalators and last trains.

### 2026-10-28
- **Noguchi Naohiko Sake Institute · Sat 7 Nov: tasting moved 16:00 → 15:00.**
  Updated the stop (time, subtitle, notes, alert) and the Confirmed wish list.

### 2026-10-26
- **Guest notes from Richard's questions and the reservation notes** (not the sheet):
  - Dress codes: Chez Calvert (strictest: smart long-sleeved shirt, dress
    shoes, jacket advisable); Kaiseki Suetomi and Sushi Ikkou (smart shirt and
    trousers). Added to each stop and as a new bullet on the Attire card.
  - Ajimori: give the reservation name as RICHARD MORIKAWA on arrival.
  - Sumiyaki Unafuji: arrive on time; the table is released after 10 minutes.
  - Quick Reference: "Cash is useful" replaced by "Payments & cash"
    (cards, ramen ticket machines, 7-Eleven / Japan Post ATMs).
- Added `CLAUDE.md` with the update workflow and this changelog rule.
- **Restored the full page.** Commit 9a3163a had replaced `index.html` with a
  plain-text stub, removing the encrypted statement and all map links. Rebuilt
  from 84f4e14 (10 Oct), with the statement and all 35 map links unchanged.
- **Sumiyaki Unafuji · Tue 10 Nov lunch: Requested → Confirmed.** Now 12:30,
  table for two (previously ~12:00, to be requested). Moved from the Requested
  to the Confirmed wish list.
