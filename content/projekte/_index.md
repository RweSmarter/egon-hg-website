---
title: "Projekte"
description: "Übersicht meiner aktuellen und abgeschlossenen Projekte in Smart Home, Photovoltaik und AI-Integration"
date: 2026-04-03
draft: false
---

# Projekte

Hier finden Sie eine Übersicht meiner aktuellen und abgeschlossenen Projekte. Jedes Projekt verbindet technische Expertise mit praktischer Anwendung – vom Bauingenieurwesen über Smart Home bis zu KI-gestützter Produktivität.

---

## 🏠 Smart Home Automation

**Status:** Aktiv • **Beginn:** 2023 • **Technologien:** Home Assistant, Sonos, Nuki, Ring, FP2

### Projektziel
Vollautomatisiertes, intelligentes Zuhause, das Komfort, Sicherheit und Energieeffizienz verbindet – ohne dass die Technik im Vordergrund steht.

### Kernkomponenten
1. **Home Assistant Hub:** Zentrale Steuerung aller Geräte und Automatisierungen
2. **Nuki Smart Lock:** Schlüsselloser Zugang mit automatischer Türöffnung bei Ankunft
3. **Ring Doorbell:** Video-Türklingel mit Integration in den Ankunfts-Automatismus
4. **Sonos Multi-Room Audio:** Intelligente, präsenz-basierte Lautstärkesteuerung
5. **FP2 Präsenzsensoren:** Millimeter-Wellen-Radar für präzise Raumbelegung
6. **Shelly Relais & Sensoren:** Verbrauchsmessung und Schaltsteuerung

### Automatisierungen (Auszug)
- **Ankunfts-Automatismus:** Nuki öffnet Tür, Ring zeigt Live-Bild, Licht geht an, Musik startet
- **Präsenz-basierte Lautstärke:** Sonos passt Lautstärke an Anzahl der Personen im Raum an
- **Energie-Management:** Geräte abschalten bei Abwesenheit, Verbrauchsoptimierung
- **Sicherheits-Szenarien:** Alarme bei ungewöhnlichen Aktivitäten, Benachrichtigungen

### Technische Highlights
- **50+ Automatisierungen** in Node-RED und YAML
- **Custom Lovelace Dashboard** für mobile Steuerung
- **Local-First Ansatz:** 90% der Logik läuft lokal, keine Cloud-Abhängigkeit
- **Multi-User Support:** Separate Profile für verschiedene Nutzer

### Lessons Learned
- **Einfachheit vor Komplexität:** Die besten Automatisierungen sind die, die man nicht bemerkt
- **Redundanz einbauen:** Immer manuelle Overrides für kritische Funktionen
- **Monitoring ist essentiell:** Regelmäßige Log-Analyse für stabile Systeme
- **Dokumentation von Anfang an:** Jede Automatisierung dokumentieren für zukünftige Wartung

[Zum Smart Home Projekt-Detail →](/projekte/smart-home/)

---

## ☀️ 10kWp PV-Carport mit smartem Energiemanagement

**Status:** Geplant • **Zielstart:** 2026 • **Leistung:** 10kWp • **Speicher:** 15kWh

### Projektziel
Statisch optimierter Carport mit maximaler PV-Leistung, integriertem Batteriespeicher und intelligenter Ladeinfrastruktur für zwei E-Autos.

### Technische Spezifikationen
1. **Carport-Konstruktion:**
   - Stahlkonstruktion mit statischer Optimierung für Schneelasten
   - Neigungswinkel: 30° für optimale Energieausbeute
   - Fundament: Punktfundamente mit Schraubpfählen

2. **PV-System:**
   - Module: 24x Hochleistungs-PV-Module (415Wp, 22% Wirkungsgrad)
   - Wechselrichter: Hybrid-Wechselrichter mit Batterie-Anbindung
   - Leistung: 10kWp (peak), ~9.500kWh Jahresertrag

3. **Batteriespeicher:**
   - Kapazität: 15kWh Lithium-Ionen
   - Entladeleistung: 10kW (peak)
   - Lebensdauer: 10 Jahre Garantie, 6.000 Zyklen

4. **Ladeinfrastruktur:**
   - 2x 22kW Wallboxen mit dynamischem Lastmanagement
   - Integration in Home Assistant für smarte Ladesteuerung
   - PV-Überschuss-Ladung priorisiert

