<!-- Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

# database name : Gamestop

# nome tabella : Videogiochi

- id BIGINT PRIMARKEY
- titolo stringa VARCHAR (40) NOTNULL
- descrizione stringa VARCHAR (100)
- autore stringa VARCHAR(30) NOTNULL
- anno date YEAR NULL
- genere stringa VARCHAR (30)NULL
- prezzo number FLOAT(3,2) 99,9 NULL
- casa_di_distrubuzione stringa VARCHAR (50)NULL
- materiale_custodia stringa VARCHAR (30)NULL
- img_copertina stringa VARCHAR()NULL
- produttore string VARCHAR (40) NULL
