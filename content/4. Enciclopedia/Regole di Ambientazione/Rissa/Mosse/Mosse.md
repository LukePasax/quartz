---
banner: "![[mosse.png]]"
banner_y: 0.155
---

# Mosse Generiche
```dataview
LIST
FROM #mossa/generica
WHERE file.folder != "z_Templates"
```
# Mosse Magiche
```dataview
LIST
FROM #mossa/magica
WHERE file.folder != "z_Templates"
```
# Mosse di Classe
```dataview
TABLE classe
FROM #mossa/classe
WHERE file.folder != "z_Templates"
```
# Assi nella Manica
L’asso nella manica è una mossa segreta di altissimo livello, utilizzabile solo una volta per [[Rissa]]. <br>
**La CD del tiro salvezza dell’asso nella manica** = 8 + il bonus di competenza del personaggio + il modificatore di Caratteristica
a scelta del personaggio.
```dataview
TABLE classe
FROM #asso-nella-manica
WHERE file.folder != "z_Templates"
```