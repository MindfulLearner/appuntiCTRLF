## Indice

1. **Utilizzo di Copilot e Strumenti di Codifica**
   - Copilot, passo passo
   - Shortcut utili: `CTRL + I`, `CTRL + /`, `@`
   - Chat e commenti
   - Tenere aperti i codici

2. **HTML**
   1. **Introduzione all'HTML**
      - Definizione e scopo
   2. **Struttura di base di un documento HTML**
      - Elementi di base: `<!DOCTYPE html>`, `<html>`, `<head>`, `<meta>`, `<title>`, `<body>`
   3. **Spiegazione della Struttura di Base**
      - Descrizione di ogni elemento
   4. **Tag principali**
      - Tag di struttura: `<html>`, `<head>`, `<title>`, `<body>`
      - Tag di testo: `<h1> ... <h6>`, `<p>`, `<br>`, `<hr>`
      - Esempi di Tag di Testo
   5. **Link**
      - Utilizzo del tag `<a>`
   6. **Immagini**
      - Utilizzo del tag `<img>`
      - Esempi di Immagini
   7. **Liste**
      - Liste non ordinate (`<ul>`, `<li>`)
      - Liste ordinate (`<ol>`, `<li>`)
      - Esempi di Liste
   8. **Tabelle**
      - Struttura delle tabelle (`<table>`, `<tr>`, `<th>`, `<td>`)
      - Esempi di Tabelle
   9. **Conclusione**
      - Riflessione sull'importanza dell'HTML
   10. **Risorse Aggiuntive**

3. **CSS**
   1. **Selettori CSS**
      - Selettori di tipo (`*`)
      - Selettori di classe (`.class`)
      - Selettori di attributi (`input[type="email"]`)
      - Pseudo-elementi (`:before`, `:after`)
      - Pseudo-classi (`:hover`, `:visited`, `:first-child`, `:last-child`)
   2. **Global Styles**
      - Reset CSS (`* { margin: 0; padding: 0; box-sizing: border-box; }`)
   3. **Posizionamento degli Elementi**
      - `position: relative`
      - `position: absolute`
   4. **Classi e ID**
      - Definizione e utilizzo delle classi e degli ID (`.square`, `.square.green`, `.square.yellow`)
   5. **Esempi Reali**
      - Esempi di stili CSS applicati

4. **Progetti e Applicazioni**
   1. **Progetto: Curriculum con HTML e CSS**
      - Creazione di un curriculum
      - Collegamento a LinkedIn e GitHub

5. **DNS e Trasmissione dei Dati**
   - Funzionamento del DNS
   - Trasmissione dei dati su Internet
   - Modello OSI

6. **Slack**
   1. **Versionamento**
      - Major, Minor, Patch
   2. **Scrivere un Ticket su Slack**
      - Consigli per una comunicazione efficace

7. **Git**
   1. **Git e Versionamento**
      - Utilizzo di `git graph`
      - Definizione di Branch
      - Esempi di URL per risorse

