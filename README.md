# Neverwinter Keybinds
Angepasste Keybinds für das Spiel [Neverwinter](http://www.arcgames.com/de/games/neverwinter). Derzeit überarbeite ich jedoch noch die finale Zuordnung der Testen. Das heißt es kann sich nochmal etwas an der aktuellen Zuordnung ändern (verbessern).

## Quellen
Da nicht alles ausschließlich auf meinem Mist gewachsen ist, anbei die Quellen derer ich mich bedient habe. Vor allem bei [Wendylblack](http://neverwinter.gamepedia.com/User:Wendylblack/) habe ich mich großzügig bezüglich der Zoomfunktion bedient. Diese bislang die beste Lösung die ich finden konnte. Alternativ kann man sich auch einmal [die auf dem Laden von Dateien basieren de Lösung](http://bolorkestar.wixsite.com/marcusguide/usefull) von [Marcus's Guides](http://bolorkestar.wixsite.com/marcusguide) anschauen.

* http://neverwinter.gamepedia.com/Emotes
* http://neverwinter.gamepedia.com/Console_command
* http://neverwinter.gamepedia.com/User:Wendylblack/tricks https://iruladoon.enjin.com/forum/m/35927129/viewthread/29214643-neverwinter-key-binding
* https://www.reddit.com/r/Neverwinter/comments/1dp0pe/command_list_for_neverwinter/
* https://www.reddit.com/r/Neverwinter/comments/4ahw6n/useful_vip_keybind_commands/

## Tastenzuordnung
Nachfolgend eine Übersicht der Tastenzuordnung:

* `Strg+f` - Mit nahem Objekt interagieren (Wenn wieder alle vor der Bank stehen.)
* `Strg+ß` - Gefährten rufen / wegschicken (Das Gefähren-Menü liegt im Standard schon `ß`.)
* `8` - Ausgewähltem Ziel nachlaufen

### Maussteuerung
* `Mausrad rauf` - Hereinzoomen
* `Mausrad runter` - Herauszoomen
* `Mausrad klicken` - Standardansicht

### Funktionstasten
* ` F5` - VIP: Bankportal beschwören
* ` F6` - VIP: Berufsmaterialien-Händler beschwören
* ` F7` - VIP: Zur Mondsteinmaske teleportieren
* ` F8` - VIP: Reisewegweiser beschwören
* ` F9` - VIP: Briefkasten beschwören
* `F10` - VIP: Verwertungsamboss beschwören

### Sechserblock
* `Einfg` - Laden der Tastenzuordnung (inkl. Luftgitarre :guitar:)
* `Entf` - HUD ein- / ausblendne
* `Pos 1` - Charakterauswahl
* `Ende` - Führt den Befehl `/stuck` aus (Hilfreich, wenn man festhängt.)
* `Strg+Ende` - Führt den Befehl `/killme` aus, wenn `/stuck` nicht mehr ausreicht
* `Bild↑` - Netzwerk-Graph
* `Bild↓` - FPS-Graph
* `Strg+Bild↑` - Speicherauslastung
* `Strg+Bild↓` - Entwicklerinformationen

### Ziffernblock
* `1` - Geste: Verbeugen
* `2` - Geste: Winken
* `3` - Geste: Lachen
* `4` - Geste: Volkstanz
* `5` - Geste: Two-Step tanzen
* `6` - Geste: Hüftschwung
* `7` - Geste: Facepalm
* `8` - Geste: Double Facepalm
* `9` - Geste: Frustriert
* `0` - Geste: Sitzen
* `,` - Geste: AFK

#### Steurungstaste + Ziffernblock
* `Strg+1` - Geste: Pushups
* `Strg+2` - Geste: Jumping Jacks (Hampelmann)
* `Strg+3` - Geste: Aufstacheln
* `Strg+4` - Geste: Achselzucken
* `Strg+5` - Geste: Einnicken
* `Strg+6` - Geste: Strecken
* `Strg+7` - Geste: Spott
* `Strg+8` - Geste: Kusch kusch, schleich dich!
* `Strg+9` - Geste: Nachdenken

#### Mathematische Tasten des Ziffernblocks
* `/` - Anrufsegen
* `*` - CombatLog ein- / ausschalten
* `-` - Gruppe und Warteliste verlassen
* `+` - *"+++"* im Allianz-Chat senden
* `Enter` - *"+++"* im Gilden-Chat senden

## Installation
Naja, man kann hier nicht wirklich von einer Installation sprechen, viel mehr werden die Keybinds eingerichtet. Hierzu müssen zuerst die Dateien `ent_keybinds.txt` und `CommandAliases.txt` herunterladen und im entsprechenden Verzeichnis ablegen:

1. `ent_keybinds.txt` :arrow_right: `Cryptic Studios\Neverwinter\Live`
2. `CommandAliases.txt` :arrow_right: `Cryptic Studios\Neverwinter\Live\localdata`

Der Speicherort des Verzeichnisses ist abhängig von der gewählten Ziellaufwerk und der Installationsmethode (Steam oder Arc) abhängig, könnte aber folgendermaßen aussehen: `C:\Program Files (x86)\Steam\steamapps\common\Cryptic Studios\Neverwinter\Live`.

Ist dieser Schritt erledigt erfolgt die weitere Einrichtung im Spiel selbst.

### Aktivierung der Keybinds
Im Spiel *(also, wenn Ihr irgendwo herumrennt)* aktiviert Ihr über Eingabetaste die Konsole, das Chat-Fenster oder wie das Dings auch sonst heißt. Mit dem Befehl `/bind_load` werden die Keybinds geladen und können voran genutzt werden. Dieser Schritt ist für jeden Charakter getrennt auszuführen... *Oh Wunder!*

### Troubleshooting
Sollte das Zoomen über der Mausrad nicht klappen und Ihr seit euch sicher, dass Ihr **"a."** ein Mausrad habt und **"b."** dieses auch funktioniert, dann einfach mal den Befehl `/fov55` im Chat-Fenster eingeben.
