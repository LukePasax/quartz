---
tags: 
- creatura
source: "LI"
statblock: inline
---
L’impresario [[Malebranche]] Dardo Maglio è fuggito da tempo dall’Inferno, dopo aver compiuto il suo “gran rifiuto”. Il suo
aspetto è ancora quello di un essere infernale: pelle rossa, scarificazioni al corpo e al viso, corna. Invece di truccarsi e mascherare
la sua natura, Maglio ha deciso di sfruttarla per il suo ruolo di imbonitore e gestore della Stamberga, richiamando
avventori e campagnoli tramite il suo aspetto e il suo parlare colorito. È sinceramente legato a [[Berenice]], che ha scoperto anni
prima in una vera catapecchia da lei infestata, il luogo dove la donna era morta di una fine violenta. Visto che lo spettro era
confinato in quel luogo, Maglio ha deciso di smontarne una parte e trasformarla in un’attrazione viaggiante, e adesso [[Berenice]]
è “confinata” sul loro caravan, libera di girare il mondo...

**Tratto Caratteriale** – Dardo Maglio parla molto spesso in [[Maccheronico]] e si atteggia a personaggio illustre e di fama.

**Ideale – Autodeterminazione.** È sacrosanto fare ciò che è giusto per lo spettacolo, anche quando potrebbe non esser conveniente,
corretto, o legittimo nei confronti degli altri.

**Legame** – Dardo Maglio è innamorato di [[Berenice]] e farebbe qualunque cosa per lei.

**Difetto** – Dardo Maglio è sempre diffidente nei confronti di preti, frati ed esorcisti.

```statblock
layout: Brancalonia
source: "LI"
 
name: Dardo Maglio
size: Medio (malebranche)
type: Umanoide
alignment: caotico neutrale
ac: 16
hp: 44
hit_dice: 8d8 + 8
speed: 12m
stats: [16, 16, 12, 12, 9, 17]
saves:
  - Des: +5
  - Car: +5
skillsaves:
  - Acrobazia: +7
  - Atletica: +5
  - Inganno: +5
  - Intrattenere: +7
  - Persuasione: +5

senses: "Percezione passiva 9, scurovisione 18 m"

languages: "Baccaglio, Male Parole, Maccheronico, Volgare"

cr: 2
spells:
- "Dardo Maglio è un incantatore di 3° livello: la caratteristica da incantatore di Dardo Maglio è Carisma (tiro salvezza degli incantesimi CD 13, +5 al tiro per colpire degli attacchi con incantesimo). Dardo Maglio ha preparato i seguenti incantesimi da bardo:"
- "Trucchetti (a volontà): mano magica, prestidigitazione"
- "1° livello (4 slot): anatema, caduta morbida, onda tonante"
- "2° livello (2 slot): blocca persone, suggestione"

traits:
- name: "Difesa senza armatura."
  desc: "Finché Dardo Maglio non indossa alcuna armatura e non impugna uno scudo, la sua CA è pari a 10 + il suo modificatore di Destrezza + il suo modificatore di Carisma."
  
- name: "Malegambe."
  desc: "La velocità base sul terreno di Dardo Maglio è 12 metri."

- name: "Malavoce."
  desc: "Dardo Maglio può lanciare l’incantesimo charme su persone una volta con questo tratto e recuperare la capacità di farlo quando completa un riposo lungo. La caratteristica da incantatore usata per questo incantesimo è Carisma."

actions:
- name: "Multiattacco."
  desc: "Dardo Maglio effettua due attacchi in mischia."
- name: "Bastone ferrato."
  desc: "Attacco con Arma da Mischia: +5 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 6 (1d6 + 3) danni contundenti o 7 (1d8 + 3) danni contundenti se impugnato a due mani."
  
reactions:
- name: "Batocchio (3/Giorno)."
  desc: "Quando Dardo Maglio viene attaccato da una creatura, può usare la sua reazione per distrarre l’avversario, che deve effettuare un tiro salvezza su Saggezza contro la CD degli incantesimi di Dardo Maglio. In caso di fallimento il bersaglio perde l’attacco ed è affascinato fino all’inizio del suo prossimo turno."
```