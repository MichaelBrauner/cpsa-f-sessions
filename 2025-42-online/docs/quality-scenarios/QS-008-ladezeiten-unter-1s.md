# QS-008: Ladezeiten bleiben konsequent unter 1s

## Qualitätsmerkmal
**[Usable](../10_quality_requirements.md#usable) > Performance**

## Szenario

| Element               | Beschreibung                                                    |
|-----------------------|-----------------------------------------------------------------|
| **Stimulus**          | Nutzer navigiert zwischen verschiedenen Screens der App        |
| **Umgebung**          | Normale Internetverbindung (3G/4G/WiFi)                       |
| **Systembestandteil** | Frontend-Performance und Backend-APIs                          |
| **Antwort**           | Neue Inhalte laden schnell und flüssig                         |
| **Antwortmetrik**     | 95% aller Seitenaufrufe laden in unter 1 Sekunde              |

## Akzeptanzkriterien
- [ ] Initial Load unter 1 Sekunde
- [ ] Navigation zwischen Screens unter 0.5 Sekunden
- [ ] Bilder laden progressiv
- [ ] Caching für häufig genutzte Inhalte
- [ ] Loading-Indikatoren für längere Operationen

## Priorität
**Hoch** - Kritisch für Nutzererfahrung