# Übung 09 — Accessibility (Barrierefreiheit)

## Erklärung

Accessibility (kurz: a11y) bedeutet, dass deine Website für alle Menschen nutzbar ist — auch für Menschen mit Sehbehinderung, die einen Screenreader benutzen.

```html
<!-- Schlechtes Beispiel -->
<div onclick="doSomething()">Klick mich</div>
<img src="logo.png">

<!-- Gutes Beispiel -->
<button onclick="doSomething()">Klick mich</button>
<img src="logo.png" alt="Firmenlogo von XY">
```

**Die wichtigsten Regeln:**

```html
<!-- 1. Immer alt-Text bei Bildern -->
<img src="foto.jpg" alt="Mann sitzt am Schreibtisch und programmiert">

<!-- 2. Labels für alle Inputs -->
<label for="email">E-Mail Adresse</label>
<input type="email" id="email" name="email">

<!-- 3. ARIA-Labels wenn kein Text vorhanden -->
<button aria-label="Menü öffnen">☰</button>

<!-- 4. Lang-Attribut auf html -->
<html lang="de">

<!-- 5. Sinnvolle Überschriften-Hierarchie -->
<h1>Haupttitel</h1>
  <h2>Abschnitt</h2>
    <h3>Unterabschnitt</h3>

<!-- 6. Skip-Navigation für Tastatur-Nutzer -->
<a href="#main-content" class="skip-link">Zum Hauptinhalt springen</a>

<!-- 7. role-Attribut -->
<div role="alert">Fehlermeldung!</div>
<nav role="navigation" aria-label="Hauptnavigation">...</nav>
```

## Aufgabe

Erstelle die Datei `09-accessibility.html`.

Nimm deine Datei aus Übung 07 (semantischer Blog) als Basis und verbessere sie:
- Alle Bilder haben aussagekräftige `alt`-Texte
- Alle Formular-Elemente haben Labels
- Füge `aria-label` bei Icons oder Buttons ohne Text hinzu
- Füge einen "Zum Hauptinhalt springen" Link ganz oben ein
- Überprüfe die Überschriften-Hierarchie — ist sie logisch?
- Füge `role` Attribute wo sinnvoll hinzu

## Ziel

- Du verstehst warum Accessibility wichtig ist
- Du kennst die grundlegenden ARIA-Attribute
- Du baust von Anfang an zugängliche Websites
