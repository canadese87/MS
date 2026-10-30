---
tags:
  - navi
  - combattimento
  - megadamage
---

# Combattimento tra navi

Il combattimento tra navi si risolve in Ship Round astratti. Si presume che ogni nave e il suo equipaggio manovrino, scelgano i bersagli e prendano decisioni tattiche corrette. I giocatori decidono quando combattere, fuggire, negoziare o arrendersi.

## Ship Round

Ogni Ship Round è composto da tre fasi, in quest'ordine:

1. [Movement Phase](#movement-phase)
2. [Attack Phase](#attack-phase)
3. [Morale Phase](#morale-phase)

Durata:

- Uno Ship Round dura da pochi minuti a qualche ora, in base alla distanza tra le navi.
- Tra uno Ship Round e il successivo il tempo torna normale; i personaggi possono agire con i normali [round](../03_violenza/round.md).
- A Contact Range: pochi minuti tra uno Ship Round e l'altro (sufficienti per alcuni round normali).
- A Firing Range: da alcune ore a diversi giorni tra uno Ship Round e l'altro.
- La maggior parte dei combattimenti termina in 1 Ship Round; quasi nessuno supera i 3.

## Movement Phase

1. Ogni nave sceglie in segreto una manovra: **evadere**, **inseguire** o **mantenere la rotta**.
2. Ogni nave sceglie in segreto quanto Fuel aggiuntivo spendere.
3. Le scelte vengono rivelate contemporaneamente.
4. Le navi che evadono o inseguono effettuano un Thrusters Check. La nave che ha speso più Fuel ha [+].

### Evadere

Si può spendere qualsiasi quantità di Fuel, ma è richiesto un minimo in base al Range:

| Range | Fuel minimo |
|---|---|
| Contact | 3 Fuel |
| Firing | 2 Fuel |
| Detection | 1 Fuel |

### Inseguire

Si può spendere qualsiasi quantità di Fuel, anche nessuna.

### Mantenere la rotta

- Non si spende Fuel aggiuntivo.
- L'avversario ottiene ciò che vuole (evadere o inseguire) senza tirare, ma spende comunque il Fuel aggiuntivo puntato.

### Risultati del Thrusters Check

| Risultato | Effetto |
|---|---|
| Successo (avversario fallisce) | La nave ottiene ciò che vuole: la distanza aumenta (evasione) o diminuisce (inseguimento) di 1 Range Band. |
| Critical Success | La nave ottiene ciò che vuole anche se l'avversario ha avuto successo. |
| Critical Failure | L'avversario ottiene ciò che vuole anche se ha fallito. |
| Altri casi (entrambi successo o entrambi fallimento) | Pareggio: il Range non cambia. |

Note:

- Un Thrusters Check fallito comporta 1 Stress a tutti a bordo (regola generale degli [Ship Stat Check](statistiche.md#ship-stat-check)).
- Con Navigation Offline (MDMG 03) la nave non può effettuare Thrusters Check.
- Con Streamlined Fuel Injectors, ogni 1 Fuel puntato vale 2.
- Il Fuel speso in combattimento si somma al Fuel necessario per il viaggio.
- Un'evasione non riuscita non impedisce all'avversario di attaccare nella successiva Attack Phase.

## Attack Phase

Al termine della Movement Phase, ogni nave a Firing Range o più vicina sceglie un bersaglio ed effettua un Battle Check. A Detection Range può attaccare solo una nave dotata di Railgun.

| Risultato del Battle Check | Effetto |
|---|---|
| Critical Success | La nave infligge il doppio dell'MDMG. |
| Successo | La nave infligge MDMG. |
| Fallimento | La nave subisce 1 MDMG, oltre all'eventuale MDMG inflitta dal nemico. |
| Critical Failure | La nave subisce 2 MDMG, oltre all'eventuale MDMG inflitta dal nemico. |

- Una nave senza armi, o con armi offline, fallisce automaticamente tutti i Battle Check; i suoi avversari hanno successo automatico.
- Un Battle Check fallito comporta 1 Stress a tutti a bordo.
- L'MDMG inflitta è il valore Megadamage del profilo della nave (es. 1d5), modificato da armi e Upgrade.

### Ship Class e scontri impossibili

- Una nave ha [+] a tutti i Battle Check e ai tiri di MDMG contro navi di 1 Class inferiore.
- Una nave di 2 o più Class superiore al nemico è considerata imbattibile in uno scontro diretto, salvo diversa decisione del Warden.

### Modificatori dell'Attack Phase

| Fonte | Effetto |
|---|---|
| Targeting Sensors | Systems Check (Firing Range): [+] ai Battle Check. |
| Electronic Countermeasures | [-] ai tiri di MDMG del nemico. |
| Laser Defense System | Annulla il bonus di MDMG del nemico derivante da Missile Launcher. |
| Missile Launcher (Heavy) | +1 MDMG. |
| Particle Beam | Il nemico effettua un Systems Check o il suo Radiation Level aumenta di 1. |
| Armi non rifornite | [-] ai Battle Check nel combattimento successivo, poi fallimento automatico. |
| Redundant Systems | Ignora un tiro di MDMG (monouso). |
| Fragile (Maintenance Issue) | +1 MDMG subita sempre. |

## Hull

L'Hull funziona come gli Armor Points di un personaggio (vedi [Attacco e danno](../03_violenza/attacco_danno.md)).

- La nave ignora ogni MDMG inferiore al suo Hull.
- Se in un singolo colpo la nave subisce MDMG pari o superiore al suo Hull, l'Hull è distrutto e la nave subisce l'MDMG residua.
- L'Hull distrutto si ripristina solo con una Major Repair (o con il Machine Shop).

## Megadamage

L'MDMG equivale a Damage e Wounds di un personaggio combinati.

- Quando la nave subisce MDMG, la si somma all'MDMG già accumulata e si segna il nuovo totale.
- Si applica l'effetto corrispondente al **nuovo totale**. Gli effetti dei totali inferiori non si sommano.
- Con 9 o più MDMG totali la nave è distrutta.
- Riparare provvisoriamente un sistema colpito ne ripristina la funzione, ma l'MDMG resta sul Manifest finché non viene rimossa con una Major Repair in porto (o con il Machine Shop). Vedi [Riparazioni](riparazioni.md).

| MDMG | Effetto |
|---|---|
| 00 | **All Systems Normal.** Nessun effetto. |
| 01 | **Emergency Fuel Leak.** Ogni spesa di Fuel costa 1 Fuel in più. |
| 02 | **Weapons Offline.** I Battle Check falliscono automaticamente. |
| 03 | **Navigation Offline.** Impossibile effettuare Thrusters Check. 10% di probabilità che tutti i dati di navigazione vengano cancellati. |
| 04 | **Fire on Deck.** L'incendio si propaga nella nave. Le aree in fiamme hanno atmosfera tossica (fumo) e altamente corrosiva (10 DMG/round). Vedi atmosfere tossiche e corrosive in [Ambiente](../04_sopravvivenza/ambiente.md). |
| 05 | **Hull Breach.** Tutti a bordo effettuano un Body Save o subiscono 1 Wound (Explosion). Con Critical Failure il personaggio viene espulso nello spazio. |
| 06 | **Life Support Systems Offline.** Ossigeno limitato a 1d10 × Crew Capacity massima. Vedi Oxygen in [Ambiente](../04_sopravvivenza/ambiente.md). |
| 07 | **Radiation Leak.** Il Radiation Level aumenta ogni 2d10 minuti. |
| 08 | **Dead in the Water.** Tutti i sistemi offline, solo alimentazione di emergenza. |
| 09+ | **Abandon Ship!** La nave è distrutta in 1d10 minuti. |

## Morale Phase

- Dopo ogni Ship Round in cui ha subito MDMG, la nave nemica effettua un Morale Check.
- Morale Check: si tira 1d10. Se il risultato è inferiore all'MDMG attuale della nave, questa può inviare un hail per proporre un cessate il fuoco e riaprire i negoziati.
- Se nessun nemico ha subito MDMG nello Ship Round, la Morale Phase si salta.

## After Battle Report

Dopo ogni scontro in cui la nave ha subito MDMG:

1. Si effettua un Systems Check.
2. Fallimento: si tira una volta sulla [Maintenance Issues Table](riparazioni.md#maintenance-issues-table).
3. Critical Failure: si tira due volte sulla tabella.

## Abbordaggio

- L'abbordaggio è possibile solo a Contact Range.
- Un Boarding Skiff può agganciarsi a una nave nemica a Contact Range e inserire una squadra d'abbordaggio; il bersaglio può effettuare un Battle Check per resistere (vedi [Veicoli Class-0](veicoli_classe_0.md#boarding-skiff)).
