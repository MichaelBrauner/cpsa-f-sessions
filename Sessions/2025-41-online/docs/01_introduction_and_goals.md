# 1. Einführung und Ziele

## 1.1 Aufgabenstellung

Entwurf einer [Cross-Platform](12_glossary.md#cross-platform) Applikation mit folgenden Kernfunktionen:

- [Verleihen](12_glossary.md#verleihen)
- [Ausleihen](12_glossary.md#ausleihen)

**Geschäftsmodell:**
- Initial: Kostenloses [Verleihen](12_glossary.md#verleihen)
- Später: [Monetarisierung](12_glossary.md#monetarisierung) möglich (ggf. Versicherungen anbieten)

*Timeline-Vorgaben und weitere Beschränkungen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

## 1.2 Qualitätsziele

Die drei wichtigsten Qualitätsziele für [WillLeihen](12_glossary.md#willleihen):

1. **[Usable](10_quality_requirements.md#usable)** - Einfache, intuitive Bedienung für schnelle Markteinführung und geringe Einstiegshürden
2. **[Flexible](10_quality_requirements.md#flexible)** - Erweiterbarkeit für neue Features bei wachsenden Anforderungen
3. **[Secure](10_quality_requirements.md#secure)** - Vertrauen durch [Datenschutz](12_glossary.md#datenschutz) und sichere Authentifizierung

*Detaillierte Qualitätsanforderungen mit messbaren Szenarien finden sich in [Kapitel 10](10_quality_requirements.md).*

## 1.3 [Stakeholder](12_glossary.md#stakeholder)

### Testerin
- Genaue App-Beschreibung für Testfälle
- Dummy-Daten für Schnittstellen
- Automatisierte Tests in [CI/CD](12_glossary.md#cicd)
- Ressourcen für Testing und Bugfixing

### Entwickler
- Saubere [Modularität](12_glossary.md#modularitaet)
- Klare Schnittstellendefinition
- [CI/CD](12_glossary.md#cicd) Pipeline
- Akzeptanzkriterien für Jira Tickets
- Code Reviews
- 30% Zeit für [technische Schulden](12_glossary.md#technische-schulden)

### Marketing
- Früher Snapshot/[Prototype](12_glossary.md#prototype) (1.5 Monate)
- Schnelle Iterationen
- Modernes Design mit [WOW-Effekt](12_glossary.md#wow-effekt)
- Webdesign-Übernahme

### Product Owner
- [Prototype](12_glossary.md#prototype) in 1.5 Monaten
- Verkaufsfähiges [MVP](12_glossary.md#mvp) in 8 Monaten
- User Stories
- Genaue MVP-Beschreibung

### Architekt
- Überblick behalten
- Technologische Richtlinien
- Kommunikation zwischen Stakeholdern
- Architektur-Standups (Mi/Fr)
