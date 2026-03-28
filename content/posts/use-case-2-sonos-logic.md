---
title: "Use Case 2: Akustisches Management im 65qm Raum"
date: 2026-03-26
tags: ["Sonos", "FP2", "Automation"]
---

# Perfekter Klang durch Präsenzsteuerung

Wie steuert man die Lautstärke in einem offenen Wohn-Essbereich von 65 Quadratmetern, wenn die Lautsprecher unterschiedliche Klangqualitäten haben? **Die Lösung kam durch eine einfache Frage – und der Aufwand war überraschend gering.**

## Das Setup
- **Küche:** 5.1 System (Beste Qualität, aber physisch unzugänglich).
- **Esszimmer & Wohnzimmer:** Sonos Play:1 (Gut erreichbar, aber schwächerer Klang).
- **Sensor:** Aqara FP2 Presence Sensor (Überwacht die Position im Raum).

## Die Logik: "Orion's Acoustic Flight Path"
Die Automatisierung erkennt, in welchem Sektor ich mich aufhalte, sobald eine Play:1 eingeschaltet wird. Orion stellt dann die Lautstärken so ein, dass der aktuelle Standort optimal beschallt wird, während die anderen Lautsprecher dezent unterstützen.

### Was mich begeistert: Der unglaublich geringe Aufwand
Ich habe Orion lediglich **drei kurze Befehle** gegeben:

1. **"Analysiere die bestehende Sonos‑Automation 'Sonos Play‑Taste – Nur präsenzgesteuerte Lautstärke' (ID 1768895357009)."**
2. **"Erweitere sie um einen manuellen Override: Wenn der Nutzer per App oder Taste die Lautstärke ändert, soll die Automatik für diese Session stoppen."**
3. **"Baue eine Multi‑Personen‑ und Tag/Nacht‑Logik ein, die die Lautstärke nach Uhrzeit und Anzahl anwesender Personen anpasst."**

**Mein Anteil:** Die Problemstellung formulieren und die Freigabe erteilen.  
**Orions Anteil:** Die gesamte Implementierung – er hat die Automation analysiert, die notwendigen Helfer‑Entitäten (`input_boolean.manuelle_lautstarke_aktiv`) angelegt, die Trigger für manuelle Lautstärkeänderungen identifiziert, die Zeit‑ und Präsenzlogik eingebaut und die gesamte Regel getestet.

**Das Ergebnis nach wenigen Minuten:** Eine erweiterte, robuste Automation, die genau das tut, was ich mir vorgestellt hatte – ohne dass ich eine einzige Zeile YAML schreiben musste.

### Die Besonderheit: Der Manual Override
Smarte Technik darf nicht bevormunden. Sobald ich die Lautstärke manuell per App oder Taste ändere, erkennt Orion diesen "menschlichen Vorrang" und stoppt die Automatik für den Rest der Session. Diese Feinheit macht den Unterschied zwischen einem nervigen und einem hilfreichen System.

## Wie daraus die Idee einer eigenen App entstand
Während wir die Automation optimierten, stellte ich fest: **Die manuelle Steuerung der Lautstärke erfolgt meist über die Sonos‑App – und die ist für schnelle Overrides nicht ideal.** Warum also nicht eine eigene, schlanke Android‑App bauen, die direkt mit Home Assistant kommuniziert und mir einen einfachen "Override‑Knopf" bietet?

Genau das haben wir in die Wege geleitet. Orion hat das Projekt **Sonos Control Android App** angelegt: Retrofit für die Home‑Assistant‑API, Hilt für Dependency Injection, Compose für die UI. Die App wird mir künftig nicht nur den Override ermöglichen, sondern auch direkten Zugriff auf alle volumenrelevanten Steuerungen geben – alles aus einer Hand, ohne Umweg über die Sonos‑App.

## Fazit
Kombiniert man präzise Sensorik (FP2) mit einer KI-Logik, entsteht ein System, das mitdenkt, ohne den Nutzer einzuschränken. **Aber noch wichtiger:** Die Zusammenarbeit mit Orion zeigt, wie effizient Mensch und KI zusammenarbeiten können. Ich denke in Zielen, er setzt sie um – und aus dieser Symbiose entstehen nicht nur funktionierende Automations, sondern auch ganz neue Produktideen.