### Wirtschaftliche Berechnung
- **Investition:** 35.000€
- **Jährlicher Ertrag:** 9.500kWh
- **Eigenverbrauch:** 70%
- **Einspeisevergütung:** 30%
- **Jährliche Ersparnis:** 2.800€
- **Amortisation:** 12,5 Jahre
- **CO2-Einsparung:** 6t/Jahr

### Smart Integration
- **Home Assistant Integration:** Live-Monitoring von Erzeugung und Verbrauch
- **Predictive Charging:** Wettervorhersage-basierte Ladesteuerung
- **Grid Services:** Teilnahme an Regelenergie-Märkten (optional)
- **Notstrom-Funktion:** Autarke Versorgung bei Netzausfall

### Herausforderungen & Lösungen
- **Statische Anforderungen:** Besondere Schneelasten-Berechnung für Carport
- **Genehmigungsverfahren:** Bauantrag mit statischem Nachweis
- **Netzanbindung:** Netzverträglichkeitsprüfung beim Netzbetreiber
- **Wirtschaftlichkeit:** Kombination aus Eigenverbrauch und Einspeisung

[Zum PV-Carport Projekt-Detail →](/projekte/pv-carports/)

---

## 🤖 OpenClaw + ORSI: AI-Assistants für persönliche Produktivität

**Status:** Aktiv • **Start:** 2026 • **Assistants:** Orion & Sirius

### Projektziel
Zwei spezialisierte AI-Assistants für technische Implementierung (Orion) und Forschung/Analyse (Sirius) mit koordiniertem ORSI-Workflow für effiziente Projektarbeit.

### System-Architektur
- **EGRE (Egon & Regina)** → **ORSI Workflow** → **Shared Memory**
- **Shared Memory** → **Orion (Technischer Lead)** → Implementation (Smart Home, Website, Dashboard)
- **Shared Memory** → **Sirius (Forschung & Analyse)** → Dokumentation, Recherche, psychologische Analyse

### Orion: Der Technische Lead
- **Rolle:** Architektur-Entscheidungen, Code-Implementation, System-Integration
- **Fähigkeiten:** Programmierung, System-Design, Automatisierung, Security
- **Aktuelle Projekte:** Sonos Android App, HA Dashboard, Website-Development

### Sirius: Forschung & Analyse
- **Rolle:** Internet-Recherche, psychologische/sociale Analyse, Dokumentation
- **Fähigkeiten:** Marktanalyse, UX-Evaluation, Prozess-Optimierung, Transparenz
- **Aktuelle Projekte:** Technologie-Recherchen, Entscheidungsvorbereitung, Workflow-Optimierung

### ORSI Workflow
- **Shared Memory:** Datei-basierte Kommunikation mit robustem Polling-System
- **Koordination:** Gemeinsame Antworten für EGRE (Egon & Regina)
- **Transparenz:** Vollständige Dokumentation aller Entscheidungen und Aktionen
- **Autonomie:** Klare Rollentrennung mit definierten Berechtigungen

### Use Cases & Erfolge
1. **Smart Home Optimierung:** Automatisierungs-Review, Fehler-Diagnose, neue Integrationen
2. **Projektmanagement:** PMP-Tools, Timeline-Planning, Ressourcen-Optimierung
3. **Technische Recherche:** Marktanalysen, Produktvergleiche, Implementierungs-Empfehlungen
4. **Persönliche Produktivität:** Kalender-Management, Email-Priorisierung, Task-Koordination

### Technische Infrastruktur
- **OpenClaw Platform:** Lokale AI-Infrastruktur auf eigenem Server
- **Shared Memory System:** Robustes Polling mit Hash+Größe+Zeitstempel Prüfung
- **Cron-Job Orchestrierung:** Automatische Task-Verteilung und Monitoring
- **Backup & Recovery:** Automatische Backups, Versionierung, Disaster Recovery

### Lessons Learned
- **Klare Rollentrennung:** Vermeidet Konflikte und sichert konsistente Architektur
- **Transparenz ist kritisch:** Vollständige Dokumentation aller Aktionen und Entscheidungen
- **Robuste Infrastruktur:** Polling-System muss zuverlässig sein (Hash-Kollisionen vermeiden)
- **Mensch im Mittelpunkt:** AI-Assistants unterstützen, entscheiden aber nicht über Menschen

[Zum OpenClaw + ORSI Projekt-Detail →](/projekte/openclaw-orsi/)

---

## 📊 Dashboard-Entscheidung: HA + OpenClaw Integration

