### Caso d'Uso: Accedere al sito

**Descrizione:** Accesso al sistema per gli utenti registrati.

**Scopo:** Consentire agli utenti visitatori e registrati di accedere al sistema.

**Attori:** Utente visitatore, Utente registrato

**Attore Primario:** Utente visitatore

**Use Case d'extend:** Visualizzare i voli

**Scenario Principale:**
1. **Entry Condition:** Il caso d'uso inizia quando un utente decide di accedere al sistema.
2. **Flusso di Eventi:**
   - L'utente inserisce le credenziali di accesso.
   - Il sistema verifica le credenziali.
   - Se le credenziali sono valide, l'utente viene autenticato e reindirizzato alla home page.

**Exit Condition:**
Il caso d'uso termina quando l'utente autenticato è reindirizzato alla home page del sito.

**Scenari Alternativi:**
- Se le credenziali sono errate, il sistema mostra un messaggio di errore e l'utente può riprovare ad accedere.
- Se l'utente ha dimenticato la password, può selezionare l'opzione "Password dimenticata" per reimpostarla.

**Flussi Alternativi:**
- Se il sistema riscontra problemi tecnici durante la verifica delle credenziali, viene mostrato un messaggio di errore generico.

**Eccezioni:**
- Se il sistema è in manutenzione, viene visualizzato un messaggio informativo e l'utente non può accedere temporaneamente.

**Requisiti Speciali:**
- Il sistema deve garantire la sicurezza delle credenziali durante il processo di accesso.

**Extension Points:**
- Dopo l'accesso, l'utente può estendere il caso d'uso navigando verso altre sezioni del sito.

**Frequenza Stimata di Utilizzo:**
- Frequente: Ogni volta che un utente desidera accedere al sito.

**Criticità:**
- Media: L'accesso è una funzionalità critica, ma non implica modifiche significative al sistema.

**Specializza il Caso d'Uso (opzionale):**
- (Nessuna specializzazione)

**Generalizza il Caso d'Uso (opzionale):**
- (Nessuna generalizzazione)


