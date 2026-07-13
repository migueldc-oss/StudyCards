# Manuale Utente StudyCards

**Versione 1.1**  
**Piattaforme:** iOS 18+ • macOS 16+

---

## Indice

1. [Benvenuti](#1-benvenuti)
2. [Primi Passi](#2-primi-passi)
3. [Organizzazione e Ordinamento](#3-organizzazione-e-ordinamento)
4. [Modalità di Studio](#4-modalità-di-studio)
5. [Importare ed Esportare](#5-importare-ed-esportare)
6. [Condividere le Flashcard](#6-condividere-le-flashcard)
7. [Impostazioni](#7-impostazioni)
8. [Consigli](#8-consigli)

---

## 1. Benvenuti

Benvenuto in **StudyCards** — un'applicazione potente ed elegante per le flashcard su iOS e macOS. Crea, gestisci e studia le tue flashcard con supporto per formule LaTeX, immagini e funzionalità di import/export integrate.

![StudyCards — iOS](screenshots/ios/main.png)
![StudyCards — macOS](screenshots/macos/main.png)

**Funzionalità Principali:**

- **Gruppi di flashcard:** organizza le tue carte per argomento o materia.
- **Flashcard complete:** ogni carta ha un fronte e un retro con supporto per testo, formule LaTeX e immagini.
- **Riordinamento manuale:** trascina le flashcard per modificare l'ordine all'interno di un gruppo.
- **Modifica dei gruppi:** modifica o elimina i gruppi dal menu contestuale (premizione prolungata).
- **Ordinamento e ricerca:** ordina e cerca i gruppi per nome, data o numero di flashcard.
- **Modalità di studio:** valuta la tua conoscenza con Facile/Dubitato/Non sapevo.
- **Import ed export:** trasferisci le tue carte tramite file CSV o JSON (con immagini base64 incorporate).
- **Condivisione:** invia le tue flashcard via email, WhatsApp, AirDrop e altro.
- **Impostazioni personalizzabili:** aspetto, lingua e ordine di studio.
- **Design adattivo:** si adatta automaticamente a iPhone, iPad e Mac.

### Requisiti

- iOS 18.0 o successivo / macOS 16.0 o successivo.
- La connessione a Internet è necessaria solo per il rendering delle formule LaTeX (MathJax).

---

## 2. Primi Passi

### 2.1 Creare un Gruppo

I gruppi ti aiutano a organizzare le flashcard per argomento, materia o categoria.

**Procedura:**

1. Apri StudyCards.
2. Tocca il pulsante **+** nella schermata principale.
3. Inserisci un nome per il tuo gruppo (es. "Vocabolario Spagnolo", "Formule Matematiche").
4. Opzionalmente, aggiungi una descrizione per identificare il contenuto del gruppo.
5. Tocca **Salva** per confermare.

![Crea Gruppo](screenshots/ios/create_group.png)

![Crea Gruppo - macOS](screenshots/macos/create_group.png)

**Suggerimenti per organizzare i gruppi:**

- Usa nomi descrittivi per un'identificazione facile.
- Considera di creare gruppi per materia, capitolo o livello di difficoltà.
- Puoi creare quanti gruppi vuoti ne hai bisogno.

### 2.2 Modificare o Eliminare un Gruppo

Puoi modificare o eliminare un gruppo direttamente dall'elenco.

**Su iOS:**

1. Premi a lungo sul nome del gruppo fino a quando appare il menu contestuale.
2. Seleziona **Modifica** per modificare il nome o la descrizione.
3. Seleziona **Elimina** per rimuovere il gruppo e tutte le sue flashcard.

**Su macOS:**

1. Fai clic destro sul nome del gruppo.
2. Seleziona **Modifica** o **Elimina**.

> **Avviso:** Eliminare un gruppo rimuove permanentemente tutte le sue flashcard. Assicurati di esportarle prima se hai bisogno di un backup.

### 2.3 Creare una Flashcard

Una volta all'interno di un gruppo, puoi iniziare ad aggiungere flashcard.

**Procedura:**

1. Apri un gruppo toccandolo.
2. Tocca il pulsante **+**.
3. Inserisci il testo del **fronte** (la domanda o l'indicazione).
4. Inserisci il testo del **retro** (la risposta o la spiegazione).
5. Opzionalmente, aggiungi un'**immagine** toccando **Seleziona Immagine**.
6. Opzionalmente, aggiungi una **formula LaTeX** usando `$...$` (in linea) o `$$...$$` (a blocco).
7. Tocca **Salva**.

![Crea Flashcard](screenshots/ios/create_card.png)

![Crea Flashcard - macOS](screenshots/macos/create_card.png)

### 2.4 Aggiungere Formule LaTeX

StudyCards supporta il rendering LaTeX tramite MathJax per la notazione matematica e scientifica.

| Tipo | Sintassi | Esempio |
|------|----------|---------|
| In linea | `$f(x) = x^2$` | La funzione è $f(x) = x^2$ |
| A blocco | `$$\int_0^1 x^2 \, dx$$` | Formula su una riga separata |

**Esempi LaTeX:**

- **Equazione quadratica:** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Teorema di Pitagora:** `$a^2 + b^2 = c^2$`
- **Integrale definito:** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Nota:** Le formule vengono renderizzate automaticamente durante il salvataggio della carta e durante le sessioni di studio.

### 2.5 Aggiungere Immagini

Puoi allegare immagini alle tue flashcard per un apprendimento visivo.

**Procedura:**

1. Durante la creazione o la modifica di una flashcard, tocca **Seleziona Immagine**.
2. Scegli di scattare una nuova foto o selezionarne una dalla libreria.
3. L'immagine verrà allegata alla flashcard.

![Aggiungi Immagine](screenshots/ios/add_image.png)

![Aggiungi Immagine - macOS](screenshots/macos/add_image.png)

> **Nota:** Le immagini vengono automaticamente ridimensionate a un massimo di 1024 pixel per ottimizzare lo spazio di archiviazione. Quando esporti in formato JSON, le immagini vengono incluse in formato base64.

### 2.6 Eliminare una Flashcard

Puoi eliminare una flashcard scorrendo verso sinistra.

**Procedura:**

1. Nell'elenco delle flashcard, scorri la carta verso sinistra.
2. Apparirà un pulsante rosso **Elimina**.
3. Tocca **Elimina** per confermare.

![Scorri per Eliminare](screenshots/ios/swipe_delete.png)

![Scorri per Eliminare - macOS](screenshots/macos/swipe_delete.png)

> **Avviso:** L'eliminazione è permanente. Assicurati di esportare le tue carte prima di eliminarle se non hai un backup.

---

## 3. Organizzazione e Ordinamento

### 3.1 Riordinamento Manuale delle Flashcard

Puoi modificare l'ordine delle flashcard all'interno di un gruppo trascinandole.

**Su iOS:**

1. Apri il gruppo con le flashcard che vuoi riordinare.
2. Tocca **Modifica** nella barra degli strumenti (angolo in alto a sinistra).
3. Appariranno le maniglie di trascinamento ⟟ accanto a ogni flashcard.
4. Trascina la flashcard nella posizione desiderata.
5. Tocca **Fine** per salvare il nuovo ordine.

**Su macOS:**

1. Apri il gruppo con le flashcard che vuoi riordinare.
2. Tocca il pulsante **Riordina** (icona ↕) nella barra degli strumenti.
3. Trascina la flashcard nella posizione desiderata.
4. Tocca **Fine** per uscire dalla modalità riordinamento.

> **Nota:** L'ordine manuale viene preservato durante l'esportazione e l'importazione delle flashcard.

### 3.2 Ordinamento dei Gruppi

Puoi ordinare l'elenco dei gruppi per diversi criteri.

**Procedura:**

1. Tocca il pulsante di ordinamento (icona ↕) nella barra degli strumenti.
2. Seleziona uno dei criteri di ordinamento:

| Criterio | Descrizione |
|----------|-------------|
| **Nome (A-Z)** | Ordine alfabetico crescente |
| **Nome (Z-A)** | Ordine alfabetico decrescente |
| **Più recenti** | Gruppi creati più di recente per primi |
| **Più vecchi** | Gruppi più vecchi per primi |
| **Numero di flashcard** | Gruppi con più flashcard per primi |

> **Nota:** L'ordinamento si applica sia alla sezione **Gruppi** che alla sezione **Studio**.

### 3.3 Ricerca dei Gruppi

**Su iOS:**

1. Scorri verso il basso sull'elenco dei gruppi per rivelare la barra di ricerca.
2. Digita il nome del gruppo che stai cercando.

**Su macOS:**

1. Usa la barra di ricerca nella parte superiore della barra laterale.
2. Digita il nome del gruppo che stai cercando.

---

## 4. Modalità di Studio

La modalità di studio è il cuore di StudyCards. Ti permette di ripassare le tue flashcard in modo interattivo e di valutare il tuo livello di conoscenza.

### 4.1 Avviare una Sessione di Studio

**Procedura:**

1. Seleziona la scheda **Studio** nella barra di navigazione.
2. Trova e seleziona il gruppo che vuoi studiare.
3. La prima flashcard apparirà sullo schermo.

![Avvia Studio](screenshots/ios/start_study.png)

![Avvia Studio - macOS](screenshots/macos/start_study.png)

### 4.2 Navigare tra le Carte

Durante una sessione di studio:

1. Leggi il **fronte** della carta (la domanda).
2. Pensa alla risposta.
3. Tocca **Mostra Risposta** o tocca la carta per rivelare il **retro** (la risposta).
4. Valuta la tua conoscenza con uno dei tre pulsanti:

| Pulsante | Significato | Descrizione |
|----------|-------------|-------------|
| 🟢 **Facile** | Lo sapevi bene | La carta verrà contrassegnata come padroneggiata. Apparirà meno frequentemente. |
| 🟡 **Dubitato** | Ti sei ricordato con difficoltà | La carta riapparirà presto per il rinforzo. |
| 🔴 **Non sapevo** | Non lo sapevi | La carta verrà ripetuta più volte finché non la impari.

**Scorciatoie da Tastiera (macOS):**

| Tasto | Azione |
|-------|--------|
| **Spazio** | Gira la carta |
| **1** | Valuta come Facile |
| **2** | Valuta come Dubitato |
| **3** | Valuta come Non sapevo |

![Modalità di Studio](screenshots/ios/study_session.png)

![Modalità di Studio - macOS](screenshots/macos/study_session.png)

### 4.3 Completare una Sessione di Studio

Quando hai ripassato tutte le carte del gruppo:

1. Apparirà un riepilogo del completamento.
2. Vedrai quante carte hai valutato come *Facile*, *Dubitato* e *Non sapevo*.
3. Tocca **Studia di Nuovo** per ripetere o **Torna ai Gruppi** per uscire.

![Riepilogo Studio](screenshots/ios/study_summary.png)

![Riepilogo Studio - macOS](screenshots/macos/study_summary.png)

---

## 5. Importare ed Esportare

StudyCards ti permette di trasferire le flashcard tra dispositivi o creare backup utilizzando file CSV e JSON.

### 5.1 Esportare le Flashcard

**Procedura:**

1. Apri il gruppo che vuoi esportare.
2. Tocca il menu delle azioni e seleziona **Esporta**.
3. Seleziona il formato di esportazione:
   - **CSV:** Formato per fogli di calcolo. Ideale per l'apertura in Excel, Numbers, ecc. Non include immagini.
   - **JSON:** Formato completo. Include testo, formule LaTeX e immagini base64.
4. Scegli dove salvare il file (File, iCloud Drive, ecc.).

![Esporta](screenshots/ios/export.png)

![Esporta - macOS](screenshots/macos/export.png)

### 5.2 Struttura del File JSON

Il file JSON esportato ha la seguente struttura:

```json
{
  "groupName": "Vocabolario Spagnolo",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "Qual è la capitale della Francia?",
      "back": "Parigi.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "stringa_base64...",
      "backImage": null
    }
  ]
}
```

### 5.3 Struttura del File CSV

Il file CSV utilizza le seguenti colonne:

```csv
front,back,frontLatex,backLatex,difficulty,frontImage,backImage
"Qual è la capitale della Francia?","Parigi.","","","0","",""
```

> **Nota:** Le immagini nel formato CSV vengono esportate come stringhe base64 nelle colonne `frontImage` e `backImage`.

### 5.4 Importare le Flashcard

**Procedura:**

1. Nell'elenco delle flashcard di un gruppo, tocca il menu delle azioni e seleziona **Importa**.
2. Seleziona un file CSV o JSON dal tuo dispositivo.
3. StudyCards importerà le flashcard nel gruppo corrente.

![Importa](screenshots/ios/import.png)

![Importa - macOS](screenshots/macos/import.png)

> **Nota:** Se importi un file JSON con immagini base64, le immagini verranno visualizzate correttamente nelle flashcard.

### 5.5 Errori Comuni di Importazione

| Errore | Causa | Soluzione |
|--------|-------|-----------|
| *Formato non riconosciuto* | Il file non è CSV o JSON valido | Verifica che il file abbia l'estensione corretta e non sia corrotto |
| *File vuoto* | Il file non contiene carte | Controlla che il file contenga almeno una riga di dati |

---

## 6. Condividere le Flashcard

StudyCards rende facile condividere le tue flashcard con gli altri.

### 6.1 Condividere un Gruppo come JSON

**Procedura:**

1. Apri il gruppo che vuoi condividere.
2. Tocca il menu delle azioni e seleziona **Condividi**.
3. Si aprirà il foglio di condivisione del sistema.
4. Scegli l'app o il metodo per inviare:
   - **AirDrop** — per dispositivi Apple vicini.
   - **Posta** — invia il file JSON come allegato.
   - **WhatsApp** — invia il file JSON come documento.
   - **Messaggi** — invia tramite iMessage.
   - **Altre app** — qualsicia accetta allegati file.

![Condividi](screenshots/ios/share.png)

![Condividi - macOS](screenshots/macos/share.png)

### 6.2 Ricevere Flashcard Condivise

Quando qualcuno ti invia un file JSON di StudyCards:

1. Apri il file sul tuo dispositivo.
2. Seleziona **Apri in StudyCards** o **Importa**.
3. Il gruppo verrà aggiunto automaticamente alla tua collezione.

---

## 7. Impostazioni

Personalizza StudyCards in base alle tue preferenze.

### 7.1 Aspetto

Controlla il tema visivo dell'app.

| Opzione | Descrizione |
|---------|-------------|
| **Sistema** | Corrisponde automaticamente all'impostazione dell'aspetto del dispositivo (chiaro o scuro). |
| **Chiaro** | Usa sempre la modalità chiara. |
| **Scuro** | Usa sempre la modalità scura. |

**Procedura:**

1. Vai alla scheda **Impostazioni**.
2. Nella sezione **Aspetto**, seleziona una delle tre opzioni.
3. La modifica viene applicata immediatamente.

![Impostazioni Aspetto](screenshots/ios/appearance.png)

![Impostazioni Aspetto - macOS](screenshots/macos/appearance.png)

### 7.2 Lingua

StudyCards è disponibile in 8 lingue. Puoi forzare una lingua specifica o usare quella predefinita del sistema.

| Lingua | Codice |
|--------|--------|
| **Sistema** | Seleziona automaticamente la lingua del dispositivo |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Procedura:**

1. Vai alla scheda **Impostazioni**.
2. Nella sezione **Lingua**, seleziona la lingua desiderata.
3. La modifica viene applicata immediatamente senza riavvio.

![Impostazioni Lingua](screenshots/ios/language.png)

![Impostazioni Lingua - macOS](screenshots/macos/language.png)

### 7.3 Ordine di Studio

Imposta l'ordine predefinito in cui le flashcard vengono mostrate durante la modalità di studio.

| Opzione | Descrizione |
|---------|-------------|
| **Sequenziale** | Le carte vengono mostrate nell'ordine di creazione (o nell'ordine manuale se le hai riordinate). |
| **Casuale** | Le carte vengono mescolate in ogni sessione. |

**Procedura:**

1. Vai alla scheda **Impostazioni**.
2. Nella sezione **Ordine di Studio**, seleziona la tua preferenza.
3. La modifica si applicherà a tutte le future sessioni di studio.

![Impostazioni Ordine di Studio](screenshots/ios/study_order.png)

![Impostazioni Ordine di Studio - macOS](screenshots/macos/study_order.png)

---

## 8. Consigli

### Organizzazione

- **Crea un gruppo per ogni materia o argomento.** Questo ti aiuterà a trovare rapidamente ciò che devi studiare.
- **Usa nomi chiari e brevi** per gruppi e flashcard. Evita testo troppo lungo da leggere sullo schermo.
- **Riordina manualmente le flashcard** per mettere quelle più importanti per prime.
- **Rivedi periodicamente i tuoi gruppi.** Elimina le carte che hai padroneggiato e aggiungine di nuove in base al tuo progresso.

### Studio

- **Usa la ripetizione a intervalli.** Studia le stesse carte in giorni diversi per consolidare la memoria a lungo termine.
- **Non ignorare le carte difficili.** Se valuti una carta come *Non sapevo*, studia di nuovo quel gruppo presto.
- **Alterna le modalità di studio.** Alterna tra ordine sequenziale e casuale per evitare di memorizzare la posizione delle carte.
- **Usa le scorciatoie da tastiera** su macOS per studiare più velocemente (Spazio, 1, 2, 3).
- **Studia in sessioni brevi.** Da 10 a 20 minuti è sufficiente per una sessione produttiva.

### Contenuto

- **Scrivi domande chiare e concise.** Evita l'ambiguità.
- **Un'idea per carta.** Non sovraccaricare il fronte o il retro con troppe informazioni.
- **Usa le immagini.** Un diagramma o un'immagine può essere più efficace di un paragrafo di testo.
- **Usa le formule LaTeX** per contenuti di matematica o scienze. Sono precise e hanno un aspetto professionale.

### Backup

- **Esporta regolarmente i tuoi gruppi.** Salva copie su iCloud Drive o sul tuo computer.
- **Usa il formato JSON** se vuoi preservare le immagini. Il CSV salva solo il testo.
- **Condividi le tue flashcard** con compagni di studio o colleghi per collaborare allo studio.

### Prestazioni

- **Chiudi le altre app** quando studi così StudyCards funziona senza interruzioni.
- **Mantieni l'app aggiornata** per le ultime funzionalità e correzioni di bug.
- **Se le formule LaTeX non vengono renderizzate**, controlla la tua connessione a Internet. MathJax deve scaricare le risorse la prima volta.

---

## Informazioni Legali

- **StudyCards** è un'applicazione sviluppata indipendentemente.
- L'uso di MathJax è soggetto alla licenza Apache 2.0.
- I tuoi dati sono memorizzati solo sul tuo dispositivo. StudyCards non raccoglie né condivide informazioni personali.

---

*Manuale Utente StudyCards — Versione 1.1 — Luglio 2026*
