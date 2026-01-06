# 🇮🇹 Italian Geological Cartography Hub (IGC-Hub)
### L'Hub digitale aperto per la cartografia geologica in Italia.

**Progetto a cura di [Geologiaintasca](https://www.geologiaintasca.it)**

Questo repository è un progetto *work-in-progress* che mira a creare un database geografico unificato (GeoJSON) delle risorse cartografiche geologiche italiane. L'obiettivo è aggregare in un'unica mappa interattiva i dati provenienti da istituzioni e ricerca accademica, facilitando la consultazione di risorse oggi distribuite su portali diversi.

[**🗺️ VAI ALLA MAPPA INTERATTIVA**](https://umap.openstreetmap.fr/it/map/cartografia-geologica-italiana_1338725)

---

## 📂 Dataset Attuali

Al momento l'Hub integra il nucleo iniziale composto da due livelli informativi:

### 1. 🔵 Cartografia Ufficiale (Progetto CARG)
Il quadro d'unione completo della cartografia geologica ufficiale italiana alla scala 1:50.000.
*   **Contenuto:** Griglia di tutti i 652 fogli geologici previsti dal progetto CARG.
*   **Fonte Dati:** Elaborazione basata sui dati pubblici del Servizio Geologico d'Italia (ISPRA).
*   **Funzionalità:** Ogni poligono rimanda direttamente alla pagina ufficiale ISPRA per il download del foglio (se disponibile).

### 2. 🔴 Ricerca Scientifica (Journal of Maps)
Una selezione curata di oltre 130 pubblicazioni scientifiche tratte dal *Journal of Maps*.
*   **Contenuto:** Mappe di dettaglio, geomorfologia, rischi geologici e nuovi rilevamenti accademici che aggiornano o integrano la cartografia ufficiale.
*   **Fonte Dati:** Metadati estratti da Crossref/Taylor & Francis.

---

## 🚀 Roadmap (Possibili sviluppi futuri)
Il progetto è pensato per essere scalabile. Alcune integrazioni tecnicamente fattibili per il futuro potrebbero includere:

- [ ] **Carta Geologica d'Italia 1:100.000 (Vecchia Serie):** Digitalizzazione del quadro d'unione della storica carta geologica nazionale (277 fogli), ancora essenziale nelle aree non coperte dal CARG.
- [ ] **Cartografia Geologica Marina:** Integrazione dei fogli geologici della piattaforma continentale (Progetto MaGIC/CARG Mare).
- [ ] **Cartografia Regionale:** Link ai portali cartografici delle singole Regioni (WMS/WFS) per le carte geologiche di sintesi (es. 1:10.000 o 1:25.000).

---

## ⚖️ Licenze e Disclaimer

Questo repository funge da **indice e aggregatore** di collegamenti a risorse esterne.

*   **Codice e Struttura Dati:** Il codice di questo repository e la struttura dei file GeoJSON sono rilasciati sotto licenza **MIT** (Open Source).
*   **Dati "CARG":** I riferimenti ai fogli geologici appartengono a *ISPRA / Servizio Geologico d'Italia*. I dati sono trattati in conformità con la licenza **IODL 2.0 (Italian Open Data License)** ove applicabile per i dati pubblici della PA.
*   **Dati "Journal of Maps":** I metadati (Titolo, DOI) sono di pubblico dominio. I contenuti linkati (PDF, Mappe) sono proprietà di *Taylor & Francis* e degli autori, soggetti alle rispettive licenze di pubblicazione.

*Geologiaintasca non è proprietaria dei dati cartografici linkati, ma fornisce esclusivamente il servizio di indicizzazione geografica.*

## 🤝 Contribuire
Il progetto è aperto alla comunità geologica italiana.
Hai una mappa da segnalare o vuoi proporre un nuovo livello informativo?
1.  Apri una **Issue** per discutere la proposta.
2.  Fai un **Fork** del repository e invia una Pull Request.
