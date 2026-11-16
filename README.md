# Isola dei Golosi — Turni e timbrature

Prototipo responsive del gestionale interno per la programmazione dei turni, la timbratura del personale e il controllo delle anomalie.

## Funzioni incluse

- accesso rapido tramite le prime due lettere del nome;
- PIN dimostrativo di quattro cifre e cambio PIN dal profilo;
- modalità timbratura con check-in e check-out;
- dashboard con presenti, assenti e ore programmate;
- turni settimanali e riepilogo del giorno successivo;
- storico mensile con dettaglio per dipendente;
- simulazione delle notifiche per ritardi, mancati ingressi e inizi anticipati;
- interfaccia ottimizzata per smartphone, tablet e PC.

## Avvio

Non sono necessarie dipendenze o una fase di compilazione. Aprire `index.html` in un browser oppure pubblicare il repository con GitHub Pages.

Per provare l'anteprima:

- scrivere le prime due lettere di `Eriona`, `Vice`, `Randagio` o `Personale`;
- usare il PIN dimostrativo `0000`;
- scegliere `Timbratura` oppure `Gestionale`.

## Stato del progetto

Questa versione è un prototipo frontend. I dati restano nella sessione del browser e non vengono ancora inviati a servizi esterni.

Non sono ancora collegati:

- autenticazione sicura lato server;
- database Supabase;
- sincronizzazione Google Sheets;
- notifiche push reali;
- autorizzazioni definitive per Direttrice, Vice e personale;
- registro di audit e approvazione delle correzioni.

Il PIN `0000` è esclusivamente dimostrativo e non deve essere utilizzato in produzione.
