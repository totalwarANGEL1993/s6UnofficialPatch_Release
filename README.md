# Inoffizieller Patch

Der inoffizielle Patch bereinigt einige Probleme in der Originalversion und in
der History Edition von "DIE SIEDLER - Aufstieg eines Königreichs", um die sich
die Entwickler einen Dreck scheren.

#### Rechtlicher Hinweis
Dieses Projekt ist ein Community-Projekt, das von Fans der Spielereihe Die 
Siedler entwickelt wurde. Es steht in keiner Verbindung zu Ubisoft oder Blue 
Byte und ist nicht offiziell autorisiert oder lizenziert.

Alle Rechte an Die Siedler – Aufstieg eines Königreichs, einschließlich Marken, 
Logos, Spielinhalten und anderen urheberrechtlich geschützten Materialien, 
liegen ausschließlich bei Ubisoft und Blue Byte.

Dieses Projekt dient ausschließlich der Modifikation und Erweiterung des 
Spielerlebnisses für bestehende, rechtmäßig erworbene Spielkopien.

## Originale Version

### Installation

Führe folgende Schritte zur Installation des Patches aus:

* Starte `S6UPOG-*.exe` (* = Versionsnummer).
  (Alle älteren Versionen müssen vorher deinstalliert werden!)
* Wähle das Verzeichnis über dem Installationsverzeichnis des Spiels.
  (z.B. `C:\Program Files\Ubisoft`)
* Starte die Installation und warte auf Abschluss.

### Deinstallation

* Öffne das Startmenü und suche `S6UnofficialPatch`.
* Führe den Uninstaller aus und warte auf Abschluss.

## History Edition

### Installation

Führe folgende Schritte zur Installation des Patches aus:

* Starte `S6UPHE-*.exe` (* = Versionsnummer).
  (Achte darauf alle vorherigen Versionen durch deinen Client zu entfernen!)
* Wähle das Verzeichnis über dem Installationsverzeichnis des Spiels.
  (z.B. `C:\SteamLibrary\steamapps\common`)
* Starte die Installation und Warte auf Abschluss.

### Deinstallation

Um den Patch zu deinstallieren, kannst du einfach in Steam oder Ubisoft Connect
die Spieldateien zurücksetzen.

### Lua Debugger

Dieser Abschnitt ist nur für Mapper interessant.

Der Patch ermöglicht es die History Edition über den LuaDebugger zu Starten. 
Dabei wird die History Edition __nur für diese Sitzung__ in das Original 
umgewandelt. Das Spiel ist dann auf Englisch und es kann nicht im Multiplayer
gespielt werden.

Um den Lua Debugger in der History Edition zu nutzen, muss das Data-Verzeichnis
ausgewählt werden, anstatt des Spielverzeichnis.

Beispiel: `C:\SteamLibrary\steamapps\common\The Settlers - Rise of an Empire - History Edition\Data`

Dann kann das Spiel ganz normal über den konventionellen Lua Debugger 
gestartet werden.