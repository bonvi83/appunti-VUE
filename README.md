# VITE + VUE + tutto il cucuzzaro

## Creazione di un nuovo progetto

1. Crea una nuova cartella con il nome del progetto
2. Apri la cartella in VSCode
3. Apri un terminale da VSCode ed esegui il comando

```bash
npm create vite@latest .
```

4. Per installare 
```bash
npm install
```

5. Per il live-server
```bash
npm run dev
```

6. Pubblica la repo su GitHub

## Installazione SASS

1. Rimuovi l'import del file `style.css` dal file `main.js`
2. Rimuovi il file `style.css`
3. Esegui il comando

```bash
npm i --save-dev sass
```

4. Crea il seguente scaffolding per i file scss:

```plaintext
src
|
| styles
| |
| | general.scss
| | partials
| | |
| | | \_mixins.scss
| | | \_variables.scss
```

5. Importa il file `general.scss` in `App.vue`. <br>
   Dovrai usare la direttiva `@use` e il tag `<style>` non dovrà avere l'attributo `scoped`.

6. Importa i file parziali nel file `general.scss`. <br>
   Dovrai usare la direttiva `@use` ed aggiungere `as *`


## Installazione Bootstrap

1. Per installare
```bash
npm i --save bootstrap @popperjs/core
```
2. Nel file nel general.scss @import "bootstrap/scss/bootstrap" (in app.vue lo abbiamo già linkato)
3. Nel main.js (per la logica di bootstrap) import * as bootstrap from "bootstrap"





### CHE DIO CE LA MANDI BUONA!