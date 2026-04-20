# Projekt Genesis - Lehrkräfte Guide

In diesem Verzeichnis finden sich alle Materialien für die SQL-Doppelstunde "Projekt Genesis" (Fokus auf Aggregatfunktionen, GROUP BY, HAVING). Die Schüler werden in vier Forschungsgruppen (⚡ Momentum, 🪐 Pangea, 🧬 Helix, 🔭 Curiosity) eingeteilt.

## 🗄️ 1. Datenbank & Rohdaten (Root-Verzeichnis)
Bevor der Unterricht startet, muss sichergestellt sein, dass die Schüler-Terminals Zugriff auf die Exoplaneten-Datenbank haben:
* **`nasa_dump.sql`**: Der komplette SQL-Dump, mit dem man die `exoplanets`-Tabelle in passenden SQL-Clients oder Datenbank-Servern aufsetzt. Enthält ca. 6000 reelle Planeten.
* **`exoplanets.db`**: Fertig vorbereitete SQLite-Datenbank. Ideal für schnellen Offline-Unterrichtseinsatz in Tools wie "DB Browser for SQLite", falls kein lokaler Web-/Datenbank-Server (DBeaver/XAMPP) zur Verfügung steht.
* **`exoplanets.csv`**: Der reine CSV-Rohdatensatz der NASA.

## 🧑‍💻 2. Schüler-Arbeitsmaterialien (Ordner `/part1` und `/part2`)
Hier befinden sich die interaktiven Arbeitsaufträge. Die HTML-Dateien sind responsiv gestaltet und können entweder lokal geöffnet oder per GitHub Pages bequem als Link im Unterricht verteilt werden.
* **`/part1/index.html`**: Das interaktive Mission-Control Interface für Akt 1 (Einführung in MIN, MAX, AVG, COUNT sowie WHERE-Filter). Hiermit starten die 4 Teams.
* **`/part2/index.html`**: Das fortgeschrittene Interface für Akt 2 (Fokus auf GROUP BY und HAVING-Klauseln).
* **`/handout/Handouts_Akt_2.pdf`** *(Nur lokal auf Lehrkraft-Ebene)*: Herkömmliche Handouts als Ersatzlösung oder für haptische Differenzierung.

## 📺 3. Lehrkräfte-Dashboard (Ordner `/web`)
Dies ist das zentrale Steuerungswerkzeug für das Smartboard oder den Beamer!
* **`/web/index.html`**: Diese Seite ruft man am Anfang der Stunde auf ("Global Summit"). Hier wird die Story ("Earth Interstellar Initiative") vorgestellt. Im integrierten Analysten-Terminal tippt man am Ende die Ergebnisse der Schüler-Gruppen ein, um den Fortschritt live zu verifizieren.

## 🗝️ 4. Musterlösungen & Ausarbeitung (Ordner `/lsg` & `/ausarbeitung` - *nur lokal!*)
*Achtung: Durch die `.gitignore`-Datei werden diese Ordner (sowie die Datenbanken) absichtlich **nicht** auf GitHub hochgeladen, damit Schüler bei Nutzung von GitHub Pages keine Lösungen finden.*
* **`/lsg/lsg_akt1.sql`** & **`lsg_akt2.sql`**: Sämtliche SQL-Musterlösungen.
* **`/ausarbeitung/Ausarbeitung.md`**: Die vollständige didaktische Ausarbeitung und der Verlaufsplan.

---

### 🎥 Visueller Impuls für den Einstieg (Tipp)
Als Einstieg empfiehlt sich die 3D "Eyes on Exoplanets" App der echten NASA, um den Schülern vor der SQL-Arbeit ein Gefühl für die weiten Entfernungen und realen Dimensionen der Planeten zu geben:
👉 [NASA Eyes on Exoplanets (Proxima Centauri b)](https://eyes.nasa.gov/apps/exo/#/planet/Proxima_Cen_b)