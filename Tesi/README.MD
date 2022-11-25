#Analisi di metodi di machine learning per la classificazione di immagini di prodotti biodegradabili
- Ci sono 2 modi per eseguire il codice:
1. Usare i file nella cartella **notebook**. Per usarli consiglio di importarli su google colab avendo svolto il progetto interamente su esso
2. Usare i codici nella cartella **CodicePython**

Metodi utilizzati:

1. Support Vector Machine
2. K nearest neighbors
3. Random Forest

- ClassificatoreSVM.ipynb: classificatore completo in cui si può utilizzare il modello creato in 2 modi:
1. inserendo un immagine presa dalla parte di TEST del dataset
2. un immagine qualsiasi presa in rete inserendo URL).
** Ho scelto il modello SVM ma è facilmente modificabile per usare gli altri seguendo gli altri notebook**

- TestFiltroUniversale.ipybn : sono presenti vari modelli tra cui scegliere per fare tuning dei parametri in modo semplice, questi modelli sono testati o sulle immagini originali, o sulle immagini a cui sono applicati i vari filtri. All'interno del codice è possibile scegliere quale filtro utilizzare
1. Discrete fourier transform
2. Sobel
3. Entropy

- TestRGB.ipynb: in questo notebook si possono fare test con i vari modelli analizzando scegliendo quale canale dello spazio colore utilizzare, e scegliendo anche quale tra i modelli utilizzare.

- PCA.ipynb: è applicata la PCA per visualizzare il dataset, sono state utilizzate 2 componenti e 3 componenti ed è stato printato graficamente il risultato
 

- Tesi.pdf: report in base ai vari test effettuati

- Presentazione.ppt: powerpoint riepilogativo basato sul report
