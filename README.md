# Progetto Sito Funghi

Sito per esercitarsi in vista dell'esame di riconoscimento funghi.

- `index.html` — il sito pubblico: test scritto a tempo (30 domande, max 3 errori),
  riconoscimento fotografico (9 funghi: 3 mortali, 3 velenosi, 3 commestibili, max 3 errori),
  sezione di studio. Legge domande e foto da Firebase (Firestore), in sola lettura.
- `admin.html` — pannello riservato (non collegato dal sito pubblico): login con Firebase
  Authentication (email/password), import domande da CSV, aggiunta domanda singola,
  caricamento foto in blocco su Firebase Storage, gestione (elenco/eliminazione) di
  domande e funghi.
- `esempio_domande.csv` — file di esempio con il formato da rispettare per importare le
  domande in blocco (colonne: categoria, domanda, a, b, c, corretta).

I dati (domande, foto) sono su Firebase; lo storico dei risultati resta invece solo
in locale nel browser di chi svolge il test, per privacy.

**Nota:** le domande fanno riferimento alla normativa vigente al momento dell'inserimento;
la legge può cambiare nel tempo, quindi i contenuti potrebbero non essere aggiornati.
Verificare sempre con fonti ufficiali e un micologo autorizzato.
