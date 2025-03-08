# 📌 Valutazione delle Mappe di Salienza Basate su Gaze Following per la Predizione dello Sguardo nei Video  

## Descrizione  
Il lavoro esplora l’uso di modelli avanzati di **intelligenza artificiale** per stimare la direzione dello sguardo in contesti dinamici e sociali, fornendo nuove prospettive sull’interazione visiva e il comportamento collettivo.

L’obiettivo della ricerca è sviluppare una **Social Context-Gaze-Behavior Value Map** che riflette la salienza visiva degli oggetti o delle persone osservate dai soggetti nei video.  
Il metodo è validato attraverso il confronto con dati di **eye-tracking**, dimostrando la capacità predittiva del modello proposto.

---

## 🔍 Abstract  
Utilizzando il modello **Gaze360** per l’analisi della direzione dello sguardo e **DensePose** per il riconoscimento delle pose umane, questo studio elabora i frame video per generare mappe di salienza che identificano le aree di maggiore interesse visivo.  
Le predizioni sono state valutate rispetto ai dati di **eye-tracking** per testare l’accuratezza del modello nel predire lo sguardo umano in scenari sociali complessi.

---

## 🛠 Metodologia  
Il progetto si basa su tecnologie di **deep learning** e **computer vision**, tra cui:  
- 🔹 **Detectron2** per la segmentazione degli oggetti nei video  
- 🔹 **DensePose** per la ricostruzione 3D delle pose umane  
- 🔹 **Gaze360** per la stima della direzione dello sguardo  
- 🔹 Analisi di regressione e filtro di **Kalman** per migliorare la predizione  

Le mappe di salienza vengono generate combinando tecniche di **istogramma 2D** e **convoluzioni gaussiane** per ottenere una stima liscia delle zone di maggiore interesse visivo.

---

## 📊 Risultati  
L’efficacia delle mappe di salienza è stata confrontata con dati reali di **eye-tracking**, mostrando che:  
✔️ La **Speaker Map** (che evidenzia i soggetti parlanti) è il miglior predittore dello sguardo  
✔️ La **Social Value Map** fornisce un’importante analisi sulle dinamiche di attenzione sociale  
✔️ Le mappe basate su caratteristiche visive di basso livello (STS Map, Center Bias Map) mostrano una predittività più uniforme, ma meno influenzata dal contesto sociale  
