### Caso d'Uso: Visualizzare i voli

**Descrizione:** Visualizzazione dei voli disponibili.

**Scopo:** Consentire agli utenti visitatori e registrati di visualizzare l'elenco dei voli.

**Attori:** Utente visitatore, Utente registrato

**Attore Primario:** Utente visitatore

**Use Case d'extend:** Check-in online

**Scenario Principale:**
1. **Entry Condition:** Il caso d'uso inizia quando un utente decide di visualizzare i voli.
2. **Flusso di Eventi:**
   - L'utente accede alla sezione "Visualizza Voli" del sito.
   - Il sistema mostra l'elenco dei voli disponibili.

**Exit Condition:**
Il caso d'uso termina quando l'utente ha visualizzato l'elenco dei voli.

**Scenari Alternativi:**
- L'utente può filtrare i voli per destinazione, data, compagnia aerea, ecc.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante la visualizzazione dei voli, viene mostrato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene visualizzato un messaggio informativo e l'utente non può visualizzare l'elenco dei voli temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la disponibilità e l'aggiornamento in tempo reale delle informazioni sui voli.

**Extension Points:**
- Dopo la visualizzazione dei voli, l'utente può estendere il caso d'uso effettuando il check-in online.

**Frequenza Stimata di Utilizzo:**
- Frequente: Ogni volta che un utente desidera consultare l'elenco dei voli disponibili.

**Criticità:**
- Media: La visualizzazione dei voli è una funzionalità importante ma non critica per la sicurezza del sistema.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)
