# Verifica termoigrometrica

Web app statica (HTML/JS, nessuna dipendenza) per la verifica termoigrometrica dell'involucro:
trasmittanza U (UNI EN ISO 6946), condensa interstiziale/Glaser e muffa (UNI EN ISO 13788),
parametri dinamici (UNI EN ISO 13786), confronto con i limiti per zona climatica.

- Dati salvati nel browser (localStorage); import/export JSON.
- `index.html` contiene tutto (motore di calcolo, database materiali/comuni, UI).

## Avvertenze
Dati climatici indicativi (profilo sinusoidale, GG in parte stimati) e limiti U riportati a memoria:
**verificare su DPR 412/93, UNI 10349, DM 26/06/2015, DM 06/08/2020** prima dell'uso professionale.
Non sono modellati ponti termici, scambio con il terreno (ISO 13370) e serramenti. Non è uno strumento certificato APE.

## Deploy Netlify
Nuovo sito da questo repo → publish directory `.`, nessun build command.
