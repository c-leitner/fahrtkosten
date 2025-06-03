# 🚆 ÖBB/Westbahn Kilometer- & Fahrtkostenrechner

Ein einfacher Web-Rechner, um basierend auf dem Schienennetz der ÖBB-Infrastruktur die Entfernung und Fahrtkosten zwischen zwei Bahnhöfen zu berechnen. Die Kosten basieren auf dem Steuerratgeber der **Arbeiterkammer Österreich (2025)**.

> 🛠️ **Frontend-only Web-App** – läuft direkt auf GitHub Pages, keine Server-Komponente erforderlich.

---

## 🔧 Features

- 📅 **Datumsauswahl** (nur Berechnungen für das aktuelle Steuerjahr erlaubt)
- 🚉 **Start- und Zielbahnhof**
- 📏 **Distanzberechnung** über die öffentliche API der ÖBB
- 💰 **Kostenberechnung** gemäß AK-Kilometersatz:
  - 0–50 km → €0,50/km  
  - 51–300 km → €0,20/km  
  - >300 km → €0,10/km  
  - **Maximalbetrag**: €109
---

## 🧪 Live-Demo

👉 [**Demo öffnen**](https://dein-github-nutzername.github.io/oebb-kostenrechner)