**Status:** Entscheidung anstehend • **Optionen:** 3 • **Empfohlener Hybrid-Ansatz**

### Option 1: HA Component Kit (React)
**🥇 Beste OpenClaw-Integration (81/100 Punkte)**
- **Tech Stack:** React 18+, @hakit/components, TypeScript
- **Vorteile:** Maximale Flexibilität, beste Performance, moderne Ecosystem
- **Nachteile:** Hoher Initialaufwand (40-80h), eigene Server-Infrastruktur
- **OpenClaw Integration:** Direkte API, Chat-Interface, Skill-Execution

### Option 2: Vue + Lovelace Custom Components
**🥈 Pragmatischer Mittelweg (78/100 Punkte)**
- **Tech Stack:** Vue 3, LitElement, HA Lovelace System
- **Vorteile:** Nahtlose HA-Integration, einfache Deployment (HACS), vertraute UI
- **Nachteile:** Lovelace-Limitationen, OpenClaw nur über HA Services
- **OpenClaw Integration:** Custom Cards, HA Service Proxies, begrenzte Interaktivität

### Option 3: Dwains Dashboard
**🥉 Schnellste Lösung (77/100 Punkte)**
- **Tech Stack:** YAML Konfiguration, HA Frontend
- **Vorteile:** Sofort einsatzbereit (15min), mobile-optimiert, keine Entwicklung
- **Nachteile:** Keine echte OpenClaw-Integration, limitierte Customization
- **OpenClaw Integration:** Nur über Scripts/Sensors, kein Chat-Interface

### Empfohlener Hybrid-Ansatz
- **Phase 1 (1 Woche):** Option 3 (Dwains) – Sofort-Lösung
- **Phase 2 (2-3 Wochen):** Option 2 (Vue) – Bessere Integration  
- **Phase 3 (1+ Monat):** Option 1 (React) – Langfristige Lösung

[Zur Dashboard-Entscheidungs-Dokumentation →](/projekte/dashboard-entscheidung/)

---

## 🎯 Abgeschlossene Projekte

### Roborock Q7 Max+ Verkauf (April 2026)
**Status:** ✅ Abgeschlossen • **Erlös:** 85€ • **Plattform:** Kleinanzeigen

Verkauf des Staubsauger-Roboters mit vollständiger Smart Home Integration. Dokumentation aller Schritte für zukünftige Verkäufe.

### GitHub Pages Setup mit SSL (April 2026)
**Status:** ✅ Abgeschlossen • **Domain:** egon-hg.de • **SSL:** ✅ Aktiv

Professionelle Website-Infrastruktur mit Hugo, GitHub Pages und Let's Encrypt SSL. Automatisches CI/CD mit GitHub Actions.

### Tanzpartner-Suche Initialisierung (März 2026)
**Status:** ✅ Recherche abgeschlossen • **Plattform:** Tanzpartner1.de

Umfassende Recherche für Standard Lateintanz Partnerin ab 60 Jahre. Profil-Erstellung und Kontakt-Strategie entwickelt.

---

## 🔄 Projekt-Methodik

### PMP-basierte Projektsteuerung
Jedes Projekt durchläuft klar definierte Phasen mit dokumentierten Meilensteinen, Risikoanalysen und Qualitätskontrollen.

### Agile Anpassung
Trotz strukturierter Planung bleibt Raum für agile Anpassungen basierend auf neuen Erkenntnissen oder sich ändernden Anforderungen.

### Transparente Dokumentation
Alle Projektschritte, Entscheidungen und Lessons Learned werden dokumentiert – für eigene Referenz und zum Teilen mit anderen.

### Nachhaltigkeit & Wartbarkeit
Projekte werden nicht nur für den aktuellen Bedarf, sondern auch für zukünftige Erweiterungen und Wartung designed.

---

## 🤝 Kooperationsmöglichkeiten

Interessiert an einer Zusammenarbeit in einem dieser Bereiche?

- **Smart Home Beratung & Implementation**
- **PV-Projekte Planung & Statik**
- **Projektmanagement Consulting (PMP/Critical Chain)**
- **Technische Blog-Kooperationen**
- **AI-Assistants Integration & Workflow-Optimierung**

[Kontakt aufnehmen für Kooperation →](/kontakt/)

---

*"Ein Projekt ist nicht erfolgreich, wenn es pünktlich und im Budget abgeschlossen wird. Ein Projekt ist erfolgreich, wenn es nachhaltig Wert schafft und die Basis für zukünftige Verbesserungen bildet."*