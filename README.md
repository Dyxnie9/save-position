THIS IS A REMAKE OF https://forum.cfx.re/t/release-save-respawn-the-last-player-position-with-mysql/15523/126

save-position
FiveM Script zum Speichern der aktuellen Position

Installation
- Lade die Datei von GitHub herunter und entpacke sie
- Nehme den Ordner "save-postion" und ziehe ihn in dein resource Verzeichnis
- Importiere die SQL Datei in deine Datenbank
- Trage "start save-position" in deine server.cfg NACH fivem-mysql-async 
!<>! (https://github.com/brouznouf/fivem-mysql-async)

Starte deinen Server neu und viel Spaß damit

KONFIGURATION
Derzeit speichert das Script die Zeit automatisch. Wenn du dies ändern möchtest gehe zur 
client.lua und ändere die Zeile 11
Ändere den Wert "10000" in deinen Entsprechenden Wert - Die Zeit ist in Milisekunden
