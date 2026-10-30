---
tags:
  - navi
  - stat
---

# Statistiche della nave

Una nave ha tre Stat che fungono sia da Stat sia da Save: Thrusters, Battle e Systems. I valori dipendono dal tipo di nave e possono essere aumentati con gli [Upgrade](potenziamenti.md) e le [Armi](armi.md).

## Stat della nave

| Stat | Uso | Equivalente del personaggio |
|---|---|---|
| Thrusters | Manovrare e accelerare in sicurezza nello spazio. | Speed |
| Battle | Puntare e attaccare altri veicoli nel combattimento tra navi. | Combat |
| Systems | Sensori, computer, manutenzione e altri sottosistemi. | Instinct (Stat generica) |

Il valore di Battle è composto da un valore Base più i bonus delle armi installate e degli eventuali Fighter (vedi [Armi](armi.md) e [Veicoli Class-0](veicoli_classe_0.md)).

## Ship Stat Check

La nave effettua Stat Check come un personaggio (vedi [Stat Check e Save](../02_regole/check_e_save.md)), con queste regole aggiuntive:

- **Fallimento:** ogni persona a bordo guadagna 1 [Stress](../02_regole/stress.md).
- **Critical Failure:** ogni persona a bordo effettua un [Panic Check](../02_regole/panico.md).
- **Critical Success:** effetti normali.
- Un risultato di 90–99 è sempre un fallimento.

### Modificatori

- **Advantage [+] / Disadvantage [-]:** si applicano come per i personaggi, ma la causa deve riguardare l'intera nave, non una singola persona.
- **Skill:** quando pertinente, un personaggio può aggiungere il proprio Skill Bonus al Ship Stat Check (vedi [Skill](../01_personaggio/skill.md)). Solo una persona per volta può aggiungere uno Skill Bonus a un singolo Check.
- Le condizioni del personaggio che aggiunge lo Skill Bonus (es. Cryosickness) possono imporre [-] al Check della nave.
- Le conseguenze di un Ship Stat Check (Stress, Panic Check) subiscono i modificatori dei singoli personaggi (es. Panic Check a [-] per personaggi in Cryosickness).

## Ship Class

La Class misura in modo generale le capacità di una nave. A Class più alta corrispondono dimensioni, potenza e costo maggiori.

| Class | Descrizione | Esempi |
|---|---|---|
| 0 | Shuttlecraft. | Shuttle, Fighter, Dropship. |
| I | Light commercial. | Raider, Executive Transport. |
| II | Medium commercial. | Freighter, Patrol Craft. |
| III | Heavy commercial. | Salvage Cutter, Jumpliner. |
| IV | Light military. | Corvette. |
| V | Medium military. | Exploration Vessel, Troopship. |

La Class determina inoltre:

- il moltiplicatore di costo di Upgrade, armi, rifornimento armi e Major Repair;
- il tipo di Fuel utilizzato (vedi [Viaggi spaziali](viaggi_spaziali.md#rifornimento-e-carburante));
- i modificatori nel combattimento contro navi di Class diversa (vedi [Combattimento](combattimento.md#ship-class-e-scontri-impossibili)).

## Designazione

La Class si abbrevia insieme al Jump Rating nel formato **J*n*C-*X***: J = Jump Rating della Jump Drive, C = Class.

- `J1C-II`: nave Jump-1, Class-II.
- `J0C-III`: nave Class-III senza Jump Drive (solo viaggi interplanetari).
