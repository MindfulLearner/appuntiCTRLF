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

#### Global Styles
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
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

---

Questi appunti dovrebbero ora contenere tutte le tue informazioni originali, arricchite con spiegazioni aggiuntive dove necessario. Se c'è altro da aggiungere o modificare, fammi sapere!


## TIPI DI SELEZIONI
Esempio di HTML:
<!-- Esempio HTML -->
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esempio CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
        <!--ID si indica con #-->
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

/* Esempio CSS */ <!--# ID MAIN-->
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

Spiegazione
HTML:

id="main": Identificatore unico per il div principale.
class="container red": Classi combinate per selezioni specifiche.
class="container blue": Un'altra combinazione di classi.
Struttura a livelli per mostrare l'uso del selettore figlio.
CSS:

#main.container.red: Seleziona l'elemento con ID main e classi container e red.
.container.red: Seleziona gli elementi con classi container e red.
.container.blue: Seleziona gli elementi con classi container e blue.
.container > .child: Seleziona i figli diretti di container con classe child.

come collegare HTML con css TRAMITE LINK

A parita di specificita vale di più quello pèiù in basso quello più specifico vale di più
##SPECIFICITA
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

css

h1 {
    color: red;
}

.gialloh1 {
    color: yellow;
}

.verdeh1 {
    color: rgb(0, 255, 76);
}

HA PIu valore verdeh1 perche e l'ultimo

TEXT alight con immagini e testi con un contenitore DIV esempio.

risalire e scendere dalle cartelle directories
url("../img/gatto-tenero.jpg")

## IMG Variables ci sono le slides
come comprire un img in div
size
opacity

color
image
repeat REPEAT y solo verticale 
position center?
background  fixed attachment attaccata alla pagina

sip uo mettere tutto in un unica linea

DEFAULT TASPARENTE

unita di misura
%
REM relativo all'HTML
 E 
 EM relativo al contenitore e x2 al font size base 16 diventa 32 es
px
vh
vw