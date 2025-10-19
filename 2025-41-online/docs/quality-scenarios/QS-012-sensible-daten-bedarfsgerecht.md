# QS-012: Sensible Personendaten nur bei Bedarf weitergeben

## Qualitätsmerkmal
**[Secure](../10_quality_requirements.md#secure) > Datenminimierung**

## Szenario

| Element               | Beschreibung                                                    |
|-----------------------|-----------------------------------------------------------------|
| **Stimulus**          | System-interne Services benötigen Nutzerdaten für Funktionalität |
| **Umgebung**          | Interne Microservices und Datenverarbeitungsprozesse          |
| **Systembestandteil** | Data Access Layer und Service-to-Service Kommunikation        |
| **Antwort**           | Nur minimal notwendige Daten werden übertragen                 |
| **Antwortmetrik**     | Jeder Service erhält nur die Daten, die für seine Funktion absolut notwendig sind |

## Akzeptanzkriterien
- [ ] Prinzip der Datenminimierung wird angewandt
- [ ] Services erhalten nur notwendige Datenfelder
- [ ] Pseudonymisierung bei nicht-kritischen Operationen
- [ ] Audit-Log für alle Datenzugriffe
- [ ] Regelmäßige Überprüfung der Datenweitergabe

## Priorität
**Hoch** - Datenschutz by Design