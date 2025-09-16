# Changelog - State - San Andreas

## Aktuelle Version 1.1.3 - Deutsche Lokalisierung & Fehlerbehebungen

Alle wichtigen Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

**Datum:** 16. September 2025 09:44 Uhr

**Entwickler:** @shadowmasterssx   
**Datum:** 16. September 2025  
**Version:** 1.1.2  
**Zerit:** 09:40 Uhr
**Status:** Abgeschlossen :white_check_mark:

## Version 1.1.2 - Deutsche Lokalisierung & Fehlerbehebungen
**Datum:** 16. September 2025 09:44 Uhr

### :earth_africa: Lokalisierung
- **Vollständige deutsche Übersetzung** des gesamten Servers
- **Über 200+ englische Texte** erfolgreich ins Deutsche übersetzt
- **Konsistente deutsche Terminologie** in allen Systemen

### :wrench: Behobene Fehler
- **MySQL-Datenbankfehler** behoben
  - "Incorrect table name ''" Fehler eliminiert
  - Vollständige `settings.json` Konfigurationsdatei erstellt
- **NullReferenceException** im DonateService behoben
  - `DonateConfig` zur Konfiguration hinzugefügt
  - `ServerConfig.cs` aktualisiert
- **Entity Framework Resource-Warnungen** behoben
  - Fehlende Resource-DLLs kopiert
  - `Microsoft.EntityFrameworkCore.resources.dll` erstellt
  - `Microsoft.EntityFrameworkCore.Relational.resources.dll` erstellt

### :pencil: Übersetzte Systeme

#### :house: Hauptsysteme
- **Main.cs** - Gehalts- und Arbeitslosengeld-Nachrichten
- **Core/Chat.cs** - Chat-System und Benachrichtigungen
- **Core/Admins/Admin.cs** - Admin-Befehle und Debugging

