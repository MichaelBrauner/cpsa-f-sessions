# 1. Einführung und Ziele

## 1.1 Aufgabenstellung

Entwurf einer Cross-Platform Applikation mit folgenden Kernfunktionen:

- Verleihen
- Ausleihen

**Geschäftsmodell:**
- Initial: Kostenloses Verleihen
- Später: Monetarisierung möglich (ggf. Versicherungen anbieten)

*Timeline-Vorgaben und weitere Beschränkungen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

## 1.2 Qualitätsziele

Die drei wichtigsten Qualitätsziele für WillLeihen:

1. **Usable** - Einfache, intuitive Bedienung für schnelle Markteinführung und geringe Einstiegshürden
2. **Flexible** - Erweiterbarkeit für neue Features bei wachsenden Anforderungen
3. **Secure** - Vertrauen durch Datenschutz und sichere Authentifizierung

*Detaillierte Qualitätsanforderungen mit messbaren Szenarien finden sich in [Kapitel 10](10_quality_requirements.md).*

## 1.3 Stakeholder

### Testerin
- Genaue App-Beschreibung für Testfälle
- Dummy-Daten für Schnittstellen
- Automatisierte Tests in CI/CD
- Ressourcen für Testing und Bugfixing

### Entwickler
- Saubere Modularität
- Klare Schnittstellendefinition
- CI/CD Pipeline
- Akzeptanzkriterien für Jira Tickets
- Code Reviews
- 30% Zeit für technische Schulden

### Marketing
- Früher Snapshot/Prototype (1.5 Monate)
- Schnelle Iterationen
- Modernes Design mit WOW-Effekt
- Webdesign-Übernahme

### Product Owner
- Prototype in 1.5 Monaten
- Verkaufsfähiges MVP in 8 Monaten
- User Stories
- Genaue MVP-Beschreibung

### Architekt
- Überblick behalten
- Technologische Richtlinien
- Kommunikation zwischen Stakeholdern
- Architektur-Standups (Mi/Fr)
