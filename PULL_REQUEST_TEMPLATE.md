## Descrizione
<!-- Spiega cosa fa questa PR in 2-3 righe -->

## Tipo di cambiamento
- [ ] Bug fix
- [ ] Nuova feature
- [ ] Refactor / miglioramento
- [ ] Documentazione
- [ ] Infrastruttura / config

## Checklist obbligatoria

### 🔐 Sicurezza — VERIFICARE PRIMA DEL MERGE
- [ ] **Nessuna API key, token o secret nel codice** (niente in chiaro, niente in commenti)
- [ ] **Nessun file .env committato** (verificare con `git diff --name-only`)
- [ ] **Nessuna credenziale hardcodata** (password, connection string, webhook URL con token)
- [ ] Variabili sensibili gestite tramite GitHub Secrets o file .env escluso da .gitignore

### ✅ Qualità
- [ ] Il codice è stato testato localmente
- [ ] Non ci sono console.log / print di debug lasciati
- [ ] Il branch è aggiornato rispetto a main

### 📋 Documentazione
- [ ] README aggiornato se necessario
- [ ] Commenti aggiunti dove il codice non è autoesplicativo

## Note per il reviewer
<!-- Cosa deve guardare con attenzione il reviewer? Ci sono decisioni architetturali da discutere? -->
