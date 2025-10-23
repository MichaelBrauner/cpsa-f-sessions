# QS-002b: Advanced Accessibility - Screen Reader Support

## Qualitätsmerkmal
**[Usable](../10_quality_requirements.md#usable) > Accessibility**

## Szenario

| Element               | Beschreibung                                                              |
|-----------------------|---------------------------------------------------------------------------|
| **Stimulus**          | Nutzer mit Blindheit oder starker Sehbeeinträchtigung nutzt Screen Reader |
| **Umgebung**          | Mobile oder Desktop-Umgebung mit aktiviertem Screen Reader                |
| **Systembestandteil** | User Interface, semantische HTML-Struktur, ARIA-Labels                    |
| **Antwort**           | App ist vollständig mit Screen Reader bedienbar                           |
| **Antwortmetrik**     | 100% der Hauptfunktionen sind mit Screen Reader nutzbar                   |

## Akzeptanzkriterien
- [ ] Alt-Texte für alle funktionalen Bilder und Icons
- [ ] Semantische HTML-Struktur (h1-h6, nav, main, etc.)
- [ ] ARIA-Labels für interaktive Elemente
- [ ] Tastaturnavigation für alle Funktionen
- [ ] Focus-Indikatoren sichtbar und logisch
- [ ] Screen Reader-Tests mit echten Nutzern
- [ ] Live-Regions für dynamische Inhalte
- [ ] Skip-Links für Navigation

## Abhängigkeiten
- [QS-002: Basic Accessibility](QS-002-accessibility-basic.md) muss implementiert sein
- Technische Schulung des Entwicklungsteams erforderlich
- Accessibility-Testing-Tools und -Prozesse etabliert

## Priorität
**Niedrig** - Erweiterte Inklusion, hoher Implementierungsaufwand

## Implementierungsaufwand
**Hoch** - Erfordert strukturelle Änderungen und umfassende Tests