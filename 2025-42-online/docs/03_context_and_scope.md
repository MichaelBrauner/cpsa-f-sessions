# 3. Kontextabgrenzung

## 3.1 Fachlicher Kontext

[WillLeihen](12_glossary.md#willleihen) ist eine [Platform](12_glossary.md#platform), über die private Nutzer Gegenstände [verleihen](12_glossary.md#verleihen) und [ausleihen](12_glossary.md#ausleihen) können.

### Externe Akteure

| Akteur                      | Sendet                                                                      | Empfängt                                      |
|-----------------------------|-----------------------------------------------------------------------------|-----------------------------------------------|
| [User](12_glossary.md#user) | Suchanfragen, Artikelangaben, [Rückgabe](12_glossary.md#rueckgabe)meldungen | Suchergebnisse, Artikeldetails, Bestätigungen |

### Fachliche Nachbarsysteme

| System                                                              | Sendet                             | Empfängt                        |
|---------------------------------------------------------------------|------------------------------------|---------------------------------|
| [Authentifizierungsdienst](12_glossary.md#authentifizierungsdienst) | Login-Tokens, Nutzeridentität      | Authentifizierungsanfragen      |
| Datenbank                                                           | Artikel-, Nutzer- und Ausleihdaten | Speicher- und Änderungsanfragen |

*Technische Details zu verwendeten Systemen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).* 

## 3.2 Technischer Kontext (optional)
Wird im [MVP](12_glossary.md#mvp)-Entwurf nicht modelliert.

## 3.3 Funktionale Anforderungen

### Registrierung
- [User](12_glossary.md#user) kann sich über Google registrieren

### Login
- [User](12_glossary.md#user) kann sich über Google einloggen
- [User](12_glossary.md#user) kann sich ausloggen

### Artikelverwaltung
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) anlegen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) bearbeiten
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) löschen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) suchen
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) [ausleihen](12_glossary.md#ausleihen)
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) zurückgeben
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) als defekt melden
- [User](12_glossary.md#user) kann [Artikel](12_glossary.md#artikel) bewerten
