# 9. Architekturentscheidungen

## 9.1 Wichtige Architekturentscheidungen

# ADR-001: Spring Framework als Backend-Technologie

## Status
Accepted

## Context
Für das Backend der Cross-Platform Applikation muss eine geeignete Technologie gewählt werden. Das MVP soll in 8 Monaten verkaufsfähig sein. Das Team benötigt eine bewährte, gut dokumentierte Lösung mit starker Community-Unterstützung.

## Decision
Wir verwenden Spring Framework als Backend-Technologie.

## Consequences
- Das Team muss Java-Kenntnisse haben oder erwerben
- Wir profitieren von etablierten Patterns und Best Practices
- Umfangreiche Community und Dokumentation verfügbar
- Gute Integration mit Java-Ecosystem
- Bewährte Enterprise-Lösung reduziert technische Risiken

---

# ADR-002: Google Login statt eigenes Auth-System

## Status
Accepted

## Context
Für die Benutzerauthentifizierung der Cross-Platform Applikation muss eine Lösung implementiert werden. Ein eigenes Auth-System würde erhebliche Entwicklungszeit und Sicherheitsverantwortung bedeuten. Das MVP muss schnell marktreif sein (8 Monate), und Kosteneinsparungen sind wichtig.

## Decision
Wir verwenden Google Login als Authentifizierungslösung anstatt ein eigenes System zu entwickeln.

## Consequences
- Kostenersparnis durch keine Eigenentwicklung eines Auth-Systems
- Reduzierte Sicherheitsverantwortung liegt bei Google
- Schnellere MVP-Entwicklung möglich
- Nutzer haben bekannten Login-Flow
- Abhängigkeit von Google Services entsteht
- Datenschutz-Compliance mit Google erforderlich
- Nutzer benötigen zwingend einen Google Account

---

# ADR-003: Frontend JavaScript Framework

## Status
Proposed

## Context
Für das Frontend der Cross-Platform Applikation muss ein geeignetes JavaScript Framework gewählt werden. Die Entscheidung beeinflusst Entwicklungsgeschwindigkeit, Team-Expertise und langfristige Wartbarkeit. Optionen sind React, Vue.js, Angular und Svelte.

## Decision
[Noch nicht entschieden - Evaluierung läuft]

## Consequences
[Werden nach der Entscheidung dokumentiert]

---

# ADR-004: Cloud-Provider

## Status
Proposed

## Context
Hosting und Deployment-Strategie für die Applikation muss definiert werden. Die Wahl beeinflusst Kosten, Skalierbarkeit und operative Komplexität. Optionen sind AWS, Azure, Google Cloud oder On-Premise.

## Decision
[Noch nicht entschieden]

## Consequences
[Werden nach der Entscheidung dokumentiert]

---

# ADR-005: Chat-Funktionalität

## Status
Proposed

## Context
Chat wurde als eine der Kernfunktionen genannt, aber es ist noch unklar, ob diese Funktionalität wirklich benötigt wird und welche Art von Chat implementiert werden soll (1:1, Gruppen, Support-Chat).

## Decision
[Anforderungsanalyse mit Product Owner erforderlich]

## Consequences
[Werden nach der Entscheidung dokumentiert]

---

# ADR-006: KI-Einsatz

## Status
Proposed

## Context
Im Workshop wurde die Frage gestellt: "Ki Einsatz sinnvoll". Es muss entschieden werden, ob und wie KI in die Applikation integriert wird (Suchfunktionalität, Bewertungen/Empfehlungen, Chat-Support).

## Decision
[Use Cases und Technical Feasibility müssen erst evaluiert werden]

## Consequences
[Werden nach der Entscheidung dokumentiert]

---

## Übersichtstabelle

| Entscheidung | Status | Datum |
|--------------|--------|-------|
| Spring Framework Backend | ✅ Accepted | Workshop Tag 1 |
| Google Login Authentication | ✅ Accepted | Workshop Tag 1 |
| Frontend JS Framework | 🔄 Proposed | Workshop Tag 1 |
| Cloud Provider | 🔄 Proposed | Workshop Tag 1 |
| Chat-Funktionalität | 🔄 Proposed | Workshop Tag 1 |
| KI-Einsatz | 🔄 Proposed | Workshop Tag 1 |