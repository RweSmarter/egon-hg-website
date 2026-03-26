# Projekt: Egon's Web-Präsenz

## Vision
Eine persönliche Webseite, die Egon's Leben, berufliches Wirken (Statik, Informatik, PV) und innovative Smart Home Use Cases (Orion + Home Assistant) präsentiert.

## Struktur-Idee
1. **Home / Intro:** Wer ist Egon? (Mission Statement)
2. **Berufliches Wirken:** Ingenieurbüro, Parkplatz PV, IT-Historie.
3. **Persönliches:** Reisen, strategisches Immobilienmanagement.
4. **Blog / Use Cases:**
    - *Post 1:* Orion - Der Geist in der Maschine (Anbindung an HA).
    - *Post 2:* Akustische Perfektion - Die Sonos-Steuerung im 65qm Raum.

## Tech-Stack (Vorschlag)
- **Static Site Generator (SSG):** Hugo oder Jekyll (schnell, sicher, perfekt für Blog-Content).
- **Hosting:** GitHub Pages oder Netlify (kostengünstig/frei, einfach zu warten).
- **Design:** Clean, technisch, seriös (Ingenieur-Stil).

## Aktueller Status
- Projektordner erstellt: `/root/.openclaw/workspace/projects/website`
- Hugo mit Blowfish Theme konfiguriert.
- Inhalte: "Über mich", zwei Use-Cases (Orion + Home Assistant, Sonos-Steuerung).
- GitHub Actions Workflow für automatisches Deployment auf GitHub Pages eingerichtet.

## GitHub Pages Setup
1. **Repository auf GitHub erstellen:**
   - Gehe zu [GitHub](https://github.com) und erstelle ein neues Repository.
   - Empfohlener Name: `egonhg.github.io` (für direkte URL `https://egonhg.github.io/`) oder ein beliebiger Name (dann URL `https://egonhg.github.io/repository-name/`).
   - **Wichtig:** Öffentliches Repository auswählen.

2. **Lokales Repository mit GitHub verbinden:**
   ```bash
   cd /root/.openclaw/workspace/projects/website
   git remote add origin https://github.com/<dein-username>/<repository-name>.git
   git push -u origin main
   ```

3. **GitHub Pages aktivieren:**
   - Nach dem Push wird der Workflow automatisch ausgeführt.
   - Gehe zu **Settings > Pages**.
   - Unter **Source** wähle **GitHub Actions**.
   - Die Seite ist nach wenigen Minuten live unter `https://<username>.github.io/<repository>/`.

4. **Custom Domain (später):**
   - In `Settings > Pages` kann später die Domain `egon-hg.de` eingetragen werden.
   - Entsprechenden CNAME-Eintrag bei STRATO setzen.

## Lokale Entwicklung
```bash
cd /root/.openclaw/workspace/projects/website
./hugo server -D
```
Die Vorschau läuft auf `http://localhost:1313`.

## Nächste Schritte
- Fotos von LinkedIn/Sopago.org in `static/img/` hochladen.
- Weitere Blogposts und Projektbeschreibungen hinzufügen.
- Bei Verfügbarkeit der STRATO-Domain `egon-hg.de` als Custom Domain konfigurieren.
