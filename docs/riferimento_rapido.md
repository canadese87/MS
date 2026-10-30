---
tags:
  - riferimento
---

# Riferimento rapido

## Tiri

| Tiro | Dado | Successo | Fallimento |
|---|---|---|---|
| Stat Check | `1d100` | < Stat (+ Skill) | +1 Stress |
| Save | `1d100` | < Save (+ Skill) | +1 Stress |
| Panic Check | `1d20` | > Stress attuale | Panic Table |

- 90–99 su `1d100`: sempre fallimento.
- Cifre uguali su `1d100`: Critical. `00` sempre Critical Success, `99` sempre Critical Failure.
- Critical Failure: Panic Check.
- `[+]`: tira due volte, tieni il migliore. `[-]`: tira due volte, tieni il peggiore. Si annullano a vicenda.
- Skill: Trained +10, Expert +15, Master +20.

Dettagli: [Stat Check e Save](02_regole/check_e_save.md), [Panic](02_regole/panico.md).

## Stress

- Iniziale 2, Minimum 2, massimo 20. Oltre 20: −1 alla Stat o al Save più pertinente per ogni punto.
- **Rest Save** (Save più basso): successo = −Stress pari alla cifra delle unità; fallimento = +1 Stress.

## Violenza

- Round ≈ 10 secondi. Movimento entro Close Range + 1 azione, oppure solo corsa entro Long Range.
- Sorpresa: Fear Save o nessuna azione fino al round successivo.
- Attacco: Combat Check; successo = Damage dell'arma; fallimento = +1 Stress.
- Damage: DR → AP (armatura + Cover) → Health. Damage ≥ AP distrugge l'armatura/Cover. AA ignora e distrugge l'armatura.
- Health a 0: +1 Wound, tiro sulla Wounds Table, Health al massimo meno l'eccesso.
- Wounds = Maximum Wounds: Death Save.
- Bleeding: 1 DMG per round per punto, ignora AP e DR.

Dettagli: [Il round](03_violenza/round.md), [Attacco e Damage](03_violenza/attacco_danno.md), [Wounds e morte](03_violenza/ferite_morte.md).

## Range

| Adjacent | Close | Long | Extreme |
|---|---|---|---|
| < 1 m | 5–10 m | 20–100 m | > 100 m |
| Può toccarti | Può raggiungerti | Puoi sparargli | Puoi sentirlo urlare |

## Cover

| Insignificant | Light | Heavy |
|---|---|---|
| AP 5 | AP 10 | AP 20, DR 5 |

## Recupero

- Riposo 6+ ore (1/giorno): Body Save, successo = Health al massimo.
- Wounds, Condition, Stat e Save: [Cure mediche](04_sopravvivenza/cure_mediche.md).
- Stress in Save: [Shore Leave](05_porti/porti_shore_leave.md).
