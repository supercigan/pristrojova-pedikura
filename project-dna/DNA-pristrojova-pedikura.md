# DNA — Přístrojová Pedikúra (Hana Pančochová)

Soubor zachycuje vizuální a strukturální DNA tohoto projektu.
Slouží jako reference pro budoucí projekty — aby byly odlišné.

---

## Barevná paleta

| Proměnná    | Hodnota     | Použití                        |
|-------------|-------------|--------------------------------|
| `--bg`      | `#FDFAF6`   | pozadí stránky (teplá krémová) |
| `--primary` | `#8B6F6A`   | hlavní barva (starorůžová/mauve) |
| `--primary-d` | `#6E5350` | hover stav primary             |
| `--gold`    | `#C9A882`   | zlaté akcenty                  |
| `--gold-l`  | `#E2CDB4`   | světlé zlaté plochy            |
| `--section` | `#F2EBE4`   | sekční pozadí                  |
| `--text`    | `#2E1F1C`   | hlavní text (tmavě hnědá)      |
| `--text-m`  | `#6B4F4A`   | sekundární text                |
| `--border`  | `#E4D8D0`   | okraje, bordery                |

**Celkový pocit palety:** teplé neutrály, zemitá starorůžová, zlaté akcenty — "luxury wellness"

---

## Typografie

- **Nadpisy:** `Fraunces` — serif, weight 300–400, kurzíva jako akcent
- **Tělo:** `Plus Jakarta Sans` — sans-serif, weight 300–600
- **Styl:** elegantní, editorial, lehký
- **Section label:** small caps + čárka vlevo (28px wide, zlatá)

---

## Layout & struktura

- **Max šířka kontejneru:** 1140px, centrovaný `margin-inline: auto`
- **Hero:** 2 sloupce 50/50, text vlevo, vizuál vpravo
- **Hero vizuál:** diagonální řez pomocí `clip-path: polygon(8% 0%, 100% 0%, 100% 100%, 0% 100%)`
- **Navigace:** fixed, glassmorphism — `backdrop-filter: blur(12px)`, výška 68px
- **Karty:** `border-radius: 12px`
- **Tlačítka:** pill shape — `border-radius: 100px`
- **Scroll reveal:** fadeIn + `translateY(28px)`, 4 úrovně zpoždění (0.1–0.4s)
- **Přechody:** `0.35s cubic-bezier(0.4, 0, 0.2, 1)`

---

## Sekce (pořadí)

1. Nav — fixed, glassmorphism
2. Hero — split 50/50 s diagonálním vizuálem
3. Služby — karty v gridu
4. O mně
5. Ceník
6. Galerie / reference
7. Kontakt + footer

---

## Ikonografie

- **Why sekce & kontakt:** Lucide icons (CDN `unpkg.com/lucide@latest`) — `flower-2`, `heart-handshake`, `users`, `shield-check`, `map-pin`, `phone`, `mail`, `clock`, `gift`
- **Servisní karty:** žádné ikony — místo nich číslování **01–06** (`Fraunces`, italic, weight 300, barva `--gold`)
- **Hero vizuál:** bez SVG monogramu — pouze info-badges (provozní doba, adresa)
- Inicializace Lucide: `lucide.createIcons()` na konci `<script>` bloku

---

## Vizuální styl celkově

- Teplé neutrály + zemitá starorůžová + zlaté akcenty
- Serif + sans kombinace (editorial feminine)
- Jemné stíny, žádné ostré kontrasty
- Minimalistický "luxury wellness" feeling
- Číslované karty místo ikon — čistší, editoriálnější look
- Žádné fotografie v hero — pouze textové badges

---

## Archetype

**Luxury wellness / feminine editorial**
Vhodné pro: kosmetika, pedikúra, manikúra, masáže, wellness studia.
Nevhodné pro: tech, sport, gastro, industriální obory.
