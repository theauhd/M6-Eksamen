# Løbeguide - Eksamensprojekt

## Indhold:
- 8+ HTML-sider: index, kategorier, knæ, pronation, carbon løbesko, neutral, trail, om-os, kontakt
- 2 CSS-filer: style.css og cards.css
- lokale SVG-billeder i /images

# Teknisk dokumentation

## Projektbeskrivelse
LøbeMatch er en hjemmeside udviklet i HTML og CSS med fokus på at hjælpe brugere med at finde den rette løbesko ud fra behov, løbestil og underlag.

Projektet består af flere undersider med forskellige kategorier af løbesko samt generel information om løb og skovalg.

---

## Teknologier
Projektet er udviklet med følgende teknologier:

- HTML
- CSS
- GitHub
- Visual Studio Code

---

## Filstruktur

Projektet består af flere HTML-sider samt separate CSS-filer til styling.

```text
projektmappe/
│
├── index.html
├── kategorier.html
├── knae.html
├── pronation.html
├── carbon.html
├── neutral.html
├── trail.html
├── om-os.html
│
├── style.css
├── cards.css
│
└── images/
```

---

## HTML-struktur

Alle sider følger samme overordnede struktur:

- Header med navigation
- Main med sidens indhold
- Footer med logo

Navigationen er implementeret med links mellem de forskellige HTML-sider, hvilket gør det muligt at navigere rundt på hjemmesiden uden brug af JavaScript.

---

## CSS og styling

Projektet anvender to CSS-filer:

### style.css
Indeholder:
- Farvevariabler
- Layout
- Navigation
- Ens header
- Responsivt design
- Typografi

CSS-variabler er anvendt for at gøre designet mere ensartet og lettere at vedligeholde.

### cards.css
Indeholder styling af:
- Cards
- Grid-layouts
- Tabs
- Hover-effekter

---

## Responsivt design

Hjemmesiden er udviklet responsivt, så layoutet tilpasser sig forskellige skærmstørrelser.

Dette er blandt andet implementeret med CSS Grid

På mindre skærme ændres layoutet fra to kolonner til én kolonne for bedre brugeroplevelse.

---

## Funktionalitet

Projektet indeholder følgende funktioner:

- Navigation mellem undersider
- Kategorisering af løbesko
- Informationskort med billeder og beskrivelser
- Responsivt layout
- Hover-effekter på cards
- Genanvendelige komponenter via fælles CSS-klasser

---

## Designvalg

Designet er udviklet med fokus på:
- Enkel navigation
- Overskuelig struktur
- Visuel konsistens på tværs af sider

Farver og spacing er gjort ensartede gennem brug af CSS-variabler og fælles komponenter.

---

## Git og versionsstyring

Projektet er versionsstyret gennem Git og GitHub.

Der er arbejdet med:
- Branches
- Commits
- Merge til main branch

Dette gjorde det muligt for gruppemedlemmer at arbejde parallelt på forskellige sider og funktioner.
