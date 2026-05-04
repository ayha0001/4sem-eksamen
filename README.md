# 4. Semester eksamen

Afsluttende eksamensprojekt lavet af Agnete, Aylin, Emilie og Oscar. Team Ulvene.

## Teknologier

Projektet er bygget op med:

- Astro
- React
- Tailwind CSS

## Navngivning

I projektet er der arbejdet med en konsistent navngivningsstruktur for at sikre overblik, læsbarhed og genbrug af komponenter.

### Pages

Sider i src/pages er navngivet med kebab-case, hvilket følger web-standarder for URL-struktur. Kebab-case er en navngivningskonvention, hvor ord skrives med små bogstaver og adskilles af bindestreger.

Eksempler:

- bliv-frivillig.astro
- kontakt-os.astro
- julegaveindsamling.astro

Dette sikrer SEO-venlige URLs og let genkendelige ruter.

### Komponenter

Komponenter er opdelt i mapper baseret på funktionalitet, fx:

- generelt
- faq
- forside

Komponenter navngives med PascalCase:

- Header.astro
- Hero.astro
- HeroLille.astro
- DelerStreg.astro

Dette gør det tydeligt, at der er tale om genbrugelige UI-komponenter.

### Semantisk navngivning

Navne er valgt ud fra funktion fremfor design:

Eksempler:

- Header → sidens topnavigation
- FooterMedlem → specifik footer variant
- KnapRoed / KnapSort → visuelle variationer

## Commit-strategi

Der anvendes en fast struktur i commit-beskeder for at skabe overblik og konsistens i projektets udvikling.

Alle commits starter med en handling:

- tilføjet → når ny funktionalitet eller filer oprettes
- fjernet → når kode eller filer slettes
- fikset → når fejl rettes

Eksempler:

- "tilføjet header komponent"
- "tilføjet kontakt-os side"
- "fjernet ikon i header"
- "fikset readme fil"

## Projektstruktur

I vores projekt, har vi opbygget vores struktur på denne måde:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └──
│   ├── components
│   │   ├── afsnit
│   │   │    ├──  BilledeTekst.astro
│   │   │    ├──  IkonKort.astro
│   │   │    ├──  IkonSektion.astro
│   │   │    ├──  ProjektKort.astro
│   │   │    ├──  ProjektSektion.astro
│   │   │    └──  TekstBillede.astro
│   │   │ 
│   │   ├── bliv-frivillig
│   │   │    ├──  FormFrivillig.astro
│   │   │    └──  Galleri.astro
│   │   │ 
│   │   ├── faq
│   │   │    └──  DropDown.astro
│   │   │ 
│   │   ├── forside
│   │   │    ├──  MotionGraphics.astro
│   │   │    ├──  Taeller.astro
│   │   │    └──  TaellerSektion.astro
│   │   │ 
│   │   ├── generelt
│   │   │    ├──  DelerStreg.astro
│   │   │    ├──  Footer.astro
│   │   │    ├──  FooterMedlem.astro
│   │   │    ├──  Header.astro
│   │   │    ├──  Hero.astro
│   │   │    ├──  HeroLille.astro
│   │   │    ├──  KnapRoed.astro
│   │   │    └──  KnapSort.astro
│   │   │ 
│   │   ├── julegaveindsamling
│   │   │    └──  VideoKort.astro
│   │   │ 
│   │   ├── kontakt-os
│   │   │    └──  KontaktInfo.astro
│   │   │ 
│   │   ├── nyt-hjem
│   │   │    ├──  SliderKort.astro
│   │   │    └──  SogHjaelp.astro
│   │   │ 
│   │   ├── om-os
│   │   │    ├──  AnsatKort.astro
│   │   │    └──  AnsatSektion.astro
│   │   │ 
│   │   ├── partnere
│   │   │    ├──  FormPartner.astro
│   │   │    ├──  PartnerBanner.astro
│   │   │    ├──  PartnerKort.astro
│   │   │    └──  PartnerSektion.astro
│   │   │ 
│   │   ├── testamente
│   │   │    └──  KontaktHjaelp.astro
│   │   │ 
│   │   └── udtalelser
│   │   │    ├──  UdtalelseKort.astro
│   │   │    └──  UdtalelseSektion.astro
│   │   │ 
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│   │   │    ├──  baeredygtighed.astro
│   │   │    ├──  bliv-frivillig.astro
│   │   │    ├──  faq.astro
│   │   │    ├──  gennemsigtighed.astro
│   │   │    ├──  hvem-er-vi.astro
│   │   │    ├──  index.astro
│   │   │    ├──  julegaveindsamling.astro
│   │   │    ├──  kontakt-os.astro
│   │   │    ├──  nyt-hjem.astro
│   │   │    ├──  partnere.astro
│   │   │    ├──  stoet-os.astro
│   │   │    ├──  testamente.astro
│   │   │    ├──  uddelinger.astro
│   │   │    ├──  udtalelser.astro
│   │   │    └──  vaernemidler.astro
│   │   │ 
│   └── styles
│            └──  global.css
└── package.json
```
