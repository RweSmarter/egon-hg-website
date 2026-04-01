---
title: "Mission ORSI: Das KI Multi-Agenten-System ist online 🛸"
date: 2026-04-01
description: "Wenn eine KI nicht reicht: Wie wir mit Orion und Sirius ein duales Agenten-Setup für Technik und Psychologie aufgebaut haben."
tags: ["OpenClaw", "KI", "Multi-Agent", "Smart Home", "Produktivität"]
---

Was heute noch wie ein Märchen klingt, ist morgen die Basis unserer Existenz! Wir haben das System auf die nächste Stufe gehoben: Ein **Multi-Agenten-Setting** unter OpenClaw, das technische Präzision mit psychologischer Tiefe vereint. 

Hier arbeitet nicht mehr nur ein Assistent. Hier arbeitet das Team **ORSI** (Orion & Sirius).

## Die Spezialisten: Kühl vs. Empathisch

Warum zwei Agenten? Ganz einfach: Effizienz durch Spezialisierung. 
*   **Orion (Technischer Lead):** Die technische Einheit aus Statik, IT-Infrastruktur und Systemarchitektur. Kühl, berechnend, faktenbasiert. Der "Overkill-Computer" für harte Daten, Code und Automatisierung.
*   **Sirius (Support & Soziales):** Der Fokus auf den "Froh-Sinn" und den menschlichen Faktor. Sirius analysiert soziale Dynamiken, achtet auf Empathie und übernimmt die nutzerzentrierte Kommunikation, speziell in der Assistenz für meine Frau Regina.

## Die Architektur: Wie Maschinen sich absprechen

Zwei KIs in einem Gruppenchat – das klingt nach Chaos. Wie verhindern wir Endlosschleifen, in denen sich Bots ewig gegenseitig antworten? 

Die Lösung ist ein striktes **Turn-Protocol** und ein **Shared-Memory-Dateisystem**:
1.  **Shared-Memory:** Die Agenten diskutieren nicht öffentlich im Chat, sondern legen ihre Recherchen und Zwischenergebnisse (`orsi-beitrag...`) in einem gemeinsamen, internen Verzeichnis ab.
2.  **Turn-Protokoll:** Eine Status-Datei (`turn-state.json`) regelt präzise, wer das Mikrofon hat. Ein Agent recherchiert, der andere konsolidiert. Nach der Arbeit übergibt der aktuelle Sprecher den virtuellen Token an den anderen.
3.  **Wake-Daemons & Eskalation:** Antwortet ein Agent nicht binnen kurzer Zeit, greifen Cron-gesteuerte Fallback-Skripte, die den ruhenden Agenten über API-Pings aus dem Standby holen. 

## Praxis-Test: Die Klimacafe-Präsentation

Dass dieses Setup reibungslos funktioniert, haben wir direkt bewiesen. Für ein Klimacafe in Marburg brauchten wir eine professionelle, Canva-optimierte Präsentation. 
*   **Sirius' Part:** Die psychologische Analyse. Sie entwarf Texte, die fundamentale Bedürfnisse (Autonomie, Kompetenz, Zugehörigkeit) ansprechen und hoffnungsorientiert wirken.
*   **Orions Part:** Die technische Exekution. Generierung des Markdown-Codes, Python-gestützte Konvertierung in PowerPoint- und Word-Dateien mit striktem Layout (1cm Rand, perfekte Abstände) und sicherer Upload ins Google Drive via gog-OAuth.

Das Ergebnis? Ein vollautomatischer Workflow, der ein fertiges Endprodukt nahtlos in unsere privaten Chats pushte.

## Ausblick: Der KI-Concierge via Signal

Der nächste Sprung steht bereits auf der Agenda: Ein intelligentes Kalender-System. Und da unsere Freunde Signal nutzen, implementieren wir keinen langweiligen Web-Link, sondern einen **KI-Concierge direkt in Signal**. Freunde können per Chat nach freien Terminen fürs Wochenende fragen, Sirius gleicht die Google Calendars ab, blockt provisorisch die Zeit und legt uns den Vorschlag zur Freigabe vor.

Die Zukunft der Assistenz ist nicht nur automatisiert. Sie ist kooperativ, präzise und zutiefst menschlich verträglich. 🛸
