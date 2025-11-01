---
tags:
  - creatura
source: "LI"
statblock: inline
---
Questo spirito appare come una dama di mezza età o nei
primi anni di vecchiaia, dai capelli lunghi e bianchi, fluenti
come onde. Sa fingersi un essere spaventoso e iroso, e sa
manipolare congegni e trucchi della Stamberga Gnaulante,
ma quando non recita la parte dello spettro vendicativo
assume l’aspetto di una quieta e bonaria signora, saggia e
compassata.
La relazione con il suo impresario è la cosa migliore che le
sia capitata nella non-vita.

**Tratto Caratteriale** – Berenice è un’amante della filosofia e
detesta chiunque abbia una mentalità chiusa.

**Ideale – Fiducia.** Berenice guarda alla vita con singolare
positività e fantasia, e ha un’incrollabile fiducia nel prossimo.

**Legame** – Berenice è innamorata di [[Dardo Maglio]] e farebbe
qualunque cosa per lui.

**Difetto** – Berenice non ha mai occasione di parlare con
la gente e quando trova qualcuno che rimane ad ascoltarla,
può perdersi in chiacchiere per ore e ore.

Berenice è un [[Confinato]] di Magnitudo 2 e possiede i
poteri unici Controllo Telecinetico e Sguardo Terrificante. A
differenza di un normale [[Confinato]], l’allineamento di Berenice
è neutrale buono e non possiede la debolezza Pace
agognata.

```statblock
layout: Brancalonia
monster: Confinato
name: Berenice
source: "LI"
 
alignment: neutrale buono

traits:
- name: "Resistenza Leggendaria (1/Giorno, Magnitudo 2) e (3/Giorno, Magnitudo 3)."
  desc: "Se il confinato fallisce un tiro salvezza, può scegliere invece di superarlo."
  
- name: "Movimento Incorporeo."
  desc: "Il confinato può muoversi attraverso altre creature e oggetti come se fossero terreno difficile. Subisce 5 (1d10) danni da forza se termina il suo turno all’interno di un oggetto."

- name: "Sensibilità alla Luce del Sole."
  desc: "Finché è esposto alla luce del sole, il confinato subisce svantaggio ai tiri per colpire, oltre che alle prove di Saggezza (Percezione) basate sulla vista."

- name: "Debolezze dei Confinati."
  desc: "Il confinato possiede i seguenti difetti:<br>- **Vincolato.** L’area di influenza del confinato è circoscritta a una zona specifica (la sua tana), come un villaggio, una valle o un bosco. Il confinato non può varcare i confini della sua tana né manifestare alcun potere al di fuori di essa.<br>- **Resti mortali.** Se le vestigia mortali del confinato vengono bruciate o se ottengono una degna sepoltura, questi viene distrutto istantaneamente."

- name: "Sguardo Gelido."
  desc: "Quando una creatura inizia il suo turno entro 3 m dal confinato, questo può obbligarla magicamente a effettuare un tiro salvezza su Costituzione con CD 13 (+1 per livello di Magnitudo). Se la creatura fallisce il tiro salvezza, subisce 1 livello di indebolimento."

  
actions:
- name: "Tocco di Decomposizione."
  desc: "Attacco con Arma da Mischia: +5 (+1 per livello di Magnitudo) al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 16 (4d6 + 2) danni necrotici. Il bersaglio deve superare un tiro salvezza su Costituzione con CD 13 (+1 per livello di Magnitudo), altrimenti il suo massimo dei punti ferita è ridotto di un ammontare pari ai danni subiti. Questa riduzione permane finché il bersaglio non completa un riposo lungo. Se questo effetto riduce il suo massimo dei punti ferita a 0, il bersaglio muore."

- name: "Controllo Telecinetico."
  desc: "Il confinato bersaglia una creatura o un oggetto incustodito situato entro 9 metri da lui. La creatura deve essere di taglia Media o inferiore per essere influenzata da questa magia; l’oggetto non deve pesare più di 75 chilogrammi. Se il bersaglio è una creatura, il confinato effettua una prova di Carisma contrapposta alla prova di Forza del bersaglio. Se il confinato vince la contesa, scaglia la creatura di un massimo di 9 metri in qualsiasi direzione (anche verso l’alto). Se la creatura entra poi in contatto con una superficie rigida o un oggetto pesante, subisce 1d6 danni per ogni 3 metri di cui si è mosso. Se il bersaglio è un oggetto che non è indossato o trasportato, il confinato lo scaglia di un massimo di 9 metri in qualsiasi direzione. Il confinato può usare l’oggetto come arma a distanza, attaccando una creatura lungo la traiettoria dell’oggetto +5 (+1 per livello di Magnitudo) e infliggendo 2d4 danni contundenti per livello di Magnitudo se colpisce."

- name: "Sguardo Terrificante."
  desc: "Il confinato bersaglia una creatura situata entro 9 metri da lui, che esso sia in grado di vedere. Il bersaglio deve effettuare un tiro salvezza su Saggezza con CD 13 (+1 per livello di Magnitudo); se lo fallisce, è paralizzato finché il confinato non gli infligge danni o fino alla fine del turno successivo del confinato. Quando la paralisi termina, il bersaglio è spaventato dal confinato per l minuto. Il bersaglio spaventato può ripetere il tiro salvezza alla fine di ogni suo turno, subendo svantaggio se può vedere il confinato; se supera il tiro salvezza, la condizione di spaventato per lui termina."

legendary_actions: 
- name: "Movimento."
  desc: "Il confinato si muove fino alla sua velocità senza provocare attacchi di opportunità."
- name: "Potere Unico (Costa 2 Azioni)."
  desc: "Il confinato utilizza un potere unico tra quelli a sua disposizione."
- name: "Tocco di Decomposizione."
  desc: "Il confinato effettua un attacco di Tocco di Decomposizione."  
```