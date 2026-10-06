## Leitfragen

1. Was passiert bei einem Marken-Wechsel von Blau auf Violett mit einem TokenSystem im Vergleich zu 500 hartcodierten Hex-Werten?

Bei einem Marken-Wechsel musst du in einem Token-System nur einen einzigen zentralen Verweis aktualisieren, der sich sofort auf alle Elemente auswirkt, anstatt 500 fehleranfällige, manuelle Änderungen im Code durchzuführen.

2. Warum braucht man drei Ebenen? Was gewinnt man durch die semantische Ebene zwischen Primitive und Komponente?

Die semantische Ebene fungiert als flexibler Puffer, der es dir erlaubt, globale Markenfarben zentral auszutauschen, ohne jede Komponente anfassen zu müssen, und gleichzeitig einzelne Komponenten umzugestalten, ohne die globale Designsprache zu beeinflussen.

3. Was bedeutet "Aliasing", und warum darf eine Komponente keinen rohen Farbwert kennen?

Aliasing ist der logische Verweis eines Tokens auf ein anderes, und Komponenten nutzen dies anstelle roher Werte, damit sie sich bei übergreifenden Anpassungen (wie einem Dark Mode) völlig automatisch anpassen und die Codebasis frei von starren Design-Entscheidungen bleibt.