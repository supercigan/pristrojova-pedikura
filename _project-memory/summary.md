# Projekt: Přístrojová Pedikúra — Hana Pančochová

**Datum zahájení:** 2026-03-24

---

## Co je hotovo

- Vytvořena struktura projektu (`_project-memory/`, `_temp-screenshots/`, `.gitignore`)
- Prošli jsme původní web (webnode) — získali jsme všechny reálné informace
- Schváleny fonty a barevná paleta
- Vytvořen kompletní jednostránkový web (`index.html`)

### Schválený design
- **Font nadpisy:** Fraunces (moderní optický serif)
- **Font text:** Plus Jakarta Sans
- **Paleta "Teplá hlína":**
  - Pozadí: `#FDFAF6`
  - Primární: `#8B6F6A` (dusty mauve)
  - Gold akcent: `#C9A882`
  - Sekce alt: `#F2EBE4`
  - Text: `#2E1F1C`

### Reálný obsah webu
- **Název:** Hana Pančochová — profesionální přístrojová pedikúra a manikúra
- **Adresa:** Dvořákova 645, Uherské Hradiště
- **Telefon:** +420 603 827 767
- **Email:** hapan11@centrum.cz
- **Provozní doba:** Po–Pá 7:30–18:00 (dle objednávek)
- **Služby:** Přístrojová pedikúra, Manikúra, Nehtová modeláž, Regenerační zábaly, Peeling, Parafinový zábal, Masáž nohou, Dárkové poukazy
- **Kosmetika:** ATOK, Batavan, Callusan

### Struktura webu (index.html)
1. **Nav** — fixed, logo HP monogram, mobile menu
2. **Hero** — fullheight, tagline, CTA (tel + služby), vizuální panel
3. **O nás** — text Hany, filozofie, animovaný blob tvar, quote karta
4. **Služby** — 6 karet (3×2 grid), SVG line ikony, featured card
5. **Proč my** — 2-col layout, 4 why-items, brand tagy kosmetiky
6. **Provozní doba** — tabulka hodin, CTA karta, email karta
7. **Kontakt** — 4 info karty + kontaktní formulář
8. **Footer** — logo, nav linky, copyright

### Technické detaily
- Single HTML file (CSS + JS embedded)
- IntersectionObserver scroll reveal animace
- Mobile responsive (breakpoints 900px, 580px)
- Vanilla JS (bez závislostí)
- Formulář: placeholder handler (bez backendu)

---

## Co se řeší

- Uživatel ještě neviděl web v prohlížeči — čeká se na feedback
- Formulář nemá backend — zatím jen UI handler

---

## Důležitá rozhodnutí

- Původní brand materiály (sage green / spa palette) byly z jiného projektu — NEPOUŽÍVAT
- Zvolena originální paleta "Teplá hlína" (dusty mauve + caramel)
- Web je čistý HTML bez frameworků — snadná správa

---

## Příští kroky

- Zobrazit web v prohlížeči a screenshotovat
- Čekat na feedback od uživatele
- Případně: ceník sekce, galerie fotek, Google Maps embed
- Případně: backend pro formulář (mailto: nebo Formspree)
