# Tímaverkefni 2

Búðu til vefsíðu og veldu eina af eftirfarandi greinum til að setja í vefsíðuna. (_Ef tími vinnst til má setja myndir í vefsíðuna._) 

1. val: [Nikulás Kópernikus](val-1-kopernikus.md)
2. val: [Var Sókrates örugglega til?](val-2-sokrates.md)
3. val: [Hvað er gerfigreind?](val-3-gervigreind.md)


> Hannaðu vefsíðuna með mismunandi viðmiðum (_breakpoints_).  <br>
Uppsetning þín er að öðru leyti frjáls og miðast við efnisval þitt.

#### Efnisyfirlit (_nav_), 

- skjástærð undir 600px
   - `<nav>` Í efnisyfirliti eru 4 tenglar, notaðu css skipunina `flex-flow: column eða grid-template-columns: 1fr` 
- skjástærð 600px og stærri
   - `<nav>` Í efnisyfirliti eru 4 tenglar, notaðu css skipunina `flex-flow: row wrap eða grid-template-columns: repeat(4, 1fr)` 

#### Farsímaskjáir (_mobile phone screen_), skjástærð undir *600px* 

- `<header>` Fyrirsögn
- `<main>` (_utanum article og aside_)
- `<article>` Meginmálstextinn kemur hér
- `<aside>` Efnisorð kemur hér
- `<footer>` Heimildaskrá + &copy; 2025 VEFÞ2VG, tímaverkfni 2. + nafnið þitt

#### Spjaldtölvur / Fartölvur *600px - 959px*

- `<nav>` 
- `<header>` 
- `<main>`
   - `<article>` `<aside>` hlið við hlið í hlutfallinu 3fr 1fr
- `<footer>`

#### Borðtölvur *960px* og stærri

- Sama uppsetning og hér að ofan nema á borðtölvuskjáum sem eru stærri en 1280px (_max-width_) á að miðjusetja `body`

---

### Námsmat

-   3% Farsímar: Undir 600px
-   3% Spjaldtölvur: 600px - 959px
-   3% Borðtölva: 960px og stærri 
-   3% Efnisorð í _'Aside'_
-   3% Tenglar í efnisyfirliti og heimildir í footer

---

### Verkefnaskil í Innu > .zip skrá 

-   Tímaverkefni 2 
-   Æfingaverkefni 4 

*Gangi þér vel* 👍
