# Übung 10 — SEO Grundlagen

## Erklärung

SEO (Search Engine Optimization) bedeutet: deine Website so bauen, dass Suchmaschinen sie gut verstehen und hoch ranken.

HTML spielt dabei eine große Rolle:

```html
<!DOCTYPE html>
<html lang="de">
<head>
  <!-- Titel der Seite — erscheint in Suchergebnissen -->
  <title>Justin Elsner | Webentwickler aus Berlin</title>

  <!-- Beschreibung — erscheint unter dem Titel in Suchergebnissen -->
  <meta name="description" content="Ich bin Justin, Webentwickler aus Berlin. Ich baue moderne Websites mit HTML, CSS und JavaScript.">

  <!-- Viewport für Mobile -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Zeichensatz -->
  <meta charset="UTF-8">

  <!-- Open Graph (für Social Media Vorschau) -->
  <meta property="og:title" content="Justin Elsner | Webentwickler">
  <meta property="og:description" content="Moderne Websites mit HTML, CSS und JavaScript">
  <meta property="og:image" content="https://example.com/vorschau.jpg">
  <meta property="og:url" content="https://justinelsner.de">

  <!-- Canonical URL (verhindert doppelte Inhalte) -->
  <link rel="canonical" href="https://example.com/diese-seite">
</head>
<body>
  <!-- Nur ein h1 pro Seite -->
  <h1>Willkommen auf meiner Website</h1>

  <!-- Sinnvolle Struktur mit semantischen Tags -->
  <main>
    <article>
      <h2>Über mich</h2>
      <p>...</p>
    </article>
  </main>
</body>
</html>
```

**SEO-Regeln für HTML:**
- Jede Seite hat einen einzigartigen `<title>` (50-60 Zeichen)
- Jede Seite hat eine `<meta name="description">` (150-160 Zeichen)
- Nur ein `<h1>` pro Seite
- Überschriften-Hierarchie ist logisch (h1 → h2 → h3)
- Bilder haben `alt`-Texte mit relevanten Keywords
- URLs sind lesbar und beschreibend

## Aufgabe

Erstelle die Datei `10-seo-grundlagen.html`.

Baue eine optimierte Seite über ein Thema das dich interessiert (z.B. ein Hobby, ein Spiel, ein Film):
- Vollständige Meta-Tags im `<head>` (title, description, viewport, charset)
- Open Graph Tags für Social Media
- Sinnvoller `<h1>` mit dem Hauptkeyword
- Strukturierter Inhalt mit `<h2>` und `<h3>`
- Bilder mit keyword-reichen `alt`-Texten
- Semantische HTML-Struktur

## Ziel

- Du verstehst welche HTML-Elemente SEO beeinflussen
- Du baust Seiten die von Anfang an suchmaschinenfreundlich sind
