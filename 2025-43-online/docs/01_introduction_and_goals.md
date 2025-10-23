# 1. Einführung und Ziele

## 1.1 Aufgabenstellung

Entwurf einer [Cross-Platform](12_glossary.md#cross-platform) Applikation mit folgenden Kernfunktionen:

- [Verleihen](12_glossary.md#verleihen)
- [Ausleihen](12_glossary.md#ausleihen)

**Geschäftsmodell:**
- Initial: Kostenloses [Verleihen](12_glossary.md#verleihen)
- Später: [Monetarisierung](12_glossary.md#monetarisierung) möglich (Ausleihgebühr, Premium-Rankings, kommerzieller API-Bereich, Versicherungen)

*Timeline-Vorgaben und weitere Beschränkungen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

## 1.2 Qualitätsziele

Die drei wichtigsten Qualitätsziele für [WillLeihen](12_glossary.md#willleihen):

1. **[Usable](10_quality_requirements.md#usable)** - Benutzerfreundlichkeit steht ganz oben, einfache intuitive Bedienung
2. **[Flexible](10_quality_requirements.md#flexible)** - Skalierbarkeit für hohe Nutzerzahlen und schnelle Entwicklung neuer Features
3. **[Secure](10_quality_requirements.md#secure)** - Vertrauen durch sichere Authentifizierung und [Datenschutz](12_glossary.md#datenschutz)

*Detaillierte Qualitätsanforderungen mit messbaren Szenarien finden sich in [Kapitel 10](10_quality_requirements.md).*

## 1.3 [Stakeholder](12_glossary.md#stakeholder)

### Tester
- Frühe Einbindung in Anforderungsphase
- Klare Abnahmekriterien für Features
- Gutes Logging und Tracing für PROD-Fehleranalyse
- Testing-Infrastruktur (Test-Datenbanken, Fixtures etc.)

### Entwickler
- Mitwirkung bei Architektur-Entscheidungen und Anforderungsanalyse
- Ausreichend Zeit für Entwicklung und PROD-Monitoring
- Moderne Technologien
- Stabile Datenmodelle (nicht ständig umwerfen)
- Keine Quick & Dirty Lösungen
- Transparente Kommunikation und frühe Einbindung in Entscheidungen

### Scrum Master
- 2-wöchentliche Sprints mit täglichen Standups
- Definition of Done (kompiliert fehlerfrei, Tests laufen, deploybar)
- Dokumentation im Code und Knowledge-Base

### Product Owner
- Wettbewerbsfähiges Produkt mit schneller Entwicklung
- Klare Anforderungen und Backlog-Priorisierung
- Regelmäßige Teamkommunikation

### Architekt
- Überblick behalten
- Technologische Richtlinien
- Kommunikation zwischen [Stakeholdern](12_glossary.md#stakeholder)