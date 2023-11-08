# Esercizio M2 W1D1 Epicode

## Rispondi alle seguenti domande:

- Cos'è un Algoritmo?
- Cos'è una Variabile
- "Undefined" e "Null" sono la stessa cosa?

# L'Algoritmo..

> _L' Algoritmo è la risoluzione di un determinato problema spiegato passo dopo passo_ 

Possiamo immaginarlo come un libretto delle istruzioni per il montaggio di un mobile Ikea.
In questo esempio, il "Problema" è montare correttamente il mobile e "l'Algoritmo" il libretto delle istruzioni, che come ben sappiamo, indica tutta l'attrezzatura a nostra disposizione e di cui abbiamo bisogno, poi tutti i passaggi passo dopo passo da quelli preliminari a quelli più elaborati.
Questo è uno degli esempi più semplici per poter spiegare cos'è un algoritmo, c'è da sapere però che in molti casi non esiste un unico algoritmo alla risoluzione di un determinato problema. Esistono molti altri problemi (spesso più complessi) che possono avere diversi algoritmi per arrivare alla soluzione, ed in quel caso la differenza tra i vari algoritmi sono i "tempi di risoluzione" e la quantità di dati utilizzati 
(materia che  viene studiata in informatica dal nome Calcolo Numerico e Algoritmi e strutture dati) ovvero la latenza di un algoritmo rispetto ad un altro, un esempio di questo problema avveniva anni fà sul calcolo delle previsioni Meteo dove i calcolatori dell'epoca non avevano una grande potenza di calcolo e l'algoritmo impiegava molto tempo nel dare una risposta e a quel punto le variabili analizzate erano già cambiate, e dato che i materiali per potenziarli erano anche molto costosi, si pensò di studiare e creare un algoritmo migliore con una latenza inferiore.


# Le Variabili...

> _Le variabili sono contenitori di informazioni/dati necessari per la risoluzione di un problema._

Seguendo l'esempio (citato prima nella spiegazione dell'algoritmo) riguardo il libretto di istruzioni del mobile Ikea, le variabili le identifichiamo come il materiale a nostra disposizione che ci permettono di montare il mobile, sono quindi, elementi essenziali senza il quale non potremmo risolvere il problema.
Per fare un esempio ancora più esaustivo potremmo far riferimento ai semplici problemi di geometria delle scuole elementari, quando ci veniva richiesto di calcolare l'area di un rettangolo. 
Per la risoluzione di tale problema ci venivano fornite delle "informazioni" o "dati" del rettangolo per poter applicare la "formula" (cio'è l'algoritmo). Ecco, tali dati solo le variabili.
In informatica questi dati possono essere di tipi diversi: 
- Stringhe
- Numeri interi
- Numeri reali
- Booleani (vero o falso)
- Array (liste)
- Oggetti / Classi

Li definiamo contenitori proprio per il fatto che possono contenere informazioni di vario tipo ed inoltre hanno la facoltà di cambiare il loro valore/contenuto nel corso delle istruzioni.
In alcuni linguaggi, però, questi contenitori sono forzatamente "Tipizzati" (Es. Java), cio'è viene assegnato in fase di creazione il tipo di contenuto che andrà a memorizzare. 
Es:
```sh
String name;
int age;
```
In questi casi, i dati possono variare ma devono mantenere la coerenza del tipo di dato.


# Differenza tra "Undefined" e "Null"...

> _Il tipo di dato Undefined è un dato creato ma NON assegnato mentre il tipo di dato Null è un dato creato ed assegnato come VUOTO._


Ci si potrebbe confondere pensando al fatto che effettivamente entrambe non hanno alcun dato interno,
ma il dato undefined ci fa capire che non è stato proprio mai assegnato un valore e di conseguenza il sistema non riesce a capire che tipo di dato sia, quindi ci risponde con "indefinito".