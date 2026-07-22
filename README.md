# 📱 FAKE SCREEN TIME PAGE

Una riproduzione web interattiva della vera chermata di blocco per riuscire ad ottenere il codice di tempo di utilizzo.

---

## 🚀 Caratteristiche principali

* **Design Reattivo:** Layout ottimizzato sia per dispositivi mobili che per schermi desktop.
* **Interfaccia Fedele:** Grafica, font e spaziatura ispirati ai sistemi operativi mobile moderni.
* **Modalità Inserimento PIN:** Simulazione visiva della tastiera numerica e dell'inserimento del codice di sblocco.
* **Zero Backend:** Funziona interamente lato client (HTML/CSS/JS puro), senza invio o salvataggio di dati.

---

## 🔑 Come funziona la simulazione del PIN

La funzionalità di inserimento del PIN è una **simulazione puramente visiva e locale**:

1. **Feedback visivo:** L'utente (il genitore o chi conoisce il codice di blocco) interagisce tramite tastiera fisica, scrivendo il codice
2. **Verifica del codice:** La pagina dirà sempre che il codice è corretto, così da ingannare il genitore, facendogli credere di aver inserito il codice nella vera pagina di blocco.
3. **Raccolta del codice:** Il codice inserito dal genitore viene salvato automaticamente nella pagina nascosta e vi rimane finché non viene cancellato.
4. **Vedere il codice:** Per vedere il codice inserito dal genitore basta digitare con la tastiera del computer la parola **pin**, a quel punto si aprirà la pagina nascosta dove potrete vedere il codice di sblocco.

---

## 🛠️ Tecnologie utilizzate

* **HTML5:** Struttura semantica della pagina e dei componenti di input.
* **CSS3:** Styling, Flexbox/Grid, sfondi sfocati (*backdrop-filter*) e animazioni di transizione.
* **JavaScript (Vanilla):** Logica di interazione con la tastiera, gestione degli stati dell'interfaccia e animazione del PIN.

---

## 📦 Come eseguirlo integrando GitHub Pages

1. Clona il repository o scarica i file sorgente.
2. Apri `index.html` direttamente nel tuo browser.
3. In alternativa, visita la demo live pubblicata tramite **GitHub Pages** al link visibile nella sezione destra di questo repository.

---

## ⚠️ Disclaimer

Questo repository è un progetto amatoriale a scopo **educativo, dimostrativo e di intrattenimento**. Non è affiliato, sponsorizzato o approvato da alcuna azienda produttrice di software o sistemi operativi. Non contiene funzionalità di raccolta credenziali o tracciamento.

## FATENE BUON USO
