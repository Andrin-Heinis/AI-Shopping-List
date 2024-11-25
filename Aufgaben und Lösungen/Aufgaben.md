# Aufgaben zur beschädigten HTML- und CSS-Datei

## HTML-Aufgaben

### 1. Falsche CSS-Datei verlinkt (HTML)
Die CSS-Datei ist mit `falscheDatei.css` falsch benannt. Ändere sie zu `styles.css`.

### 2. Fehlender `placeholder`-Text korrigieren (HTML)
Der `placeholder` im Eingabefeld hat einen Tippfehler ("Artikel hznzufügen"). Ändere ihn zu "Artikel hinzufügen".

### 3. Fehlendes schliessendes Tag (HTML)
Das `<button>`-Element ist nicht korrekt geschlossen. Füge das fehlende schliessende Tag `</button>` hinzu.

### 4. Falscher Listentyp (HTML)
Die `<ul>`-Liste wird mit einem falschen Tag `<ol>` geöffnet. Ändere es zu `<ul>`.

### 5. Fehlender JavaScript-Dateiname (HTML)
Die JavaScript-Datei ist mit `falschesScript.js` verlinkt. Ändere sie zu `app.js`.

### 6. Leeres `div` für Vorschläge (HTML)
Das `<div>`-Element für Vorschläge (`#suggestions`) ist leer. Füge einen Beispieltext wie "Hier erscheinen Vorschläge" hinzu.

### 7. Fehlende `id` im Eingabefeld (HTML)
Das Eingabefeld hat keine `id`. Füge die `id="itemInput"` hinzu.

### 8. Tippfehler im `onclick`-Attribut (HTML)
Das Attribut `onlick` ist falsch geschrieben. Ändere es zu `onclick`.

### 9. Fehlerhafter Sprachcode (HTML)
Der Sprachcode im `<html>`-Tag ist korrekt `de`, aber überprüfe ihn und bestätige, dass er passt.

### 10. Titel verbessern (HTML)
Der Titel der Webseite ist etwas allgemein. Ändere ihn zu "Meine Einkaufsliste".

### 11. Ungenutztes `<meta>`-Tag (HTML)
Prüfe, ob ein weiteres `<meta>`-Tag für Keywords oder eine Beschreibung der Seite hinzugefügt werden kann.

### 12. Fehlender Dokumenttyp (HTML)
Stelle sicher, dass die Deklaration `<!DOCTYPE html>` am Anfang der Datei vorhanden ist.

### 13. Fehlende Alt-Texte (HTML)
Wenn Bilder hinzugefügt werden, füge immer `alt`-Attribute hinzu. Erstelle eine Vorlage für ein Bild:
```html
<img src="/ignore/bild.jpg" alt="Beschreibung">
```

### 14. Barrierefreiheit verbessern (HTML)
Füge ein `label` für das Eingabefeld hinzu:
```html
<label for="itemInput">Artikel:</label>
```

### 15. Footer hinzufügen (HTML)
Am Ende der Seite fehlt ein Footer. Ergänze ihn:
```html
<footer>© 2024 - Meine Einkaufsliste</footer>
```

### 16. Fehlende Struktur in der Liste (HTML)
Füge beispielhafte `<li>`-Elemente zur Einkaufsliste hinzu:
```html
<ul id="shoppingList">
    <li>Beispielartikel</li>
</ul>
```

### 17. Ungeordnete Semantik (HTML)
Füge Absätze oder Inhalte hinzu und stelle sicher, dass sie mit `<p>`-Tags strukturiert sind.

### 18. `<nav>`-Element einfügen (HTML)
Füge ein `<nav>`-Element hinzu, das später für eine Navigation verwendet werden kann:
```html
<nav>
    <a href="#shoppingList">Zur Liste</a>
</nav>
```

### 19. Tabellenformatierung (HTML)
Erstelle eine Tabelle, die optional für andere Inhalte genutzt werden kann:
```html
<table>
    <tr>
        <th>Artikel</th>
        <th>Menge</th>
    </tr>
    <tr>
        <td>Apfel</td>
        <td>3</td>
    </tr>
</table>
```

### 20. Kommentare einfügen (HTML)
Füge sinnvolle Kommentare in den HTML-Code ein, um die Struktur zu dokumentieren.

---

## CSS-Aufgaben

### 21. Hintergrund reparieren (CSS)
Der Hintergrund verwendet `linaer-gradient`, was falsch geschrieben ist. Korrigiere es zu `linear-gradient`.

### 22. Schriftart korrigieren (CSS)
Die Schriftart "Popins" existiert nicht. Ändere sie zu "Poppins".

### 23. Ausrichtung der Elemente (CSS)
Die Elemente im `<body>` und `<li>` sind nicht richtig ausgerichtet, weil `cneter` falsch geschrieben ist. Ändere es zu "center".

### 24. Überschrift zentrieren (CSS)
Die `<h1>`-Überschrift wird nicht zentriert, da `text-align: cneter;` falsch ist. Behebe den Fehler.

### 25. Schrift-Durchstreichung reparieren (CSS)
In der CSS-Klasse `.checked` ist die Text-Durchstreichung defekt, weil `line-trhough` verwendet wurde. Ändere es zu "line-through".

### 26. Fehlende Einheiten ergänzen (CSS)
In der CSS-Datei fehlen an manchen Stellen Einheiten, z. B. bei `border-radious: 8px;` oder `trasition: background-color 0.3s ease;`. Füge die korrekten Einheiten hinzu.

### 27. Farben anpassen (CSS)
Die Schaltflächen verwenden standardmässig `#007bff`. Ändere es zu einem anderen Blauton, z. B. `#0066cc`.

### 28. Liste hervorheben (CSS)
Füge einen Hover-Effekt für die Listenelemente (`<li>`) hinzu:
```css
li:hover {
    background-color: #f0f0f0;
}
```

### 29. Barrierefreiheit verbessern (CSS)
Erhöhe den Kontrast von Text und Hintergrundfarbe, damit es besser lesbar ist. Ändere z. B. `#888` in `#555`.

### 30. Animation für Button (CSS)
Füge eine einfache Animation für den Button hinzu, wenn er angeklickt wird:
```css
button:active {
    transform: scale(0.95);
    background-color: #004080;
}
```
