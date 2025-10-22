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