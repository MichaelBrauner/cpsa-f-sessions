# 2. Architekturbeschränkungen

## 2.1 Organisatorische Randbedingungen

### Timeline & Budget
- **Budget:** 1 Million Euro
- **Timeline:** 1 Jahr Entwicklungszeit
- **Team:** Entwickler (2), Testerin, Scrum Master, Product Owner, Architekt

### Projektorganisation
- **Sprints:** 2-wöchentliche Sprints mit täglichen Standups (5 Min/Person)
- **Sprint-Scope:** Einmal festgelegt bleibt bestehen (keine nachträglichen Änderungen)
- **Communication:** Wöchentliche Rückmeldung an Product Owner über Status

## 2.2 Qualitätssicherung

- **Code Reviews:** Pro Story beim Branch-Merge
- **Tests:** Keine 100%ige Abdeckung, sondern funktionsorientiert
- **Definition of Done:** Code kompiliert fehlerfrei, Tests laufen durch, deploybar in TEST-Umgebung
- **Testing-Infrastruktur:** Wird von Tester verwaltet (Test-Datenbanken, Fixtures etc.)