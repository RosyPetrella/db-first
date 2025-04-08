<!-- Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti
delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
come visto in classe fai un file readme.md
inserisci nome della tabella,
inserisci le colonne per definire il modello
assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna -->

## table name: 'auto'

## table columns

- id: Primary key - auto_increment - notnull
- marca: VARCHAR - notnull
- modello: VARCHAR - notnull
- tipo carrozzeria: VARCHAR - notnull
- cilindrata: INT - notnull
- cv: INT - notnull
- colore: VARCHAR - notnull
- anno immatricolazione: YEAR - notnull
- km: INT - notnull
- porte: SMALL INT - notnull
- prezzo: INT - notnull
- disponibilità: TINY INT - default(1)
- alimentazione: VARCHAR - notnull
- cambio: VARCHAR - default(1)
- stato: VARCHAR - notnull
- dimensioni: VARCHAR - notnull
- descrizione: TEXT - null(0)
