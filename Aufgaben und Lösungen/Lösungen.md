# Tutorial (Lösungen)

Falls du nicht weiterkommst, hier sind Hinweise und Lösungen:

## HTML-Lösungen

### 1. **Falsche CSS-Datei verlinkt**:
   - Die CSS-Datei ist falsch benannt als `falscheDatei.css`. Ändere sie auf `styles.css`.

   **Die richtige Lösung**:
   ```html
   <link rel="stylesheet" href="/Webseite/styles.css">
   ```

### 2. **Fehlender `placeholder`-Text korrigieren**:
   - Der `placeholder`-Text enthält einen Tippfehler. Ändere `hznzufügen` zu `hinzufügen`.

   **Die richtige Lösung**:
   ```html
   <input type="text" id="itemInput" placeholder="Artikel hinzufügen">
   ```

### 3. **Fehlendes schließendes Tag**:
   - Das `<button>`-Element ist nicht geschlossen.

   **Die richtige Lösung**:
   ```html
   <button onclick="addItem()">Hinzufügen</button>
   ```

### 4. **Falscher Listentyp**:
   - Der Listentyp `<ol>` ist falsch. Ändere ihn zu `<ul>`.

   **Die richtige Lösung**:
   ```html
   <ul id="shoppingList"></ul>
   ```

### 5. **Fehlender JavaScript-Dateiname**:
   - Die JavaScript-Datei ist falsch benannt als `falschesScript.js`. Ändere sie auf `app.js`.

   **Die richtige Lösung**:
   ```html
   <script src="/Webseite/app.js"></script>
   ```

### 6. **Leeres `div` für Vorschläge**:
   - Das `div` ist leer. Füge einen Platzhaltertext hinzu.

   **Die richtige Lösung**:
   ```html
   <div id="suggestions">Hier erscheinen Vorschläge</div>
   ```

### 7. **Fehlende `id` im Eingabefeld**:
   - Füge die fehlende `id="itemInput"` hinzu.

   **Die richtige Lösung**:
   ```html
   <input type="text" id="itemInput" placeholder="Artikel hinzufügen">
   ```

### 8. **Tippfehler im `onclick`-Attribut**:
   - Das Attribut `onlick` ist falsch geschrieben. Korrigiere es zu `onclick`.

   **Die richtige Lösung**:
   ```html
   <button onclick="addItem()">Hinzufügen</button>
   ```

### 9. **Fehlerhafter Sprachcode**:
   - Der Sprachcode `de` ist korrekt. Hier ist ein Beispiel, wie es aussehen sollte:

   **Die richtige Lösung**:
   ```html
   <html lang="de">
   ```

### 10. **Titel verbessern**:
   - Ändere den Titel zu etwas aussagekräftigerem, z. B. "Meine Einkaufsliste".

   **Die richtige Lösung**:
   ```html
   <title>Meine Einkaufsliste</title>
   ```

---

## CSS-Lösungen

### 11. **Hintergrund reparieren**:
   - Der Fehler liegt bei `linaer-gradient`. Ändere ihn zu `linear-gradient`.

   **Die richtige Lösung**:
   ```css
   background: linear-gradient(135deg, #d1e8ff, #f8f9fa);
   ```

### 12. **Schriftart korrigieren**:
   - Die Schriftart `Popins` ist falsch. Ändere sie zu `Poppins`.

   **Die richtige Lösung**:
   ```css
   font-family: 'Poppins', Arial, sans-serif;
   ```

### 13. **Ausrichtung der Elemente**:
   - Der Wert `cneter` ist falsch. Ändere ihn zu `center`.

   **Die richtige Lösung**:
   ```css
   text-align: center;
   ```

### 14. **Überschrift zentrieren**:
   - Der Fehler liegt bei `text-align: cneter`. Korrigiere ihn.

   **Die richtige Lösung**:
   ```css
   text-align: center;
   ```

### 15. **Schrift-Durchstreichung reparieren**:
   - Der Wert `line-trhough` ist falsch. Ändere ihn zu `line-through`.

   **Die richtige Lösung**:
   ```css
   text-decoration: line-through;
   ```

### 16. **Fehlende Einheiten ergänzen**:
   - Der Fehler liegt bei fehlenden Einheiten, z. B. `8px` statt `8`.

   **Die richtige Lösung**:
   ```css
   border-radius: 8px;
   ```

### 17. **Farben anpassen**:
   - Ändere die Standardfarbe `#007bff` zu `#0066cc`.

   **Die richtige Lösung**:
   ```css
   background-color: #0066cc;
   ```

### 18. **Liste hervorheben**:
   - Füge einen Hover-Effekt für die Liste hinzu.

   **Die richtige Lösung**:
   ```css
   li:hover {
       background-color: #f0f0f0;
   }
   ```

### 19. **Barrierefreiheit verbessern**:
   - Ändere den Kontrast von `#888` zu `#555` für bessere Lesbarkeit.

   **Die richtige Lösung**:
   ```css
   color: #555;
   ```

### 20. **Animation für Button**:
   - Füge eine Animation hinzu, wenn der Button gedrückt wird.

   **Die richtige Lösung**:
   ```css
   button:active {
       transform: scale(0.95);
       background-color: #004080;
   }
   ```