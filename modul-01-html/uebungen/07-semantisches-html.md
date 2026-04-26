# Übung 07 — Semantisches HTML

## Erklärung

Semantisches HTML bedeutet: Tags die beschreiben **was** ihr Inhalt ist — nicht nur wie er aussieht.

```html
<!-- Nicht semantisch -->
<div id="header">...</div>
<div id="nav">...</div>
<div id="content">...</div>
<div id="footer">...</div>

<!-- Semantisch -->
<header>...</header>
<nav>...</nav>
<main>...</main>
<footer>...</footer>
```

**Die wichtigsten semantischen Tags:**

```html
<header>   <!-- Kopfbereich der Seite oder eines Abschnitts -->
<nav>      <!-- Navigation / Menü -->
<main>     <!-- Hauptinhalt der Seite (nur einmal!) -->
<section>  <!-- Thematischer Abschnitt -->
<article>  <!-- Eigenständiger Inhalt (Blogpost, Nachricht...) -->
<aside>    <!-- Seiteninhalt (Sidebar, Zusatzinfo) -->
<footer>   <!-- Fußbereich -->
<figure>   <!-- Bild mit Beschriftung -->
<figcaption> <!-- Beschriftung für figure -->
<time>     <!-- Datum/Uhrzeit -->
<address>  <!-- Kontaktinformationen -->
```

**Warum semantisch?**
- Besser für Screenreader (Barrierefreiheit)
- Besser für Suchmaschinen (SEO)
- Besser lesbar für andere Entwickler

## Aufgabe

Erstelle die Datei `07-semantisches-html.html`.

Baue eine Seite für einen fiktiven Blog mit:
- `<header>` mit Logo-Text und Seitentitel
- `<nav>` mit 4 Navigationspunkten (Links)
- `<main>` mit zwei `<article>` Elementen (zwei Blogposts)
  - Jeder Artikel hat: `<h2>` Titel, `<time>` Datum, `<p>` Text, `<figure>` mit Bild und `<figcaption>`
- `<aside>` mit "Über den Autor" Text
- `<footer>` mit Copyright-Text

## Ziel

- Du verstehst den Unterschied zwischen semantisch und nicht-semantisch
- Du kannst eine sinnvoll strukturierte Seite aufbauen
