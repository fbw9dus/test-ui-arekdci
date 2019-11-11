# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   45/60 Punkten
#### Punktabzüge für:
- [_] (10) Elemente passen sich nicht an Fensterbreite an
- [_] (10) Tags nicht geschlossen oder falsch verschachtelt
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [_] (10) Zweckfremde Tags verwendet
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [x] (5) Falsche Datei-Pfade
```diff
- Weder Logo noch das Hintergrundbild werden geladen, wenn der Ordner anders heißt. Das passiert mit richtigen Pfaden nicht.
```
- [x] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- Alle spans auf der Seite auszuwählen um eine Farbe zu ändern ist zu ungenau
```
- [_] (5) Fehlende essentielle Tag-Attribute
