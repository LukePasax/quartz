---
tags: 
- creatura
source: "MA"
statblock: inline
---

I Confinati sono probabilmente i più potenti tra gli spettri e le fantasime che le canaglie possono incontrare nel Regno. Si tratta
di esseri di antico dolore, oscuri intenti e grandi poteri, che per qualche motivo rimangono a infestare il luogo dove sono morti.
Le loro tenebrose capacità sono talmente estese e radicate nel luogo che infestano da riuscire a dare vita a fenomeni paranormali
di ogni tipo: poltergeist, possessione, incendi, disgregazione della materia e persino controllo di cadaveri e altri spettri.
L’unico aspetto positivo della loro terrificante esistenza è che la loro area di influenza è limitata da un qualche confine che
essi non possono varcare, a meno di speciali condizioni: un castello, un sotterraneo, un veliero, un villaggio o persino un’intera
città. Da questo limite, prendono il loro nome.

| Livello Magnitudo | Numero Poteri | Modififica alle statistiche base                                                                          | GS             |
| :---------------: | :-----------: | --------------------------------------------------------------------------------------------------------- | -------------- |
|         1         |       1       | Statistiche Base.                                                                                         | 7 (2.900 PE)   |
|         2         |       2       | Punti Ferita 119 (14d8 + 56) , Resistenza Leggendaria (1/Giorno),<br>Azioni Leggendarie.                  | 9 (5.000 PE)   |
|         3         |       3       | Punti Ferita 136 (16d8 + 64), Resistenza Leggendaria (3/Giorno),<br>Azioni Leggendarie, Multiattacco (2). | 13 (10.000 PE) |

# Magnitudo
La magnitudo indica il livello di potere del confinato: maggiore è la magnitudo e maggiori saranno resistenza, potenza e
capacità uniche dell’apparizione.
Per ogni livello di magnitudo, il confinato ottiene un potere unico a scelta dalla lista dei poteri del confinato. Inoltre il livello
di magnitudo si somma alla CD dei tiri salvezza, al tiro per colpire e alle prove di abilità del confinato.

