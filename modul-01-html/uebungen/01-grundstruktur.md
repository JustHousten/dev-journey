# Übung 01 — Die Grundstruktur

## Erklärung

Jede HTML-Seite hat ein Grundgerüst. Ohne dieses Gerüst funktioniert nichts:

```html
<!DOCTYPE html>
<html lang="de">
  <head>
    <meta charset="UTF-8">
    <title>Meine erste Seite</title>
  </head>
  <body>
    <!-- Hier kommt der sichtbare Inhalt -->
  </body>
</html>
```

**Was bedeutet was:**
- `<!DOCTYPE html>` — sagt dem Browser: das ist HTML5
- `<html lang="de">` — Beginn der Seite, Sprache Deutsch
- `<head>` — unsichtbare Infos über die Seite (Titel, Zeichensatz...)
- `<title>` — der Text der im Browser-Tab erscheint
- `<body>` — alles was der Benutzer sieht kommt hier rein

## Aufgabe

Erstelle die Datei `01-grundstruktur.html` im gleichen Ordner.

Baue das Grundgerüst nach und schreib in den `<body>` einen kurzen Text über dich — einfach als normalen Text, noch kein besonderer Tag.

## Ziel

- Du verstehst den Aufbau einer HTML-Seite
- Die Seite öffnet sich im Browser ohne Fehler
- Im Browser-Tab steht dein gewählter Titel
