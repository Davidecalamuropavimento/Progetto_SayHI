# 🤖 SayHi! - Chatbot Interattivo

## Descrizione Progetto

**SayHi!** è un'applicazione web interattiva sviluppata in **JavaScript**, **HTML** e **CSS** che simula un chatbot intelligente capace di conversare con gli utenti.

L'applicazione riconosce diversi tipi di messaggi e risponde in modo intelligente e appropriato, offrendo un'esperienza di chat realistica e accattivante.

### Caratteristiche Principali

✅ **Interfaccia moderna e intuitiva** - Design gradiente attraente  
✅ **Riconoscimento intelligente** dei messaggi tramite pattern matching  
✅ **Risposte variabili** - Molteplici risposte casuali per la stessa categoria  
✅ **Chat in tempo reale** - Interazione istantanea con il chatbot  
✅ **Design responsive** - Funziona perfettamente su desktop e mobile  
✅ **Animazioni fluide** - Messaggi che appaiono con animazioni eleganti  
✅ **Invio con Enter** - Puoi inviare messaggi premendo il tasto Enter  
✅ **Scrolling automatico** - La chat scorre sempre all'ultimo messaggio  

---

## 🚀 Come Usare

### Avvio dell'Applicazione

1. **Apri il file `sayhi.html`** con un doppio click
2. Il browser si aprirà automaticamente con il chatbot
3. **Scrivi un messaggio** nella casella di input
4. **Premi "Invia"** o il tasto **Enter**
5. Il chatbot risponderà automaticamente!

### Esempi di Messaggi

Prova a scrivere:
- `Ciao` → Il chatbot ti saluta
- `Chi sei?` → Ti presenta se stesso
- `Cosa puoi fare?` → Ti spiega le sue funzioni
- `Grazie` → Ti ringrazia
- `Scuola` → Parla di argomenti scolastici
- `Progetto` → Commenta il progetto FSL

---

## 📁 Struttura del Progetto

```
SayHi/
├── sayhi.html  (file unico che contiene tutto)
├── README.md   (documentazione)
```

**Nota:** L'intero progetto è contenuto in un **unico file HTML** per facilità d'uso e caricamento.

---

## 💻 Tecnologie Utilizzate

- **HTML5** - Struttura semantica della pagina
- **CSS3** - Styling avanzato con gradients e animazioni
- **JavaScript** - Logica del chatbot e interazione utente

### Competenze Dimostrate

✓ Manipolazione del DOM  
✓ Event listeners (click, keypress)  
✓ Pattern matching per il riconoscimento di testi  
✓ Generazione di risposte casuali  
✓ CSS animations e flexbox  
✓ Buone pratiche di codice  

---

## 🎯 Funzionalità Implementate

### 1. **Riconoscimento dei Pattern**
Il chatbot riconosce automaticamente le intenzioni dell'utente analizzando le parole chiave nel messaggio.

**Categorie di risposte:**
- **Saluti** - Ciao, Salve, Hey, Buongiorno...
- **Nome** - Come ti chiami? Chi sei?
- **Aiuto** - Cosa puoi fare? Come funzioni?
- **Grazie** - Grazie, Grazie mille, Merci...
- **Scuola** - Scuola, Studio, Compiti, Esame...
- **Progetto** - Progetto, FSL, Chatbot, JavaScript...
- **Default** - Risposte generiche per altri messaggi

### 2. **Risposta Casuale**
Per ogni categoria, il chatbot seleziona **una risposta casuale** da un elenco, rendendo la conversazione più naturale e variata.

### 3. **Interfaccia Utente**
- Messaggi dell'utente in **grigio a destra**
- Messaggi del bot in **blu a sinistra**
- Animazioni di slide-in per ogni messaggio
- Scrolling automatico alla fine della chat

### 4. **Interazione Facile**
- Invio tramite **bottone "Invia"**
- Invio tramite **tasto Enter**
- Focus automatico sull'input dopo l'invio

---

## 🔧 Come Personalizzare

### Aggiungere Nuove Risposte

Apri il file `sayhi.html` e trova la sezione `responses`. Aggiungi nuove categorie così:

```javascript
nomeCategoria: {
    patterns: ['parola1', 'parola2', 'parola3'],
    responses: [
        'Risposta 1',
        'Risposta 2',
        'Risposta 3'
    ]
},
```

### Cambiare Colori

Modifica i codici colore nel CSS:
- `#667eea` - Colore primario (viola)
- `#764ba2` - Colore secondario (viola scuro)

### Cambiare il Titolo o la Descrizione

Modifica l'HTML nel file:
```html
<h1>🤖 SayHi!</h1>
<p>Ciao! Sono qui per aiutarti</p>
```

---

## 📋 Requisiti di Sistema

- Browser web moderno (Chrome, Firefox, Safari, Edge)
- Niente connessione internet richiesta
- Niente server necessario
- Funziona offline

---

## 👨‍💼 Informazioni Progetto

**Tipo:** Project Work FSL (Formazione Sull'Uso Linguistico)  
**Linguaggio:** JavaScript  
**Livello:** Introduttivo/Intermedio  
**Durata:** Progetto educativo per corso di programmazione web  

---

## 📝 Note Importanti

- ✅ L'applicazione è **completamente funzionale**
- ✅ **Non richiede installazioni** - Basta aprire il file HTML
- ✅ **Perfettamente compatibile** con tutti i browser moderni
- ✅ **Pronto per il caricamento** in piattaforma

---

## 🎓 Competenze Scolastiche FSL

Questo progetto dimostra le competenze acquisite in:

1. **Sviluppo Web** - HTML, CSS, JavaScript
2. **Programmazione** - Logica, funzioni, array, oggetti
3. **User Experience** - Design intuitivo e responsivo
4. **Problem Solving** - Risoluzione di problemi tramite codice
5. **Intelligenza Artificiale Semplice** - Pattern matching e risposte intelligenti

---

## 📞 Supporto e Domande

Se hai domande sul progetto o vuoi aggiunte:
- Controlla la console del browser (F12) per eventuali errori
- Verifica che il file `sayhi.html` sia aperto correttamente
- Assicurati di usare un browser aggiornato

---

## ✨ Fatto con ❤️

Progetto realizzato come parte del corso FSL (Formazione Sull'Uso Linguistico) in JavaScript.

**Versione:** 1.0  
**Data:** 2026  
**Autore:** Davidecalamuropavimento