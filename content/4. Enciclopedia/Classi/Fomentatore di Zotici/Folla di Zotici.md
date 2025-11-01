---
tags: 
- creatura
source: "AT"
statblock: inline

---
```statblock
layout: Brancalonia
source: "AT"
name: Folla di Zotici
size: Medio
type: Sciame di umanoidi Medi
alignment: generalmente legale neutrale
ac: 11
hp: 8 + il modificatore di Carisma del personaggio (la folla di zotici ha un numero di Dadi Vita [d8] pari al livello da fomentatore di zotici del personaggio)
hit_dice: 6d8
speed: 6m
stats: [17, 7, 10, 6, 9, 8]
saves:
  - Cos: +0 + BdC
skillsaves:
  - Percezione: -1 + BdC
  - Sopravvivenza: -1 + BdC

condition_immunities: "afferrato, paralizzato, pietrificato, prono, stordito, trattenuto" 

senses: "Percezione passiva 9 + BdC"

languages: "Volgare"

cr: -

traits:
- name: "Sciame."
  desc: "La folla di zotici può occupare lo spazio di un’altra creatura e viceversa e può muoversi attraverso qualsiasi apertura sufficientemente larga da far passare un umanoide Piccolo. La folla di zotici non può ottenere punti ferita temporanei."

actions:
- name: "Attacco della Marmaglia."
  desc: "Attacco con Arma da Mischia: +1 più BdC al tiro per colpire, portata 0 m, una creatura nello spazio dello sciame. Colpito: 2d4 + BdC danni contundenti o 1d4 + BdC danni contundenti se la folla di zotici possiede la metà dei suoi punti ferita o meno."
```