---
tags:
  - navi
  - range
  - sensori
  - comunicazioni
---

# Rilevamento e comunicazioni

Negli incontri tra navi la distanza si misura in modo astratto con tre Range Band. Il Range determina le informazioni ottenibili con i sensori, la latenza delle comunicazioni e le opzioni di combattimento.

## Range Band

| Range | Definizione | Comunicazione | Combattimento |
|---|---|---|---|
| Detection | Navi nello stesso sistema stellare. | Lenta. | Di norma nessun rischio; solo Railgun. |
| Firing | Navi a settimane di distanza. | Con latenza. | Rischio di combattimento; tutte le armi. |
| Contact | Navi a pochi giorni di distanza. | Senza latenza. | Rischio di combattimento e di abbordaggio; tutte le armi. |

### Tabella di riferimento rapido

| | Contact | Firing | Detection |
|---|---|---|---|
| Distanza tipica | Da pianeta a orbita bassa. | Da pianeta a luna, stazione, campo di asteroidi. | Da pianeta a pianeta distante. |
| Tempo di viaggio | Minuti. | Da ore a giorni. | Da settimane a mesi. |
| Latenza di hailing | Nessuna. | Secondi. | Da minuti a ore. |
| Combattimento | Abbordaggio. Tutte le armi. | Tutte le armi. | Solo Railgun. |

!!! note
    Il manuale originale definisce Firing Range come "a settimane" e Contact Range come "a pochi giorni" di distanza, mentre la tabella di riferimento rapido indica tempi di viaggio di ore–giorni (Firing) e minuti (Contact). Il Warden applica la scala adatta alla situazione.

## Scansione e sensori

I sensori della nave forniscono informazioni su navi, relitti, stazioni, pianeti, lune, asteroidi e altri corpi celesti. Più è vicino il Range, maggiore è il dettaglio. Il livello di dettaglio è a discrezione del Warden.

| Range | Informazioni rivelate |
|---|---|
| Detection | Presenza, traiettoria, posizione, dimensione approssimativa, dati del Transponder trasmessi (con ritardo). |
| Firing | Traiettoria, dati del Transponder, Class, tipo, armi. |
| Contact | Traiettoria, dati del Transponder, Class, tipo, presenza di forme di vita, stato della nave (danni), dati visivi. |

Modificatori:

- **Deep Space Scanners:** +1 Range Band a tutte le capacità di rilevamento (vedi [Upgrade](potenziamenti.md)).
- **Signature Reduction:** la nave è rilevabile solo con un Systems Check [-] riuscito a Firing Range.
- **Poor scanners** (Maintenance Issue): la nave deve trovarsi una Range Band più vicina del normale per ottenere le stesse informazioni.

## Hailing

Le comunicazioni non sono istantanee: la latenza cresce con la distanza.

| Range | Latenza |
|---|---|
| Contact | Nessuna. |
| Firing | Secondi. |
| Detection | Da minuti a ore. |
| Oltre | Da ore a giorni o più (o mai). |

## Transponder

- Il Transponder è un sistema radio automatico che trasmette in continuazione i dati della nave: callsign, nome del capitano, tipo, Class, porto d'origine, destinazione e altro.
- I dati del Transponder sono soggetti alla latenza della tabella di Hailing.
- Nella maggior parte dei sistemi stellari spegnere il Transponder è illegale o altamente sospetto.

## Ispezioni doganali

I Patrol Craft sorvegliano le navi nel loro sistema.

1. Nave con Transponder spento: 50% di probabilità che il Patrol Craft la contatti (hail).
2. Se la nave accende il Transponder e si sottopone all'interrogatorio: di norma 50% di probabilità che il Patrol Craft esiga di abbordarla per un'ispezione visiva di equipaggio e carico (in cerca di contrabbando o di una tangente).
3. Squadra d'abbordaggio: 1d10+1 Marine (Grunt): Combat 30, SMG 2d10 DMG, Instinct 25, Wounds 2.

I Patrol Craft impegnati in operazioni di polizia ordinarie effettuano i Morale Check a [-] (vedi [Combattimento](combattimento.md#morale-phase)).

### Contrabbando

Si tira 1d10 per il tipo di merce; il carico è di 1d5 container.

| d10 | 1d5 container pieni di… |
|---|---|
| 0 | Fauna esotica: 10% di probabilità che gli animali siano vivi. |
| 1 | Persone (tirare 1d10): 0 lavoratori a contratto vincolato; 1–3 prigionieri; 4–6 rifugiati; 7–8 coloni (sotto NDA); 9 ribelli anti-corporativi. |
| 2 | Androids. |
| 3 | Proprietà intellettuale: film, fumetti, musica. |
| 4 | Beni culturali: arte, pornografia, libri proibiti. |
| 5 | Armi: 70% armi civili corte, 29% armi militari, 1% armi sperimentali fuorilegge. |
| 6 | Contraffazioni (tirare 1d10): 0 prodotti alimentari; 1–3 media di intrattenimento; 4–6 abbigliamento, sneakers; 7–8 documenti, etichette di marca; 9 gioielli e accessori. |
| 7 | Medicinali, attrezzature e farmaci salvavita. |
| 8 | Beni rubati: veicoli, cibo, beni di lusso. |
| 9 | Materiale pericoloso. |

## Distress Signal

Procedura: la nave passa all'alimentazione di emergenza, l'equipaggio si chiude nei Cryopod, si trasmette un Distress Signal e si attendono i soccorsi. Si tira 1d10 sulla tabella.

| d10 | Tempo di risposta | Effetto |
|---|---|---|
| 0 | 2d10 settimane | — |
| 1–2 | 2d10 mesi | — |
| 3–4 | 2d10 anni | Body Save; se fallito, −1d5 a tutte le Stat e i Save. |
| 5 | 2d10 decenni | Body Save [-]; se fallito, −1d10 a tutte le Stat e i Save. |
| 6–9 | Mai | Nessun soccorso. |

La Maintenance Issue *Unable to send distress signals* impedisce questa procedura (vedi [Riparazioni](riparazioni.md)).