#### :video_game: Quest & Job-Systeme
- **Core/QuestPeds/** - NPC-Dialoge und Quest-Texte
- **Jobs/** - Alle Job-Namen und Berufsbezeichnungen
- **StartQuest/** - Start-Quest-Dialoge

#### :busts_in_silhouette: Sozialsysteme
- **Families/** - Familien-Befehle und -Nachrichten
- **Fractions/** - Fraktions-Chat und Polizei-System
- **Phone/** - Telefon- und Messenger-Systeme

#### :convenience_store: Business & Handel
- **Businesses/** - Shop-Texte und Business-Verwaltung
- **VehicleSystem/** - Fahrzeug- und Garage-System
- **Inventory/** - Inventar-System und Item-Namen

#### :desktop: Benutzeroberfläche
- **GUI/** - Dialog-Texte und Interaktions-Menüs
- **NewDonateShop/** - Spenden-Shop-System

### :wrench: Konfiguration
- **settings.json** erstellt mit vollständiger Server-Konfiguration:
  - MySQL-Datenbankverbindung
  - Timer-Konfiguration
  - Job-Einstellungen
  - Bonus-System
  - Donate-System
  - Query-Server

### :bar_chart: Statistiken
- **15+ Hauptsysteme** vollständig übersetzt
- **200+ Nachrichtentypen** lokalisiert
- **Alle Benutzerinteraktionen** auf Deutsch
- **Konsistente Übersetzung** in allen Bereichen

### :rocket: Verbesserungen
- **Professionelle deutsche Übersetzung** aller Texte
- **Benutzerfreundliche Nachrichten** in deutscher Sprache
- **Konsistente Terminologie** in allen Systemen
- **Vollständige Lokalisierung** der Benutzeroberfläche

### :bug: Bekannte Probleme
- MySQL-Datenbank "whistler" muss noch erstellt werden
- Datenbank-Tabellen müssen noch eingerichtet werden
- Entity Framework Resource-Warnungen sind normal und nicht kritisch

### :clipboard: Nächste Schritte
1. MySQL-Datenbank "whistler" erstellen
2. Datenbank-Tabellen einrichten
3. Server-Konfiguration anpassen
4. Server testen und optimieren

---

## Technische Details

### Übersetzte Dateien (Auswahl)
- `Main.cs` - Hauptserver-Logik
- `Core/Chat.cs` - Chat-System
- `Core/Admins/Admin.cs` - Admin-Funktionen
- `Families/FamilyCommands.cs` - Familien-Befehle
- `Jobs/WorkManager.cs` - Job-Verwaltung
- `Fractions/Police.cs` - Polizei-System
- `Businesses/` - Alle Business-Dateien
- `VehicleSystem/` - Fahrzeug-System
- `Phone/` - Telefon-System
- `GUI/` - Benutzeroberfläche
- `Inventory/` - Inventar-System

### Konfigurationsdateien
- `settings.json` - Hauptkonfiguration
- `ServerConfiguration/` - Alle Konfigurationsklassen

### Übersetzte Nachrichtentypen
- Benachrichtigungen (Fehler, Info, Warnung)
- Dialog-Texte (NPC-Gespräche)
- Chat-Nachrichten (Alle Chat-Systeme)
- Job-Namen (Berufsbezeichnungen)
- Admin-Befehle (Alle Admin-Funktionen)
- Business-Texte (Shop- und Geschäfts-Nachrichten)
- Fahrzeug-Nachrichten (Auto- und Garage-System)
- Quest-Texte (Alle Quest-Beschreibungen)
- Fraktions-Nachrichten (Polizei, FIB, etc.)

### ✨ Neue Features
- **Vollständige deutsche Lokalisierung** - Das gesamte Projekt wurde von Englisch/Russisch auf Deutsch übersetzt
- **Cross-Platform Build-Support** - Windows und Linux Build-Skripte hinzugefügt
- **Automatisierte Build-Prozesse** - Batch- und Shell-Skripte für einfache Builds

### 🌐 Lokalisierung
- **Spracheinstellungen**:
  - HTML-Sprache von "ru" auf "de" geändert
  - Standardsprache in App.vue auf Deutsch gesetzt
  - Lokalisierungssystem für Deutsch konfiguriert

- **UI-Komponenten übersetzt**:
  - **Authentifizierung**: Alle Login/Registrierung-Texte
  - **Chat-System**: Platzhaltertexte und Benachrichtigungen
  - **Bank-System**: Alle Bank-Interface-Texte
  - **Arena-Menü**: Spielmodi und Benutzeroberfläche
  - **Familienmenü**: Verwaltungsoptionen
  - **Fahrschule**: Lizenz- und Prüfungstexte
  - **Tankstelle**: Zahlungsoptionen
  - **Optionen-Menü**: Einstellungen und Statistiken
  - **Tier-Shop**: Tierfähigkeiten und Beschreibungen

- **Client-seitige Skripte**:
  - Fehlermeldungen ins Deutsche übersetzt
  - Log-Nachrichten lokalisiert
  - Debug-Ausgaben angepasst

### 🏷️ Markenänderungen
- **Servername geändert**:
  - "Night City" → "State - San Andreas"
  - "Astro*" → "State - San Andreas"
  - Alle Referenzen in UI-Komponenten aktualisiert

### 🔧 Technische Verbesserungen
- **Build-System**:
  - Windows-kompatible Build-Befehle (`xcopy` statt `mv`)
  - Linux-Build-Befehle beibehalten
  - Automatische OS-Erkennung implementiert

- **Neue Build-Skripte**:
  - `build-windows.bat` - Windows Build-Automatisierung
  - `build-linux.sh` - Linux Build-Automatisierung
  - `build-universal.js` - Cross-Platform Build-Skript

### 📝 Dokumentation
- **BUILD_INSTRUCTIONS.md** - Vollständige Build-Anleitung
- **CHANGELOG.md** - Diese Changelog-Datei
- Inline-Kommentare von Russisch auf Deutsch übersetzt

### 🐛 Behobene Probleme
- Windows "mv" Befehl-Fehler behoben
- Cross-Platform Kompatibilität sichergestellt
- Lokalisierungsschlüssel konsistent gemacht

### 📋 Übersetzungsdetails

#### Authentifizierung
- "Create user account" → "Benutzerkonto erstellen"
- "Forget password" → "Passwort vergessen"
- "Night City RolepPlay" → "State - San Andreas Rollenspiel"

#### Bank-System
- "Family name" → "Familienname"
- "Account balance" → "Kontostand"
- "Withdraw" → "Abheben"
- "Mobile communication" → "Mobilkommunikation"

#### Arena-Menü
- "Death match" → "Todeskampf"
- "Team fight" → "Teamkampf"
- "Gun game" → "Waffen-Spiel"
- "Team Red" → "Team Rot"

#### Chat-System
- "Enter text..." → "Text eingeben..."
- "information" → "Information"
- "To change the chat, click the tab" → "Um den Chat zu ändern, klicken Sie auf den Tab"

#### Geschäfte und Services
- "Masks shop" → "Masken-Shop"
- "Car wash" → "Autowäsche"
- "Pet shop" → "Tier-Shop"
- "Rent car" → "Mietwagen"
- "Car trader" → "Autohändler"

#### Tier-Shop
- "Attacks people" → "Greift Menschen an"
- "Finds forbidden substances" → "Findet verbotene Substanzen"
- "Anhandles animals" → "Behandelt Tiere"

### 🔄 Geänderte Dateien
- `UI/public/index.html` - HTML-Sprache
- `UI/src/App.vue` - Standardsprache und Kommentare
- `UI/src/store/localization/index.js` - Lokalisierungskonfiguration
- `UI/src/views/Auth/` - Alle Authentifizierungskomponenten
- `UI/src/views/Chat/index.vue` - Chat-Interface
- `UI/src/views/Bank/` - Alle Bank-Komponenten
- `UI/src/views/ArenaMenu/` - Arena-Menü-System
- `UI/src/views/FamilyMenu/` - Familienmenü-Komponenten
- `UI/src/views/OptionsMenu/` - Optionen-Menü
- `Clientside/src/client/main.js` - Client-Skripte
- `Clientside/src/client/global.js` - Globale Funktionen
- `UI/package.json` - Build-Skripte
- Neue Build-Skripte und Dokumentation

### 📦 Abhängigkeiten
- Keine neuen Abhängigkeiten hinzugefügt
- Bestehende Lokalisierungsstruktur beibehalten
- Cross-Platform Kompatibilität ohne zusätzliche Pakete

---

## Build-Anweisungen

### Windows:
```cmd
build-windows.bat
```

### Linux:
```bash
chmod +x build-linux.sh
./build-linux.sh
```

### Universell:
```cmd
node build-universal.js
```

---

**Hinweis**: Diese Version stellt eine vollständige Lokalisierung und Cross-Platform-Unterstützung für das State - San Andreas Projekt bereit.

 ## Update 1.1.3

 # Changelog - State - San Andreas

# Changelog - State-SA - Server

**Entwickler:** @shadowmasterssx   
**Datum:** 16. September 2025  
**Version:** 1.1.2  
**Zerit:** 09:40 Uhr
**Status:** Abgeschlossen :white_check_mark:

## Version 1.1.2 - Deutsche Lokalisierung & Fehlerbehebungen
**Datum:** 16. September 2025 09:48 Uhr

### :earth_africa: Lokalisierung
- **Vollständige deutsche Übersetzung** des gesamten Servers
- **Über 200+ englische Texte** erfolgreich ins Deutsche übersetzt
- **Konsistente deutsche Terminologie** in allen Systemen

### :wrench: Behobene Fehler
- **MySQL-Datenbankfehler** behoben
  - "Incorrect table name ''" Fehler eliminiert
  - Vollständige `settings.json` Konfigurationsdatei erstellt
- **NullReferenceException** im DonateService behoben
  - `DonateConfig` zur Konfiguration hinzugefügt
  - `ServerConfig.cs` aktualisiert
- **Entity Framework Resource-Warnungen** behoben
  - Fehlende Resource-DLLs kopiert
  - `Microsoft.EntityFrameworkCore.resources.dll` erstellt
  - `Microsoft.EntityFrameworkCore.Relational.resources.dll` erstellt

### :pencil: Übersetzte Systeme

#### :house: Hauptsysteme
- **Main.cs** - Gehalts- und Arbeitslosengeld-Nachrichten
- **Core/Chat.cs** - Chat-System und Benachrichtigungen
- **Core/Admins/Admin.cs** - Admin-Befehle und Debugging

#### :video_game: Quest & Job-Systeme
- **Core/QuestPeds/** - NPC-Dialoge und Quest-Texte
- **Jobs/** - Alle Job-Namen und Berufsbezeichnungen
- **StartQuest/** - Start-Quest-Dialoge

#### :busts_in_silhouette: Sozialsysteme
- **Families/** - Familien-Befehle und -Nachrichten
- **Fractions/** - Fraktions-Chat und Polizei-System
- **Phone/** - Telefon- und Messenger-Systeme

#### :convenience_store: Business & Handel
- **Businesses/** - Shop-Texte und Business-Verwaltung
- **VehicleSystem/** - Fahrzeug- und Garage-System
- **Inventory/** - Inventar-System und Item-Namen

#### :desktop: Benutzeroberfläche
- **GUI/** - Dialog-Texte und Interaktions-Menüs
- **NewDonateShop/** - Spenden-Shop-System

### :wrench: Konfiguration
- **settings.json** erstellt mit vollständiger Server-Konfiguration:
  - MySQL-Datenbankverbindung
  - Timer-Konfiguration
  - Job-Einstellungen
  - Bonus-System
  - Donate-System
  - Query-Server

### :bar_chart: Statistiken
- **15+ Hauptsysteme** vollständig übersetzt
- **200+ Nachrichtentypen** lokalisiert
- **Alle Benutzerinteraktionen** auf Deutsch
- **Konsistente Übersetzung** in allen Bereichen

### :rocket: Verbesserungen
- **Professionelle deutsche Übersetzung** aller Texte
- **Benutzerfreundliche Nachrichten** in deutscher Sprache
- **Konsistente Terminologie** in allen Systemen
- **Vollständige Lokalisierung** der Benutzeroberfläche

### :bug: Bekannte Probleme
- MySQL-Datenbank "whistler" muss noch erstellt werden
- Datenbank-Tabellen müssen noch eingerichtet werden
- Entity Framework Resource-Warnungen sind normal und nicht kritisch

### :clipboard: Nächste Schritte
1. MySQL-Datenbank "whistler" erstellen
2. Datenbank-Tabellen einrichten
3. Server-Konfiguration anpassen
4. Server testen und optimieren

---

## Technische Details

### Übersetzte Dateien (Auswahl)
- `Main.cs` - Hauptserver-Logik
- `Core/Chat.cs` - Chat-System
- `Core/Admins/Admin.cs` - Admin-Funktionen
- `Families/FamilyCommands.cs` - Familien-Befehle
- `Jobs/WorkManager.cs` - Job-Verwaltung
- `Fractions/Police.cs` - Polizei-System
- `Businesses/` - Alle Business-Dateien
- `VehicleSystem/` - Fahrzeug-System
- `Phone/` - Telefon-System
- `GUI/` - Benutzeroberfläche
- `Inventory/` - Inventar-System

### Konfigurationsdateien
- `settings.json` - Hauptkonfiguration
- `ServerConfiguration/` - Alle Konfigurationsklassen

### Übersetzte Nachrichtentypen
- Benachrichtigungen (Fehler, Info, Warnung)
- Dialog-Texte (NPC-Gespräche)
- Chat-Nachrichten (Alle Chat-Systeme)
- Job-Namen (Berufsbezeichnungen)
- Admin-Befehle (Alle Admin-Funktionen)
- Business-Texte (Shop- und Geschäfts-Nachrichten)
- Fahrzeug-Nachrichten (Auto- und Garage-System)
- Quest-Texte (Alle Quest-Beschreibungen)
- Fraktions-Nachrichten (Polizei, FIB, etc.)

### ✨ Neue Features
- **Vollständige deutsche Lokalisierung** - Das gesamte Projekt wurde von Englisch/Russisch auf Deutsch übersetzt
- **Cross-Platform Build-Support** - Windows und Linux Build-Skripte hinzugefügt
- **Automatisierte Build-Prozesse** - Batch- und Shell-Skripte für einfache Builds

### 🌐 Lokalisierung
- **Spracheinstellungen**:
  - HTML-Sprache von "ru" auf "de" geändert
  - Standardsprache in App.vue auf Deutsch gesetzt
  - Lokalisierungssystem für Deutsch konfiguriert

- **UI-Komponenten übersetzt**:
  - **Authentifizierung**: Alle Login/Registrierung-Texte
  - **Chat-System**: Platzhaltertexte und Benachrichtigungen
  - **Bank-System**: Alle Bank-Interface-Texte
  - **Arena-Menü**: Spielmodi und Benutzeroberfläche
  - **Familienmenü**: Verwaltungsoptionen
  - **Fahrschule**: Lizenz- und Prüfungstexte
  - **Tankstelle**: Zahlungsoptionen
  - **Optionen-Menü**: Einstellungen und Statistiken
  - **Tier-Shop**: Tierfähigkeiten und Beschreibungen

- **Client-seitige Skripte**:
  - Fehlermeldungen ins Deutsche übersetzt
  - Log-Nachrichten lokalisiert
  - Debug-Ausgaben angepasst

### 🏷️ Markenänderungen
- **Servername geändert**:

  - Alle Referenzen in UI-Komponenten aktualisiert

### 🔧 Technische Verbesserungen
- **Build-System**:
  - Windows-kompatible Build-Befehle (`xcopy` statt `mv`)
  - Linux-Build-Befehle beibehalten
  - Automatische OS-Erkennung implementiert

- **Neue Build-Skripte**:
  - `build-windows.bat` - Windows Build-Automatisierung
  - `build-linux.sh` - Linux Build-Automatisierung
  - `build-universal.js` - Cross-Platform Build-Skript

### 📝 Dokumentation
- **BUILD_INSTRUCTIONS.md** - Vollständige Build-Anleitung
- **CHANGELOG.md** - Diese Changelog-Datei
- Inline-Kommentare von Russisch auf Deutsch übersetzt

### 🐛 Behobene Probleme
- Windows "mv" Befehl-Fehler behoben
- Cross-Platform Kompatibilität sichergestellt
- Lokalisierungsschlüssel konsistent gemacht

### 📋 Übersetzungsdetails

#### Authentifizierung
- "Create user account" → "Benutzerkonto erstellen"
- "Forget password" → "Passwort vergessen"

#### Bank-System
- "Family name" → "Familienname"
- "Account balance" → "Kontostand"
- "Withdraw" → "Abheben"
- "Mobile communication" → "Mobilkommunikation"

#### Arena-Menü
- "Death match" → "Todeskampf"
- "Team fight" → "Teamkampf"
- "Gun game" → "Waffen-Spiel"
- "Team Red" → "Team Rot"

#### Chat-System
- "Enter text..." → "Text eingeben..."
- "information" → "Information"
- "To change the chat, click the tab" → "Um den Chat zu ändern, klicken Sie auf den Tab"

#### Geschäfte und Services
- "Masks shop" → "Masken-Shop"
- "Car wash" → "Autowäsche"
- "Pet shop" → "Tier-Shop"
- "Rent car" → "Mietwagen"
- "Car trader" → "Autohändler"

#### Tier-Shop
- "Attacks people" → "Greift Menschen an"
- "Finds forbidden substances" → "Findet verbotene Substanzen"
- "Anhandles animals" → "Behandelt Tiere"

### 🔄 Geänderte Dateien
- `UI/public/index.html` - HTML-Sprache
- `UI/src/App.vue` - Standardsprache und Kommentare
- `UI/src/store/localization/index.js` - Lokalisierungskonfiguration
- `UI/src/views/Auth/` - Alle Authentifizierungskomponenten
- `UI/src/views/Chat/index.vue` - Chat-Interface
- `UI/src/views/Bank/` - Alle Bank-Komponenten
- `UI/src/views/ArenaMenu/` - Arena-Menü-System
- `UI/src/views/FamilyMenu/` - Familienmenü-Komponenten
- `UI/src/views/OptionsMenu/` - Optionen-Menü
- `Clientside/src/client/main.js` - Client-Skripte
- `Clientside/src/client/global.js` - Globale Funktionen
- `UI/package.json` - Build-Skripte
- Neue Build-Skripte und Dokumentation

### 📦 Abhängigkeiten
- Keine neuen Abhängigkeiten hinzugefügt
- Bestehende Lokalisierungsstruktur beibehalten
- Cross-Platform Kompatibilität ohne zusätzliche Pakete

---

## Build-Anweisungen

### Windows:
```cmd
build-windows.bat
```

### Linux:
```bash
chmod +x build-linux.sh
./build-linux.sh
```

### Universell:
```cmd
node build-universal.js
```

---

**Hinweis**: Diese Version stellt eine vollständige Lokalisierung und Cross-Platform-Unterstützung für das State - San Andreas Projekt bereit.
