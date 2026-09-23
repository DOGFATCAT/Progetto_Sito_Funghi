# Progetto Sito Funghi

Sito per esercitarsi in vista dell'esame di riconoscimento funghi.

- `index.html` — l'app completa: test scritto a tempo (30 domande, max 3 errori),
  riconoscimento fotografico (9 funghi: 3 mortali, 3 velenosi, 3 commestibili, max 3 errori),
  sezione di studio, gestione contenuti protetta da accesso (email + password) con import
  domande da CSV e caricamento foto in blocco.
- `esempio_domande.csv` — file di esempio con il formato da rispettare per importare le
  domande in blocco (colonne: categoria, domanda, a, b, c, corretta).

La versione online e funzionante (con database e storico) è pubblicata come artifact su
Claude — questo repository serve come backup del codice sorgente.

**Nota:** le domande fanno riferimento alla normativa vigente al momento dell'inserimento;
la legge può cambiare nel tempo, quindi i contenuti potrebbero non essere aggiornati.
Verificare sempre con fonti ufficiali e un micologo autorizzato.
