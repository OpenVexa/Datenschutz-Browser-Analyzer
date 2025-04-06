# 🕵️‍♀️ Datenschutz Browser Analyzer

Der **Datenschutz Browser Analyzer** ist ein leichtgewichtiges, clientseitiges Tool zur Bewertung von Datenschutzrisiken im Webbrowser. Es erkennt gängige Tracking-Techniken wie Cookies, Local Storage, Session Storage und identifiziert potenziell sensible Tracker.

> 🔐 Entwickelt von [OpenVexa](https://openvexa.de)  
> 🧾 Lizenz: GNU GPLv3

---

## 🚀 Funktionen

- Zählt und analysiert:
  - 🍪 Cookies
  - 💾 Local Storage
  - 🕒 Session Storage
  - 🌐 Verwendete Domains
- Bewertet das Tracking-Risiko (Niedrig / Mittel / Hoch)
- Erkennt sensible Tracker anhand vordefinierter Schlüsselwörter
- Zeigt detaillierte Browserinformationen
- Gibt konkrete Empfehlungen zur Verbesserung der Privatsphäre
- Erstellt herunterladbare Datenschutz-Berichte
- Option: Alle Tracker löschen

---

## 🖥️ Live-Demo

Das Tool ist vollständig offlinefähig – keine Serververbindung nötig.

### 🔧 So verwendest du es:

1. Repository klonen oder ZIP herunterladen
2. Die Datei `index.html` im Browser öffnen (per Doppelklick oder Drag-and-Drop)
3. Auf **„Datenschutz-Analyse starten“** klicken
4. Analyseergebnisse prüfen, Empfehlungen ansehen, Bericht erstellen

---

## 📦 Installation

```bash
git clone https://github.com/dein-benutzername/datenschutz-browser-analyzer.git
cd datenschutz-browser-analyzer

## 🧠 Technik

- **HTML5 / CSS3 / JavaScript (Vanilla)**
- **Keine externen Abhängigkeiten**
- **Vollständig lokal ausführbar (100 % clientseitig)**
- **Erkennung sensibler Tracker anhand vordefinierter Schlüsselwörter:**

```js
const SENSITIVE_KEYWORDS = [
  'session', 'login', 'auth', 'token', 
  'user', 'tracking', 'analytics', 
  'google', 'facebook', 'ad', 'marketing'
];

## 📝 Lizenz

Dieses Projekt ist unter der [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html) lizenziert.

---

## 🙌 Mitmachen

Beiträge, Feedback oder Ideen sind jederzeit willkommen!  
Erstelle einfach ein [Issue](https://github.com/dein-benutzername/datenschutz-browser-analyzer/issues) oder sende einen Pull Request.

---

## 📩 Kontakt

**Website:** [https://openvexa.de](https://openvexa.de)  
**E-Mail:** info@openvexa.de


