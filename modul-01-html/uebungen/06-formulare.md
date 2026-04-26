# Übung 06 — Formulare

## Erklärung

```html
<form>
  <!-- Textfeld -->
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Dein Name">

  <!-- E-Mail -->
  <input type="email" id="email" name="email" placeholder="deine@email.de">

  <!-- Passwort -->
  <input type="password" id="passwort" name="passwort">

  <!-- Zahl -->
  <input type="number" id="alter" name="alter" min="0" max="120">

  <!-- Checkbox -->
  <input type="checkbox" id="agb" name="agb">
  <label for="agb">Ich akzeptiere die AGB</label>

  <!-- Radio Buttons -->
  <input type="radio" id="maennlich" name="geschlecht" value="m">
  <label for="maennlich">Männlich</label>
  <input type="radio" id="weiblich" name="geschlecht" value="w">
  <label for="weiblich">Weiblich</label>

  <!-- Dropdown -->
  <select id="land" name="land">
    <option value="de">Deutschland</option>
    <option value="at">Österreich</option>
    <option value="ch">Schweiz</option>
  </select>

  <!-- Mehrzeiliges Textfeld -->
  <textarea id="nachricht" name="nachricht" rows="5" cols="40"></textarea>

  <!-- Button -->
  <button type="submit">Absenden</button>
</form>
```

**Wichtig:** `<label>` und `<input>` gehören zusammen — das `for` im Label muss zur `id` des Inputs passen.

## Aufgabe

Erstelle die Datei `06-formulare.html`.

Baue ein Registrierungsformular mit:
- Vorname, Nachname (Textfelder)
- E-Mail Adresse
- Passwort
- Geburtsdatum (`type="date"`)
- Geschlecht (Radio Buttons)
- Land (Dropdown mit 5 Ländern)
- Interessen (mindestens 3 Checkboxen)
- Nachricht / Über mich (Textarea)
- Absenden-Button

## Ziel

- Du kennst die wichtigsten Input-Typen
- Du verstehst wie `label` und `input` zusammengehören
- Du kannst ein vollständiges Formular bauen
