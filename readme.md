# Projekt Genesis - Lehrkräfte Guide

In diesem Verzeichnis finden sich alle Materialien für die SQL-Doppelstunde "Projekt Genesis" (Fokus auf Aggregatfunktionen, GROUP BY, HAVING). Die Schüler werden in vier Forschungsgruppen (⚡ Momentum, 🪐 Pangea, 🧬 Helix, 🔭 Curiosity) eingeteilt.

## 🗄️ 1. Datenbank & Rohdaten (Root-Verzeichnis)
Bevor der Unterricht startet, muss sichergestellt sein, dass die Schüler-Terminals Zugriff auf die Exoplaneten-Datenbank haben:
* **`nasa_dump.sql`**: Der komplette SQL-Dump, mit dem man die `exoplanets`-Tabelle in passenden SQL-Clients oder Datenbank-Servern aufsetzt. Enthält ca. 6000 reelle Planeten.
* **`exoplanets.db`**: Fertig vorbereitete SQLite-Datenbank. Ideal für schnellen Offline-Unterrichtseinsatz in Tools wie "DB Browser for SQLite", falls kein lokaler Web-/Datenbank-Server (DBeaver/XAMPP) zur Verfügung steht.
* **`exoplanets.csv`**: Der reine CSV-Rohdatensatz der NASA.

## 🧑‍💻 2. Schüler-Arbeitsmaterialien (Ordner `/handout`)
Hier befinden sich die interaktiven Arbeitsaufträge. Die HTML-Dateien sind im modernen Brutalism-Design gestaltet und komplett offline im Browser lauffähig (sofern Tailwind lokal liegt, ansonsten mit normaler Internetverbindung).
* **`/handout/web/index-akt1.html`**: Das interaktive Mission-Control Interface für Akt 1 (Einführung in MIN, MAX, AVG, COUNT sowie WHERE-Filter). Hiermit starten die 4 Teams.
* **`/handout/web/index-akt2.html`**: Das fortgeschrittene Interface für Akt 2 (Fokus auf GROUP BY und HAVING-Klauseln in der Auswertung).
* **`/handout/Handouts_Akt_2.pdf`**: Herkömmliche Handouts/Arbeitsblätter als Ersatzlösung.

## 📺 3. Lehrkräfte-Dashboard (Ordner `/web`)
Dies ist das zentrale Steuerungswerkzeug für das Smartboard oder den Beamer!
* **`/web/index.html`**: Diese Seite ruft man am Anfang der Stunde auf ("Global Summit"). Hier wird die Story ("Earth Interstellar Initiative") mit passender musikalischer/visueller Atmosphäre vorgestellt. Im integrierten Analysten-Terminal tippt man am Ende die Ergebnisse der Schüler-Gruppen ein, um den Fortschritt live zu verifizieren.

## 🗝️ 4. Musterlösungen (Ordner `/lsg`)
* **`/lsg/lsg_akt1.sql`**: Sämtliche SQL-Musterlösungen aller 4 Forschungsgruppen für den ersten Akt (auskommentiert mit Erklärungen für die Lehrkraft).
* **`/lsg/lsg_akt2.sql`**: Sämtliche SQL-Musterlösungen für den zweiten Akt (inklusive Bonus-Aufgaben wie ORDER BY-Verknüpfungen).

---

### 🎥 Visueller Impuls für den Einstieg (Tipp)
Als Einstieg empfiehlt sich die 3D "Eyes on Exoplanets" App der echten NASA, um den Schülern vor der SQL-Arbeit ein Gefühl für die weiten Entfernungen und realen Dimensionen der Planeten zu geben:
👉 [NASA Eyes on Exoplanets (Proxima Centauri b)](https://eyes.nasa.gov/apps/exo/#/planet/Proxima_Cen_b)