---
tags:
  - sopravvivenza
  - ambiente
---

# Ambiente e sopravvivenza

Rischi ambientali più comuni.

## Atmosfere

| Atmosfera | Requisito | Effetto senza protezione |
|---|---|---|
| **Toxic** | Rebreather o armatura con riserva d'ossigeno | 1d10 DMG per round; Body Save per dimezzare. |
| **Corrosive** | Equipaggiamento e armatura specializzati | Da 1 DMG/round (Mildly Corrosive) a 10 DMG/round (Highly Corrosive). Oltre questo livello l'attraversamento è impossibile senza equipaggiamento specializzato. |

## Bleeding

- Un personaggio con **Bleeding** subisce 1 DMG per round per ogni punto di Bleeding finché l'emorragia non viene fermata.
- Il Bleeding è cumulativo: Bleeding 1 + Bleeding +1 = 2 DMG per round.
- Il danno da Bleeding ignora Armor e Damage Reduction.
- Bendare una ferita richiede un'azione nel round. Vedi [Il round](../03_violenza/round.md).

## Cryosickness

- Al risveglio dalla cryosleep il personaggio è **cryosick**: `[-]` a tutti i tiri per **1 settimana**.
- Le cryochamber potenziate possono attenuare l'effetto.
- Uno Stimpak cura immediatamente la cryosickness.
- In cryosleep i parametri vitali sono preservati e l'invecchiamento rallenta; di norma lo Stress non si riduce.

## Exhaustion

- Dopo **12 ore** di attività, Body Save ogni ora. Fallimento: +1 Stress e 1 DMG.
- Dopo **24 ore** di attività: `[-]` a tutti i tiri finché il personaggio non riposa per 8 ore.

## Cibo e acqua

- **Cibo**: sopravvivenza massima circa 3 settimane. Dopo 24 ore senza cibo: `[-]` a tutti i tiri.
- **Acqua**: minimo di sopravvivenza 1 L al giorno. A questo livello:
    - ogni attività faticosa (corsa, combattimento, riparazioni meccaniche) richiede un Body Save o il personaggio sviene;
    - `[-]` a tutti i tiri.

## Oxygen

### Senza ossigeno

- Il personaggio resta cosciente per **15 secondi**, poi perde i sensi.
- Dopo aver perso i sensi sopravvive **1d5 minuti**, poi muore.

### Riserva d'ossigeno della nave

Si applica se tutto il Life Support System di una nave va offline.

1. **Riserva** = `1d10` × capacità massima di equipaggio.
2. Ogni 24 ore si sottrae il numero di membri dell'equipaggio che respirano.
3. Ogni membro impegnato in attività faticosa (corsa, combattimento, riparazioni meccaniche) riduce la riserva di ulteriori 2.
4. Gli Android non consumano ossigeno. Chi è in cryosleep non consuma ossigeno.

| Condizione | Effetto |
|---|---|
| Riserva < 2 × numero di persone che respirano | `[-]` a tutti i tiri. |
| Riserva < numero di persone che respirano | Ogni persona che respira: Body Save, altrimenti Death Save. |
| Riserva esaurita | 15 secondi di coscienza, poi 1d5 minuti prima della morte. |

## Radiation

| Livello | Fonte tipica | Effetto |
|---|---|---|
| **1 – Trace** | Radiazione ordinaria, raggi cosmici | Nessun effetto immediato. Possibili effetti a lungo termine (cancro, ecc.). |
| **2 – Acute** | Reattori o Warp Core non schermati | −1 a tutte le Stat e i Save ogni round. |
| **3 – Lethal** | Armi atomiche, contatto diretto con un Warp Core | Ogni round: Body Save o dose letale (morte entro 1d5 giorni). |

- Le armature con **Radiation Shielding** (es. Hazard Suit) bloccano tutti e tre i livelli.
- Le Radiation Pills riducono di 1 il Radiation Level per 2d10 minuti (1d5 DMG).

## Temperatura

- Di norma caldo e freddo non hanno effetti.
- In condizioni estreme si effettua un **Body Save ogni ora**; in caso di fallimento il personaggio subisce gli effetti di freddo o caldo estremo.

| Condizione | Regola |
|---|---|
| **Extreme Cold** | Sotto zero, senza abbigliamento adeguato, ipotermia e congelamento insorgono in 10–30 minuti. L'ipotermia uccide in un intervallo tra 30 minuti e 6 ore. Per sopravvivere occorre riportare il corpo a temperatura normale. |
| **Extreme Heat** | Oltre 40 °C (100 °F) il colpo di calore uccide in poche ore. La vittima deve spostarsi immediatamente in un luogo più fresco. |

## Overdose

Assumere più di uno Stimpak (o altra droga pericolosa) in un giorno: si tira `1d10`; se il risultato è inferiore al numero di dosi assunte nelle ultime 24 ore, [Death Save](../03_violenza/ferite_morte.md#death-save).