8. **Struttura HTML: 1.1**
   - Esempio di struttura di un documento HTML con vari tag (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<aside>`, `<footer>`)

9. **Tag HTML e Attributi**
   - Attributi comuni: `class`, `id`, `style`, `title`, `href`, `src`, `alt`, `type`, `value`, `name`

10. **Entity Code**
    - Utilizzo di codici entità per simboli speciali

11. **Utilizzo del Tag `<span>`**
    - Quando e come utilizzare `<span>`

12. **Esempi di Paragrafi**
    - Struttura e utilizzo dei paragrafi con tag `<p>`

13. **Collegamento tra HTML e CSS**
    - Utilizzo del tag `<link>` per collegare un file CSS a un file HTML

14. **Specificità CSS**
    - Regole di specificità per l'applicazione degli stili CSS

15. **Text-align con immagini e testi**
    - Tecniche di allineamento

16. **Risalire e scendere nelle cartelle (directories)**
    - Utilizzo dei percorsi relativi per risalire e scendere nelle directory

17. **Immagini e Variabili CSS**
    - Tecniche per gestire immagini e variabili CSS

18. **Valori Predefiniti e Unità di Misura**
    - Unità di misura CSS (`%`, `rem`, `em`, `px`, `vh`, `vw`)

19. **Simboli e Scorciatoie**
    - Scorciatoie per simboli e caratteri speciali (backtick, tilde)


//riga 370 nuovi


Utilizzo di Copilot, cercare di fare le cose passo passo, CTRL I e chat e tasto destro e commenti,tener aperto i code, 
ctrl + I /explain chioccola e slash possono essere utili

  <!--ricarica pagina ogni 2 sec-->
    <meta http-equiv="refresh" content="2">


    Puoi copiare questo testo e salvarlo in un file `.md` per usarlo come riferimento.

sarebbe meglio fare un .square
.square.green
.square.yellow separati

.

css position relavive e absolut

ricordarsi sempre 
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

e ricordarsi di gaurdare bnene i nomi.

# Lezione HTML - Sistemato

## Introduzione all'HTML

L'HTML (HyperText Markup Language) è il linguaggio standard per creare pagine web. Viene utilizzato per descrivere la struttura di una pagina web usando una serie di elementi, che sono rappresentati da tag.

## Struttura di base di un documento HTML

Ogni documento HTML deve avere una struttura di base che include i seguenti elementi:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Benvenuti!</h1>
    <p>Questo è un paragrafo di esempio.</p>
</body>
</html>
```

p da perdefault uno spazioo
span

### Spiegazione della Struttura di Base

- `<!DOCTYPE html>`: Dichiara il tipo di documento e la versione HTML utilizzata.
- `<html lang="en">`: Tag radice che contiene tutti gli altri elementi del documento. L'attributo `lang` specifica la lingua del documento.
- `<head>`: Contiene meta-informazioni sul documento, come il charset e il titolo.
- `<meta charset="UTF-8">`: Definisce la codifica dei caratteri del documento.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Imposta la larghezza della pagina in base alla larghezza dello schermo del dispositivo.
- `<title>`: Specifica il titolo del documento che appare nella barra del titolo del browser.
- `<body>`: Contiene il contenuto visibile della pagina web.

## Tag principali

### Tag di struttura
- `<html>`: Radice del documento HTML.
- `<head>`: Contiene meta-informazioni sul documento.
- `<title>`: Titolo del documento.
- `<body>`: Contiene il contenuto del documento.

### Tag di testo
- `<h1> ... <h6>`: Intestazioni di livello 1-6, usate per i titoli.
- `<p>`: Paragrafo.
- `<br>`: Interruzione di riga.
- `<hr>`: Linea orizzontale.

#### Esempi di Tag di Testo

```html
<h1>Questo è un titolo principale</h1>
<h2>Questo è un sottotitolo</h2>
<p>Questo è un paragrafo di esempio.</p>
<p>Questo è un altro paragrafo.</p>
<br>
<p>Dopo questo paragrafo c'è una linea orizzontale.</p>
<hr>
<p>Questo paragrafo viene dopo una linea orizzontale.</p>
```

### Link

Il tag `<a>` viene usato per i link. Gli attributi principali sono `href` per specificare l'URL e `target` per determinare dove aprire il link.

Esempio:

```html
<a href="https://www.example.com" target="_blank">Visita Example.com</a>
```

### Immagini

Il tag `<img>` viene usato per le immagini. Gli attributi principali sono `src` per il percorso dell'immagine e `alt` per il testo alternativo.

Esempio:

```html
<img src="immagine.jpg" alt="Descrizione dell'immagine">
```

#### Esempi di Immagini

```html
<img src="https://www.example.com/logo.png" alt="Logo di Example.com">
<img src="foto.jpg" alt="Foto di esempio" width="500" height="600">
```

### Liste

#### Liste non ordinate

Le liste non ordinate usano il tag `<ul>` per la lista e `<li>` per ogni elemento della lista.

```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ul>
```

#### Liste ordinate

Le liste ordinate usano il tag `<ol>` per la lista e `<li>` per ogni elemento della lista.

```html
<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ol>
```

#### Esempi di Liste

```html
<h2>Lista non ordinata:</h2>
<ul>
    <li>Elemento non ordinato 1</li>
    <li>Elemento non ordinato 2</li>
    <li>Elemento non ordinato 3</li>
</ul>

<h2>Lista ordinata:</h2>
<ol>
    <li>Elemento ordinato 1</li>
    <li>Elemento ordinato 2</li>
    <li>Elemento ordinato 3</li>
</ol>
```

### Tabelle

Le tabelle sono create con il tag `<table>`, e usano `<tr>` per le righe, `<th>` per le intestazioni di colonna, e `<td>` per le celle dei dati.

c e border , colspan definisce quanto occupa di spazio una collonna di un tag td
 tag thead

Esempio:

```html
<table border="1">
    <thead> <!--tipo un haderr -->
        <tr>
            <th>Intestazione 1</th>
            <th>Intestazione 2</th>
        </tr>
        <tr>
            <td>Dato 1</td>
            <td>Dato 2</td>
        </tr>
        <tr>
            <td>Dato 3</td>
            <td>Dato 4</td>
        </tr>
    </thead>
</table>
```

#### Esempi di Tabelle

```html
<h2>Tabella semplice:</h2>
<table>
    <tr>
        <th>Nome</th>
        <th>Età</th>
        <th>Città</th>
    </tr>
    <tr>
        <td>Mario</td>
        <td>30</td>
        <td>Roma</td>
    </tr>
    <tr>
        <td>Luigi</td>
        <td>25</td>
        <td>Milano</td>
    </tr>
</table>

<h2>Tabella con bordo:</h2>
<table border="1">
    <tr>
        <th>Prodotto</th>
        <th>Prezzo</th>
        <th>Quantità</th>
    </tr>
    <tr>
        <td>Penna</td>
        <td>1.50€</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Quaderno</td>
        <td>2.00€</td>
        <td>5</td>
    </tr>
</table>
```

## Conclusione

L'HTML è un linguaggio fondamentale per la creazione di pagine web. Conoscere i suoi elementi di base e le loro applicazioni pratiche è essenziale per qualsiasi sviluppatore web. Questa lezione copre solo gli elementi fondamentali, ma l'HTML offre molte altre funzionalità avanzate che possono essere esplorate man mano che si acquisisce maggiore esperienza.

### Risorse Aggiuntive

- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [Mozilla Developer Network (MDN) HTML Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Living Standard](https://html.spec.whatwg.org/multipage/)

Continua a esplorare e sperimentare con l'HTML per diventare un esperto nella creazione di contenuti web!
//////
```markdown
# Selettori CSS

## Selettori di tipo
- **Star selector** (`*`): Seleziona tutti gli elementi.
  ```css
  * {
      color: red;
  }
  ```
  Cambia il colore di tutti gli elementi a rosso.

## Selettori di classe
- **Selettore di discendenti** (`div .starred`): Seleziona tutti gli elementi con la classe `starred` che sono discendenti di un `div`.
  ```css
  div .starred {
      color: blue;
  }
  ```
  Cambia il colore di tutti gli elementi con la classe `starred` all'interno di un `div` a blu.

- **Selettore di figli** (`div > .starred`): Seleziona tutti gli elementi con la classe `starred` che sono figli diretti di un `div`.
  ```css
  div > .starred {
      color: green;
  }
  ```
  Cambia il colore di tutti gli elementi con la classe `starred` che sono figli diretti di un `div` a verde.

## Pseudo-elementi
- **`:before` e `:after`**: Inseriscono contenuto prima o dopo l'elemento selezionato.
  ```css
  .star:before {
      content: "★";
      color: gold;
  }
  .star:after {
      content: "★";
      color: gold;
  }
  ``` Entity code
  Aggiunge una stella dorata prima e dopo ogni elemento con la classe `star`.

## Selettori di attributi
- **Selettore di attributi** (`input[type="email"]`): Seleziona tutti gli elementi `input` con l'attributo `type` uguale a `email`.
  ```css
  input[type="email"] {
      border: 1px solid blue;
  }
  ```
  Aggiunge un bordo blu a tutti gli `input` di tipo `email`.

## Pseudo-classi
- **`:hover`**: Seleziona l'elemento quando viene passato il mouse sopra.
  ```css
  a:hover {
      color: red;
  }
  ```
  Cambia il colore di un link a rosso quando ci si passa sopra con il mouse.

- **`:visited`**: Seleziona un link che è stato visitato.
  ```css
  a:visited {
      color: purple;
  }
  ```
  Cambia il colore di un link visitato a viola.

- **`:first-child`**: Seleziona il primo figlio di un elemento.
  ```css
  p:first-child {
      font-weight: bold;
  }
  ```
  Rende il testo del primo paragrafo in grassetto.

- **`:last-child`**: Seleziona l'ultimo figlio di un elemento.
  ```css
  p:last-child {
      font-style: italic;
  }
  ```
  Rende il testo dell'ultimo paragrafo in corsivo.

## Esempi Reali
### Esempio 1: Lista di email lette e non lette
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        .row.read {
            background-color: #e0e0e0;
        }
        .row.unread {
            background-color: #ffffff;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="row read">Email 1 (Letta)</div>
    <div class="row unread">Email 2 (Non letta)</div>
    <div class="row read">Email 3 (Letta)</div>
</body>
</html>
```
### Esempio 2: Form con input email
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        input[type="email"] {
            border: 1px solid blue;
        }
    </style>
</head>
<body>
    <form>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
    </form>
</body>
</html>
```
```


---

### CSS Basics

#### Global Styles guardare meglioo e capire meglio il border box
```css
* {
    margin: 0; /* Per evitare spazi */
    padding: 0; /* Per evitare spazi e margini */
    box-sizing: border-box; /* Per evitare problemi di layout */
    border box non midifcherà il padding
    font-family: Arial, sans-serif; /* Per uniformare i font */

    PERCHé QUANDO si mette il padding all'interno di un elemento, il padding si aggiunge al contenuto e quindi ci sono dei calcoli che vengono fatti. Se si mette box-sizing: border-box, il padding viene incluso nel calcolo del contenuto e quindi non ci sono problemi di layout.
esempi qui:
    https://www.w3schools.com/css/css3_box-sizing.asp

```css

}
```
Ricordarsi sempre di azzerare margini e padding e impostare il box-sizing per evitare problemi di layout.

#### Posizionamento degli Elementi
- **CSS position relative e absolute**

### Classi e ID

#### Definizione delle Classi e degli ID
- `.square`
- `.square.green`
- `.square.yellow`

### Prima Lezione

#### PROFESSIONISTI
- ALESSIO
- ALESSANDRO
- MICHELE

#### La Nostra Giornata Tipo
- Non ho ancora Gmail Drive.

### Progetto: Curriculum con HTML e CSS

- Creare un curriculum utilizzando HTML e CSS.
- Collegare a LinkedIn e GitHub.

### DNS e Trasmissione dei Dati

#### DNS
- Dove si trova `corriere.it`: si trova all'indirizzo specifico del DNS.

#### Trasmissione dei Dati
- Il messaggio HTML viene inviato in pacchetti.
- Caricare un file intero può far perdere pacchetti.
- Buffering assicura che il programma sappia se manca un pacchetto.
- I pacchetti mancanti indicano che qualcosa è andato storto.
- 7 livelli del flusso di informazioni (modello OSI).

### Slack

#### Versionamento
- **Major** - Cambiamento importante (es. da 4 a 5).
- **Minor** - Cambiamento minore (es. da 38 a 39).
- **Patch** - Correzione minima (es. da 125 a 126).

### Scrivere un Ticket su Slack

- Non scrivere solo "help", cercare di essere chiari il più possibile.

### Git

#### Git e Versionamento
- `git graph` - Visualizza il grafico dei commit.
- **Branch** - Un ramo di sviluppo separato.
- Esempio di URL per risorsa: `url("C:\Users\Josh\Desktop\VSCODEPROGETTI\BOOLEAN\LEZIONI\CTRL+F\01-GIT-VSCode-Boolean.pdf")`

### HTML Basics

#### Struttura di un Documento HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>Il mio Documento</title>
</head>
<body>
    <header>Informazioni importanti per ora titolo</header>
    <main>Questo è il contenuto principale della pagina</main>
    <section>Informazioni sulla nostra azienda tematica documento</section>
    <article>Questo è un articolo di notizie.</article>
    <nav>Link ecc.</nav>
    <aside>Link correlati</aside>
    <footer>Contiene info al sito tipo copyright etc.</footer>
</body>
</html>
```

#### Tag Importanti
- **header** - Informazioni importanti o titoli.
- **main** - Contenuto principale della pagina.
- **section** - Una sezione tematica del documento.
- **article** - Un articolo indipendente e auto-contenuto.
- **nav** - Contiene i link di navigazione.
- **aside** - Contenuto correlato o complementare.
- **footer** - Informazioni di chiusura, come copyright.

### Tag HTML e Attributi

#### Attributi Comuni
- **class** - Definisce uno o più nomi di classe per un elemento.
- **id** - Specifica un identificatore unico per un elemento.
- **style** - Aggiunge stili CSS inline a un elemento.
- **title** - Fornisce informazioni extra su un elemento (visualizzato come tooltip).
- **href** - Specifica l'URL di un link.
- **src** - Definisce la fonte di un'immagine, script o altra risorsa.
- **alt** - Fornisce testo alternativo per un'immagine.
- **type** - Specifica il tipo di input, pulsante o script.
- **value** - Definisce il valore di un elemento di input.
- **name** - Nomina l'elemento per l'invio dei dati del modulo.

### Tabelle in HTML

#### Struttura di una Tabella
```html
<table>
    <tr>
        <th>Intestazione</th>
        <th>Intestazione</th>
    </tr>
    <tr>
        <td>Dati</td>
        <td>Dati</td>
    </tr>
</table>
```
- **tr** - Definisce una riga nella tabella.
- **td** - Definisce una cella nella tabella.
- **th** - Definisce una cella di intestazione.

### Entity Code

#### Codici Entità
- Utilizzare codici entità per simboli speciali, come `&star;` per una stella.

### Utilizzo del Tag `<span>`

#### Quando Usare `<span>`
- Utilizzare `<span>` per stilizzare porzioni di testo inline senza interrompere il flusso del documento.

### Note Varie

#### Target per Link
- Per aprire un link in una nuova scheda, utilizzare `target="_blank"`.

### Struttura HTML: 1.1

```html
<!DOCTYPE html>
<html>
<head>
    <title>Lezione 1.1</title>
</head>
<body>
    <!-- header>nav>ul>li>a -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
                <li><a href="#">Link 3</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Titolo Principale</h1>
        <h2>Sottotitolo 1</h2>
        <h3>Sottotitolo 2</h3>
    </main>
</body>
</html>
```

#### Tag Heading
- **H1** è SEMPRE UNO SOLO e deve esserci solo 1.
- I tag heading sono gerarchici:
  - **H1** sta sopra **H2**
  - **H2** sta sotto **H1**

### Esempi di Paragrafi

```html
<p>
    dweakjdnwaa<br>
    wdeokopwdkapkwad<br>
    dwadnawidkwa<br>
</p>
```

---separatore organizzato

# Tipi di Selezioni

## Esempio di HTML:

```html
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esempio CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- ID si indica con # -->
    <div id="main" class="container red">Contenuto principale</div>
    <div class="container">Altro contenuto</div>
    <div class="container red">Contenuto rosso</div>
    <div class="container blue">Contenuto blu</div>
    <div class="container">
        <div class="child">Figlio 1</div>
        <div class="child">Figlio 2</div>
    </div>
    <div class="child">Non figlio</div>
</body>
</html>
```

## Esempio di CSS:

```css
/* ID MAIN */
#main.container.red {
    background-color: yellow;
    color: white;
}

.container.red {
    background-color: red;
    color: white;
}

.container.blue {
    background-color: blue;
    color: white;
}

.container > .child {
    color: blue;
}
```

### Spiegazione:

#### HTML:

- `id="main"`: Identificatore unico per il div principale.
- `class="container red"`: Classi combinate per selezioni specifiche.
- `class="container blue"`: Un'altra combinazione di classi.
- Struttura a livelli per mostrare l'uso del selettore figlio.

#### CSS:

- `#main.container.red`: Seleziona l'elemento con ID `main` e classi `container` e `red`.
- `.container.red`: Seleziona gli elementi con classi `container` e `red`.
- `.container.blue`: Seleziona gli elementi con classi `container` e `blue`.
- `.container > .child`: Seleziona i figli diretti di `container` con classe `child`.

## Collegamento tra HTML e CSS:

Per collegare un file CSS a un file HTML, si utilizza il tag `<link>` all'interno dell'elemento `<head>` del file HTML:

```html
<link rel="stylesheet" href="styles.css">
```

A parità di specificità, vale di più quello più in basso. Quello più specifico vale di più.

## Specificità:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>csstest</title>
    <link rel="stylesheet" href="./css/master.css">
</head>
<body>
    <h1 class="verdeh1 gialloh1">CIAO</h1>
</body>
</html>
```

### CSS:

```css
h1 {
    color: red;
}

.gialloh1 {
    color: yellow;
}

.verdeh1 {
    color: rgb(0, 255, 76);
}
```

In questo esempio, ha più valore `verdeh1` perché è l'ultimo dichiarato.

## Text-align con immagini e testi:

Per allineare testo e immagini all'interno di un contenitore `div`, si può utilizzare il CSS:

```css
div {
    text-align: center;
}
```

## Risalire e scendere nelle cartelle (directories):

Per risalire di una directory e scendere in una directory specifica, si utilizza:

```css
url("../img/gatto-tenero.jpg")
```

## Immagini e Variabili:

### Come coprire un'immagine in un `div`:

```css
div {
    background-image: url('path/to/image.jpg');
    background-size: cover;
    opacity: 0.8;
}
```

### Proprieta CSS:

- `background-color`
- `background-image`
- `background-repeat: repeat-y;` (solo verticale)
- `background-position: center;`
- `background-attachment: fixed;` (attaccata alla pagina)

Si può mettere tutto in un'unica linea:

```css
div {
    background: url('path/to/image.jpg') center/cover no-repeat fixed;
}
```

### Valori Predefiniti e Unità di Misura:

- **Default trasparente**: `opacity: 1;`
- **Unità di misura**:
  - `%`: Percentuale
  - `rem`: Relativo all'elemento radice HTML
  - `em`: Relativo al contenitore, es. `2em` al font size base 16 diventa 32px
  - `px`: Pixel
  - `vh`: Viewport height
  - `vw`: Viewport width

## Simboli e Scorciatoie:

- **Backtick**:
  - `alt + 96`: ``
  - `option + 9` o `option + 8`: ``
- **Tilde**:
  - `alt + 126`: `~`
  - `option + 5` su MacBook: `~` 

  .-- SEPARATORE ORGNIZZAZIONE ANCORA SISTEMARE c

    ```css stili per il bordo
stile dashed
border: 1px dashed black;
dotted linee puntinate
double linee doppie
groove linee incavate
ridge linee rialzate
inset linee incassate
outset linee rialzate

```css

## Esempi di Bordi

```css
border è il bordo
il primo px è il top, il secondo è il right, il terzo è il bottom, il quarto è il left1
border-width: 10px 20px; è il top e il bottom 10px e il right e il left 20px
```
border-width;10px 20px 30px; è il top 10px, il right 20px, il bottom 30px, il left 20px
```css
border-width: 10px 20px 30px 40px; è il top 10px, il right 20px, il bottom 30px, il left 40px
```css

## padding è lo spazio tra il contenuto e il bordo e il margin è lo spazio tra il bordo e il contenitore
    padding: 10px 20px 30px 40px;
    il primo px è il top, il secondo è il right, il terzo è il bottom, il quarto è il left1
    stessa progrssione per il margin
```css


## centrare un blocco margin 0 auto
```css
text align center centra solo il testo
mentre per centrare un blocco si usa margin 0 auto
margin: 0 auto;
LINK https://www.w3schools.com/css/css_margin.asp
```css


## Utilizzo di `not` in CSS importante 

```css
se definisco margin 0 globale
usare not
esempio voglio usare not su tag li 
allora scrivo ul li:not(.class) {
    margin: 0;
}
https://www.w3schools.com/cssref/sel_not.php}

```cs

come usare .container per centrare un blocco
.container {
    margin: 0 auto;
    width: 80%;
```css


##SELETTORI CSS
```css
selezione header img, selezion1, selezion2
```css
per selezionare tutto dentro header 
header * {
    color: red;
}
```


selettori avanzati 

lo spzio mi va a selezionare tutti i figli a qualunque livello di discendenza
ul li:first-child {
    background-color: #f1f1f1;
}
```css

mentre il ul > li:first-child seleziona solo i figli diretti

cosi seleziono il primo figlio di un ul senza prendere in considerazione i figli di ul
ul > :first-child {
    background-color: #f1f1f1;
}
```css

se e presente ul > :firstchild {
    background-color: #f1f1f1;
}

e ce un div allora ul > div:first-child non funzionerà 

allora ul > li:first child non funzionerà
```css