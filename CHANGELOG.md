# Changelog

Tutte le modifiche rilevanti al sito della Stazione Meteo di Motta Visconti vengono registrate qui, in ordine cronologico inverso.

## 2026-09-09

### Aggiunto
- Sezione "Fulmine più vicino oggi" nel box fulmini: mostra la distanza minima registrata nella giornata (non solo l'ultimo rilevato), sia in testata che accanto al dato principale
- Nuova sezione "Fonti Dati Esterne" nel popup Specifiche Tecniche, con l'elenco completo delle API e dei portali usati (Open-Meteo, Laghi.net, ARPA Lombardia, Protezione Civile, Google Maps Platform)
- Dettaglio orario ogni 3 ore per ciascun giorno di previsione (stile "ilmeteo.it"), consultabile cliccando sul giorno
- Sezione "Record Storici": temperature e pioggia estreme dal 1940 ad oggi (Open-Meteo Historical/ERA5), con cache robusta per non sovraccaricare l'API esterna

### Modificato
- Soglia di allerta lampeggiante del box fulmini abbassata da 50 km a 10 km, per evitare falsi allarmi su eventi lontani
- Box previsioni rinominato "Previsioni Future", spostato sopra la sezione Stagione/Sole/Luna, esteso a includere il giorno corrente ("Oggi")
- Contrasto del testo "Moderato" nel box Raggi UV migliorato (sfondo giallo scurito per leggibilità)
- Legenda del livello polline ridotta ai 4 livelli realmente utili (rimossi "Nessuno" e "Molto Basso"), ora su una sola riga anche da smartphone
- Compattate le card di Temperatura, Umidità, Pressione, Vento, Raggi UV, Pioggia, Qualità dell'Aria, le 3 rilevazioni del Fiume Ticino e i pulsanti del footer
- Colore e lunghezza della freccia di direzione vento nella bussola, per non sovrapporsi più all'indicatore Nord
- Testi e dimensioni dei titoli uniformati in tutte le card del sito

### Risolto
- Bug nel calcolo del box fulmini che causava un errore silenzioso nei giorni senza rilevamenti
- Popup "Specifiche Tecniche" non scorrevole su schermi bassi (il contenuto superiore restava inaccessibile su smartphone)
- Bussola del vento deformata (ovale anziché circolare) dopo la riduzione dimensionale delle card
- Duplicazione della logica delle fasi lunari, unificata in un'unica funzione

## 2026-09-08

### Aggiunto
- Banner di allerta meteo basato sul bollettino di criticità della Protezione Civile
- Monitoraggio del livello idrometrico del Fiume Ticino a Bereguardo, poi esteso a Vigevano e Pavia
- Pulsanti dedicati con ultima misura in evidenza e grafico storico al tocco

### Risolto
- Picco anomalo nel grafico del livello idrometrico di Bereguardo (valore -86.4 seguito da uno zero errato)

## Versioni precedenti

Le modifiche antecedenti al 2026-09-08 non sono state tracciate in un changelog strutturato.
