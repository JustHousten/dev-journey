# Übung 04 — Links und Bilder

## Erklärung

```html
<!-- Link -->
<a href="https://www.google.com">Zu Google</a>

<!-- Link öffnet in neuem Tab -->
<a href="https://www.google.com" target="_blank">Zu Google (neuer Tab)</a>

<!-- Link zu einer anderen Seite im eigenen Projekt -->
<a href="andere-seite.html">Zur anderen Seite</a>

<!-- Bild -->
<img src="bild.jpg" alt="Beschreibung des Bildes">

<!-- Bild aus dem Internet -->
<img src="https://example.com/bild.jpg" alt="Beschreibung">

<!-- Bild als Link -->
<a href="https://www.google.com">
  <img src="bild.jpg" alt="Beschreibung">
</a>
```

**Wichtig:** Das `alt`-Attribut bei Bildern ist Pflicht — es beschreibt das Bild für Screenreader und falls das Bild nicht lädt.

## Aufgabe

Erstelle die Datei `04-links-und-bilder.html`.

Baue eine Seite mit:
- Mindestens 3 Links zu Websites die du magst — einer davon öffnet in neuem Tab
- Ein Bild aus dem Internet (einfach eine Bild-URL kopieren)
- Einen Link der zu deiner `02-texte-und-ueberschriften.html` führt
- Einen Link der als Bild dargestellt wird

## Ziel

- Du verstehst wie `href` und `src` funktionieren
- Du weißt wann `target="_blank"` sinnvoll ist
- Du weißt warum `alt` wichtig ist
