# Übung 03 — Listen

## Erklärung

HTML kennt zwei Arten von Listen:

```html
<!-- Ungeordnete Liste (Punkte) -->
<ul>
  <li>Punkt eins</li>
  <li>Punkt zwei</li>
  <li>Punkt drei</li>
</ul>

<!-- Geordnete Liste (Zahlen) -->
<ol>
  <li>Erster Schritt</li>
  <li>Zweiter Schritt</li>
  <li>Dritter Schritt</li>
</ol>

<!-- Listen können verschachtelt werden -->
<ul>
  <li>Hauptpunkt
    <ul>
      <li>Unterpunkt</li>
      <li>Unterpunkt</li>
    </ul>
  </li>
</ul>
```

- `<ul>` — unordered list (keine Reihenfolge)
- `<ol>` — ordered list (mit Reihenfolge)
- `<li>` — list item (ein Listenelement)

## Aufgabe

Erstelle die Datei `03-listen.html`.

Baue eine Seite mit:
- Eine `<ul>` mit deinen Top 5 Lieblingsfilmen oder -serien
- Eine `<ol>` mit den 3 Dingen die du als erstes lernen möchtest
- Eine verschachtelte `<ul>` — z.B. Kategorien mit Unterpunkten (Hobbys → Sport → Fußball, Schwimmen...)

## Ziel

- Du kennst den Unterschied zwischen `<ul>` und `<ol>`
- Du kannst Listen verschachteln
