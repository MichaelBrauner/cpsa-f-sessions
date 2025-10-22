## Erste Fragen

* Wie verdienen wir daran?
* Was ist der Scope?
* Wie soll ausgerollt werden?
  * Wo wird das gehostet?
* Muss man sich Registrieren?
* Wie sieht das mit dem Datenschutz aus
* Wie können wir das Nutzerfreundliche gestalten
* Ki Einsatz sinnvoll
* Funktionsumfang
     * Chat
     * Suche
     * Bewertungen
* Mobile App oder nicht 

## Warum einen Architekten

- Über das grobe Ganze überblick behalten. - Technologische Richtlinien festlegen.
- Ideen sammeln und darüber Sprechen (kommunizieren).
- Vermitteln zwischen den einzelnen Stakeholdern.
- Lohnt sich ein Architekt wirklich? Für einen Entwickler?

## Jobausschreibung

**Aufgaben:** 

* Entwurf einer Cross-Plattform Applikation
* Analyse der Anforderungen
* Begleiten der Umsetzung
* Auswahl und Integration geeigneter Technologien für Frontend, Backend, Datenhaltung und Sicherheit
* Kommunikation und Vermittlung zwischen Softwareentwicklung und Stakeholdern

**Ihr Profil:** 

* Fachwissen und Leidenschaft: Du hast ein abgeschlossenes Studium oder Ausbildung als Informatiker oder einem vergleichbarem Studiengang
* Erfahrung: Du bringst mehrjährige Berufserfahrung in der Architektur webbasierter Applikationen mit
* Technische Kompetenz: Du besitzt fundierte Kenntnisse in der Entwicklung und dem Betrieb von webbasierten Applikationen
* Kommunikationsstärke: Du verfügst über ausgezeichnete Kommunikationsfähigkeiten, die eine offene, lösungsorientierte und hilfsbereite Zusammenarbeit fördern.
* Sprachkenntnisse: Sehr gute Deutsch- und gute Englischkenntnisse
* iSAQB CPSA-Foundation certified. 

**Wir bieten:**

* Obstkorb
* Kicker
* Flache Hierarchien
* Top Teamstimmung
* Kaffee-Flat
* Scream-Room

## Was ist Architecture
- Grundstruktur
- Bauplan
- Rahmenbedingungen vorgehen
  - Sprache
  - Technologien
- lebt, ist flexibel - iterativ 
  - Anpassen, wenn sich die Anforderungen ändern
- Bausteine mit Beziehungen
  - Strukturen
- Abstraktion
  - ist nicht die Lösung selbst
  - sondern nur die Planung
  - gibt Hilfestellung zur Umsetzung
- Kommunikation mit verschiedenen Stakeholder 
- Review des Codes

## Kick-Off

### Testerin
- Genaue Beschreibung der APP, um Testfälle entwerfen zu können
- Schnittstellen mit Dummy Daten testen können (Fixtures)
- Automatisierte Tests in CI/CD Pipeline
  - i/o flexibel
- Resourcen für das Testing - Bugfixing

### Entwickler
- Saubere Modularität - Konsistenz im Code 
- Wartbarkeit und Erweiterbarkeit
- CI/CD 
- klare Schnittstellendefinition
- gute Abstimmung zwischen Backend und Frontend (Headless)
- Akzeptanzkriterien für Jira Tickets
- ADR
- Technische Schulden vermeiden
  - Code Reviews
  - Abstimmungen während des Sprints
- Codequalität als fester Bestandteil (nicht als nachgezogenes Übel)
  - Zeitdruck darf nicht zulasten der Qualität gehen
  - Ein Feature weniger ist besser als technische Schuld aufzunehmen
- Starten mit einem MVP 
- Architekturmeetings (Dev sollen einbezogen werden)

### Marketing
- früher Snapshot des Programms - Prototype (für die Außenwelt)
  - schneller Weg zum MVP (ASAP - 1.5 Monate)
  - Vorher können wir nicht arbeiten. 
- Schnelle Iterationen (Konstante Features)
  - kurze agile Sprints
- Modernes Design
  - WOW Effekt

### Product Owner 
- Prototype
  - 1.5 Monate
- MVP (verkaufsfähig)
  - spätestens 8 Monate

#### Beschlüsse

- PO entwirft ersten Entwurf nächste Woche 
  - Zusammenarbeit mit dem Marketing
  - User Stories
- Genaue Beschreibung (MVP)                   -       2-3 Wochen 
  - Security
  - CI/CD (minimal)
  - Testsuite
  - Verkaufsready (Bezahlsystem)
  - ggf. Deployment über Makefile
- MVP                                         -       8 Monate  
- Tech-Stack
  - Spring Framework
- Mittwoch und Freitag - Architektur-Standup 
  - Entwickler MUSS dabei
- Wir bieten Verleihen erstmal unentgeltlich an
  - quick time to market
  - schnelles MVP
- Entwickler und Testerin arbeiten eng zusammen
  - Testerin schreibt auch Code (TestCases)
- 30% für Beseitigung von technischer Schuld + Testing mit Antje
- Security 
  - ganz einfach Google Login
- Akzepttanzkriterien für Jira Tickets
  - Pipeline successful
  - Dokumentation
    - nur Onboarding-Doku
    - Tests sind deklarativ formuliert
- Bausteinmodell Entity Model - bis nächste Woche
- ADR erstmal weglassen (nur wenns nötig wird)
- Codereviews - wenn nötig 
- kurze agile Sprint
- Marketing übernimmt Webdesign
  - nichts geht raus an den Kunden, was nicht fixiert

### Geschäftsmodelle
-  ggf. Versicherungen anbieten

#### Offene Fragen

- Welches JS-Framework
- Cloud ?
- Testing conventions for naming 