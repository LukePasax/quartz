---
tags: 
- creatura
source: "LI"
statblock: inline
---
Il “Buseccone” in atto da [[Ventresca]] e da Brunello
non è altro che una variante locale galaverniana
della ricetta del Midolliano, orrido piatto di
portata colossale e distruttrice che rappresenta
uno dei segreti più terribili della cucina occulta dei
cagliomanti elaborata in onore della Pasta Mater.
Questa orrenda preparazione cagliomantica
consiste di fatto in un essere formato da montagne
di frattaglie, trippe, cervella, coratelle,
animelle e altre parti animali mescolate assieme,
in continua cottura e decomposizione, con in
aggiunta tuberi, cipolle e aromi per insaporire
la ricetta.
Piatto della cucina povera e popolare, il Buseccone
di [[Ventresca]] è trasformato in particolare in
questa avventura in un mostro alto dieci piedi,
grondante sugo e ciccetti di carne, il cui
unico scopo è quello di distruggere ogni
cosa attorno a sé, gettare il panico in
paese e ferire quanta più gente possibile,
per distrarre tutti coloro che sono alla
ricerca della principessa e coprire la fuga
di Lelia e Scannafagiuolo.

```statblock
layout: Brancalonia
image: "[[midolliano.png]]"
source: "LI"
 
name: Midolliano
size: Enorme
type: Non Morto
alignment: Neutrale Malvagio
ac: 12
hp: 126
hit_dice: 11d12 + 55
speed: 12m
stats: [20, 7, 21, 3, 10, 4]

damage_immunities: "Veleno"
condition_immunities: "afferrato, affascinato, avvelenato, indebolimento, paralizzato, pietrificato, privo di sensi, spaventato, trattenuto" 
senses: "Percezione passiva 10, scurovisione 36 m"
languages: "capisce il Volgare ma non può parlarlo"
cr: 8

traits:
- name: "Carica."
  desc: "Se il midolliano si muove di almeno 4,5 metri in linea retta verso un bersaglio e poi lo colpisce con un attacco di schianto nello stesso turno, il bersaglio subisce 11 (2d10) danni contundenti extra. Se il bersaglio è una creatura, deve superare un tiro salvezza su Forza con CD 16, altrimenti è spinto fino a un massimo di 6 metri più lontano dal midolliano e cade a terra prono."
  
- name: "Fetore Letale."
  desc: "Ogni creatura che inizia il proprio turno entro 9 metri dal midolliano deve superare un tiro salvezza su Costituzione con CD 16, altrimenti subisce 3 (1d6) danni da veleno ed è avvelenata fino all’inizio del proprio turno successivo."

- name: "Spasmi di morte."
  desc: "Quando il midolliano muore, esplode e ogni creatura situata entro 6 metri da lui deve effettuare un tiro salvezza su Destrezza con CD 11; se lo fallisce, subisce 21 (6d6) danni da veleno ed è avvelenata fino all’inizio del proprio turno successivo, mentre se lo supera, subisce la metà di quei danni e non è avvelenata."
  
actions:
- name: "Multiattacco."
  desc: "Il midolliano effettua due attacchi con schianto."
  
- name: "Schianto."
  desc: "Attacco con Arma da Mischia: +8 al tiro per colpire, portata 3 m, un bersaglio. Colpito: 16 (2d10 + 5) danni contundenti."

- name: "Pioggia di Frattaglie (Ricarica 5-6)."
  desc: "Il midolliano scaglia cinque pezzi di carne putrefatta, ognuno dei quali può colpire un bersaglio situato entro 36 metri dal midolliano e che esso sia in grado di vedere. Un bersaglio deve effettuare un tiro salvezza su Destrezza con CD 16; se lo fallisce, subisce 3 (1d6) danni contundenti + 3 (1d6) danni da veleno, mentre se lo supera, subisce la metà di quei danni."
```