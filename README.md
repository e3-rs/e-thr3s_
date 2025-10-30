# e-thr3s AI
**Preamble:**

It is not in the author´s attention to shock newbies at their first steps in ai.
**It is recommended** to read and rate this project idea with an **intermediate level of some AI-courses** or some experience on linux terminal prompt.

Why?
It could be difficult to follow the author´s deep diving description and ideas with this much specific termini. But this technical description is need to understand what the usp/idea/valueable benefit will be.

 
Allright? 
Appreciate your understanding 😊, and sorry for that.
Now enjoy.



e-thr3s AI  (spoken *e-threes*  A EI)


## Summary

**ehoch3s oder e-thr3** (einkauf-einfach-effizient) ist ein intelligenter Assistent zur semantischen Analyse externer Ereignismeldungen mit dem Ziel, strategische Einkaufsentscheidungen datenbasiert zu unterstützen. Das System identifiziert potenziell relevante Zusammenhänge zwischen globalen Ereignissen (z. B. Naturkatastrophen, Rohstoffentwicklungen, Wirtschaftsnachrichten) und unternehmensspezifischen Beschaffungsinteressen.


## Background

Moderne AI und Gen AI ist sehr ressourcen intensiv. Es soll ein schlanker AI Assistent speziell für den Einkauf/Procurement geschaffen werden.
Besonders gute Risk-Alerts Modelle sind sehr kostenintensiv und ein der Genemigungsworkflow zur Freigabe lang.
Dieses Tool soll den Einstieg und die Sinnhaftigkeit teurer Tool näherbringen. Der /user erhällt daten, die er als letzte Instanz plaubilisieren muss.
## How is it used?


```

## Funktionen

- **Semantisches Ereignis-Matching**  
  Automatisierte Verknüpfung von Nachrichteninhalten anhand von Schlüsselbegriffen und semantischer Nähe. Beispiel:  
  *„Orkan in Indonesien“ + „Indonesien = Hauptproduzent L1 von Wolle“ → Indoniesien, GEOPOS „Wolle betroffen durch Orkan, L1“*

- **Relevanzbewertung & Alert-System**  
  Visualisierung potenziell kritischer Ereignisse mit Wahrscheinlichkeitsindikatoren zur Einschätzung der Relevanz für definierte Beschaffungsbereiche oder Lieferanten.
  Marktpreis gester, Marktpreiseheute

- **Feedback-Mechanismus zur Modelloptimierung**  
  Nutzer:innen können Alerts mit „Daumen hoch“ oder „Daumen runter“ bewerten, um die semantische Gewichtung und Matching-Logik kontinuierlich zu verbessern.

## Zielgruppe

Das System richtet sich primär an strategische Einkäufer:innen, Supply-Chain-Manager:innen und Entscheidungsträger:innen, die externe Einflussfaktoren frühzeitig erkennen und in ihre Beschaffungsstrategie integrieren möchten – bei minimalem manuellem Aufwand.


## Data Stack
- **Programmiersprache:** Python 3.8+
// Nicht abschließend - weitere Module folgend // 
- **NLP & semantische Analyse:**  
  - `spaCy`  
  - `sentence-transformers`
- **Datenextraktion & Scraping:**  
  - `newspaper3k`  
  - `Scrapy`
- **Visualisierung & Dashboard:**  
  - `Plotly`  
  - `Seaborn`  
  - `Dash`
- **GUI / GTK Assintent in Planung**








## Data sources and AI methods


ehoch3s nutzt öffentlich zugängliche APIs zur Beschaffung aktueller Nachrichtenmeldungen:

- [NewsData.io](https://newsdata.io)  
- [NewsAPI.org](https://newsapi.org)  
- [GNews API](https://gnews.io)  

- *Optional, Liste nicht vollständig (zukünftig geplant):* [Perigon](https://perigon.io) für kontextuelle Analyse und Entitäten-Erkennung
Die Integration zusätzlicher, auch kommerzieller APIs ist über eine modulare Schnittstelle vorgesehen.





## Challenges


-/-

## Installation

1. Repository klonen:
   ```bash
   git clone https://github.com/_dev_name_/e-thr3s.git
   cd e-thr3s
   ```

2. Abhängigkeiten installieren:
   ```bash
   pip install -r requirements.txt
   ```





## Acknowledgments

## Start

Das Hauptskript `e-thr3s.py` kann über die Kommandozeile ausgeführt werden:

```bash
python e-thr3s.py --input meldungen.json --bereich textil --dashboard
```

- `--input`: Pfad zur JSON-Datei mit strukturierten Meldungen  
- `--bereich`: Zielbranche oder Warengruppe zur Relevanzbewertung  
- `--dashboard`: Optionaler Parameter zur Aktivierung der visuellen Darstellung

---

## Demo

Da sich das Projekt aktuell in der frühen Entwicklungsphase befindet und als nicht-kommerzielles Hobbyprojekt betrieben wird, stehen derzeit keine Beispiel-Dateien oder öffentliche Demos zur Verfügung. Eine Bereitstellung entsprechender Ressourcen ist für zukünftige Releases geplant.

---

## License

Dieses Projekt steht unter der **GNU Affero General Public License v3.0 (AGPL-3.0)**.  
Jegliche Nutzung – insbesondere über Netzwerkschnittstellen – verpflichtet zur Offenlegung des Quellcodes und etwaiger Modifikationen.  
Kommerzielle Nutzung außerhalb des vorgesehenen Basissystems ist derzeit nicht gestattet.

---


## Contact

Derzeit handelt es sich um ein nicht-kommerzielles Entwicklungsprojekt ohne offizielle Supportstruktur.  
Für Rückfragen oder Hinweise kann das GitHub-Issue-Tracking verwendet werden.

