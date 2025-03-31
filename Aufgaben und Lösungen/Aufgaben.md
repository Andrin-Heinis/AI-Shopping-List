# Aufgaben zur beschädigten HTML- und CSS-Datei

## HTML-Aufgaben

### 1. Falsche CSS-Datei verlinkt (HTML)
Die CSS-Datei ist mit `falscheDateiName.css` falsch benannt. Ändere sie zu `styles.css`. (Tipp: Die Datei befindet sich auf der linken Seite im "Webseite" Ordner.)

### 2. Fehlender `placeholder`-Text korrigieren (HTML)
Der `placeholder` im Eingabefeld hat einen Tippfehler ("Artikel hznzufügen"). Ändere ihn zu "Artikel hinzufügen".

### 3. Fehlendes schliessendes Tag (HTML)
Das `<button>`-Element ist nicht korrekt geschlossen. Füge das fehlende schliessende Tag `</button>` hinzu.

### 4. Falscher Listentyp (HTML)
Die `<ul>`-Liste wird mit einem falschen Tag `<ol>` geöffnet. Ändere es zu `<ul>`.

### 5. Fehlender JavaScript-Dateiname (HTML)
Die JavaScript-Datei ist mit `falscherScriptName.js` verlinkt. Ändere sie zu `app.js`.

### 6. Fehlende `id` im Eingabefeld (HTML)
Das Eingabefeld hat keine `id`. Füge die `id="itemInput"` hinzu. Das ganze soll danach ungefähr so aussehen:

```html
  <input id="itemInput" [rest vom Code...]>
```

### 7. Tippfehler im `onclick`-Attribut (HTML)
Das Attribut `onlick` ist falsch geschrieben. Ändere es zu `onclick`.

### 8. Fehlerhafter Sprachcode (HTML)
Der Sprachcode im `<html>`-Tag ist auf `en` eingestellt, wechsle es zu deutsch, also `de`.

```html
  <html lang="de">
```

### 9. Titel verbessern (HTML)
Der Titel der Webseite ist etwas allgemein. Ändere ihn zu "Meine Einkaufsliste".

### 10. Fehlender Dokumenttyp (HTML)
Stelle sicher, dass die Deklaration `<!DOCTYPE html>` am Anfang der Datei vorhanden ist.

```html
<!DOCTYPE html>
<html>...
```

### 11. Fehlende Alt-Texte (HTML)
Wenn Bilder hinzugefügt werden, füge immer `alt`-Attribute hinzu. Erstelle eine Vorlage für ein Bild:
```html
<img src="/ignore/bild.png" alt="Beschreibung">
```

### 12. Barrierefreiheit verbessern (HTML)
Füge ein `label` für das Eingabefeld hinzu:
```html
<label for="itemInput">Artikel:</label>
```

### 13. Footer hinzufügen (HTML)
Am Ende der Seite fehlt ein Footer. Ergänze ihn:
```html
<footer>© 2025 - Meine Einkaufsliste</footer>
```

---

## CSS-Aufgaben

### 14. Hintergrund reparieren (CSS)
Der Hintergrund verwendet `linaer-gradient`, was falsch geschrieben ist. Korrigiere es zu `linear-gradient`.

### 15. Schriftart korrigieren (CSS)
Die Schriftart "Popins" existiert nicht. Ändere sie zu "Poppins".

### 16. Ausrichtung der Elemente (CSS)
Die Elemente im `<body>` und `<li>` sind nicht richtig ausgerichtet, weil `cneter` falsch geschrieben ist. Ändere es zu "center".

### 17. Überschrift zentrieren (CSS)
Die `<h1>`-Überschrift wird nicht zentriert, da `text-align: cneter;` falsch ist. Behebe den Fehler.

### 18. Schrift-Durchstreichung reparieren (CSS)
In der CSS-Klasse `.checked` ist die Text-Durchstreichung defekt, weil `line-trhough` verwendet wurde. Ändere es zu "line-through".

### 19. Fehlende Einheiten ergänzen (CSS)
In der CSS-Datei fehlen an manchen Stellen Einheiten, z. B. bei `border-radious: 8px;` oder `trasition: background-color 0.3s ease;`. Füge die korrekten Einheiten hinzu.

### 20. Farben anpassen (CSS)
Die Schaltflächen verwenden standardmässig `#007bff`. Ändere es zu einem anderen Blauton, z. B. `#0066cc`.

### 21. Liste hervorheben (CSS)
Füge einen Hover-Effekt für die Listenelemente (`<li>`) hinzu:
```css
li:hover {
    background-color: #f0f0f0;
}
```

### 22. Barrierefreiheit verbessern (CSS)
Erhöhe den Kontrast von Text und Hintergrundfarbe, damit es besser lesbar ist. Ändere z. B. `#888` in `#555`.

### 23. Animation für Button (CSS)
Füge eine einfache Animation für den Button hinzu, wenn er angeklickt wird:
```css
button:active {
    transform: scale(0.95);
    background-color: #004080;
}
```
