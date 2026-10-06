<!-- ELUCENIA technical documentation · controle-da-asma-gina · it · no clinical/professional/rights approval -->

# Controllo dei sintomi dell’asma (GINA)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/controle-da-asma-gina)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Sintomi diurni più di 2 volte a settimana

`diurno`

### Risvegli notturni dovuti all’asma

`noturno`

### Uso di farmaco al bisogno (SABA) più di 2 volte alla settimana

`alivio`

### Limitazione delle attività dovuta all’asma

`limit`

## Edizione del metodo

GINA strategia 2021: sintomi su 4 settimane, 4 domande; SABA al bisogno; 0/1–2/3–4

## Formula documentata

Nelle ultime 4 settimane contare: sintomi diurni \> 2×/settimana; risvegli notturni per asma; SABA al bisogno \> 2×/settimana (escluso prima dell’esercizio); limitazione delle attività.

0 = controllato · 1–2 = parzialmente controllato · 3–4 = non controllato.

## Limiti e popolazione

La valutazione GINA 2021 qui calcolata riguarda il controllo dei sintomi nelle ultime quattro settimane negli adulti e nei bambini di età superiore a 5 anni, con la domanda sul farmaco al bisogno riferita ai SABA. Questo conteggio non valuta l’intero rischio futuro di riacutizzazione, la funzione polmonare, le comorbilità, la tecnica inalatoria o l’aderenza. Controllo dei sintomi e gravità dell’asma non sono equivalenti. L’adattamento del materiale rimane soggetto alle condizioni del titolare dei diritti.

## Riferimenti

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

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

Asma ben controllata

Mantenere il trattamento; considerare di ridurre il gradino se controllata per 3 mesi.


### 2

Asma parzialmente controllata

Rivedere la tecnica inalatoria, l’aderenza, le comorbidità e i fattori di rischio prima di salire di gradino.


### 3

Asma non controllata

Rivedere tecnica, aderenza e fattori scatenanti; considerare di salire di gradino del trattamento.

