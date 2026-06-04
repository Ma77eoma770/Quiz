# Quiz App — Interactive Quiz Platform

Una web app interattiva e moderna per esercitarsi con domande a risposta multipla su vari ambiti (Economia Politica, Basi di Dati, Interazione Uomo-Macchina e Marketing). 

Il design è completamente riprogettato prendendo ispirazione dall'estetica pulita, minimale e focalizzata sul contenuto di **Google Forms**.

---

## 🚀 Caratteristiche Principali

*   **Aesthetica Google Forms**: Struttura a schede (card) bianche con bordi arrotondati e ombreggiature delicate su sfondo lavanda chiaro.
*   **Selezione Dataset Interattiva**: Sostituzione del classico menu a tendina con una griglia di tessere informative che indicano materia, categoria e numero di domande.
*   **Filtri Rapidi & Ricerca**: Filtri immediati per categoria (Tutti, Marketing, Informatica, Economia) e barra di ricerca predittiva in tempo reale.
*   **Ottimizzazioni Frontend (Lazy Loading & Cache)**: I dati del quiz vengono scaricati in modo asincrono solo al momento del bisogno e salvati in cache per evitare richieste di rete duplicate.
*   **Rendering LaTeX (MathJax)**: Supporto nativo integrato per formule matematiche complesse (es. equazioni IS-LM o relazioni relazionali in Basi di Dati).
*   **Feedback Visivo & Divertente**: Valutazione immediata delle risposte inviate (verde per le risposte esatte, rosso per le errate) e reazioni animate con simpatici gatti in base alla percentuale di successo.

---

## 📁 Struttura del Progetto

```text
Quiz/
├── index.html                  # L'applicazione Web a pagina singola (HTML5/CSS3/JavaScript)
├── dataset/                    # Cartella contenente i dataset JSON per il quiz
└── src/                        # Risorse statiche dell'applicazione (GIF animate di reazione)
```

---

## 🛠️ Come Avviare l'Applicazione

A causa delle restrizioni di sicurezza dei browser moderni (CORS), non è possibile effettuare richieste `fetch()` asincrone per i file JSON locali se il file HTML viene aperto direttamente tramite doppio click (`file://`).

Per utilizzare l'applicazione localmente sul tuo computer:

1.  Apri una finestra del terminale all'interno della cartella principale del progetto.
2.  Avvia un server HTTP locale utilizzando Python (già preinstallato sulla maggior parte dei sistemi):
    ```bash
    python3 -m http.server 8000
    ```
3.  Apri il tuo browser web preferito e naviga all'indirizzo:
    ```text
    http://localhost:8000
    ```

---

## 📄 Licenza

Questo progetto è distribuito sotto la licenza MIT. Per maggiori dettagli, consulta il file [LICENSE](LICENSE).
