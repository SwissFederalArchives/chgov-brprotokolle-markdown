# Aiuto

## Ricerca semplice

Immettere una parola chiave nell’apposito campo della pagina iniziale. Questa parola sarà cercata in tutti i verbali.

L’asse cronologico permette di restringere la ricerca a un determinato periodo.

## Ricerca avanzata

La ricerca fuzzy considera anche le parole che hanno una grafia simile ai termini immessi.

È possibile utilizzare la ricerca nei marginalia per focalizzare la ricerca nei verbali manoscritti sul titolo / oggetto delle decisioni.

Per la ricerca avanzata sono disponibili più opzioni:

- Ricerca di parole, espressioni e frasi («parola» «questa è una frase»)\
Esempio: «Cantone di Zurigo»
- Ricerca con caratteri jolly: ? (un solo carattere), * (più caratteri), ~ (ricerca fuzzy)\
Esempi: Z?rigo, Zur*, Zurigo~
- Operatori booleani: && (AND), || (OR), ! (NOT)\
Esempi: Cantone && Berna, Berna || Zurigo, Cantone !Città (anche: Cantone AND Berna, Berna OR Zurigo, Cantone NOT Città)

## Elenco dei risultati

L’elenco dei risultati visualizza i verbali in cui compare la parola chiave.

Cliccando su un verbale, questo si aprirà alla prima occorrenza della parola chiave.

L’algoritmo di ricerca calcola la rilevanza delle pagine in funzione del numero di risultati che contengono (la rilevanza cresce con il numero di risultati). L’elenco dei risultati riporta le pagine che contengono il termine cercato. Lo stesso verbale vi comparirà quindi più volte se diverse sue pagine contengono risultati.

## Elenco cronologico

I verbali delle decisioni del Consiglio federale sono ordinati cronologicamente. Se si immette una data precisa, sarà visualizzato un determinato verbale.

![Stampa schermo "Ricerca per data"](/md/assets/it-scrn-browser.png)

## Visualizzazione interattiva della pagina (dettaglio)

I verbali sono consultati nel viewer [Archival IIIF](https://archival-iiif.github.io/){target="_blank"} Viewer (IIIF = [International Image Interoperability Framework](https://de.wikipedia.org/wiki/International_Image_Interoperability_Framework){target="_blank"}).

Basato sull’applicazione browser [Mirador](https://projectmirador.org/){target="_blank"}, il viewer offre diverse funzioni:

- Visualizzazione parallela dell’originale digitalizzato e del testo trascritto automaticamente
- Corrispondenza riga per riga tra il manoscritto e il testo trascritto automaticamente
- Zoom e navigazione all’interno delle pagine
- Sfogliare il documento
- Saltare da una pagina all’altra
- Ricerca all’interno del documento
- Scaricare i verbali in formato PDF e/o il testo trascritto automaticamente

![Stampa schermo "Mirador"](/md/assets/it-scrn-mirador.png)
HTR: Handwritten Text Recognition\
OCR: Optical Character Recognition
