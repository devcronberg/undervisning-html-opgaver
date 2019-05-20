# Start på HTML

Dette er en meget simpel opgave der kan hjælpe med at komme igang med HTML.

Du skal: 

- Oprette en mappe
- I mappen skal du oprette en fil kaldet index.html
- Tilføj en standard HTML5 struktur
  - doctype
  - header
  - body
  - Brug evt. VS Code's skabelon (! + tabulering) eller en udvidet fra [HTML5 Boilerplate](https://html5boilerplate.com/)
- Siden skal have en titel
- Sørg for at validere den inden du går videre
  - Den skal være HTML5 valid
- Body-opmærknigen (indholdet på siden) skal bestå af
  - En enkelt overskrift (h1) med noget tekst
  - En enkelt paragraf (p) med noget tekst
- Sørg igen for, at siden er HTML5 valid
- Åbn siden i en browser (brug evt Live Server Extension i VS code)
  - Ser det ok ud?

---

## CSS

- Tilret nu h1-opmærkningen så den har en attribut kaldet "class" med en værdi på "ov" (class="ov")
- Opret en ny fil i samme mappe kaldet style.css
- Tilføj følgende til filen

```css
.ov {
  color: red;
}
```

- Sørg for, at linke css-filen med html-filen i headeren med:

```html
<link rel="stylesheet" href="style.css">
```

- Efter en reload skulle overskriften gerne blive rød
  - Ser det ok ud?

## JavaScript

- Tilret p-opmærkning så den har en "id"-attribut med værdien "minP" (id="minP")
- Opret en ny fil i mappen kaldet app.js med følgende indhold:

```javascript
(function() {
  document.getElementById("minP").onclick = function() {
    this.style.fontSize = "4em";
  };
})();
```

- Sørg for at linke app.js til html-filen ved at tilføje en script-reference _i bunden_ af siden (lige før </body>):

```html
<script src="app.js"></script>
```

- Efter en reload og et klik på paragraffen skulle teksten gerne blive stor
  - Virker det?
