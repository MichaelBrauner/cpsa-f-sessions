# ADR-005: Image CDN Integration

## Status
Accepted

## Context
Bilder sind ein zentraler Bestandteil der WillLeihen-Plattform. Nutzer laden Produktbilder hoch, die schnell und in verschiedenen Auflösungen verfügbar sein müssen. Performance-Anforderung: Bilder sollen in unter 2 Sekunden laden.

## Decision
Wir integrieren Cloudinary als Image CDN für automatische Bildoptimierung, Größenanpassung und globale Verteilung.

## Consequences
- **Positiv**: Automatische Bildoptimierung, schnelle Ladezeiten, globale Verfügbarkeit
- **Negativ**: Zusätzliche Kosten, externe Abhängigkeit
- **Risiko**: Vendor Lock-in bei Cloudinary
- **Mitigation**: Standard-APIs verwenden für einfache Migration zu anderen CDN-Anbietern