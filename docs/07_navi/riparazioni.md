---
tags:
  - navi
  - riparazioni
  - manutenzione
---

# Riparazioni e manutenzione

La nave accumula problemi di manutenzione (Repair), Minor o Major, che si annotano nella sezione Repairs del [Ship Manifest](manifest.md).

## Condizione iniziale

Quando i personaggi acquisiscono una nave, si tirano **1d5+1** Repair sulla [Maintenance Issues Table](#maintenance-issues-table).

## Manutenzione ordinaria

Una volta all'anno la nave effettua un **Maintenance Check** (Systems Check):

| Risultato | Effetto |
|---|---|
| Successo | Nessun effetto. |
| Fallimento | 1 tiro sulla Maintenance Issues Table. Tutti a bordo guadagnano 1 [Stress](../02_regole/stress.md). |
| Critical Failure | 2 tiri sulla Maintenance Issues Table. Tutti a bordo effettuano un [Panic Check](../02_regole/panico.md). |

- Un ingegnere capo dedicato a bordo, o lavoro di manutenzione svolto dall'equipaggio (es. durante lo Shore Leave), può conferire [+] al Maintenance Check, a discrezione del Warden.
- La Maintenance Issue *Lemon* impone [-] ai Maintenance Check.

Si tira sulla tabella anche dopo un combattimento in cui la nave ha subito MDMG (vedi [After Battle Report](combattimento.md#after-battle-report)).

## Minor Repair

- Danni estetici, pulizia e piccoli lavori eseguibili dall'equipaggio durante il volo.
- Durata: circa 2d10 giorni.
- Se l'equipaggio ha poco tempo o manca di attrezzi o risorse, il Warden può richiedere uno Stat Check:
    - Fallimento: la riparazione richiede più tempo e risorse.
    - Critical Failure: la Minor Repair diventa una Major Repair e deve essere eseguita in porto.

## Major Repair

- Danni strutturali o di sistema su larga scala, incluse la riparazione di MDMG e di Hull.
- Eseguibili solo in porto (eccezione: Machine Shop, fino a 3 MDMG e 3 Hull; vedi [Upgrade](potenziamenti.md)).
- Costo: **1d5mcr × Class della nave** per ogni Major Repair.
- Ogni punto di Hull o di MDMG conta come una Major Repair separata ai fini del costo.
- Durata: da alcuni mesi fino a un anno, in base alla gravità del danno e alla disponibilità di parti e manodopera.

## Maintenance Issues Table

Si tira 1d100. Il risultato indica se si tratta di una Minor o di una Major Repair.

### Minor Repair

| d100 | Problema |
|---|---|
| 00 | Rancid smell permeates cabins. |
| 01 | Huge mess everywhere. |
| 02 | Staticky comms. |
| 03 | Faulty electrical system. |
| 04 | Loose couplings. |
| 05 | Hidden (highly illegal) contraband. |
| 06 | Autopilot systems down. |
| 07 | Leaking hydraulic systems. |
| 08 | Creaking hull. |
| 09 | Damaged bulkheads. |
| 10 | Misaligned docking clamps. |
| 11 | Viewports blocked. |
| 12 | Jammed exterior airlocks. |
| 13 | Dysfunctional gravity plating. |
| 14 | Out of code compliance. |
| 15 | Controls sticking. |
| 16 | Coolant leak. |
| 17 | Miscalibrated Thruster Gimbal System. |
| 18 | Bevy of OSHA violations. |
| 19 | Blocked air vents. |
| 20 | Emergency lighting only. |
| 21 | Internal networking issues. |
| 22 | Inaccurate data collection. |
| 34 | Worn landing struts. |
| 35 | Out-of-date air filters. |
| 36 | Corroded pipes. |
| 37 | Inaccurate orbital transfer navigation. |
| 38 | Worn out fuel injection nozzles. |
| 39 | Inoperative exterior lighting system. |
| 40 | Defective intercom system. |
| 41 | Inadequate waste recycling. |
| 42 | Faulty altitude control thrusters. |
| 43 | Insufficient Life Support redundancy. |
| 44 | Delayed communication relays. |
| 45 | Damaged fuel lines. |
| 46 | Corroded exhaust manifolds. |
| 47 | Terminal displays non-functional. |
| 48 | Check engine light won't turn off. |
| 49 | Failed backup systems. |
| 50 | Faulty door locks. |
| 51 | Buggy communications. |
| 52 | Infected food storage facilities. |
| 53 | Corrupted data banks. |
| 54 | Jammed cargo bay doors. |
| 55 | Flickering interior lights. |
| 56 | Failed airlock seals. |
| 67 | Miscalibrated guidance system. |
| 68 | Overloaded power storage. |
| 69 | Malfunctioning sensor arrays. |
| 70 | Failed Water Recovery System. |
| 71 | Micrometeoroid hull damage. |
| 72 | Faulty Carbon Dioxide Removal Assembly. |
| 73 | Solar panel degradation. |
| 74 | Computer failure from cosmic radiation. |
| 75 | Overloaded circuitry. |
| 76 | Malfunctioning plasma thruster. |
| 77 | Thermal management system failure. |
| 78 | Intermittent electrical outages. |
| 79 | Fire suppression system out of code. |
| 80 | Damaged floor paneling. |
| 81 | Broken light fixture in remote corridor. |
| 82 | Damaged coolant pump. |
| 83 | Cracked viewports. |
| 84 | Systems overloaded with malware. |
| 85 | Leaky fuel valve. |
| 86 | Jammed exhaust vent. |
| 87 | Stuck waste disposal chute. |
| 88 | Lifts non-functioning. |
| 89 | Damaged communications antenna. |

### Major Repair

| d100 | Problema | Effetto |
|---|---|---|
| 23 | Oxygen leak. | Se la nave è a corto di O2, perde 1d5 O2 aggiuntivo al giorno. |
| 24 | Throttled afterburners. | −2d10 Thrusters. |
| 25 | Lemon. | Maintenance Check a [-]. |
| 26 | Slow acceleration. | +1 settimana a ogni viaggio. |
| 27 | Inaccurate navigation. | — |
| 28 | Miscalibrated targeting sensors. | −1d10 Battle. |
| 29 | Faulty cryopods. | Incubi. La Cryosickness dura 1 settimana in più. |
| 30 | Malfunctioning escape pods. | — |
| 31 | Unable to send distress signals. | — |
| 32 | Sabotaged coolant system. | — |
| 33 | Death trap. | [-] a tutti i tiri. |
| 57 | Fuel leak. | +1 Fuel consumato a ogni spesa di Fuel. |
| 58 | Jump bug. | 10% di probabilità che un Jump duri 2d10 mesi invece di 2d10 giorni. |
| 59 | Fragile. | +1 MDMG subita sempre. |
| 60 | Cracked heat shields. | — |
| 61 | Outdated software. | −1d10 Systems. |
| 62 | Inadequate water filtration. | Parassiti nella riserva d'acqua. |
| 63 | Malfunctioning waste management system. | — |
| 64 | Fusion Reactors overheating. | — |
| 65 | Failed radiation filter. | — |
| 66 | Radiation leak. | L'intera nave è a Radiation Level 2. |
| 90 | Clogged air filtration. | Crew Capacity dimezzata. |
| 91 | Malfunctioning climate control. | 29 °C (85 °F) costanti. |
| 92 | No emergency power. | — |
| 93 | Weak frame. | −1 Hull, −1 Upgrade. |
| 94 | Toxic chemical spill. | — |
| 95 | Poor scanners. | La nave deve essere una Range Band più vicina del normale per rilevare. |
| 96 | Counterfeit papers. | La nave è rubata; su di essa pende una taglia. |
| 97 | Corrupted A.I. | — |
| 98 | Warp Cores fail. | I Warp Core falliscono il 10% delle volte. |
| 99 | Rust bucket. | Tutto ciò che può guastarsi si guasta. +1 Minimum Stress all'equipaggio. |

Le voci senza effetto meccanico specifico sono applicate dal Warden come complicazioni narrative. Per Radiation Level e O2 vedi [Ambiente](../04_sopravvivenza/ambiente.md).
