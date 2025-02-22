# Settimana introduttiva
Corso serale MiaTech

## Per clonare il repository:
```bash
git clone https://github.com/camillatofani/settimana-introduttiva.git
```

### Martedì 11
- Ruolo del Front End Developer
- Ruolo del Back End Developer
- Ruolo del Full Stack Developer
- Che cos'è Git
- Che cos'è GitHub
- Come creare un repository su GitHub
- Come clonare il repository di GitHub sul proprio PC
```bash
git clone https://github.com/xxxxxxxxxxxx/xxxxxxxxxxxx.git
```
- Muoversi tra la cartella del repository
- Creare il primo file di un sito internet (index.html)
- Che cos'è l'html
- I comandi di git per inviare le modifiche dei file in locale (= sul proprio PC) a GitHub:
```bash
git status
git add .
git commit -m "Description"
git push
```

### Mercoledì 12
- Rivisto velocemente tutto ciò che abbiamo fatto la sera prima
- Differenza tra tag "di apertura e chiusura" e "self-closing"
- Attributi dei tag: che cosa sono e come si scrivono
- Tag principali: h1 (....h6), p, button, img, div, span, ul, ol, li
```html
<h1>Titolo 1</h1>
<h2>Titolo 2</h2>
<h3>Titolo 3</h3>
<h4>Titolo 4</h4>
<h5>Titolo 5</h5>
<h6>Titolo 6</h6>
<p>Lorem ipsum dolo</p>
<button>Clicca qui</button>
<img src="xxxxxxxx.xxx">
<div>Elemento generico di tipo block</div>
<span>Elemento generico di tipo inline</span>
<ul>
 <li>Singolo elemento di una lista generica</li>
 <li>Singolo elemento di una lista generica</li>
 <li>Singolo elemento di una lista generica</li>
</ul>
<ol>
 <li>Singolo elemento di una lista numerata</li>
 <li>Singolo elemento di una lista numerata</li>
 <li>Singolo elemento di una lista numerata</li>
</ol>
```
- Differenza tra tag di tipo "block" e tag ti tipo "inline"
- Abbiamo giocato con l'attributo "style"

### Giovedì 13
- Rivisto velocemente tutto ciò che abbiamo fatto la sera prima
- Creato il file style.css
- Come inserire lo stile all'interno del file style.css
- Che cosa sono le classi
- Che cosa sono gli id
- L'importanza gerarchica dello stile tra: tag, classe, id e style inline:
```html
 <h1 class="intestazione" id="titolo" style="color: red;">Ciao</h1>
```
- Modificare i valori di default del css
- Come si ispeziona il codice (Tasto destro del mouse all'interno del browser)
- Come modificare momentaneamente lo stile del sito direttamente dal browser
- La possibilità di commentare il codice per poterlo conservare ma renderlo "non eseguibile"
- Abbiamo giocato cambiando i colori del sito della Nike
- Visto un accenno di animazioni con il css (button:hover)

### Venerdì 14
- Rivisto velocemente tutto ciò che abbiamo fatto la sera prima
- Corretto insieme il progetto di uno studente. Lo trovate [qui](https://github.com/ValCode26/valentin-code.git)
- Parlato dell'indentazione del codice [qui un approfondimento](https://it.wikipedia.org/wiki/Indentazione)
- Creato :root per gestire le variabili in css
- Visto come poter inserire il colore all'interno del nostro css, ad esempio per il rosso:
```css
 color: red;
 color: rgba(255,0,0,0);
 color: #ff0000
```
- Modificato le classi css all'interno delle media queries per far diventare il nostro sito responsive:
```css
@media (max-width: 480px) {
	.tel {
		display: none;
	}
}
```
- Visto la differenza tra "p.bg-color" e "p .bg-color"
```css
p.bg-primary {
	background-color: var(--primary);
}

p .bg-secondary {
	background-color: var(--third);
}
```
- Visto che la nomenclatura dei file non può contenere spazi
- Abbiamo visto che solo un file, quello principale, si deve chiamare index.html, tutti gli altri devono essere chiamati diversamente
- Ogni nome che inseriamo deve essere "parlante", quindi spiegare a che cosa serve il determinato elemento. Ad esempio la pagina contatti la chiameremo contact.html e quella dello shop la chiameremo shop.html. Idem per il nome delle classi

### Da Martedì 18 a Venerdì 21
Qui il nuovo repository: [qui](https://github.com/camillatofani/project-mia-febbraio)
