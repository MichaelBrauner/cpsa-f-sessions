# 11. Risiken und technische Schulden

## 11.1 Identifizierte Risiken

### Technologierisiken

| Risiko | Beschreibung | Wahrscheinlichkeit | Auswirkung | Mitigationsmaßnahmen |
|--------|--------------|-------------------|------------|----------------------|
| **Thymeleaf Veraltung** | Frontend-Technologie könnte an Bedeutung verlieren oder nicht mehr weiterentwickelt werden | Mittel | Hoch | Framework-Migration vorbereiten, modulare Frontend-Architektur |

### Abhängigkeitsrisiken

| Risiko | Beschreibung | Wahrscheinlichkeit | Auswirkung | Mitigationsmaßnahmen |
|--------|--------------|-------------------|------------|----------------------|
| **Externe Authentifizierung** | Bugs oder Ausfälle in Google OAuth könnten Login-Funktionalität beeinträchtigen | Niedrig | Hoch | Fallback-Mechanismen, Alternative Login-Provider vorbereiten |

### Anforderungsrisiken

| Risiko | Beschreibung | Wahrscheinlichkeit | Auswirkung | Mitigationsmaßnahmen |
|--------|--------------|-------------------|------------|----------------------|
| **Fehlende User Stories** | Funktionale Requirements ohne detaillierte User Stories könnten zu Missverständnissen und Fehlimplementierungen führen | Mittel | Mittel | Regelmäßige Stakeholder-Abstimmung, Prototyping für Feedback |

## 11.2 Technische Schulden

*Noch zu dokumentieren - werden während der Entwicklung identifiziert*

## 11.3 Monitoring und Review

- **Risiko-Review:** Monatlich im Team
- **Mitigation-Status:** Wird in Sprint-Retrospektiven besprochen
- **Neue Risiken:** Werden kontinuierlich in diese Dokumentation aufgenommen