```statblock
layout: Brancalonia
image: "[[confinato.png]]"
source: "MA"
 
name: Confinato
size: Medio
type: Non morto
alignment: neutrale malvagio
ac: 12
hp: 94
hit_dice: 12d8 + 40
speed: 0 m, Volare 18 m (fluttuare)
stats: [6, 14, 18, 12, 14, 17]

damage_resistances: "acido, fuoco, fulmine, tuono; contundente, perforante e tagliente da attacchi non magici"

damage_immunities: "freddo, necrotico, veleno"

condition_immunities: "affascinato, afferrato, avvelenato, indebolimento, paralizzato, pietrificato, privo di sensi, prono, spaventato, trattenuto" 

senses: "Percezione passiva 12, scurovisione 18 m"

languages: "Linguaggi che conosceva in vita"

cr: 7
traits:
- name: "Resistenza Leggendaria (1/Giorno, Magnitudo 2) e (3/Giorno, Magnitudo 3)."
  desc: "Se il confinato fallisce un tiro salvezza, può scegliere invece di superarlo."
  
- name: "Movimento Incorporeo."
  desc: "Il confinato può muoversi attraverso altre creature e oggetti come se fossero terreno difficile. Subisce 5 (1d10) danni da forza se termina il suo turno all’interno di un oggetto."

- name: "Sensibilità alla Luce del Sole."
  desc: "Finché è esposto alla luce del sole, il confinato subisce svantaggio ai tiri per colpire, oltre che alle prove di Saggezza (Percezione) basate sulla vista."

- name: "Debolezze dei Confinati."
  desc: "Il confinato possiede i seguenti difetti:<br>- **Vincolato.** L’area di influenza del confinato è circoscritta a una zona specifica (la sua tana), come un villaggio, una valle o un bosco. Il confinato non può varcare i confini della sua tana né manifestare alcun potere al di fuori di essa.<br>- **Resti mortali.** Se le vestigia mortali del confinato vengono bruciate o se ottengono una degna sepoltura, questi viene distrutto istantaneamente.<br>- **Pace agognata.** Se viene data pace al confinato, sanando il dissidio che lo tormenta, questi scomparirà per sempre."

- name: "Sguardo Gelido."
  desc: "Quando una creatura inizia il suo turno entro 3 m dal confinato, questo può obbligarla magicamente a effettuare un tiro salvezza su Costituzione con CD 13 (+1 per livello di Magnitudo). Se la creatura fallisce il tiro salvezza, subisce 1 livello di indebolimento."

actions:
- name: "Tocco di Decomposizione."
  desc: "Attacco con Arma da Mischia: +5 (+1 per livello di Magnitudo) al tiro per colpire, portata 1,5 m, un bersaglio. Colpito: 16 (4d6 + 2) danni necrotici. Il bersaglio deve superare un tiro salvezza su Costituzione con CD 13 (+1 per livello di Magnitudo), altrimenti il suo massimo dei punti ferita è ridotto di un ammontare pari ai danni subiti. Questa riduzione permane finché il bersaglio non completa un riposo lungo. Se questo effetto riduce il suo massimo dei punti ferita a 0, il bersaglio muore."

- name: "Combustione."
  desc: "Il confinato bersaglia una creatura situata entro 18 metri da lui, che esso sia in grado di vedere. Il bersaglio deve effettuare un tiro salvezza su Costituzione con CD 13 (+1 per livello di Magnitudo) o; se lo fallisce, prende fuoco e subisce 1d6 danni da fuoco per livello di Magnitudo all’inizio di ogni suo turno. Il bersaglio può ripetere il tiro salvezza alla fine di ogni suo turno e, se lo supera, l’effetto per lui termina. Bagnando il bersaglio con dell’Acqua Santa l’effetto termina immediatamente."

- name: "Controllo Telecinetico."
  desc: "Il confinato bersaglia una creatura o un oggetto incustodito situato entro 9 metri da lui. La creatura deve essere di taglia Media o inferiore per essere influenzata da questa magia; l’oggetto non deve pesare più di 75 chilogrammi. Se il bersaglio è una creatura, il confinato effettua una prova di Carisma contrapposta alla prova di Forza del bersaglio. Se il confinato vince la contesa, scaglia la creatura di un massimo di 9 metri in qualsiasi direzione (anche verso l’alto). Se la creatura entra poi in contatto con una superficie rigida o un oggetto pesante, subisce 1d6 danni per ogni 3 metri di cui si è mosso. Se il bersaglio è un oggetto che non è indossato o trasportato, il confinato lo scaglia di un massimo di 9 metri in qualsiasi direzione. Il confinato può usare l’oggetto come arma a distanza, attaccando una creatura lungo la traiettoria dell’oggetto +5 (+1 per livello di Magnitudo) e infliggendo 2d4 danni contundenti per livello di Magnitudo se colpisce."

- name: "Possessione (Ricarica 6)."
  desc: "Un umanoide situato entro 1,5 metri dal confinato e che quest’ultimo sia in grado di vedere deve superare un tiro salvezza su Carisma con CD 13 (+1 per livello di Magnitudo), altrimenti è posseduto dal confinato; poi il confinato scompare e il bersaglio è incapacitato e perde il controllo del suo corpo. Ora il confinato controlla il corpo del bersaglio, ma senza privarlo della sua consapevolezza. Il confinato non può essere bersagliato da alcun attacco, incantesimo o altro effetto, ad eccezione di quelli che scacciano i non morti, e conserva allineamento, Intelligenza, Saggezza, Carisma e immunità alle condizioni di affascinato e spaventato. Sotto ogni altro aspetto usa le statistiche del bersaglio posseduto, ma non accede alle sue conoscenze, privilegi di classe o competenze. La possessione dura finché il corpo non scende a 0 punti ferita, il confinato non le pone termine impiegando un’azione bonus o il confinato non è scacciato oppure obbligato ad abbandonare il corpo da un effetto come l’incantesimo dissolvi il bene e il male. Quando la possessione termina, il confinato ricompare in uno spazio libero entro 1,5 metri dal corpo. Il bersaglio è immune alla Possessione di questo confinato per 24 ore dopo avere superato il tiro salvezza o dopo che la possessione è terminata."

- name: "Sguardo Terrificante."
  desc: "Il confinato bersaglia una creatura situata entro 9 metri da lui, che esso sia in grado di vedere. Il bersaglio deve effettuare un tiro salvezza su Saggezza con CD 13 (+1 per livello di Magnitudo); se lo fallisce, è paralizzato finché il confinato non gli infligge danni o fino alla fine del turno successivo del confinato. Quando la paralisi termina, il bersaglio è spaventato dal confinato per l minuto. Il bersaglio spaventato può ripetere il tiro salvezza alla fine di ogni suo turno, subendo svantaggio se può vedere il confinato; se supera il tiro salvezza, la condizione di spaventato per lui termina."

- name: "Signore degli Insoluti (1/Giorno)."
  desc: "Il confinato risveglia i morti presenti nella sua tana. Un numero di zombi pari a 1d4 per livello di Magnitudo, sopraggiungono in un round. Gli zombi sono sotto il controllo del confinato e rimangono per 1 ora, finché il confinato non muore o finché il confinato non li congeda con un’azione bonus."

legendary_actions: 
- name: "Movimento."
  desc: "Il confinato si muove fino alla sua velocità senza provocare attacchi di opportunità."
- name: "Potere Unico (Costa 2 Azioni)."
  desc: "Il confinato utilizza un potere unico tra quelli a sua disposizione."
- name: "Tocco di Decomposizione."
  desc: "Il confinato effettua un attacco di Tocco di Decomposizione."
```

