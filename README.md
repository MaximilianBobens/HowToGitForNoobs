Git-Integration aktivieren

Öffne dein Projekt in Rider.

Wähle im Menü VCS ▶ Enable Version Control Integration….

Wähle Git und klicke auf OK.

Lokales Git-Repository initialisieren (falls noch nicht vorhanden)

Rider legt dann automatisch ein lokales Git-Repository im Projektordner an.

Alternativ: Rechtsklick aufs Projekt im Solution Explorer ▶ Git ▶ Init.

Neues GitHub-Repository erstellen

Öffne deinen Browser und gehe zu GitHub.

Erstelle ein neues Repository (z. B. über den New-Button oben links).

Gib Name, Beschreibung und Sichtbarkeit an und klicke auf Create repository.

Kopiere die HTTPS-URL (z. B. https://github.com/username/repo.git).

Remote-URL in Rider hinzufügen

In Rider: View ▶ Tool Windows ▶ Git (oder unten rechts auf das Git-Icon klicken).

Im Git-Toolfenster oben rechts auf das Zahnrad-Symbol ▶ Manage Remotes….

Klicke auf +, füge als Name „origin“ und als URL deine kopierte HTTPS-Adresse ein, dann OK.

Dateien zum Commit vormerken

Wechsle im Git-Toolfenster auf den Reiter Local Changes.

Markiere alle Dateien, die du versionieren möchtest (üblicherweise alle neuen/angepassten Dateien).

Rechtsklick ▶ Add to VCS (wird oft automatisch gemacht, sobald du in Local Changes bist).

Commit und Push

Gib unten im Commit-Fenster eine aussagekräftige Commit-Message ein (z. B. „Initial project setup“).

Klicke auf den Pfeil neben Commit und wähle Commit and Push….

Überprüfe im erscheinenden Dialog, dass als Remote „origin“ und als Branch „main“ (oder „master“) ausgewählt ist, und bestätige mit Push.

Erfolg prüfen

Lade dein GitHub-Repository im Browser neu.

Deine Commits und Dateien sollten jetzt im Repository sichtbar sein.
