# Projekt: Přístrojová Pedikúra — Hana Pančochová

**Datum zahájení:** 2026-03-24

---

## Co je hotovo

- Vytvořena struktura projektu (`_project-memory/`, `_temp-screenshots/`, `.gitignore`)
- Prošli jsme původní web (webnode) — získali jsme všechny reálné informace
- Schváleny fonty a barevná paleta
- Vytvořen kompletní jednostránkový web (`index.html`)
- Projekt pushnut na GitHub: https://github.com/supercigan/pristrojova-pedikura

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
1. **Nav** — fixed, logo HP monogram, mobile menu, "Objednat se" → #kontakt
2. **Hero** — fullheight, tagline, CTA → #kontakt, velký otisk chodidla (sole + 5 prstů)
3. **O nás** — text Hany, filozofie, animovaný blob tvar (6-lístkový květ)
4. **Služby** — 6 karet (3×2 grid), intuitivní SVG ikony:
   - Přístrojová pedikúra → otisk chodidla
   - Manikúra → lahvička s lakem
   - Nehtová modeláž → pilník u prstu
   - Regenerační zábaly → list s kapkami
   - Peeling & Parafinový zábal → svíčka s plamenem
   - Masáž nohou → dvě dlaně s vlnovkami
5. **Proč my** — 4 pilíře, brand tagy kosmetiky
6. **Provozní doba** — tabulka, CTA karta s tel. číslem
7. **Kontakt** — 4 info karty + kontaktní formulář
8. **Footer** — logo, nav linky, copyright

### Úpravy provedené po vytvoření
- Smazán quote blok v sekci O nás
- Tlačítka "Zavolat a objednat" a "Objednat se" → scrollují na #kontakt
- Nadpis "Na kvalitě záleží" (zjednodušen)
- Ikona u dárkových poukazů → dárková krabička s mašlí
- Ikona v hero → velký otisk chodidla (120×120 SVG)
- Ikona v about blob → 6-lístkový květ (nahrazen nevhodný tvar)
- Watermark: "Demo verze — Tomáš Smolík", opacity 0.09, fixed overlay, id="demo-watermark"

### Technické detaily
- Single HTML file (CSS + JS embedded)
- IntersectionObserver scroll reveal animace
- Mobile responsive (breakpoints 900px, 580px)
- Vanilla JS (bez závislostí)
- Formulář: placeholder handler (bez backendu)

### GitHub
- Repo: https://github.com/supercigan/pristrojova-pedikura
- Username: supercigan
- Credentials: Windows Credential Manager (automaticky dostupné)

---

## Co se řeší

- Web zatím bez reálných fotek (placeholdery / prázdná místa)
- Formulář nemá backend — zatím jen UI handler

---

## Důležitá rozhodnutí

- Původní brand materiály (sage green / spa palette) byly z jiného projektu — NEPOUŽÍVAT
- Zvolena originální paleta "Teplá hlína" (dusty mauve + caramel)
- Web je čistý HTML bez frameworků — snadná správa
- Všechna CTA tlačítka vedou na #kontakt, ne na tel: link (lepší UX na desktopu)

---

## Příští kroky

- Přidat reálné fotky interiéru/ošetření
- Doplnit ceník (pokud ho Hana poskytne)
- Backend pro kontaktní formulář (Formspree nebo mailto:)
- Případně: Google Maps embed v sekci kontakt
- Před nasazením: smazat watermark (odstranit `<div id="demo-watermark">`)
