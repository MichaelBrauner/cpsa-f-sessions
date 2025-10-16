# QS-001: Ausfallsicherheit der Datenbank

## Qualitätsmerkmal
**Reliable > Ausfallsicherheit**

## Szenario

| Element               | Beschreibung                                                    |
|-----------------------|-----------------------------------------------------------------|
| **Stimulus**          | Datenbank-Server fällt aus oder wird nicht erreichbar          |
| **Umgebung**          | Normaler Betrieb mit aktiven Nutzern                           |
| **Systembestandteil** | Datenbank-Layer der Anwendung                                  |
| **Antwort**           | System nutzt Backup-Datenbank oder lokalen Cache               |
| **Antwortmetrik**     | Failover innerhalb von 30 Sekunden, keine Datenverluste       |

## Akzeptanzkriterien
- [ ] Automatisches Failover zu Backup-Datenbank
- [ ] Nutzer bemerken Ausfall maximal 30 Sekunden
- [ ] Keine Datenverluste bei Ausfall
- [ ] System loggt Ausfälle für Monitoring

## Priorität
**Hoch** - Kritisch für Systemstabilität