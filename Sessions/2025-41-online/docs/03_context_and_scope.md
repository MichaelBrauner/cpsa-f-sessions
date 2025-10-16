# 3. Kontextabgrenzung

## 3.1 Fachlicher Kontext

WillLeihen ist eine Plattform, über die private Nutzer Gegenstände verleihen und ausleihen können.

### Externe Akteure
- **User** - jeder User kann Ausleihen und Verleihen

### Fachliche Nachbarsysteme
- **Authentifizierungsdienst** – Login, Registrierung
- **Datenbank** – Datenhaltung

*Technische Details zu verwendeten Systemen siehe [Kapitel 2 - Architekturbeschränkungen](02_architecture_constraints.md).*

### Informationsflüsse
- User ↔ WillLeihen: Such-, Rückgabeprozesse und Angebotsverwaltung
- WillLeihen ↔ Authentifizierungsdienst: Identifikation 

## 3.2 Technischer Kontext (optional)
Wird im MVP-Entwurf nicht modelliert.

## 3.3 Funktionale Anforderungen

### Registrierung
- User kann sich über Google registrieren

### Login
- User kann sich über Google einloggen
- User kann sich ausloggen

### Artikelverwaltung
- User kann Artikel anlegen
- User kann Artikel bearbeiten
- User kann Artikel löschen
- User kann Artikel suchen
- User kann Artikel ausleihen
- User kann Artikel zurückgeben
- User kann Artikel als defekt melden
- User kann Artikel bewerten
