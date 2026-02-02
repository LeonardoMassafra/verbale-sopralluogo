# 🚀 Guida Setup GitHub Pages - Passo per Passo

## ✅ Requisiti

- Account GitHub (gratis su https://github.com)
- 5 minuti di tempo
- I file del progetto (che hai già!)

---

## 📋 PROCEDURA COMPLETA

### STEP 1: Crea Account GitHub (se non ce l'hai)

1. Vai su **https://github.com**
2. Click su **Sign up**
3. Inserisci email, password, username
4. Verifica email
5. ✅ Account creato!

---

### STEP 2: Crea Repository

1. Vai su **https://github.com/new**
   
2. Compila il form:
   - **Repository name:** `verbale-sopralluogo`
   - **Description:** "Sistema gestione verbali sopralluogo"
   - **Visibility:** ⚪ Public (IMPORTANTE per GitHub Pages gratis!)
   - **Initialize:** ❌ NON selezionare nulla (README, .gitignore, license)

3. Click **Create repository**

✅ Repository creato! Vedrai una pagina con istruzioni.

---

### STEP 3: Carica i File

**METODO A - Upload Web (PIÙ SEMPLICE):**

1. Nella pagina del repository, click su:
   ```
   uploading an existing file
   ```

2. **Trascina** il file `index.html` nella finestra
   (oppure click "choose your files" e selezionalo)

3. In basso:
   - Commit message: "Aggiungi webapp verbale sopralluogo"
   - Click **Commit changes**

4. Ripeti per `README.md` se vuoi includere la documentazione

✅ File caricati!

---

**METODO B - Git da Terminale (Avanzato):**

```bash
# Clona il repository
git clone https://github.com/[TUO-USERNAME]/verbale-sopralluogo.git
cd verbale-sopralluogo

# Copia i file
# (copia index.html, README.md nella cartella)

# Commit e push
git add .
git commit -m "Initial commit - Verbale Sopralluogo WebApp"
git push origin main
```

---

### STEP 4: Attiva GitHub Pages

1. Nel repository, click su **⚙️ Settings** (tab in alto)

2. Nel menu laterale sinistro, scorri fino a **Pages**

3. Nella sezione "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** main (o master se non vedi main)
   - **Folder:** / (root)

4. Click **Save**

5. Vedrai il messaggio:
   ```
   ✅ Your site is ready to be published at:
   https://[tuo-username].github.io/verbale-sopralluogo/
   ```

⏱️ **Attendi 1-2 minuti** per il deploy

---

### STEP 5: Verifica

1. Copia l'URL: `https://[tuo-username].github.io/verbale-sopralluogo/`

2. Aprilo nel browser

3. ✅ **Dovrebbe funzionare!**

---

## 📱 Aggiungi alla Home del Telefono

### iPhone/iPad:

1. Apri l'URL in **Safari**
2. Click sull'icona **Condividi** 🔖 (in basso al centro)
3. Scorri e seleziona **"Aggiungi alla schermata Home"**
4. Scegli un nome (es. "Verbale Sopralluogo")
5. Click **Aggiungi**

✅ Ora hai l'icona come una vera app!

### Android:

1. Apri l'URL in **Chrome**
2. Menu **⋮** (in alto a destra)
3. **"Aggiungi a Home"** o "Installa app"
4. Conferma

✅ App aggiunta alla home!

---

## 🔄 Come Aggiornare l'App

Quando vuoi modificare l'app:

1. Modifica `index.html` localmente
2. Vai sul repository GitHub
3. Click su `index.html`
4. Click sull'icona **matita** ✏️ (in alto a destra)
5. Modifica il file
6. Scroll in basso → **Commit changes**

⏱️ L'aggiornamento sarà online in 1-2 minuti!

**Su mobile:** Ricarica la pagina (swipe down) per vedere le modifiche.

---

## 🆘 Problemi Comuni

### "Non vedo il tab Pages in Settings"
- Il repository deve essere **Public**
- Vai in Settings → General → Danger Zone → Change visibility → Public

### "404 - File not found"
- Assicurati che il file si chiami **index.html** (non Index.html o index.htm)
- Controlla di averlo caricato nella root del repository

### "La pagina è bianca"
- Apri Console del browser (F12)
- Controlla errori JavaScript
- Verifica che il file sia valido HTML

### "I pulsanti non funzionano"
- ✅ Su **iPhone** DEVE essere servito da web (GitHub Pages funziona!)
- ❌ File locale su iPhone NON funziona (limitazione Safari)

### "Ho perso i dati quando cambio URL"
- localStorage è legato al dominio
- Esporta JSON prima di cambiare URL
- Importa JSON nel nuovo URL

---

## 🎯 URL Personalizzato (Opzionale)

Vuoi un URL più carino tipo `verbale.tuodominio.com`?

1. In Settings → Pages → Custom domain
2. Inserisci il tuo dominio
3. Configura DNS del dominio:
   ```
   CNAME → [tuo-username].github.io
   ```

📘 Guida completa: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

---

## ✅ Checklist Finale

- [ ] Account GitHub creato
- [ ] Repository pubblico creato
- [ ] File index.html caricato
- [ ] GitHub Pages attivato
- [ ] URL funzionante in browser desktop
- [ ] URL funzionante su iPhone/Android
- [ ] App aggiunta alla Home (opzionale)
- [ ] Test compilazione verbale
- [ ] Test export PDF
- [ ] Test salvataggio dati

---

## 🎉 FATTO!

Hai la tua webapp professionale online, funzionante su tutti i dispositivi!

**URL da condividere con colleghi:**
```
https://[tuo-username].github.io/verbale-sopralluogo/
```

Segnalo e usa! 🚀📱
