# 3. Kontextabgrenzung

## 3.1 Fachlicher Kontext

[WillLeihen](12_glossary.md#willleihen) ist eine [Platform](12_glossary.md#platform), über die private Nutzer Gegenstände [verleihen](12_glossary.md#verleihen) und [ausleihen](12_glossary.md#ausleihen) können.

### Externe Akteure

| Akteur                                | Sendet                                                                      | Empfängt                                      |
|---------------------------------------|-----------------------------------------------------------------------------|-----------------------------------------------|
| [User](12_glossary.md#user)           | Suchanfragen, Artikelangaben, [Rückgabe](12_glossary.md#rueckgabe)meldungen | Suchergebnisse, Artikeldetails, Bestätigungen |
| [Moderator](12_glossary.md#moderator) | Moderationsentscheidungen, Freigaben                                        | Angebote zur Prüfung, Beschwerden             |

### Fachliche Nachbarsysteme

| System                                                              | Sendet                             | Empfängt                        |
|---------------------------------------------------------------------|------------------------------------|---------------------------------|
| [Authentifizierungsdienst](12_glossary.md#authentifizierungsdienst) | Login-Tokens, Nutzeridentität      | Authentifizierungsanfragen      |
| Datenbank                                                           | Artikel-, Nutzer- und Ausleihdaten | Speicher- und Änderungsanfragen |
| Bezahlsystem (Peer-to-Peer)                                         | Transaktionsbestätigungen          | Zahlungsanfragen                |
| Geodatenservice                                                     | Entfernungsberechnungen            | Standortdaten                   |

*Technische Details zu verwendeten Systemen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

## 3.2 Technischer Kontext (optional)
Wird im [MVP](12_glossary.md#mvp)-Entwurf nicht modelliert.

## 3.3 Funktionale Anforderungen

### Account-Management
- [User](12_glossary.md#user) kann sich registrieren
- [User](12_glossary.md#user) kann sich einloggen
- [User](12_glossary.md#user) kann sich ausloggen
- [User](12_glossary.md#user) kann Profil bearbeiten

### Artikelverwaltung
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) anlegen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) bearbeiten
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) löschen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) als verfügbar/nicht verfügbar markieren

### Suche und Ausleihe
- [User](12_glossary.md#user) kann nach Maschinen/Dienstleistungen suchen
- [User](12_glossary.md#user) kann entfernungsbasiertes Ranking nutzen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) [ausleihen](12_glossary.md#ausleihen)
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) zurückgeben
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) als defekt melden
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) bewerten

### Kommunikation
- [User](12_glossary.md#user) kann direkt mit anderen Nutzern chatten
- [User](12_glossary.md#user) kann Nachrichten über Ausleihvorgänge erhalten

## 3.4 Scope und Abgrenzung

### Was ist Teil des MVP?
- Account-Management und Authentifizierung
- Artikelverwaltung (CRUD-Operationen)
- Suche mit entfernungsbasiertem Ranking
- Basis-Ausleihprozess und Rückgabe
- Direkte Kommunikation zwischen Nutzern
- Bewertungssystem für Artikel

### Ideen für Post-MVP

**Moderation:**
- [Moderator](12_glossary.md#moderator) kann Angebote prüfen und freigeben
- [Moderator](12_glossary.md#moderator) kann unangemessene Inhalte entfernen
- System kann automatische Vorfilterung durchführen

**Bezahlung:**
- [User](12_glossary.md#user) kann Peer-to-Peer Zahlungen durchführen
- System kann Ausleihgebühren verwalten
- System kann Transaktionshistorie führen

**Mehrsprachigkeit:**
- System kann in verschiedenen Sprachen angezeigt werden
- [User](12_glossary.md#user) kann bevorzugte Sprache einstellen

**Plattform-Erweiterungen:**
- System kann Backlog für geplante Features verwalten
- [User](12_glossary.md#user) kann Feature-Wünsche einreichen
- Individuelle Shopseiten mit erweiterten Kontaktdetails