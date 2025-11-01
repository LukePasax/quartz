---
tags: 
- creatura
source: "MA"
aliases: cacciatori di equitaglia
statblock: inline
---
I Cacciatori di Taglia sono tra i più grossi figli di una somara che le canaglie potrebbero incontrare: ossi duri, veterani di guerre,
spedizioni e indagini, abituati a trattare alla pari con capitani di ventura, capibanda e ufficiali. Si tratta spesso di cagnacci
da tenersi lontano dalle terga con trucchi e accordi, piuttosto che da affrontare a brutto muso.

> [!quote|mark] Fracasso da Trivelle
> “Porgi l'altra guancia, fratello, che io porgerò l'altro palmo”



```statblock
layout: Brancalonia
source: "MA"
 
name: Cacciatore di Equitaglia
size: Medio (qualsiasi razza)
type: Umanoide
alignment: qualsiasi allineamento
ac: 16
hp: 71
hit_dice: 11d8 + 22
speed: 9m
stats: [14, 18, 14, 13, 14, 12]
saves:
  - For: +5
  - Des: +7
skillsaves:
  - Atletica: +5
  - Furtività: +7
  - Percezione: +5
  - Sopravvivenza: +5 

senses: "Percezione passiva 15"

languages: "Baccaglio, Volgare"

cr: 5

traits:
- name: "Resistenza Leggendaria (1/Giorno)."
  desc: "Se il cacciatore fallisce un tiro salvezza, può scegliere invece di superarlo."
  
- name: "Attacco Furtivo."
  desc: "Una volta per turno, il cacciatore infligge 14 (4d6) danni extra quando colpisce un bersaglio con un attacco con un’arma e dispone di vantaggio al tiro per colpire, oppure quando il bersaglio si trova entro 1,5 metri da un alleato del cacciatore (purché l’alleato non sia incapacitato e il cacciatore non subisca svantaggio al tiro per colpire)."

- name: "Udito e Vista Acuti."
  desc: "Il cacciatore di taglia dispone di vantaggio alle prove di Saggezza (Percezione) basate sull’udito o sulla vista."
  
- name: "Tattiche del Branco."
  desc: "Il cacciatore di taglia dispone di vantaggio a un tiro per colpire contro una creatura se almeno uno degli alleati del combattente si trova entro 1,5 metri dalla creatura e non è incapacitato."

actions:
- name: "Multiattacco."
  desc: "Il cacciatore può effettuare tre attacchi in mischia: due con la spada corta e uno con il pugnale. Oppure effettua due attacchi a distanza (non più di uno con la balestra a mano o con la rete)."
- name: "Spada Corta."
  desc: "Attacco con Arma da Mischia: +7 al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 7 (1d6 + 4) danni perforanti."
- name: "Pugnale."
  desc: "Attacco con Arma da Mischia o a Distanza: +7 al tiro per colpire, portata 1,5 m o gittata 6/18 m, un bersaglio. Colpito: 6 (1d4 + 4) danni perforanti."
- name: "Balestra a Mano."
  desc: "Attacco con Arma a Distanza: +7 al tiro per colpire, gittata 9/36 m, un bersaglio. Colpito: 7 (1d6 + 4) danni perforanti e il bersaglio deve superare un tiro salvezza su Costituzione con CD 13, altrimenti è avvelenato per 1 ora. Se il tiro salvezza fallisce di 5 o più, il bersaglio è anche privo di sensi finché è avvelenato in questo modo. Il bersaglio si risveglia se subisce danni o se un’altra creatura usa un’azione per svegliarlo scuotendolo."
- name: "Rete."
  desc: "Attacco con Arma a Distanza: +5 al tiro per colpire, gittata 1,5/4,5 m, una creatura di taglia Grande o inferiore. Colpito: il bersaglio è trattenuto. Una creatura può usare la sua azione per effettuare una prova di Forza con CD 10 per liberare se stessa o un’altra creatura nella rete, terminando l’effetto in caso di successo. Infliggendo 5 danni taglienti alla rete (CA 10), il bersaglio è liberato senza subire danni e la rete è distrutta."

legendary_actions:
- name: "Movimento."
  desc: "Il cacciatore si muove fino alla sua velocità senza provocare attacchi di opportunità."
- name: "Attacco (Costa 2 Azioni)."
  desc: "Il cacciatore effettua un attacco con la spada corta o un attacco con la balestra a mano."
- name: "Rete."
  desc: "Il cacciatore effettua un attacco con la Rete."
  
reactions:
- name: "Parata."
  desc: "Il cacciatore di taglia aggiunge 3 alla sua CA contro un attacco in mischia che lo colpirebbe. Per farlo, il cacciatore deve vedere l’attaccante e deve impugnare un’arma da mischia."
```