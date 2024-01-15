### Caso d'Uso: Iscriversi al sito

**Descrizione:** Registrazione di un nuovo utente nel sistema.

**Scopo:** Consentire agli utenti visitatori di diventare utenti registrati.

**Attori:** Utente visitatore

**Attore Primario:** Utente visitatore

**Use Case d'extend:** Accedere al sito

**Scenario Principale:**
1. **Entry Condition:** Il caso d'uso inizia quando un utente visitatore decide di registrarsi.
2. **Flusso di Eventi:**
   - L'utente visitatore clicca sul pulsante di registrazione.
   - Compila il modulo di registrazione con le informazioni richieste.
   - Invia il modulo.
3. **Exit Condition:** Il caso d'uso termina quando il sistema registra con successo le informazioni del nuovo utente e lo autentica automaticamente nel sistema.

**Scenari Alternativi:**
- Se l'utente inserisce informazioni non valide, il sistema mostra un messaggio di errore.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante la registrazione, viene visualizzato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene mostrato un messaggio informativo e l'utente non può registrarsi temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la sicurezza delle informazioni durante il processo di registrazione.

**Extension Points:**
- Dopo la registrazione, l'utente può estendere il caso d'uso accedendo al sito.

**Frequenza Stimata di Utilizzo:**
- Frequente: Ogni volta che un utente desidera diventare un utente registrato.

**Criticità:**
- Alta: La registrazione è una funzionalità critica per permettere agli utenti di accedere al sistema.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)
