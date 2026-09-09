# 🏦 Silicon — Bank App Landningssida (Flexbox + Grid-variant)

En responsiv, en-sidig landningssida för en mobil bank-app, byggd i ren HTML och CSS utifrån en Figma-designmall.

---

## 📖 Om projektet

Det här projektet bygger en komplett, responsiv landningssida utan ramverk och utan JavaScript.

Projektet demonstrerar ett komplett arbetsflöde från design till kod:
- Design hämtad från en Figma-mall och omsatt till semantisk HTML/CSS
- Responsiv layout i tre steg (desktop, tablet, mobil), byggd efter tre separata breakpoint-varianter i källdesignen
- Interaktiva element (hamburgermeny, FAQ-accordion) byggda med ren HTML/CSS istället för JavaScript
- Layouttekniken väljs efter vad som passar bäst för varje sektion — Flexbox för enklare rader/kolumner, CSS Grid för äkta rutnät
- Design tokens (färger, typografi, skuggor) som CSS-variabler, hämtade direkt från källdesignens designsystem

---

## 🚀 Kom igång

Inga installationssteg eller beroenden behövs.

### 1. Klona projektet
```bash
git clone https://github.com/<ditt-användarnamn>/silicon-landningssida.git
cd silicon-landningssida
```

### 2. Öppna sidan
```bash
open index.html
```
Eller dubbelklicka på `index.html` i valfri webbläsare.

---

## 📁 Projektstruktur

```
silicon-landningssida/
├── index.html              Sidans HTML-struktur
├── styles.css               All styling, design tokens och responsiv layout
├── bilder/                  Alla bilder och ikoner
└── README.md                 Dokumentation (den här filen)
```

---

## ✨ Egenskaper

| Egenskap | Beskrivning |
|---|---|
| Responsiv | Tre steg: desktop, tablet (≤768px), mobil (≤480px) |
| Ingen JavaScript | Hamburgermeny och FAQ-accordion byggda med ren HTML/CSS |
| Flexbox + CSS Grid | Grid för rutnät (logotyper, ikonrutnät, testimonial-kort, FAQ-kontaktrutor), Flexbox för övriga rader/kolumner |
| Tillgänglighet | Synlig fokusmarkering, stöd för `prefers-reduced-motion` |
| Design tokens | Färg-, typografi- och skuggskala som CSS-variabler |

---

## 🎨 Källa

Designen är byggd utifrån Figma-mallen **"Silicon Design Template"**.

## ⚠️ Kända begränsningar

Källdesignen innehåller inte alla sektioner i alla skärmstorlekar — medvetna designval, inte buggar:

| Sektion | Döljs vid |
|---|---|
| App Features | ≤768px |
| Testimonials Section | ≤768px |
| Logos / Brands | ≤480px |

---

## 🛠️ Teknikstack

| Komponent | Beskrivning |
|---|---|
| HTML5 | Semantisk markup |
| CSS3 | Flexbox, CSS Grid, `clamp()`, `aspect-ratio`, CSS custom properties |
| Manrope (Google Fonts) | Typsnitt |

---

## 👥 Team

- Leo
- Nina
- Sara
- Peter

Arbetet delas upp sektion för sektion.
