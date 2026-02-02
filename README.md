# 📋 Verbale di Sopralluogo - WebApp

Sistema completo per la gestione digitale dei verbali di sopralluogo cantiere.

## 🌐 Demo Online

**URL:** https://[tuo-username].github.io/verbale-sopralluogo/

## ✨ Caratteristiche

- ✅ **Funziona su tutti i dispositivi** (Desktop, Tablet, Smartphone)
- ✅ **Compilazione diretta da cantiere** con tablet/smartphone
- ✅ **Salvataggio automatico** in localStorage
- ✅ **Upload foto** con compressione automatica
- ✅ **Export PDF professionale** con foto incluse
- ✅ **Export JSON** ottimizzato per AI (Claude/ChatGPT)
- ✅ **Firme digitali** con dito/stylus
- ✅ **Offline-ready** dopo primo caricamento

## 🚀 Setup GitHub Pages (5 minuti)

### Passo 1: Crea Repository

1. Vai su https://github.com/new
2. Nome repository: `verbale-sopralluogo`
3. Visibilità: **Public** (per GitHub Pages gratis)
4. ✅ Crea repository

### Passo 2: Carica Files

**Opzione A - Web Interface:**
1. Click su "uploading an existing file"
2. Trascina `index.html` nella pagina
3. Click "Commit changes"

**Opzione B - Git CLI:**
```bash
git clone https://github.com/[tuo-username]/verbale-sopralluogo.git
cd verbale-sopralluogo
# Copia index.html nella cartella
git add .
git commit -m "Initial commit"
git push
```

### Passo 3: Attiva GitHub Pages

1. Vai in **Settings** del repository
2. Sezione **Pages** (menu laterale sinistro)
3. Source: **Deploy from a branch**
4. Branch: **main** (o master)
5. Folder: **/ (root)**
6. Click **Save**

⏱️ Attendi 1-2 minuti

### Passo 4: Verifica

Vai su: `https://[tuo-username].github.io/verbale-sopralluogo/`

✅ Dovrebbe funzionare perfettamente su iPhone, Android, Desktop!

---

## 📱 Uso su Mobile

### iPhone/iPad (Safari):
1. Apri l'URL nel browser
2. Click su 🔖 Condividi
3. "Aggiungi a Home"
4. Ora hai l'icona come una app!

### Android (Chrome):
1. Apri l'URL nel browser
2. Menu ⋮ → "Aggiungi a Home"
3. L'app appare nella home!

---

## 📸 Gestione Foto

### Limiti Ottimizzati:
- **Checklist:** max 20 foto
- **Documentazione:** max 30 foto
- **Compressione automatica:** 1200x1200px, qualità 80%
- **Dimensione stimata:** ~80 KB per foto

### Totale Consigliato:
- Verbale normale: 5-10 foto ✅
- Verbale complesso: 20-30 foto ✅
- Verbale fotografico: 40-50 foto ⚠️

---

## 💾 Salvataggio Dati

### localStorage (Automatico):
- Salvataggio continuo mentre compili
- Dati persistono anche chiudendo browser
- **Limite:** ~5 MB

### Export JSON:
- Dati senza immagini (ottimizzato)
- Backup e trasferimento dispositivi
- Import in Claude/ChatGPT per relazioni

### Export PDF:
- Documento completo con foto
- Pronto per archiviazione/firma
- Dimensioni dipendono dalle foto

---

## 🔧 Aggiornamenti

Per aggiornare l'app:

1. Modifica `index.html` localmente
2. Carica su GitHub (push o upload web)
3. GitHub Pages si aggiorna automaticamente (1-2 min)
4. **Mobile:** Ricarica pagina (pull to refresh)

---

## 🆘 Troubleshooting

### "I pulsanti non funzionano su iPhone"
- ✅ **Soluzione:** Usa l'URL online, NON il file locale
- File locali sono bloccati da Safari per sicurezza

### "Ho perso i dati"
- localStorage è per-dominio
- Se cambi URL, i dati non si trasferiscono
- **Soluzione:** Esporta JSON regolarmente

### "Le foto occupano troppo spazio"
- Esporta PDF con foto correnti
- Click "🔄 Nuovo" per svuotare localStorage
- Inizia nuovo verbale

### "Voglio personalizzare"
- Modifica `index.html`
- Cerca `<!-- Sezioni -->` per struttura
- Cerca `<style>` per colori/layout
- Cerca `const FOTO_CONFIG` per limiti foto

---

## 📊 Uso con AI

### Generare Relazione con Claude:

1. Esporta JSON dal verbale
2. Carica in Claude (claude.ai)
3. Prompt esempio:

```
Ho un verbale di sopralluogo in formato JSON.

[Incolla JSON]

Scrivi una relazione professionale che includa:
1. Sintesi dello stato lavori
2. Analisi delle non conformità con priorità
3. Piano d'azione con responsabili e scadenze
4. Raccomandazioni tecniche

Nota: Le foto sono disponibili nel PDF allegato.
```

### Con PDF:
- Carica PDF in Claude
- Claude vede foto + testo
- Può analizzare visivamente le criticità

---

## 📄 Licenza

Questo progetto è fornito "as-is" per uso interno aziendale.

---

## 🙋 Supporto

Per problemi o richieste:
1. Apri una Issue su GitHub
2. Descrivi il problema con screenshot
3. Indica dispositivo e browser usato

---

**Versione:** 2.1  
**Ultimo aggiornamento:** Febbraio 2026
