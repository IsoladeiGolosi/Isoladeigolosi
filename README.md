# Isola dei Golosi — Turni e timbrature

Gestionale responsive per turni, timbrature, profili del personale e comunicazioni dei lavoratori intermittenti.

## Funzioni

- accesso con almeno tre lettere del nome e PIN personale;
- completamento del nome soltanto in presenza del PIN;
- cambio del PIN dal profilo personale;
- check-in e check-out;
- dashboard, turni settimanali e storico mensile;
- notifiche per anomalie e variazioni;
- profilo con dati contrattuali e consenso privacy;
- sezione Invio Modulo Chiamata;
- interfaccia ottimizzata per smartphone, tablet e PC.

## Accesso

I codici non sono pubblicati nel repository:

- PIN provvisorio: `****`;
- PIN personale: `****`;
- eventuali codici di servizio: `****`.

Per accedere, scrivere almeno tre lettere del proprio nome e inserire il PIN personale. Il sistema propone soltanto i nomi compatibili con il PIN digitato.

## Sicurezza

I profili e i PIN sono gestiti dal backend Supabase. I PIN sono memorizzati tramite hash e non in chiaro. Le tabelle del personale sono protette da Row Level Security e non sono accessibili direttamente dal browser.

## Pubblicazione

Il sito è distribuito tramite Vercel dal branch principale del repository.

## Stato

La sezione Invio Modulo Chiamata contiene la logica prevista per i contratti a chiamata. L'invio esterno rimane disattivato finché non vengono configurati e collaudati i dati tecnici del servizio.
