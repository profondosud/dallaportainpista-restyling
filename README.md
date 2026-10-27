# Dalla Porta in Pista · Restyling (proposta)

Proposta di restyling del sito [dallaportainpista.it](https://www.dallaportainpista.it/), realizzata come demo statica (HTML + CSS, senza framework).

## Cosa cambia rispetto al sito attuale
- Layout a scorrimento unico, con una gerarchia chiara: hero → numeri → corsi → circuiti → noleggio → Lorenzo → contatti.
- Prezzi di corsi, circuiti, moto e attrezzatura presentati in tabelle e card leggibili, senza fogli di calcolo.
- Stessa palette del brand (nero, lime `#DDFF00`, bianco) e stessi font (Bebas Neue per i titoli, Roboto per il testo).
- Responsive: test previsto su mobile, tablet e desktop, con menu a scomparsa sotto 768px.
- Nessun dato sensibile nel codice pubblico (l'IBAN presente nelle impostazioni del sito attuale non è incluso).

## Fonti dei contenuti
- Testi, prezzi, circuiti, moto e attrezzatura: estratti dai dati pubblici del sito attuale.
- Logo e immagini: del brand e del sito attuale, usati solo per questa proposta.

## Da verificare prima della consegna
- Numero WhatsApp `+39 379 324 7414`: ricavato dal codice del sito attuale, da confermare con il cliente.
- Prezzi: sono quelli pubblicati oggi, da riconfermare.
- Foto: la foto hero è riutilizzata anche nella sezione "Lorenzo"; servirebbe un ritratto dedicato.
- Pagine di dettaglio (corsi, singoli circuiti, prenotazione online) non incluse in questa demo.

## Struttura
```
index.html      pagina unica
assets/         logo, favicon, foto hero e circuiti (ottimizzate per il web)
```

## Anteprima locale
Aprire `index.html` nel browser, oppure pubblicare su GitHub Pages dal branch `main`.
