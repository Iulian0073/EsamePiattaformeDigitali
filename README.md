---------------------
- Nome: Iulian      -
- Cognome: Condrea  -
- Matricola: 292904 -
---------------------



----------------------
-Titolo del progetto -
----------------------



-Manipolazione Dati Utente-



Il progetto è stato svolto con l'interfaccia Swagger Editor online.

Il servizio implementato offre 6 modalità di gestione dei dati dell'utente:

1. L'pzione "Crea Utente", ha l'abilità di creare diversi tipi di account con la compilazione
   di 8 campi tra cui Id, Nome Utente, Nome, Cognome, e-mail, Password e Cellulare.

2. L'opzione "Accesso Utenti", la quale è in grado di accedere ad un account precedentemente 
   creato con la compilazioine di Nome Utente e Password, quest'opzione disponde di 2 risposte
   ovvero il codice 200 il quale avverte che l'operazione è andata a buonfine e il codice 400
   che avverte l'utente l'invalidità di Nome Utente o Password.
   Inoltre l'opzione ha la funzionalità di concedere 3 tentativi di accesso all'ora.

3. L'opzione "Disconnessione Utente", dispone della disconnessione di un utente senza codici di
   successo o d'errore.

4. L'opzione "Ricerca Utente", dove si deve compilare l'unico campo con un nome utente, se l'opzione 
   avrà successo con il codice 200, verranno visualizzate tutte le informazioni riferenti all'utente 
   inserito, invece se si sbagli a digitare il nome utente, in uscita si verificherà il codice 400 
   che avviserà l'invalidità del nome utente fornito e si può verificare anche il codice 404 ovvero
   che l'utente inserito non è stato trovato

5. L'opzione "Aggiornamento Utente", dà la possibilità di modificare i dati di un utente inserito nella 
   barra "Nome Utente" come se si rifacesse la registrazione dell'utente, quest'opzione ha in uscita 2 
   codici, 400 e 404, ovvero Utente fornito invalido e Utente non trovato.

6. L'opzione "Cancellazione Utente" dispone dei permessi di eliminare un intero account solamente inserendo
   il nome utente, anche questo ha 2 codici d'errore, 400 e 404, Utente fornito invalido e Utente non trovato.


Come implementazione url ho utilizzato quello fornito gratuitamente dall'OPenAPI ovvero:
petstore.swagger.io