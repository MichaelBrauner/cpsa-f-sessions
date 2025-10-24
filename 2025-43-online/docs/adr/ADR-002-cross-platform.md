# ADR-002: Cross-Platform Unterstützung

## Status
Accepted

## Context
Die Anwendung soll auf mehreren Plattformen verfügbar sein (Web, iOS, Android). Dies ist eine Anforderung aus den Entwickler-Diskussionen.

## Decision
Wir verwenden React Native für die mobile App-Entwicklung und React für die Web-Anwendung. Dies ermöglicht Code-Sharing zwischen den Plattformen bei gleichzeitig nativer Performance.

## Consequences
- **Positiv**: Einheitliche Codebasis, schnellere Entwicklung, konsistente UX
- **Negativ**: Potenzielle Performance-Einbußen gegenüber nativen Apps
- **Risiko**: Abhängigkeit von React Native Framework
- **Mitigation**: Performance-kritische Module können nativ implementiert werden