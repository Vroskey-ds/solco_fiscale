Il professore si è impersonificato in un cliente, vuole farci ragionare come "business analyst" per 
insegnarci al meglio il corso di progetto del software.

Si è finto un azienda che ho chiamato io "solco fiscale", che è una azienda regionale che si occupa della
gestione di calcolo e notifica all'utente delle tasse che deve pagare in base alla terra.

Hanno già un sistema, ma gira su windows 7 ed è in una lan chiusa, il programma di calcolo gira su visual basic.
La loro predisposizione è anche quella di modernizzarsi e quindi valutano l'ipotesi di una migrazione cloud.

In tal caso bisogna proporre 2 opzioni, quella di mantenere i loro sistemi attivi senza introdurre il cloud.

Oppure proporre una opzione di migrazione in cloude su azure, in quanto ci hanno detto che è possibile per 
loro avere delle licenze microsoft per la durata di circa 15 anni.

Bisogna anche proporre degli adattamenti sul loro workflow. 
Essendo un'azienda regionale la migrazione potrà avvenire dal venerdì sera ed essere operativa il lunedì mattina.

Oppure adottare una misura graduale che permette ai dipendenti e responsabili di potersi adattare.

Per fare la piattaforma proporrei una soluzione web in quanto i dipendenti sono in smart working (lavoro da remoto) 2 giorni alla settimana, e in quel caso non potrebbero lavorare alle funzionalià di calcolo delle tasse.

La piattaforma deve prevedere un login, che essendo in cloud potrebbe essere gestita direttamente da microsoft, 
dovrebbe poter consentire un servizio di login incluso con l'hosting cloud.

Il sistema  deve avere 3 tipi di utenti: Amministratori - Responsabile Area - Utente normale.

    - Amministratori: Noi admin che possiamo tenere un accesso per qualsiasi tipi di problemi
    - Responsabile Area: Responsabile che deve approvare(ogni 30 giorni l'invio al cliente) e poter cancellare le richieste di tasse.
    -Utente normale: Dipendente che può solo confermare le informazioni sui terreni che arrivano.


Al momento i dati catastali su cui vanno calcolate le tasse arrivano ogni 30 giorni su un foglio excel di al 
massimo 20 righe, non è automatizzato al momento, c'è un dipendente che li inserisce a mano.

La nostra proposta può contenere un sistema automatico che quando riceve questi dati dal catasto 
elabora il file excel e crea delle insert al database in automatico che permette al dipendente o responsabile di 
approvarle per effettivamente inserire nel database.

Deve essere possibile avere uno storico e i log di chi ha fatto determinate operazioni.

Il budget di questo progetto è 50.000/60.000 €, dati da un bando.

Per mandare i dati agli agricoltori sarebbe una bella implementazione gradita quella che ogni 30 giorni il responsabile abbia la possibilità dalla piattaforma di: visonare il resoconto tramite un pdf di tutte le tasse che gli agricoltori devono mandare e poter accettare per permettere l'invio automatico a tutti i soggetti interessati.

