# Sistemi di Elaborazione (A.A. 2018/19)

Sito Web del corso di "Sistemi di Elaborazione" (modulo di Architettura degli Elaboratori) del corso di laurea in Ingegneria delle Telecomunicazioni dell'Università di Pisa.

* Responsabile: [Nicola Tonellotto](http://pomino.isti.cnr.it/~khast/)
* CFU: 6
* Periodo: Secondo semestre
* Lingua: Italiano
* Lezioni: Lunedì 15:30-18:30 (SI3) e Martedì 16:30 - 18:30 (B23).
* Orario di ricevimento: Dopo le lezioni o tramite appuntamento (presso il CNR)
* Email: nicola [dot] tonellotto [at] isti [dot] cnr [dot] it

## Prerequisiti obbligatori

* Conoscenza di base del C/C++
* Strutture dati e algoritmi di base
* Concetti di sistemi operativi

Tutti questi prerequisiti sono soddisfatti dal corso di "Fondamenti di Informatica e Calcolatori" del primo anno.

## Libro di testo

David A. Patterson e John L. Hennessy

**Struttura e progetto dei calcolatori**

edito da Zanichelli (quarta edizione italiana condotta sulla quinta edizione americana)

[<img src="https://staticmy.zanichelli.it/catalogo/assets/small/m40001.9788808352026.jpg">]

## Esame

L'esame consiste una prova orale, composta da una prima parte sul modulo "Programmazione Avanzata in Ambiente UNIX" da compilare in forma scritta e da discutere con la commissione d'esame, seguita da una seconda parte sul modulo "Architetture degli Elaboratori" da discutere con la commissione d'esame.

## Lezioni

|Data|Orario|Argomenti|Slide|
|:--:|:---------:|------|:----:|
|04/03|15:30-18:30|Introduzione, componenti di un calcolatore, livelli di astrazione. Prestazioni dei processori: latenza, throughput, speedup. Tempo di esecuzione e sue componenti: clock, IC, CPI. Esempi.|[PDF](slides/capitolo1.pdf)
|05/03|16:30-18:30|Esercizi sul calcolo delle prestazioni dei processori. Rappresentazione delle istruzioni: operazioni aritmetiche e operandi su registri. |[PDF](slides/capitolo2.1.pdf)
|18/03|15:30-18:30|Operandi in memoria. Oprezioni load word e store word. Operazioni con operando immediato. costante zero. Interi senza segno e in complemento a 2. Estensione di segno. Architettura a programma memorizzato. Istruzioni in formato R. Istruzioni in formato I. Esercizi sul codice assembly MIPS e sul calcolo delle prestazioni dei processori. |[PDF](slides/capitolo2.2.pdf)
|19/03|16:30-18:30| Concetto di programma memorizzato. Operazioni logiche e di shift. Operazioni condizionali e di salto. Invocazione delle procedure. Esempi con procedure foglia e non-foglia. Registri SP, FP e GP.|[PDF](slides/capitolo2.3.pdf)
|25/03|15:30-18:30|Operazioni assembler su byte e halfword. Esempo copia_stringa. Salti. Modalità di indirizzamento. Traduzione e avvio dei programmi. Esempio bubblesort. Cenni su ISA x86. Esercizi su operazioni logiche e di shift. Esercizi sulla comprensione di porzioni di codice assembler.|[PDF](slides/capitolo2.4.pdf)
|02/04|16:30-18:30| Aritmetica per elaboratori. Sommatore a 1 bit. Addizione e sottrazione intere. Gestione dell'overflow. Moltiplicazione intera. Virgola mobile e standard IEEE Std 754-1985. Formati a singola e doppia precisione. Somma in virgola mobile. Cenni di parallelismo sui dati. |[PDF](slides/capitolo3.pdf)
|08/04|15:30-18:30| Esecuzione di un'istruzione: fetch, decode, execute. Multiplexer. Basi della progettazione logica: elementi combinatori e sequenziali. Clock e temporizzazione. Istruzioni in formato R, load/store, di salto. Composizione degli elementi logici. Unità di elaborazione completa. Cenni sull'unità di controllo. Esercizi sulla comprensione di porzioni di codice assembler.|[PDF](slides/capitolo4.1.pdf)
|09/04|16:30-18:30| Unità di controllo e controllore della ALU. Elaborazione di istruzioni di tipo R, load e branch on equal. Elaborazione dell'istruzione jump. Problemi di prestazioni. Pipelining nel processore. Prestazioni della pipeline. Progettazione del processore con pipeline.|[PDF](slides/capitolo4.2.pdf)
