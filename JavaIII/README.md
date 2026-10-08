# Java III – Klinika e CSS

## Përshkrimi

Ky projekt paraqet një afishe për Klubin e Debatit.

## Çfarë u implementua

- CSS i jashtëm
- CSS variables
- Klasa të ripërdorshme
- CSS cascade
- Box model
- Responsive width
- Hover state
- Focus-visible state
- Accessibility

## Kaskada

`#poster` ka specifikë më të lartë se `.poster`, prandaj rregullat e tij fitojnë në kaskadë.

U rregullua konflikti pa përdorur `!important`.

## Box Model

U përdor:

`box-sizing: border-box`

për të kontrolluar më mirë width, padding dhe border dhe për të shmangur overflow.

## Testimi

Faqja u testua edhe në viewport 360px dhe fokusi u kontrollua me tastin Tab.