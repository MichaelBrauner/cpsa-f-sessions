# 10. Qualitätsanforderungen

## 10.1 Qualitätsbaum

### Übersicht der Hauptqualitätsmerkmale

- [Usable](#usable)
- [Secure](#secure)
- [Flexible](#flexible)
- [Reliable](#reliable)

*Externe Vorgaben und Beschränkungen zu Qualitätsanforderungen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

---

### Usable

| Untermerkmal         | Szenario                                                                                                  | Priorität | Datei   |
|----------------------|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Bedienbarkeit        | [Reduzierung auf das Nötigste - leichte Bedienbarkeit](quality-scenarios/QS-001-leichte-bedienbarkeit.md) | Hoch      | QS-001  |
| Performance          | [Suchresultate unter 3 Sekunden im Heim-WLAN](quality-scenarios/QS-003-suchresultate-performance.md)      | Hoch      | QS-003  |
| Bildperformance      | [Hohe Performance beim Laden von Bildern](quality-scenarios/QS-004-bilder-performance.md)                 | Hoch      | QS-004  |
| Accessibility (Basic) | [Basic Accessibility - Farben und Kontraste](quality-scenarios/QS-002-accessibility-basic.md)             | Mittel    | QS-002  |
| Accessibility (Advanced) | [Advanced Accessibility - Screen Reader Support](quality-scenarios/QS-002b-accessibility-advanced.md)  | Niedrig   | QS-002b |

### Secure

**Security-Philosophie:**
Security wird nach bewährten Industriestandards umgesetzt (OWASP Top 10). Übertriebene Sicherheitsmaßnahmen, die die Benutzererfahrung erheblich beeinträchtigen, werden vermieden - angemessene Security für den Anwendungskontext.

| Untermerkmal                              | Szenario                                                                                                   | Priorität | Datei  |
|-------------------------------------------|------------------------------------------------------------------------------------------------------------|-----------|--------|
| [Datenschutz](12_glossary.md#datenschutz) | [DSGVO-konforme Datenverarbeitung](quality-scenarios/QS-005-dsgvo-konformitaet.md)                         | Kritisch  | QS-005 |
| Jugendschutz                              | [Jugendschutz und Datensicherheit gewährleisten](quality-scenarios/QS-006-jugendschutz-datensicherheit.md) | Hoch      | QS-006 |
| Datensicherheit                           | [Sichere Speicherung und Übertragung von Nutzerdaten](quality-scenarios/QS-007-datensicherheit.md)         | Hoch      | QS-007 |

### Flexible

| Untermerkmal     | Szenario                                                                                          | Priorität | Datei  |
|------------------|---------------------------------------------------------------------------------------------------|-----------|--------|
| Skalierbarkeit   | [Schnelle Entwicklung neuer Features](quality-scenarios/QS-008-feature-entwicklung.md)            | Hoch      | QS-008 |
| Erweiterbarkeit  | [Peer-to-Peer Bezahlfunktion integrieren](quality-scenarios/QS-009-bezahlfunktion-integration.md) | Mittel    | QS-009 |
| Modularität      | [Moderation von Angeboten hinzufügen](quality-scenarios/QS-010-moderation-angebote.md)            | Mittel    | QS-010 |
| Mehrsprachigkeit | [Mehrsprachigkeit implementieren](quality-scenarios/QS-011-mehrsprachigkeit.md)                   | Mittel    | QS-011 |

### Reliable

| Untermerkmal      | Szenario                                                                                     | Priorität | Datei  |
|-------------------|----------------------------------------------------------------------------------------------|-----------|--------|
| Ausfallsicherheit | [Recovery innerhalb von 15 Minuten](quality-scenarios/QS-012-recovery-15min.md)              | Kritisch  | QS-012 |
| Stabilität        | [Stabilität bei hoher Nutzeranzahl](quality-scenarios/QS-013-hohe-nutzerzahl-stabilitaet.md) | Hoch      | QS-013 |

## 10.2 Qualitätsszenarien

### Prioritätsstufen

| Priorität | Bedeutung | ATAM-Relevanz |
|-----------|-----------|---------------|
| **Kritisch** | Systemausfall/Rechtsverstoß wenn nicht erfüllt | Sofortige Analyse erforderlich |
| **Hoch** | Große Auswirkung auf Nutzererfahrung/Business | Hohe ATAM-Priorität |
| **Mittel** | Wichtig für Qualität, aber nicht kritisch | Mittlere ATAM-Priorität |
| **Niedrig** | Nice-to-have, kann später implementiert werden | Niedrige ATAM-Priorität |

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