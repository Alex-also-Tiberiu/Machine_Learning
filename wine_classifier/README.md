# Wine Classifier Project

## Descrizione
Questo progetto utilizza il dataset "Wine" fornito da `sklearn.datasets` per costruire e valutare modelli di classificazione. L'obiettivo è prevedere la categoria di un vino in base alle sue caratteristiche chimiche. Sono stati implementati diversi approcci, tra cui:

- **Support Vector Machines (SVM)** con kernel lineare e RBF.
- **Random Forest** e altri algoritmi di classificazione.

## Struttura del Progetto

La cartella `wine_classifier` contiene i seguenti file:

- **`wine.ipynb`**: Notebook che esplora il dataset e implementa modelli di classificazione come Random Forest e K-Nearest Neighbors (KNN).
- **`wine-svm.ipynb`**: Notebook che implementa modelli SVM con kernel lineare e RBF, includendo la visualizzazione delle confusion matrix.
- **`requirements.txt`**: File con le dipendenze necessarie per eseguire i notebook.

## Dipendenze

Le dipendenze richieste sono elencate in `requirements.txt`. Per installarle, eseguire il seguente comando:

```bash
pip install -r requirements.txt
```

## Dataset

Il dataset "Wine" è incluso nella libreria `sklearn.datasets` e contiene informazioni su tre tipi di vino, con 13 caratteristiche chimiche per ciascun campione.

## Istruzioni per l'Esecuzione

1. Clonare o scaricare il progetto.
2. Installare le dipendenze utilizzando il comando sopra.
3. Aprire i notebook `wine.ipynb` e `wine-svm.ipynb` in un ambiente Jupyter Notebook o JupyterLab.
4. Eseguire le celle per esplorare i dati, addestrare i modelli e visualizzare i risultati.

## Visualizzazioni

- **Grafici Pairplot**: Per esplorare le relazioni tra le caratteristiche del dataset.
- **Confusion Matrix**: Per valutare le prestazioni dei modelli SVM con kernel lineare e RBF.

## Contatti
Per domande o suggerimenti, contattare l'autore del progetto.
