---
tags: 
- creatura
source: "MA"
statblock: inline
---
Il più comune e diffuso esponente della criminalità del Regno,
sia di campagna che di città: lestofanti armati di coltello
e pronti a tutto, manigoldi che viaggiano al seguito degli
eserciti per finire e saccheggiare i feriti, assassini da quattro
soldi, picchiatori e sicari professionisti al comando dell’Onorata
Società.
```statblock
layout: Brancalonia
source: "MA"
 
name: Tagliagole
size: Medio (umano)
type: Umanoide
alignment: qualsiasi allineamento
ac: 15
hp: 39
hit_dice: 1d8 + 8
speed: 9m
stats: [12, 16, 12, 13, 14, 11]
skillsaves:
  - Furtività: +5
  - Percezione: +4 

senses: "Percezione passiva 14"

languages: "Volgare"

cr: 2

traits:
- name: "Azione Scaltra."
  desc: "A ogni suo turno, il tagliagole può usare un’azione bonus per effettuare l’azione di Scatto, Disimpegno o Nascondersi."
  
- name: "Attacco Furtivo."
  desc: "Una volta per turno, il tagliagole infligge 7 (2d6) danni extra quando colpisce un bersaglio con un attacco con un’arma e dispone di vantaggio al tiro per colpire, oppure quando il bersaglio si trova entro 1,5 metri da un alleato del tagliagole (purché l’alleato non sia incapacitato e il tagliagole subisca svantaggio al tiro per colpire)."
  
actions:
- name: "Multiattacco."
  desc: "Il tagliagole effettua due attacchi in mischia o due attacchi a distanza."
- name: "Spada Corta."
  desc: "Attacco con Arma da Mischia: +5 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 6 (1d6 + 3) danni perforanti."
- name: "Pugnale."
  desc: "Attacco con Arma da Mischia o a Distanza: +5 al tiro per colpire, portata 1,5 m o gittata 6/18 m, un bersaglio. Colpito: 5 (1d4 + 3) danni perforanti."
```