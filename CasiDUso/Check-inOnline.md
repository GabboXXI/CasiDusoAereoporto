### Caso d'Uso: Check-in Online

**Descrizione:** Effettuare il check-in online per un volo.

**Scopo:** Consentire agli utenti registrati, amministratori e compagnie aeree di effettuare il check-in online.

**Attori:** Utente registrato, Amministratore, Compagnia aerea

**Attore Primario:** Utente registrato

**Use Case d'extend:** Prenotazione Lounge

**Scenario Principale:** L'utente si collega al sito web dell'aeroporto per effettuare il check-in online in modo pratico e veloce.
1. **Entry Condition:** Il caso d'uso inizia quando un utente registrato o un amministratore decide di effettuare il check-in online.
2. **Flusso di Eventi:**
   - L'utente accede alla sezione "Check-in Online" del sito.
   - Seleziona il volo desiderato.
   - Compila le informazioni richieste.
   - Conferma il check-in.

**Exit Condition:**
Il caso d'uso termina quando il sistema registra con successo il check-in online.

**Scenari Alternativi:**
- Se il check-in online non è disponibile per il volo selezionato, il sistema mostra un messaggio informativo.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante il check-in online, viene visualizzato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene visualizzato un messaggio informativo e l'utente non può effettuare il check-in online temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la disponibilità e la validità delle informazioni relative al check-in.

**Extension Points:**
- Dopo il check-in online, l'utente può estendere il caso d'uso prenotando l'accesso a una lounge.

**Frequenza Stimata di Utilizzo:**
- Frequente: Ogni volta che un utente desidera effettuare il check-in per un volo.

**Criticità:**
- Media: Il check-in online è una funzionalità importante, ma non critica per la sicurezza del sistema.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)
