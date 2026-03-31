30/03
Esercizio definizione dei requisiti:
partiamo da una legacy codebase
REQUISITI:
sistema di login (username e password)
dati forniti dal catasto (excel)
- inseriti manualmente nel sistema da addetti (possibile automazione)
- preferibilmente ottenerlo in tempi brevi tramite documento online
- excel verrà fornito a noi
- importante mantenere lo storico (ogni giorno), se tutto sullo stesso server (dati nuovi e backup) importante spostare in un altro server.
- dal momento che vengono ricevuti 20 excel ogni mese (relativmanete pochi), non ha senso andare a cambiare il formato, ovvero il protocollo che ha l’azienda con il catasto su come rappresenta i dati.
macro-catorie di utenti di sistema (amministratori [admin informatico], responsabili di area [cliente con cui sto parlando che può fare praticamente tutto, disabilitare, inserire], dipendenti[con priviligi limitati])
vuole che le tasse siano calcolare tramite un algoritmo (legacy già utilizzato) che si basa su diversi aspetti, tipo di terreno o altri dettagli.
- l’algoritmo esiste, ovvero avremo il codice (visual basic) che avrebbe bisogno di una modernizzazione (in realtà, se funziona, molto spesso non conviene tradurlo o modernizzarlo, molto spesso si evita molti problemi o bug che si possono evitare).
- ogni mese calcolo delle tasse, in base al tipo della tassa si hanno modalità e tempi di pagamento diversi (già fatto dall’algoritmo legacy (domanda importante)?  Cliente: ‘Si lo fa già’)

automazziare una catena, del tipo: calcolo tasse -> creazione pdf da inviare -> preparazione mail con pdf allegato -> semplice bottone per l’invio delle mail.
Avete un contratto del Cloud? Che tipo di database utilizzi o hai a disposizione? Con quanti dati lavorate? Cliente: ‘Si ci piacerebbe migrare a cloud? Noi; ‘Chi paga?’
il nuovo software deve avere interfaccia grafica simile a quella precedenze, questo richiede che gli utilizzatori siano foramti successivamente.
- Richiesta possibilità di filtrare per un certo argomento (concetto di ‘la fame vien mangiando’, ‘Le piacerebbe avere anche un filtro per codice fiscale/privincia?’ e così via)
gli utilizzatori (circa 5 o 6 dipendenti) utilizzano macchine windows 7, in cui solo un pc ha accesso ad internet per l’invio delle mail e sono collegati al server interno all’zienda tramite lan. In questi casi, per motivi di compatibilità o supporto hardware, conviene assolutamente migrare su Cloud, in modo che possiamo evitare ed astrarre complessità del tipo migrazione hardware, aggiornamenti o altro che porta via tempo e soldi.
possibile implementazione di pagina web per dare la possibilità di visualizzare dati pubblici a clienti (dell’azienda con cui stiamo parlando), possibile implementazione di login tramite SPID.
- quanti utenti ci aspettiamo su questa pagina web? Quanti sono gli agricoltori o proprietari terrieri? Se sono 20 nessun problema, ma se sono 10000 allora bisogna prendere determinate decisioni tecniche.
richiesta gestione e creazione di file di log (visibile solo ad alcuni utenti aziendali)
Domanda da fare: ‘Volete un app mobile?’, ‘Per caso volete che i dipendenti possano lavorare in smart? (risolutore di molti problemi)’, risposta: ‘si, 2 o 3 volte alla settimana’.
AFTERMARKET: manutenzione di almeno 6/12 mesi inclusa


macro-aree di un progetto: login, grafica, business logi, persistenza e logging, bisogna aspettarsi e vedremo che molti servizi quasi il 60% sono già implementati da servizi pre-esistenti, come login di google ad esempio.
Chiaramente poi li si considera il budget e il pagamento dei servizi.