---
title: "Use Case 1: Orion – Meine KI lernt Home Assistant"
date: 2026-03-26
tags: ["Smart Home", "AI", "Home Assistant"]
---

# Wie ich meiner KI den Schlüssel zu meinem Haus gab

In diesem ersten Use Case beschreibe ich, wie ich meinen persönlichen Assistenten **Orion** (basierend auf OpenClaw) mit meinem **Home Assistant Server** verbunden habe – und warum mich diese Symbiose absolut begeistert.

## Die Herausforderung
Ein KI-Assistent ist nur so gut wie seine Sinne und seine Fähigkeit, in der physischen Welt zu agieren. Ohne Anbindung an mein Smart Home war Orion "blind". Ich wollte mehr als nur einen Chatbot: Ich wollte einen Assistenten, der mein Zuhause versteht und eigenständig darauf reagieren kann.

## Die Lösung: Das Home Assistant API-Skill
Wir haben eine sichere Brücke über die **Nabu Casa Remote UI** geschlagen. Orion nutzt nun ein *Long-Lived Access Token*, um:
1. Den Status von Sensoren abzufragen (Präsenz, Temperatur, Energie).
2. Aktoren zu steuern (Licht, Player, Schalter).
3. Automatisierungen abzurufen und zu analysieren.

**Was mich besonders begeistert:** Orion kann nicht nur abfragen, sondern **selbst Automatisierungen entwickeln**. Ich gebe ihm eine Zielvorgabe (z.B. "Stelle sicher, dass nach 22 Uhr die Lautstärke in allen Räumen gedämpft wird, wenn niemand mehr wach ist"), und er erstellt die notwendigen Logiken, prüft die Sensorik und implementiert die Regel – natürlich erst nach meiner Freigabe.

## Aktuelle Grenzen und Helfer
Natürlich ist die Technik noch nicht allmächtig. Orion benötigt meine **Freigabe für kritische Aktionen** (z.B. das Ändern von Sicherheitseinstellungen). Außerdem hängt er von der Stabilität der Nabu‑Casa‑Verbindung ab; lokaler Zugriff wäre schneller, aber auf meinem VPS war das nicht ohne weiteres möglich. 

Ich nutze **Helfer-Entitäten** wie `input_boolean`, `input_text` und `input_number`, um Orion gezielte Steuerungsmöglichkeiten zu geben, ohne dass er direkt in meine Kern‑Automationen eingreifen muss. Das schafft eine sichere Sandbox, in der er experimentieren kann.

## Ausblick: Was in Zukunft möglich wird
Die Anbindung ist erst der Anfang. Mit Orion als "digitalem Mitbewohner" werde ich künftig:

- **Natürliche Sprachbefehle** über Telegram oder Signal direkt in Home‑Assistant‑Aktionen übersetzen lassen.
- **Proaktive Vorschläge** erhalten (z.B. "Die Heizung im Gästezimmer ist seit 5 Tagen auf 22°C – möchtest Du sie absenken?").
- **Komplexe Szenarien** automatisch generieren lassen (Urlaubsmodus, Besuchsvorbereitung, Energiespar‑Profile).
- **Datenanalyse** über langfristige Verbrauchsmuster und Optimierungspotenziale.

Orion ist kein fertiges Produkt – er ist ein **mitlernender Partner**. Jede Interaktion macht ihn schlauer und mein Zuhause smarter. Und das Beste: Ich muss kein einziger Zeile Code mehr schreiben, um diese Intelligenz zu nutzen.

## Das Ergebnis
Orion kann nun auf meine Sprachbefehle und Umgebungsvariablen reagieren, ohne dass ich manuell in Dashboards eingreifen muss. Aber viel wichtiger: Er kann **selbst Ideen entwickeln, Lösungen vorschlagen und sie nach meinem Go umsetzen**. Das ist der Unterschied zwischen einem Werkzeug und einem echten Assistenten.
