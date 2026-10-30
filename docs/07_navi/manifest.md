---
tags:
  - navi
  - ship manifest
---

# Ship Manifest

Il Ship Manifest è la scheda della nave. Registra Stat, risorse, danni, equipaggio, Upgrade, carico e Repair della nave.

## Campi del Ship Manifest

| Campo | Contenuto | Regole |
|---|---|---|
| Ship Identifier | Nome della nave. | — |
| Captain | Nome del capitano. | — |
| Make / Model / Jump / Class / Type | Produttore, modello, Jump Rating, Class, tipo (es. Valecore T9LC, J1C-II, Freighter). | [Statistiche](statistiche.md) |
| Transponder (ON/OFF) | Stato del Transponder. | [Rilevamento e comunicazioni](rilevamento_comunicazioni.md) |
| Stats & Saves | Thrusters, Battle, Systems. Per Battle si annotano valore Base e Total. | [Statistiche](statistiche.md) |
| Fuel | Fuel attuale e massimo. | [Viaggi spaziali](viaggi_spaziali.md) |
| Warp Cores | Numero di Warp Core a bordo. | [Viaggi spaziali](viaggi_spaziali.md) |
| Weapons | Armi installate e relativo bonus a Battle. | [Armi](armi.md) |
| Megadamage | Tracciato dell'MDMG accumulata (01–09+), con valore Base e Total dell'MDMG inflitta. | [Combattimento](combattimento.md) |
| Hull Points | Hull attuale. | [Combattimento](combattimento.md) |
| Hardpoints | Hardpoint installati / massimi. | [Armi](armi.md) |
| Upgrades | Upgrade installati / massimi. | [Upgrade](potenziamenti.md) |
| Crew | Equipaggio attuale / Crew Capacity massima; elenco dei membri. | — |
| Cryopods, Escape Pods | Numero di Cryopod e di Escape Pod. | — |
| O2 Remaining | Ossigeno residuo in caso di guasto del supporto vitale. | [Ambiente](../04_sopravvivenza/ambiente.md) |
| Deckplan | Mappa della nave: diagramma di flusso o elenco dei moduli. | — |
| Cargo | Carico rilevante a bordo. | — |
| Repairs (Minor / Major) | Problemi di manutenzione in corso. | [Riparazioni](riparazioni.md) |

## Effetti di Megadamage sul Manifest

| MDMG | Effetto |
|---|---|
| 01 | **Emergency Fuel Leak.** Ogni spesa di Fuel costa 1 Fuel in più. |
| 02 | **Weapons Offline.** I Battle Check falliscono automaticamente. |
| 03 | **Navigation Offline.** Impossibile effettuare Thrusters Check. 10% di probabilità che tutti i dati di navigazione vengano cancellati. |
| 04 | **Fire on Deck.** L'incendio si propaga nell'interno della nave. Atmosfera tossica e corrosiva (10 DMG/round). |
| 05 | **Hull Breach.** Tutti a bordo effettuano un Body Save o subiscono 1 Wound (Explosion). Critical Failure: espulsione nello spazio. |
| 06 | **Life Support Systems Offline.** Ossigeno limitato a 1d10 × Crew Capacity. |
| 07 | **Radiation Leak.** Il Radiation Level aumenta ogni 2d10 minuti. |
| 08 | **Dead in the Water.** Tutti i sistemi offline, solo alimentazione di emergenza. |
| 09+ | **Abandon Ship!** La nave è distrutta in 1d10 minuti. |

La tabella completa e le regole di applicazione sono in [Combattimento tra navi](combattimento.md#megadamage).

## Moduli del Deckplan

Icone standard per i moduli del Deckplan:

Airlock, Cabin, Cargo, Command, Comms, Computer, Cryo, Docking, Door, Duct Access, Galley, Gravity, Hangar, Hardpoint, Jump Drive, Ladderway, Life Support, Maint., Medbay, Power, Scanners, Science Lab, Terminal, Unpressurized Area.

## Assegnazione della nave

- Le navi non si costruiscono come i personaggi. Il Warden assegna ai personaggi una nave predefinita, scelta tra i [tipi di nave](tipi_di_nave.md).
- Alla nave acquisita si applicano le Repair iniziali (vedi [Condizione iniziale](riparazioni.md#condizione-iniziale)).
- La nave può essere modificata in seguito tramite [Upgrade](potenziamenti.md) e [Armi](armi.md).
- La tenuta dettagliata dei registri è facoltativa.
