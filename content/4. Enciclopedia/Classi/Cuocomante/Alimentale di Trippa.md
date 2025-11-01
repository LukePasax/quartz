---
tags: 
- creatura
source: "AT"
statblock: inline
---

```statblock
layout: Brancalonia
source: "AT"
name: Alimentale di Trippa
size: Grande
type: Costrutto
alignment: senza allineamento
ac: 11 + BdC
hp: 6 + il modificatore di Saggezza del personaggio + sei volte il livello da cuocomante del personaggio (l’alimentale ha un numero di Dadi Vita [d10] pari al livello da cuocomante del personaggio)
hit_dice: 6d10
speed: 9 m
stats: [14, 8, 16, 2, 8, 3]
saves:
- For: +2 + BdC
- Cos: +3 + BdC
skillsaves:
- Atletica: +2 + BdC
- Percezione: -1 + BdC
damage_vulnerabilities: 
damage_resistances: "Danni contundenti da attacchi non magici"
damage_immunities: "psichico, veleno"
condition_immunities: "affascinato, avvelenato, indebolimento, privato dei sensi, spaventato"
senses: "Percezione passiva 9 + BdC, scurovisione 18 m"
languages: "Capisce il linguaggio del personaggio ma non può parlare"
cr: -
traits:
- name: Cotto a Puntino
  desc: "Quando l’alimentale di trippa subisce danni da fuoco, si lessa leggermente; la sua velocità è ridotta di 3 metri e subisce svantaggio ai tiri per colpire fino alla fine del suo turno successivo."
- name: Natura Speciale
  desc: "L’alimentale non ha bisogno di respirare, mangiare, bere o dormire."
actions:
- name: Trippa in Umido
  desc: "Attacco con Arma da Mischia: modificatore di attacco dell’incantesimo del personaggio al tiro per colpire, portata 3 m, un bersaglio nel campo visivo del personaggio. Colpito: 2d6 + BdC danni contundenti e il se il bersaglio è una creatura deve superare un tiro salvezza su Forza contro la CD del tiro salvezza dell’incantesimo del personaggio, altrimenti cade a terra prono."
- name: Frattaglie Maleodoranti
  desc: "L’alimentale di trippa lancia delle frattaglie in un punto a sua scelta situato entro 9 metri che esso sia in grado di vedere. Ogni creatura situata entro un raggio di 3 m da quel punto deve superare un tiro salvezza su Costituzione contro la CD del tiro salvezza dell’incantesimo del personaggio, altrimenti è avvelenata fino alla fine del suo turno successivo. Se supera il tiro salvezza, la creatura è immune alla Frattaglie Maleodoranti dell’alimentale di trippa per l’ora successiva."
```
