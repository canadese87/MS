---
tags:
  - regole base
  - stat check
  - save
---

# Stat Check e Save

Entrambi si risolvono tirando `1d100` contro un valore bersaglio. Il tiro riesce se è **strettamente inferiore** al valore.

## Stat Check

Si effettua quando il personaggio vuole compiere un'azione il cui fallimento ha un costo elevato.

1. Il Warden indica la Stat pertinente e le conseguenze del fallimento.
2. Si aggiunge l'eventuale Skill Bonus pertinente alla Stat.
3. Si tira `1d100`.
4. **Successo**: risultato < Stat (+ Skill).
5. **Fallimento**: risultato ≥ Stat (+ Skill). Il personaggio guadagna 1 Stress.
6. Un risultato tra **90 e 99** è sempre un fallimento.

### Le quattro Stat

| Stat | Ambito |
|---|---|
| **Strength** | Forza fisica: tenere chiusa una porta, trasportare un compagno, arrampicarsi, spingere, saltare. |
| **Speed** | Rapidità: agire prima di qualcun altro, superare un passaggio prima che si chiuda, fuggire. |
| **Intellect** | Applicare addestramento ed esperienza sotto pressione, risolvere problemi complessi, inventare o riparare. |
| **Combat** | Combattere. |

## Save

Si effettua come reazione per evitare un pericolo o un trauma.

1. Il Warden indica il Save pertinente.
2. Si aggiunge l'eventuale Skill Bonus pertinente.
3. Si tira `1d100`.
4. **Successo**: risultato < Save (+ Skill).
5. **Fallimento**: risultato ≥ Save (+ Skill). Il personaggio guadagna 1 Stress.
6. Un risultato tra **90 e 99** è sempre un fallimento.

### I tre Save

| Save | Ambito |
|---|---|
| **Sanity** | Razionalizzare incoerenze logiche, dare senso al caos, riconoscere illusioni e imitazioni, gestire lo Stress. |
| **Fear** | Mantenere il controllo di fronte a paura, solitudine, depressione e altre ondate emotive. |
| **Body** | Riflessi rapidi; resistere a fame, malattie e organismi che tentano di invadere il corpo. |

## Modificatori

Tre elementi modificano Stat Check e Save: Advantage/Disadvantage, Critical, Skill.

### Advantage e Disadvantage

- Si applicano a **qualsiasi tiro**: Stat Check, Save, Panic Check, Damage, ecc.
- **Advantage `[+]`**: per un vantaggio situazionale (es. assistenza di un altro personaggio, strumento adatto) si tira due volte e si tiene il risultato **migliore**.
- **Disadvantage `[-]`**: per uno svantaggio situazionale (es. maltempo, scarsa visibilità) si tira due volte e si tiene il risultato **peggiore**.
- Notazione: `Body Save [+]` = Body Save con Advantage.
- Advantage e Disadvantage contemporanei si annullano.

### Critical

- Un risultato con due cifre uguali (`00`, `11`, `22` … `99`) su uno Stat Check o un Save è un **Critical**.
- **Critical Success**: il Critical è anche un successo. L'esito è molto favorevole.
- **Critical Failure**: il Critical è anche un fallimento. L'esito è molto sfavorevole e il personaggio deve effettuare un [Panic Check](panico.md).
- `00` è sempre un Critical Success. `99` è sempre un Critical Failure.
- Con Advantage o Disadvantage si valuta il Critical sul risultato tenuto.

### Skill

Se il personaggio possiede una Skill pertinente al compito, ne somma lo Skill Bonus alla Stat o al Save prima del tiro.

| Livello | Bonus |
|---|---|
| Nessuna Skill | +0 (il Warden può imporre `[-]` o vietare il tentativo per compiti complessi) |
| Trained | +10 |
| Expert | +15 |
| Master | +20 |

Vedi [Skill](../01_personaggio/skill.md).
