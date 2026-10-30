---
tags:
  - violenza
  - attacco
  - armor
  - cover
---

# Attacco e Damage

## Attacco

1. Si effettua un **Combat Check** (con l'eventuale Skill pertinente, es. Firearms o Hand-to-Hand Combat).
2. **Successo**: si tira il Damage dell'arma e lo si sottrae alla Health del bersaglio, dopo Damage Reduction, Armor e Cover.
3. **Fallimento**: la situazione peggiora (a discrezione del Warden) e l'attaccante guadagna 1 Stress.

Statistiche delle armi: [Armi e armature](../01_personaggio/armi_armature.md).

## Damage

1. Il Damage (DMG) si sottrae alla Health.
2. Se la Health arriva a zero, il personaggio subisce **1 Wound** e tira sulla [Wounds Table](ferite_morte.md#wounds-table).
3. La Health torna al massimo, meno il danno in eccesso (carryover).
4. Quando il numero di Wounds raggiunge il Maximum Wounds, il personaggio effettua un [Death Save](ferite_morte.md#death-save).

Alcuni attacchi infliggono Wounds direttamente, ignorando Armor e Damage Reduction.

## Armor

Ordine di applicazione: **Damage Reduction → Armor Points → Health**.

| Regola | Effetto |
|---|---|
| **Damage Reduction (DR)** | Riduce sempre il Damage ricevuto del valore indicato. Si applica per prima, anche se l'armatura è distrutta e anche contro armi Anti-Armor. |
| **Armor Points (AP)** | Il Damage di un singolo colpo **inferiore** all'AP viene ignorato. |
| Distruzione | Se un singolo colpo infligge Damage **maggiore o uguale** all'AP, l'armatura è distrutta e il personaggio subisce il Damage restante (Damage − AP). |
| **Anti-Armor (AA)** | Un'arma AA che colpisce ignora l'armatura e la distrugge. |

## Cover

L'ambiente può fornire protezione (**Cover**). Il Cover funziona come un'armatura: il Damage inferiore al suo AP è ignorato; un colpo con Damage maggiore o uguale al suo AP lo distrugge. AP di armatura e Cover si sommano.

| Cover | Esempi | Valore |
|---|---|---|
| Insignificant Cover | Mobili e porte in legno, scudi corporei | AP 5 |
| Light Cover | Alberi, paratie, mobili in metallo | AP 10 |
| Heavy Cover | Porte di airlock, travi in cemento, navi | AP 20, DR 5 |

- Il Cover protegge di norma solo dagli attacchi a distanza; in alcune situazioni può bloccare un attacco corpo a corpo.
- Chi spara da una posizione di Cover è considerato fuori dal Cover fino al proprio turno successivo.
