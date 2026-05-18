# EventFlow – DJ & Event Planning Tool

**Product Name**
EventFlow – DJ & Event Planning Tool

---

**Overview**
EventFlow ist eine webbasierte Anwendung, die Eventveranstaltern hilft, Veranstaltungen effizient zu planen und zu organisieren. Der Fokus liegt auf der Verwaltung von Events, der Erstellung von DJ-Lineups und der automatischen Generierung von Timetables. Die Anwendung bietet eine visuelle und intuitive Darstellung des Eventablaufs und vereinfacht die Planung komplexer Veranstaltungen wie Club-Events oder Festivals.

---

**Problem**
Eventveranstalter stehen häufig vor folgenden Herausforderungen:

* manuelle und fehleranfällige Planung von Timetables
* unübersichtliche Organisation von DJs und Sets
* hoher Zeitaufwand beim Erstellen eines Eventablaufs
* fehlende zentrale Plattform zur Eventplanung

Dies führt zu ineffizienten Abläufen und Planungsproblemen.

---

**Solution**
EventFlow bietet eine zentrale digitale Lösung, die Eventplanung strukturiert und automatisiert.
Die Anwendung ermöglicht es, Events zu erstellen, DJs hinzuzufügen und automatisch einen vollständigen Zeitplan zu generieren. Dadurch wird die Planung schneller, übersichtlicher und weniger fehleranfällig.

---

**Target Users**

* Eventveranstalter (Clubs, Festivals, kleine Events)
* DJs und DJ-Booker
* Club-Manager
* Personen, die kleinere Musik-Events organisieren

---

**Core Features**

**1. Event Management**

* Erstellung von Events mit Name, Datum, Start- und Endzeit
* Eingabe von Location und Event-Details

**2. DJ Lineup System**

* Hinzufügen von DJs mit Name, Genre und Set-Dauer
* optionale Bewertung oder Energie-Level

**3. Automatischer Timetable Generator**

* automatische Berechnung der Set-Reihenfolge
* Erstellung von Start- und Endzeiten für jeden DJ
* Anpassung bei Änderungen in Echtzeit

**4. Visuelle Timeline**

* grafische Darstellung des gesamten Eventablaufs
* übersichtliche Darstellung der DJ-Sets

**5. (Optional) Smart Arrangement**

* automatische Optimierung der Reihenfolge (z. B. Warm-up → Peak → Closing)

---

**Non-Goals**

* Ticketverkauf oder Payment-Systeme
* komplexe Benutzer- oder Rollenverwaltung
* Echtzeit-Messaging zwischen Nutzern
* Cloud-basierte Multi-User-Kollaboration (Version 1)
* mobile App (nur Web-Version im ersten Schritt)

---

**Success Criteria**
Das Projekt gilt als erfolgreich, wenn:

* ein Event erfolgreich erstellt werden kann
* DJs hinzugefügt und verwaltet werden können
* ein funktionierender Timetable automatisch generiert wird
* die Timeline visuell verständlich dargestellt wird
* die Anwendung stabil und intuitiv bedienbar ist

Optional:

* positives Feedback von Testnutzern (z. B. Mitschüler oder Lehrer)

---

**Suggested Tech Stack**

**Frontend:**

* HTML (Struktur)
* CSS (modernes Dark UI mit Animationen)
* JavaScript (Logik und Interaktivität)

**State Management / Storage:**

* Local Storage (für Events und DJs in Version 1)

**Optional (Erweiterung):**

* Node.js (Backend für erweiterte Funktionen)
* Express.js (API Struktur)
* MongoDB (Datenbank für Events und Nutzer)

**UI/UX Tools (optional):**

* Figma für Designplanung

---



## User Roles / User Types – EventFlow

### 1. Veranstalter (Organizer)

Der Veranstalter erstellt und verwaltet Events.
Er kann:

* neue Events erstellen
* DJs hinzufügen
* Timetables generieren
* Änderungen am Ablauf vornehmen
* den Überblick über das gesamte Event behalten


---

### 2. DJ / Artist

Der DJ kann seinen geplanten Slot und Eventinformationen einsehen.
Mögliche Funktionen:

* eigene Set-Zeit ansehen
* Eventdetails abrufen
* Informationen zum Lineup sehen



---

### 3. Crew / Staff

Die Crew unterstützt den Veranstalter beim Eventablauf.
Mögliche Funktionen:

* Timetable einsehen
* Aufbau- oder Ablaufzeiten prüfen
* Informationen zu Artists und Sets abrufen



---

### 4. Gast / Besucher

Der Gast kann Informationen über das Event ansehen.
Mögliche Funktionen:

* DJ-Lineup ansehen
* Start- und Endzeiten prüfen
* Eventinformationen abrufen




