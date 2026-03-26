---
title: "Use Case 2: Akustisches Management im 65qm Raum"
date: 2026-03-26
tags: ["Sonos", "FP2", "Automation"]
---

# Perfekter Klang durch Präsenzsteuerung

Wie steuert man die Lautstärke in einem offenen Wohn-Essbereich von 65 Quadratmetern, wenn die Lautsprecher unterschiedliche Klangqualitäten haben?

## Das Setup
- **Küche:** 5.1 System (Beste Qualität, aber physisch unzugänglich).
- **Esszimmer & Wohnzimmer:** Sonos Play:1 (Gut erreichbar, aber schwächerer Klang).
- **Sensor:** Aqara FP2 Presence Sensor (Überwacht die Position im Raum).

## Die Logik: "Orion's Acoustic Flight Path"
Die Automatisierung erkennt, in welchem Sektor ich mich aufhalte, sobald eine Play:1 eingeschaltet wird. Orion stellt dann die Lautstärken so ein, dass der aktuelle Standort optimal beschallt wird, während die anderen Lautsprecher dezent unterstützen.

### Die Besonderheit: Der Manual Override
Smarte Technik darf nicht bevormunden. Sobald ich die Lautstärke manuell per App oder Taste ändere, erkennt Orion diesen "menschlichen Vorrang" und stoppt die Automatik für den Rest der Session.

## Fazit
Kombiniert man präzise Sensorik (FP2) mit einer KI-Logik, entsteht ein System, das mitdenkt, ohne den Nutzer einzuschränken.
