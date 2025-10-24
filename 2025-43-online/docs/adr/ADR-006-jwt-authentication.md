# ADR-006: JWT Token Authentication

## Status
Accepted

## Context
Die Plattform benötigt sichere Nutzerauthentifizierung für Transaktionen und persönliche Daten. Gleichzeitig soll das System skalierbar bleiben und Performance-Anforderungen erfüllen.

## Decision
Wir verwenden JWT (JSON Web Tokens) für die Nutzerauthentifizierung. Tokens werden bei jeder API-Anfrage validiert.

## Consequences
- **Positiv**: Stateless Authentication, gute Skalierbarkeit, sichere Datenübertragung
- **Negativ**: Potenzielle Performance-Einbußen durch Token-Validierung bei jedem Request
- **Risiko**: Token-Management und Refresh-Logik erforderlich
- **Mitigation**: Caching der Token-Validierung, angemessene Token-Laufzeiten