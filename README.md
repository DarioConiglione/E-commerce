E-Commerce Project 
Questo progetto è un'applicazione e-commerce full-stack sviluppata partendo da zero. Il mio focus è stato sul backend, ove progettato e implementato l'intero flusso di gestione degli ordini, dalla convalida dei dati di checkout alla persistenza su database relazionale, fino alla notifica automatica all'utente.

🛠 Tech Stack (Backend)
Node.js & Express: Architettura del server e gestione delle API RESTful.

MySQL: Database relazionale per la memorizzazione sicura di ordini e dati utente.

MailTrap: Integrazione SMTP per il testing e l'invio delle email di conferma.

Dotenv: Gestione sicura delle variabili d'ambiente e delle credenziali sensibili.

🏗 Contributo Tecnico: Flusso dell'Ordine e Logica di Business
Il mio lavoro si è concentrato sulla creazione di un sistema robusto per la finalizzazione dell'acquisto.

1. Architettura del Database & Relazioni
Ho progettato la struttura MySQL focalizzandomi sulla tabella Ordini.

Schema Relazionale: Creazione di tabelle ottimizzate per collegare i dati anagrafici dell'utente, i dettagli della spedizione e i prodotti acquistati.

Integrità dei dati: Implementazione di vincoli nel DB per garantire che ogni ordine sia correttamente associato a un utente e a un set di dati validi.

2. Processo di Checkout & Persistenza
Ho sviluppato i Controller e i Router necessari per gestire la transazione:

Ricezione Dati: Gestione dei dati inviati dal frontend (informazioni di pagamento simulate e dati personali).

Logica di Scrittura: Una volta validati i dati, il sistema aggiorna la tabella degli ordini in tempo reale, garantendo che ogni acquisto sia tracciato correttamente nel sistema.

3. Sistema di Notifica Automatica (Email Service)
Per migliorare l'esperienza utente (UX), ho integrato un servizio di messaggistica post-acquisto:

Integrazione MailTrap: Configurazione del server SMTP per l'invio di email transazionali.

Email di Conferma: Al termine della scrittura sul DB, il sistema invia automaticamente un'email all'utente con il riepilogo dell'ordine, confermando l'avvenuto acquisto.

