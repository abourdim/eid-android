# Play Store listing — Eid News Network (عيد)

Draft copy for Google Play Console "Main store listing" page. Play Console accepts separate translations per language — upload all three.

---

## Metadata (common to all languages)

- **Package name**: `org.workshopdiy.eid`
- **Category**: `Books & Reference` (primary), `Education` (secondary if allowed)
- **Tags**: Islamic studies, Arabic, trilingual, education, al-Ghazali
- **Contact email**: `abdelhak.bourdim@gmail.com`
- **Website**: `https://workshop-diy.org`
- **Privacy policy URL**: REQUIRED — host a simple page (see template at end of this file).
- **Content rating**: Everyone (no violence, no gambling, no mature content).
- **Ads**: No.
- **In-app purchases**: No.
- **Data safety**: No data collected, no data shared.

---

## Arabic (ar) — primary

### App name (≤30 chars)
```
عيد
```

### Short description (≤80 chars)
```
تهنئة عيد مبارك + عدّاد — فن إسلامي مع دراما هاكرز
```

### Full description (≤4000 chars)
```
🌙 عيد

بطاقة تهنئة عيد مبارك بصفحة واحدة بأسلوب نشرة أخبار تلفزيونية مباشرة — خط إسلامي يلتقي دراما القرصنة. التاريخ الهجري، عدّاد العيد، شريط أخبار، تسلسل طرفية، زر مشاركة.

— من workshop-diy.org
```

---

## English (en)

### App name
```
Eid News Network — Eid News Network
```

### Short description
```
Eid Mubarak greeting + countdown — Islamic art meets hacker drama
```

### Full description
```
🌙 Eid News Network

A single-page Eid Mubarak greeting card styled as a live TV news broadcast — Islamic calligraphy meets hacker drama. Hijri date, Eid countdown, scrolling ticker, terminal sequence, share button. Personalize with `?to=Name`.

— From workshop-diy.org
```

---

## French (fr)

### App name
```
Eid News Network — Réseau News Eid
```

### Short description
```
Vœux Aïd Moubarak + compte à rebours — art islamique et drame hacker
```

### Full description
```
🌙 Réseau News Eid

Carte de vœux Aïd Moubarak monopage stylisée comme un journal TV en direct — calligraphie islamique et drame hacker. Date hijri, compte à rebours de l'Aïd, ticker, séquence terminal, bouton de partage.

— De workshop-diy.org
```

---

## Graphics needed (minimum)

| Asset | Size | Source |
|---|---|---|
| App icon | 512×512 PNG | `store-assets/play-store-icon-512.png` (regenerate per book) |
| Feature graphic | 1024×500 PNG | `store-assets/feature-graphic.png` (render from `feature-graphic.html`) |
| Phone screenshots | min 2, 320–3840px, 16:9 portrait | Capture from emulator / real device |
| 7" tablet screenshots (optional) | min 2, 1024×600+ | Run emulator with tablet profile |

Screenshots to capture (book-specific — adjust list to actual app screens):
1. Home / cover / introduction
2. Main content navigation
3. Reading or interaction mode
4. Quiz or self-assessment (if applicable)
5. Theme switch (optional — shows the 3 variants)

---

## Privacy policy template

Copy to a public page (GitHub Pages works). Change email + date.

```
Privacy Policy — Eid News Network
Last updated: 2026-04-27

The Eid News Network app does not collect, store, transmit, or share any personal
data. All content is bundled with the app and runs entirely on your device.
The app does not use analytics, advertising networks, crash reporters, or
third-party SDKs.

The app requires no special permissions beyond internet access, which is
used only to load the occasional external link (e.g. workshop-diy.org) if
you tap it — never silently in the background.

If you have questions, contact: abdelhak.bourdim@gmail.com
```
