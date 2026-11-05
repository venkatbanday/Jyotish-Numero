# ✨ Jyotish Numero – Free Horoscope & Numerology App

A free, single-page web app for **Vedic horoscope** and **numerology**. Enter your details and instantly get your numbers, name analysis, mobile number analysis, birth chart and life-period (Dasha) timeline.

**Built by Venkateswara Rao Banday**

---

## Features

| Area | What you get |
|---|---|
| **Core numerology** | Driver (Mulank), Conductor (Bhagyank), Chaldean name number, soul urge, personality number |
| **Driver–Conductor combination** | Star rating, meaning, and life/career insights for all 81 combinations |
| **Divine meaning** | Ruling planet, deity, mantra, meaning, remedy, lucky colour, day and gemstone for Driver and Conductor |
| **Lo Shu grid** | Visual grid with missing numbers to strengthen |
| **Name correction** | Spelling variants whose total suits your Driver and Conductor numbers |
| **Mobile number analysis** | Clear Suitable / Partly suitable / Not suitable verdict with a score, number meaning, divine support, pair-by-pair reading and best-suited totals |
| **Chinese numerology** | Bagua Shuzi (8-star) analysis of mobile numbers, plus Chinese zodiac and traditional lucky numbers |
| **Missing-number remedies** | Step-by-step remedies for every number missing from your Lo Shu grid |
| **Vedic birth chart** | Lagna (Ascendant), Moon sign (Rashi), Sun sign, Nakshatra and pada (sidereal, Lahiri ayanamsa) |
| **Vimshottari Dasha** | Full life-period timeline with the currently running period highlighted |
| **Place search** | Search any town or city worldwide; latitude, longitude and time zone (including daylight saving) are filled automatically |

## Privacy

All calculations run **in your browser**. Your name, birth details and mobile number are never uploaded or stored. The only network request is the optional place-of-birth search (see below).

## Run it

It is a single file with no build step.

- **Locally:** download `index.html` and open it in any modern browser.
- **On GitHub Pages:**
  1. Create a repository and upload `index.html` and this `README.md`.
  2. Go to **Settings → Pages**.
  3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then save.
  4. Your app goes live at `https://<your-username>.github.io/<repository-name>/`.

## How it works

- **Numerology:** Chaldean letter values; Driver = birth day reduced to a single digit; Conductor = all digits of the full birth date reduced to a single digit.
- **Combination data:** Driver–Conductor, life/career and mobile-pair texts come from the `81 Combinations` spreadsheet embedded in the page.
- **Astronomy:** Sun and Moon longitudes use low-precision series; the Ascendant is computed from sidereal time and your latitude/longitude. Sidereal positions use the Lahiri ayanamsa.
- **Place search:** uses the free [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api), which needs an internet connection. If it is unavailable, enter latitude, longitude and time zone manually.

## Limitations

- The chart currently covers Sun, Moon and Lagna only. Other planets, house-wise predictions and compatibility matching are not yet included.
- The Moon position is accurate to well under one degree, so a birth within a few minutes of a sign or Nakshatra boundary may fall on the wrong side.
- Name-correction and "friendly number" rules follow common traditional Chaldean tables and may differ from other schools.

## Roadmap ideas

- All nine planets and a visual chart (North/South Indian style)
- House-wise predictions and Yogas
- Marriage compatibility (Kundli matching)
- Hindi and Telugu language support
- Downloadable PDF report

## Disclaimer

This app is for **guidance, self-reflection and entertainment only**. It is not a substitute for professional medical, legal, financial or psychological advice.

## Credits

Created by **Venkateswara Rao Banday**. Free to use and share.
