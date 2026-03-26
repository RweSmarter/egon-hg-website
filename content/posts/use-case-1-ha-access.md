---
title: "Use Case 1: Orion – Meine KI lernt Home Assistant"
date: 2026-03-26
tags: ["Smart Home", "AI", "Home Assistant"]
---

# Wie ich meiner KI den Schlüssel zu meinem Haus gab

In diesem ersten Use Case beschreibe ich, wie ich meinen persönlichen Assistenten **Orion** (basierend auf OpenClaw) mit meinem **Home Assistant Server** verbunden habe.

## Die Herausforderung
Ein KI-Assistent ist nur so gut wie seine Sinne und seine Fähigkeit, in der physischen Welt zu agieren. Ohne Anbindung an mein Smart Home war Orion "blind".

## Die Lösung: Das Home Assistant API-Skill
Wir haben eine sichere Brücke über die **Nabu Casa Remote UI** geschlagen. Orion nutzt nun ein *Long-Lived Access Token*, um:
1. Den Status von Sensoren abzufragen (Präsenz, Temperatur, Energie).
2. Aktoren zu steuern (Licht, Player, Schalter).

## Das Ergebnis
Orion kann nun auf meine Sprachbefehle und Umgebungsvariablen reagieren, ohne dass ich manuell in Dashboards eingreifen muss.
