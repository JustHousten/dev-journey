# Übung 08 — HTML5 Features

## Erklärung

HTML5 hat viele nützliche Features eingeführt:

```html
<!-- Video einbinden -->
<video controls width="600">
  <source src="video.mp4" type="video/mp4">
  Dein Browser unterstützt kein Video.
</video>

<!-- Audio einbinden -->
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>

<!-- Fortschrittsbalken -->
<progress value="70" max="100"></progress>

<!-- Schieberegler -->
<input type="range" min="0" max="100" value="50">

<!-- Farbauswahl -->
<input type="color" value="#ff0000">

<!-- Details / Akkordeon -->
<details>
  <summary>Klick mich</summary>
  <p>Versteckter Inhalt der erscheint wenn man klickt.</p>
</details>

<!-- Datalist (Autocomplete für Input) -->
<input list="sprachen" placeholder="Programmiersprache">
<datalist id="sprachen">
  <option value="Python">
  <option value="JavaScript">
  <option value="HTML">
</datalist>

<!-- Meta Tags im Head -->
<meta name="description" content="Beschreibung der Seite">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Aufgabe

Erstelle die Datei `08-html5-features.html`.

Baue eine "Interaktive Vorstellungsseite" mit:
- Ein `<video>` oder `<audio>` Element (URL aus dem Internet reicht)
- Einen `<progress>` Balken der deinen "Lernfortschritt" zeigt
- Einen `<input type="range">` als "Wie gut kennst du dich mit Computern aus?"
- Mindestens 3 `<details>` Elemente (z.B. FAQs über dich)
- Eine `<datalist>` für Lieblingssprachen oder Hobbys
- Einen `<input type="color">` für "Meine Lieblingsfarbe"

## Ziel

- Du kennst die wichtigsten HTML5-Elemente
- Du siehst wie viel mit reinem HTML schon möglich ist
