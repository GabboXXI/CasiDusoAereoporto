### Caso d'Uso: Gestire Voli

**Descrizione:** Gestione delle informazioni e delle operazioni legate ai voli.

**Scopo:** Consentire agli utenti registrati e agli amministratori di gestire le informazioni e le operazioni legate ai voli.

**Attori:** Utente registrato, Amministratore

**Attore Primario:** Amministratore

**Use Case d'extend:** (Nessuno)

**Scenario Principale:**
1. **Entry Condition:** Il caso d'uso inizia quando un amministratore o un utente registrato decide di gestire i voli.
2. **Flusso di Eventi:**
   - L'amministratore accede alla sezione "Gestione Voli" del sistema.
   - Visualizza l'elenco dei voli esistenti.
   - Modifica informazioni sui voli (orari, destinazioni, compagnie aeree, ecc.).
   - Aggiunge nuovi voli al sistema.
   - Cancella voli esistenti.

**Exit Condition:**
Il caso d'uso termina quando l'amministratore completa le operazioni di gestione dei voli.

**Scenari Alternativi:**
- L'utente registrato potrebbe avere accesso limitato alla modifica delle informazioni sui voli, principalmente per quanto riguarda la prenotazione.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante la gestione dei voli, viene visualizzato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene visualizzato un messaggio informativo e gli utenti non possono gestire i voli temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la coerenza e la validità delle informazioni sui voli.

**Extension Points:**
- Dopo la gestione dei voli, l'amministratore o l'utente registrato possono estendere il caso d'uso effettuando il check-in online o prenotando una lounge.

**Frequenza Stimata di Utilizzo:**
- Moderata: Gli amministratori potrebbero gestire i voli in base alle necessità di pianificazione e aggiornamento del sistema.

**Criticità:**
- Alta: La gestione dei voli è una funzionalità critica per mantenere aggiornato il sistema e fornire informazioni precise agli utenti.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)
