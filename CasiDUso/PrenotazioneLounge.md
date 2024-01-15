### Caso d'Uso: Prenotazione Lounge

**Descrizione:** Prenotazione dell'accesso a una lounge dell'aeroporto.

**Scopo:** Consentire agli utenti registrati e agli amministratori di prenotare l'accesso a una lounge.

**Attori:** Utente registrato, Amministratore

**Attore Primario:** Utente registrato

**Use Case d'extend:** Gestire voli

**Scenario Principale:**
1. **Entry Condition:** Il caso d'uso inizia quando un utente registrato decide di prenotare l'accesso a una lounge.
2. **Flusso di Eventi:**
   - L'utente accede alla sezione "Prenotazione Lounge" del sito.
   - Seleziona la lounge desiderata.
   - Sceglie la data e l'orario di accesso.
   - Conferma la prenotazione.

**Exit Condition:**
Il caso d'uso termina quando il sistema registra con successo la prenotazione dell'accesso alla lounge.

**Scenari Alternativi:**
- Se la lounge è piena per la data e l'orario desiderati, il sistema mostra un messaggio informativo e l'utente può scegliere un'altra data o orario.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante la prenotazione, viene visualizzato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene visualizzato un messaggio informativo e l'utente non può effettuare la prenotazione temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la disponibilità e la validità delle informazioni sulle lounge e gestire correttamente le prenotazioni.

**Extension Points:**
- Dopo la prenotazione della lounge, l'utente può estendere il caso d'uso gestendo i voli.

**Frequenza Stimata di Utilizzo:**
- Moderata: Gli utenti potrebbero effettuare la prenotazione sporadicamente in base alle necessità di viaggio.

**Criticità:**
- Bassa: La prenotazione della lounge è una funzionalità importante, ma non critica per la sicurezza del sistema.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)