# La Tana di un Confinato
Tipiche “tane” dei Confinati sono: un villaggio fantasma
sperduto tra i monti, una torre infestata, un tratto di foresta
o di palude, un complesso di grotte o di segrete, una nave
alla deriva, un’isola di piccole dimensioni, la contrada attorno
a un crocevia, un tratto di strada (o una Strada che non
va da nessuna parte, vedi pag. 85).

## azioni di tana
A conteggio di iniziativa 20 (in caso di parità di iniziativa,
il confinato perde), il confinato può effettuare un’azione di
tana per provocare uno degli effetti magici seguenti; non
può usare lo stesso effetto in due round di fila.
- Il confinato chiama a sé gli spiriti delle creature che sono
morte nella sua tana. Queste apparizioni si materializzano
e attaccano una creatura situata entro 18 metri da lui e
che egli sia in grado di vedere. Il bersaglio deve effettuare
un tiro salvezza su Costituzione con CD 13 + livello di
Magnitudo; se lo fallisce, subisce 3d6 danni necrotici per
livello di Magnitudo, mentre se lo supera, subisce la metà
di quei danni. Poi le apparizioni svaniscono.
- Il confinato evoca a sé un non morto presente nella sua tana.
- Il confinato può lanciare l’incantesimo Scagliare
Maledizione (non è richiesta concentrazione) a una
creatura visibile che si trovi entro 36 m da lui (tiro salvezza
con CD 13 + livello di Magnitudo).

## effetti regionali
La regione che circonda la tana di un confinato è alterata
dalla presenza innaturale della creatura, che genera uno o
più dei seguenti effetti:
- La presenza di non morti spettrali nella regione aumenta
visibilmente.
- I vegetali entro 150 metri dalla tana avvizziscono, gli steli
dei fiori e i rami degli alberi diventano contorti e spinosi.
- Nubi temporalesche offuscano il cielo sopra la tana del
confinato, non lasciando filtrare la luce del sole.
- Rumori inquietanti come sussurri e cigolii, oggetti
inanimati che si muovo di loro spontanea volontà, come
porte che si chiudono, oggetti che fluttuano nell’aria
per poi cadere a terra inermi, ecc. Il confinato non ha
controllo su questi fenomeni.
Se il confinato è distrutto, questi effetti terminano immediatamente.