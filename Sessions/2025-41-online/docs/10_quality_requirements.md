# 10. Qualitätsanforderungen

## 10.1 Qualitätsbaum

### Übersicht der Hauptqualitätsmerkmale

- [Reliable](#reliable)
- [Usable](#usable)
- [Secure](#secure)
- [Flexible](#flexible)

*Externe Vorgaben und Beschränkungen zu Qualitätsanforderungen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

---

### Reliable

| Untermerkmal      | Szenario                                                                                         | Priorität | Datei  |
|-------------------|--------------------------------------------------------------------------------------------------|-----------|--------|
| Ausfallsicherheit | [Ausfallsicherheit der Datenbank](quality-scenarios/QS-001-datenbank-ausfallsicherheit.md)       | Hoch      | QS-001 |
| Portabilität      | [App auf verschiedenen [Plattformen](12_glossary.md#platform)](quality-scenarios/QS-002-plattform-portabilitaet.md)         | Hoch      | QS-002 |
| Stabilität        | [Stabilität bei hoher Nutzeranzahl](quality-scenarios/QS-003-hohe-nutzerzahl-stabilitaet.md)     | Hoch      | QS-003 |
| [UI-Konsistenz](12_glossary.md#ui-konsistenz)     | [Konsistenz des UI über alle [Plattformen](12_glossary.md#platform)](quality-scenarios/QS-004-ui-konsistenz-plattformen.md) | Mittel    | QS-004 |
| Responsive UI     | [Bequem zu bedienen / [Responsive UI](12_glossary.md#responsive-ui)](quality-scenarios/QS-005-responsive-ui.md)                  | Hoch      | QS-005 |

### Usable

| Untermerkmal           | Szenario                                                                                            | Priorität | Datei  |
|------------------------|-----------------------------------------------------------------------------------------------------|-----------|--------|
| Benutzerfreundlichkeit | [[User](12_glossary.md#user) kann leicht und schnell [Artikel](12_glossary.md#artikel) anlegen](quality-scenarios/QS-006-artikel-anlegen-einfach.md) | Hoch      | QS-006 |
| Einstiegshürde         | [Geringe Einstiegshürde für neue Nutzer](quality-scenarios/QS-007-geringe-einstiegshuerde.md)       | Hoch      | QS-007 |
| Performance            | [Ladezeiten bleiben unter 1s](quality-scenarios/QS-008-ladezeiten-unter-1s.md)                      | Hoch      | QS-008 |

### Secure

| Untermerkmal      | Szenario                                                                                                   | Priorität | Datei  |
|-------------------|------------------------------------------------------------------------------------------------------------|-----------|--------|
| [Authentifizierung](12_glossary.md#authentifizierungsdienst) | [Authentifizierung für sensible Bereiche](quality-scenarios/QS-009-authentifizierung-sensible-bereiche.md) | Hoch      | QS-009 |
| [Datenschutz](12_glossary.md#datenschutz)       | [Personenbezogene Daten nicht nach außen](quality-scenarios/QS-011-datenschutz-keine-weitergabe.md)        | Hoch      | QS-011 |
| [Datenminimierung](12_glossary.md#datenminimierung)  | [Sensible Daten nur bei Bedarf weitergeben](quality-scenarios/QS-012-sensible-daten-bedarfsgerecht.md)     | Hoch      | QS-012 |

### Flexible

| Untermerkmal            | Szenario                                                                                                       | Priorität | Datei  |
|-------------------------|----------------------------------------------------------------------------------------------------------------|-----------|--------|
| Erweiterbarkeit         | [Neuer Login-Provider hinzufügen](quality-scenarios/QS-010-login-provider-erweiterung.md)                      | Hoch      | QS-010 |
| Wartbarkeit             | [Entwickler können gesamte Codebase betreuen](quality-scenarios/QS-013-entwickler-codebase-betreuung.md)       | Mittel    | QS-013 |
| Plattformunabhängigkeit | [App auf verschiedenen Plattformen ausführen](quality-scenarios/QS-014-plattformuebergreifende-ausfuehrung.md) | Mittel    | QS-014 |
| UI-Anpassbarkeit        | [UI-Änderungen einfach und schnell](quality-scenarios/QS-015-ui-aenderungen-schnell.md)                        | Hoch      | QS-015 |

## 10.2 Qualitätsszenarien

### Format der Qualitätsszenarien

Alle Qualitätsszenarien folgen dem standardisierten arc42-Format:

| Element               | Beschreibung                                          |
|-----------------------|-------------------------------------------------------|
| **Stimulus**          | Was löst das Szenario aus? (Ereignis, Aktion, Quelle) |
| **Umgebung**          | Unter welchen Bedingungen tritt das Szenario auf?     |
| **Systembestandteil** | Welcher Teil des Systems ist betroffen?               |
| **Antwort**           | Wie reagiert das System?                              |
| **Antwortmetrik**     | Wie wird die Antwort gemessen? (konkrete Metriken)    |

### Szenario-Dateien

Alle detaillierten Qualitätsszenarien befinden sich im `/quality-scenarios` Ordner als separate Dateien und folgen diesem einheitlichen Format.