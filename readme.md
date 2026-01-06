# Epicode-M2W1D1

## Risponndi alle seguenti domande:
1. Cos' è un algoritmo? Prova a spiegarlo con parole tue, come se lo dovessi spiegare a qualcuno che non ne capisce molto di informatica.
2. Cos' è una variabile? Prova a spiegarlo con parole tue, come se lo dovessi spiegare a qualcuno che non ne capisce molto di informatica.
3. Undefined e null sono la stessa cosa?

#


### Cos' è un algoritmo?

Per algoritmo si intende una porzione di codice, o anche una sequenza di istruzioni a cascata, il cui scopo è la risoluzione di un problema. Ogni istruzione è una linea di codice e l'ordine di lettura e di esecuzione di tali istruzioni è dall'alto verso il basso, poichè la macchina (il nostro computer) legge ed interpreta (in linguaggio macchina) le istruzioni una per volta, a velocità molto elevate.  
Un esempio pratico nella vita quotidiana è quando ci fermiamo presso la stazione di benzina per far ricaricare il serbatoio della vettura. Tutti quelli che sono per noi una serie di automatismi sono in realtà una serie di azioni (istruzioni) che facciamo in seguenza, ed una per volta, per svolgere il nostro compito che ci eravamo prefissati (fare benzina). Sostare presso la stazione di benzina, schiacciare il freno, spegnere l'auto, rimuovere le chiavi, aprire la portiera, scendere dall'auto, inserire le banconote in base alla quantita di benzina che ci serve, inserire l'erogatore nel bocchettone del serbatoio ed infine riporlo nella colonnina; sono tutte istruzioni che ci servono per il nostro scopo finale e tutte insieme formano l'algoritmo.

#


### Cos' è una variabile?

Una variabile è una sorta di contentiore il cui scopo è immagazzinare un dato. La fase di creazione di una variabile si suddivide in fase di **dichiarazione** di quest'ultima e fase di **inizializzazione**. La fase di dichiarazione avviene tramite l'uso di una **parola chiave** (**let** in Javascript) a cui posticiperemo il **nome** della variabile. Tale nome sarà univoco all'interno della porzione di codice in cui si trova la dichiarazione. Nel momento in cui dichiariamo una variabile, stiamo chiedendo alla nostra macchina di allocare spazio in memoria RAM, ovvero di riservare dei byte (in base al tipo di dato da immagazzinare) nella memoria ad un determinato indirizzo, fino al momento della sua deallocazione. Il nome della variabile funge invece da riferimento al dato immagazzinato, cioè alla macchina serve per capire a quale indirizzo in memoria noi ci stiamo riferendo.  
La fase di inizializzazione è importante per "avvisare" la macchina che tipo di dato debba immagazzinare, dato che al momento della dichiarazione della variabile, essa è **undefined**. Nei linguaggi di programmazione vi sono diversi tipi di dati con cui si puo' lavorare: Integer, Double, Float, Char, Stringhe, Boolean... Ognuno di essi occupa una quantità di byte differenti in memoria. Inizializzare la variabile serve alla macchina per capire quanto spazio allocare in memoria.  
Inoltre esistono anche le costanti, che a differenza delle variabili hanno un valore fisso che non potra piu essere cambiato tramite assegnazione, a differenza delle variabili, il cui valore puo cambiare nel corso del codice. Per questo motivo per le costanti è obbligatorio inizializzare la costante nel momento della sua dichiarazione.

#


### Undefined e null sono la stessa cosa?

Undefined e null non sono la stessa cosa. Al momento della dichiarazione di una variabile, se non la inizializiamo, all'interno di essa non solo non troveremo alcun dato memorizzato, ma la macchina non saprà neanche che tipo di dato o oggetto si tratti.  
Null invece indica che all'interno della variabile non vi è alcun dato memorizzato, ma la macchina sa il tipo di dato con cui stiamo lavorando. Il null non equivale allo 0, poichè anche lo 0 è un dato, mentre null non lo è.  
Inoltre è possibili assegnare null ad una variabile per 'ripulirla', nel caso in cui vogliamo evitare di incorrere in eventuali errori. Mentre undefined non è possibile assegnarlo