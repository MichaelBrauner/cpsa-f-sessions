## Erste Fragen

## Warum einen Architekten

- Über das grobe Ganze überblick behalten. - Technologische Richtlinien festlegen.
- Ideen sammeln und darüber Sprechen (kommunizieren).
- Vermitteln zwischen den einzelnen Stakeholdern.

## Jobausschreibung

* Entwurf und Weiterentwicklung der Softwarearchitektur für die WillLeihen-Plattform
* Auswahl geeigneter Technologien und Frameworks (Cloud, Microservices, API-Design, etc.)
* Enge Zusammenarbeit mit Entwicklung, UX/UI und ggf. externen Partnern
* Erstellung technischer Konzepte, Architekturdiagramme und Entscheidungsdokumentationen
* Sicherstellung von Skalierbarkeit, Wartbarkeit und Sicherheit der Lösung

**Ihr Profil:** 
* Kommuniktaionsfreudig
* Flexibel
* Belastbar
* 
**Wir bieten:**

* schlechten Kaffee
* Keinen Obstkorb
* keinen festen Arbeitsplatz (nur für die Anfangsphase vorgesehen)

## Was ist Architecture
...

## Kick-Off

### Tester:in
- positiver Umgang mit Fehlern 
- keine Blame-Culture 
- möchte in der Anforderungsphase schon mit einbezogen werden
- Abnahmekritieren für die Features sollen gefunden werden
- keine unnötigen Metriken (z.B. Unit-Tests 100% - Abdeckung)
- Vor jeder Implementationsphase klären, wie und was getestet wird und mit welchem Aufwand
- Code Reviews um ggf. fehlende Tests verhindern
- Gutes Logging und Tracing - für mühelose Nachvollziehbarkeit von Fehlern im PROD-System

### Entwickler

#### Entwickler 1
- Mitwirken bei der Anforderungsanalyse
- genug Zeit zum Entwickeln (keine Quick&Dirty Lösung)
- genug Zeit für das Monitoring des PROD-Systems
- transparente Kommunikation - möchte früh eingebunden werden in die Entscheidungsfindungsprozesse
- CI/CD
- Moderne Technologien
- Test-Driven-Development

#### Entwickler 2
- bei Entscheidungsprozessen mitwirken (Microservices / Monolith)
- TDD
- Entscheidungen über Technlogien und Sprachen
- klare Anforderungen im Vorfeld (nicht so viele Änderungen während der Entwicklung)
- Datenmodelle sollte nicht ständig umgeworfen werden
- Cloud Lösung - für Skalierung

### Scrum Master
- 2 Wöchentliche Sprints mit täglichen Standups
    - Time-Boxed (jeder bekommt in den täglichen Standups 5 Minuten Sprechzeit)
- Am Ende jedes Sprints haben wir eine herzeigbare Version unsere Produkts (CI)
- PO wird am Ende jedes Sprints eingebunden (Sprint-Review)
- Definition of Done (Projekt compiliert fehlerfrei, alle Tests laufen durch und kann deployed werden in TEST-Umgebung)
- Documentation im Code (Annotationen/Klassen) als auch in der Knowledge-Base (dort befindet sich auch die SA-Documentation)

### Product Owner 
- Produkt soll wettberwerbsfähig sein
- anfangs kostenlos anbieten - später dann kostenpflichtig (Ausleihgebühr)
- Benutzerfreundlichen steht ganz oben
- Schnelle Entwicklung (Konkurrenz abhängen)
- Projekt soll gut definiert sein. - Es soll klare Anforderungen geben 
- Priorisierung spielt große Rolle - Backlog bauen und betreuen
- Teamarbeit und Kommunikation - es braucht regelmäßige Kommunikation mit dem restlichen Team (nicht nur im Sprint-Review)

### Überschneidungen
- Alle - Jeder möchte gute Kommunikation haben und bei Anforderungen mitwirken
- Entwickler - Spannung gegen "schnelle Entwicklung"
- Entwickler - Code soll nicht im Code zusätzlich dokumentiert werden, der    Code ist seine eigene Doku
- Tester - Was heißt "alle Tests sollen durchlaufen"?

#### Beschlüsse
- Einmal die Woche Rückmeldung an Product Owner über Status, Featurewünsche vonseiten Product Owner
- Einmal festgelegter Sprint Scope bleibt bestehen (keine nachträgliche Änderung von Features während dem Sprint)
- Features müssen richtige Größe haben (nicht zu groß, damit Features auch mal fertig werden)
- Code Reviews - pro Story - Beim Einpflegen in den Branch
- Tests - keine 100%ige Abdeckung, 
- Tests sollen sicherstellen, dass das Feature funktioniert wie erwünscht, pro Feature beschließen welche Tests benötigt werden
- Tester kümmert sich um die Testing INfrastruktur (Test-Datenbanken, Filesystem-Abstraktionen, Fixtures etc.) 

### Geschäftsmodelle
- Ausleihgebühr
- Premium für bessere Rankings
- kommerzieller Bereich (API für z.B. Baumärkte)
- Versicherungen verkaufen 

#### Offene Fragen

- Wie verifizieren sich die User, dammit es zu keinen Scam kommen kann. 

#### Nächste Schritte

- Wo wollen wir hin 
  - Was muss als nächstes besprochen werden
  - Muss ausdefiniert werden was bis wann
- Kommunikationskanäle festlegen
  - festhalten mit einem Organigramm
  - Liste mit Kontaktdaten
- Tools festlegen
  - Jira
  - Confluence
  - IDE
- UseCases erstellen (Funktionale Anforderungen fixieren)
- Wie viele Nutzer sind zu erwarten (Traffic)
- Konkurrenz-Analyse