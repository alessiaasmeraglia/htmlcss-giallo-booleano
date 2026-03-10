# htmlcss-giallo-booleano

## Obiettivo

Realizzare la versione responsive della pagina ricetta lavorando **solo** nel file `responsive.css`, senza modificare `index.html` o `style.css`.

## Consegna

### Tablet (`min-width: 768px`)

* allineare il logo a sinistra nell’header
* aumentare il padding del contenuto principale
* mostrare il testo `(Dolce Tradizionale)`
* aumentare la dimensione del titolo
* disporre le informazioni della ricetta a griglia
* allargare i bottoni social
* mostrare il banner pubblicitario
* far circondare l’immagine dal testo nella descrizione

### Desktop (`min-width: 992px`)

* aumentare ancora la dimensione del titolo
* riportare le informazioni della ricetta una sotto l’altra
* disporre video e info della ricetta uno accanto all’altro
* mostrare i nomi delle piattaforme social
* disporre footer e menu sulla stessa riga, ai lati opposti

### Bonus Large Mobile (`min-width: 576px`)

* far circondare l’immagine dal testo già da 576px
* allargare i bottoni social già da 576px

## Breakpoint usati

* `576px` → large mobile
* `768px` → tablet
* `992px` → desktop

## Strategia

Il progetto parte già con una versione mobile pronta. Le modifiche responsive vanno aggiunte in `responsive.css` usando media query che sovrascrivono il comportamento base.

## Esempio struttura CSS

```css
@media screen and (min-width: 576px) {
  /* regole large mobile */
}

@media screen and (min-width: 768px) {
  /* regole tablet */
}

@media screen and (min-width: 992px) {
  /* regole desktop */
}
```

## Note utili

* usare `float: left` per far scorrere il testo attorno all’immagine
* usare `display: grid` per la disposizione a griglia delle quick notes
* usare `display: flex` per affiancare video e dettagli ricetta su desktop
* mostrare elementi nascosti nel CSS base con `display: block` o `display: inline`

## File del progetto

* `index.html`
* `style.css`
* `responsive.css`

## Autore

Esercizio svolto per il progetto Boolean **Giallo Booleano**.
