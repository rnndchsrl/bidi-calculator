# Virtuelle Distanz – VW BiDi Rechner

Dieses Projekt ist ein **HTML/JS‑Rechner**, der die **virtuelle Batterielaufleistung** nach VW‑BiDi‑Formel berechnet.  
Er ist für **GitHub Pages** optimiert und nutzt eine getrennte `models.json`, damit WLTP‑Werte leicht erweiterbar sind.

---

## 🔧 Funktionen

- Berechnung der **virtuellen Distanz in km** nach:
Virtuelle Distanz [km] = (V2H + V2L‑Energie [Wh]) / (ungünstigster WLTP‑Verbrauch [Wh/km])
- Eingabe der Energie in **kWh** auf zwei Arten:
- Direkt als Energie in kWh (z. B. 12,0 kWh).
- Oder über **kWh pro Tag × Anzahl Tage** (z. B. 3,5 kWh/Tag über 100 Tage).
- Konfigurationsdatei `models.json` enthält:
- Unterstützte Fahrzeugfamilien (z. B. ID.3, ID.4, Enyaq, Born, Q4 e‑tron etc.)
- WLTP‑Verbrauchswerte in Wh/km  
→ Modelle und Verbrauchswerte sind **ohne** die `index.html` zu berühren erweiterbar/änderbar.

---

## 🚀 Nutzung im Browser

### 1. Lokal nutzen

- Repository‑Ordner öffnen.
- `index.html` im Browser öffnen (per Doppelklick oder `file://`).
- Wähle im Dropdown dein Modell, gib die V2H/V2L‑Energie ein und klicke auf „Virtuelle Distanz berechnen“.
