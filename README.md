
# Esercizi svolti di Statistica

## Ambienti

Per il testo dell'esercizio esiste l'ambiente `esercizio`.

``` tex
\begin{esercizio}
... il testo dell'esercizio va qui ...
\end{esercizio}
```

Anche per la soluzione esiste un ambiente dedicato, `soluzione`.

``` tex
\begin{soluzione}
... il testo della soluzione va qui ...
\end{soluzione}
```

Molto facile, no?


## Struttura del sorgente LaTeX

Il file importanti sono questi:

* `main.tex` è il file principale. Se volete creare un pdf, dovete farlo da questo file.
* `preamble.tex` è il preambolo. È importante, ma potete ignorare la sua esistenza.
* `descrittiva.tex` e `inferenziale.tex` sono i files che contengono gli esercizi e gli svolgimenti. È su questi file che dovete mettere mano per aggiungere o modificare contenuti.
