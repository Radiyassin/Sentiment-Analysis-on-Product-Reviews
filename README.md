
# 📊 Sentiment Analyse Dashboard für Produktbewertungen

Ein interaktives Web-Dashboard zur automatisierten Analyse von Kundenbewertungen mit Sentiment-Erkennung, Visualisierung und Chatbot-Unterstützung.


![Description](https://habrastorage.org/webt/t6/sr/jr/t6srjrmjjmm6qn8gpld9emy4txu.gif)

## 🧠 Projektbeschreibung

Diese Anwendung ermöglicht es Nutzer:innen, eine CSV-Datei mit Produktbewertungen hochzuladen. Die Bewertungen werden mithilfe von Natural Language Processing (NLP) analysiert und in positive, neutrale oder negative Stimmungen klassifiziert. Die Ergebnisse werden visuell dargestellt und können als PDF exportiert werden. Zusätzlich gibt es einen integrierten Chatbot, der Fragen zu den Bewertungen beantworten kann.

---

## ⚙️ Technologien

- **Python / Flask** – Backend-Logik und API
- **NLTK + VADER** – Sentiment-Analyse
- **Pandas** – Datenverarbeitung
- **HTML / CSS / JavaScript** – Benutzeroberfläche
- **Chart.js** – Visualisierung der Ergebnisse
- **OpenAI GPT-3.5** – Chatbot-Integration
- **jsPDF + html2canvas** – PDF-Export

---

## 🖼️ Demo

![UI Screenshot](./static/images/ui_preview.png)

---

## 🚀 Funktionen

- 📥 CSV-Upload mit Produktbewertungen
- 📊 Automatische Sentiment-Analyse (positiv/neutral/negativ)
- 🧩 Extraktion häufig negativer Begriffe
- 📈 Tendenzvorhersage des Verkaufspotenzials
- 🤖 Integrierter Chatbot (GPT-3.5) mit kontextuellen Antworten
- 📄 PDF-Export mit Diagrammen
- 🌐 Web-Interface mit responsive Design

---


## 📦 Installation

```bash
# 1. Repository klonen
git clone https://github.com/dein-nutzername/sentiment-dashboard.git
cd sentiment-dashboard

# 2. Virtuelle Umgebung (optional)
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# 3. Abhängigkeiten installieren
pip install -r requirements.txt

# 4. App starten
python run.py
```


---


---
>>>>>>> 9e71adc (Initial commit with Flask app and documentation)
