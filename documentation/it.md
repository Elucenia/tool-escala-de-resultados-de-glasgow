<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · it · no clinical/professional/rights approval -->

# Scala degli esiti di Glasgow (GOS)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-resultados-de-glasgow)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Situazione del paziente

`gos`

- `1` — 1 – Decesso
- `2` — 2 – Stato vegetativo persistente: nessuna risposta significativa, cicli sonno-veglia
- `3` — 3 – Disabilità grave: cosciente, ma dipendente da un’altra persona nella vita quotidiana
- `4` — 4 – Disabilità moderata: indipendente, ma con esiti (può usare i trasporti e lavorare in un ambiente protetto)
- `5` — 5 – Buon recupero: riprende la vita normale anche con deficit minori

## Edizione del metodo

GOS/Jennett–Bond 1975: 5 categorie; favorevole 4–5; non GOSE a 8 categorie

## Formula documentata

Scegliere la categoria più adatta. Gli studi distinguono solitamente favorevole (4 e 5) e sfavorevole (1 a 3).

## Limiti e popolazione

Valuta l’esito funzionale dopo una lesione cerebrale, considerando la disabilità fisica e mentale. Registrare il tempo di follow-up e l’edizione di cinque categorie. La GOS non deve essere trattata come equivalente alla GOSE di otto categorie né come una previsione basata sui dati al ricovero.

## Riferimenti

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Disabilità grave (esito sfavorevole)


### 2

Disabilità moderata (esito favorevole)


### 3

Buon recupero (esito favorevole)

