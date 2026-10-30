---
tags:
  - creature
  - warden
---

# Regole generali delle creature

Le creature (horror) sono definite da uno Stat Block sintetico. I valori sono linee guida: il Warden li interpreta e li adatta durante il gioco.

## Formato dello Stat Block

Formato standard:

`[C:XX Attacco XdX DMG o Special Ability I:XX AP:XX W:XX(XX)]`

| Voce | Significato |
|---|---|
| Name | Nome con cui l'entità è identificata. Può essere ignoto ai personaggi. |
| Combat (C) | Capacità della creatura di combattere e difendersi. |
| Attack | Nome dell'arma o dell'attacco seguito dal Damage (DMG). |
| Instinct (I) | Valore unico per ogni Stat o Save non specificato. |
| Armor Points (AP) | Armatura della creatura. |
| Maximum Wounds (W) | Numero di Wound che uccidono la creatura; tra parentesi la Health. |
| Special Ability | Capacità con effetto meccanico (Save, Stress, infezioni, ecc.). |

### Combat e Attack

- Una creatura può avere più attacchi o nessuno.
- L'assenza di un attacco elencato non significa che la creatura non possa attaccare: indica solo che l'attacco non richiede una definizione specifica.
- "As Weapon": la creatura usa un'arma; il DMG è quello dell'arma ([Armi e armature](../01_personaggio/armi_armature.md)).

### Instinct

- Instinct sostituisce ogni Stat o Save non indicato.
- Esempio di regola: una creatura con Instinct 65 e nessun'altra Stat ha Combat 65, Speed 65, Intellect 65, Body Save 65, ecc.

### Armor Points

- Gli AP funzionano come per i personaggi ([Attacco e danno](../03_violenza/attacco_danno.md)).
- Possono rappresentare armatura naturale, resistenza o altre capacità.

### Maximum Wounds e Health

- Quando la creatura subisce il numero di Wound pari a Maximum Wounds, muore.
- La Health è indicata tra parentesi: `W:3(30)` = 3 Wound, 30 Health per Wound.
- Se non è indicata Health, qualsiasi danno infligge un Wound.
- Ogni volta che subisce un Wound, la creatura cambia tattica o comportamento.
- Regole di Wound: [Ferite e morte](../03_violenza/ferite_morte.md).

### Special Ability

- Le Special Ability elencate hanno effetto meccanico esplicito.
- Le creature possono avere capacità non elencate; il Warden le definisce quando necessario.

### Entità di scala navale

Alcune entità usano le statistiche delle navi: classe (es. `J1C-II`), Thrusters (THR), Battle (BTL), Systems (SYS), Crew, Hull e Megadamage (MDMG). Si risolvono con le regole delle navi dello Shipbreaker's Toolkit.

## Five Quick Horrors

Modelli di base per creare rapidamente una creatura. Tirare 1d10 o scegliere.

| 1d10 | Modello | Stat Block | Funzione |
|---|---|---|---|
| 0 | Anomaly | `[3d10 DMG I:75]` | Non danneggiabile con armi convenzionali, o troppo astratta per essere attaccata. Va evitata, intrappolata o soddisfatta; non sconfitta. |
| 1–2 | Brute | `[C:65 4d10 DMG I:35 AP:10 W:3(40)]` | Grande e resistente. Va ingannata o logorata in più incontri. |
| 3–5 | Guard | `[C:35 2d10 DMG I:25 W:2(10)]` | Nemico comune, armato, in piccoli gruppi. Può chiamare rinforzi. |
| 6–7 | Hunter | `[C:75 3d10 DMG I:65 AP:5 W:2(30)]` | Solitario, preferisce furtività e imboscate. Elimina i personaggi uno alla volta. |
| 8–9 | Swarm | `[C:25 1d10 DMG I:25 W:1(X)]` | X = numero di individui nel gruppo. Ogni individuo cade con un colpo; il gruppo riceve rinforzi continui. |

Procedura d'uso:

1. **Anomaly**: stabilire cosa vuole l'entità; costruire l'incontro sull'evitarla o soddisfarla.
2. **Brute**: mostrare in anticipo la distruzione che causa; lasciare vie di fuga e prevedere incontri ripetuti.
3. **Guard**: segnalarne la presenza prima dell'incontro; devono essere evitabili.
4. **Hunter**: collocarlo in zone con scarsa visibilità o udibilità; può lasciare una scia di cadaveri che ne annuncia l'arrivo.
5. **Swarm**: l'obiettivo dei personaggi è la fuga.

## Tabella riepilogativa

| Entità | Stat Block | Pagina |
|---|---|---|
| 4YOUREYEZ Algorithm | 1% di probabilità che qualsiasi dispositivo elettronico (Android inclusi) sia infetto | [Infezioni](infezioni.md#4youreyez-algorithm) |
| Angels | C:100 Trumpets: Sanity Save [-] o in ginocchio piangendo; I:95; Panic Check alla vista | [Mostri](mostri.md#angels) |
| Belladonnas | C:75 Talons 4d10 DMG; I:75 AP:10 W:3(30); Tail Poison | [Mostri](mostri.md#belladonnas) |
| The Body Politic | C:40 Organic Diplomatic Mission 3d10 DMG; I:20 W:1(10) | [Infezioni](infezioni.md#the-body-politic) |
| The Brown Stream | Nessuno Stat Block | [Anomalie](anomalie.md#the-brown-stream) |
| C-Levels | C:15 Unarmed; I:45 W:1 | [Umanoidi](umanoidi.md#c-levels) |
| Cabin 102-B | Sanity Save per ogni ora all'interno | [Anomalie](anomalie.md#cabin-102-b) |
| Chronopods | I:95 AP:30 W:5(100); Sanity Save al posto di Combat | [Mostri](mostri.md#chronopods) |
| Demons | C:65 Attack 3d10 DMG; I:75 AP:5 W:5(100); Whisper | [Mostri](mostri.md#demons) |
| Dorians | C:20 Tiny Fists 1d5 DMG; I:30 AP:5 W:2(45); Psionic Wave of Mutilation | [Umanoidi](umanoidi.md#dorians) |
| The Drowning | C:15 Unarmed; I:25 W:1(1); 10% di teletrasporto e resurrezione alla morte | [Umanoidi](umanoidi.md#the-drowning) |
| The Engineer | C:65 Wrench 2d10 DMG; I:75 AP:1 W:3(20) | [Umanoidi](umanoidi.md#the-engineer) |
| Entity LKA-5 | C:65 Appendage 3d10 DMG; I:35 AP:10 W:3(50); Consume | [Mostri](mostri.md#entity-lka-5) |
| Family Meal No. 5 | +1 Minimum Stress a ogni visione | [Anomalie](anomalie.md#family-meal-no-5) |
| Freighter 54 | J1C-II THR:25 BTL:20 SYS:20 CREW:12; -1d5 Sanity Save a ogni abbordaggio | [Navi e colossi](navi_colossi.md#freighter-54) |
| Good | C:0 I:— W:— | [Anomalie](anomalie.md#good) |
| Ghouls | C:45 Improvised Weapons 1d10 DMG; I:75 W:2(10) | [Umanoidi](umanoidi.md#ghouls) |
| Granny | C:40 Bite 2d10 DMG; I:65 W:5(30) | [Mostri](mostri.md#granny) |
| Greys | C:35 Beam Weapon 5d10 DMG; I:65 W:2(10); Radiation Level 2 | [Umanoidi](umanoidi.md#greys) |
| Hatchetman | C:90 Scythe 1d100 DMG o Heavy Gun 5d10 DMG; I:65 AP:15 W:5(30) | [Umanoidi](umanoidi.md#hatchetman) |
| Headjackers | C:45 I:15 W:1(5); Infect | [Infezioni](infezioni.md#headjackers) |
| Husks | C:35 Unarmed 2d10 DMG; I:25 W:1(20); Howl | [Infezioni](infezioni.md#husks) |
| Hyperspace Raiders | C:55 Pulse Rifle 3d10 DMG; I:55 AP:5 W:2(10); teletrasporto Close Range | [Umanoidi](umanoidi.md#hyperspace-raiders) |
| Incubus | C:95 Claws 3d10 DMG; I:75 AP:10 W:3(30); Acid Blood | [Infezioni](infezioni.md#incubus) |
| Little Gods | I:85; Bend Reality | [Mostri](mostri.md#little-gods) |
| Mother | Genera un Succubus in 1d10 ore | [Mostri](mostri.md#mother) |
| Monolith | Alla prima interazione, 50%: Stat/Save casuale ±1d10 | [Anomalie](anomalie.md#monolith) |
| Nomads | J1C-III THR:20 BTL:55 1d10 MDMG SYS:5 HULL:2 | [Navi e colossi](navi_colossi.md#nomads) |
| Noöcentric Transmission | Sanity Save per resistere | [Anomalie](anomalie.md#noocentric-transmission) |
| Omnivore | C:85 Ritual Claws 3d10 DMG o Plasma Rifle 2d100 DMG; I:65 AP:7 W:3(40) | [Umanoidi](umanoidi.md#omnivore) |
| Ooidopolis Picocivilization | 1d10 MDMG; I:80 W:100(1.000) | [Navi e colossi](navi_colossi.md#ooidopolis-picocivilization) |
| Possessed | C:55 I:45; Possess | [Infezioni](infezioni.md#possessed) |
| Pure Love | C:15 Unrelenting Hug 0 DMG; I:25 W:1 | [Umanoidi](umanoidi.md#pure-love) |
| Root Language | Minimum Stress +1; regole di censura lessicale | [Infezioni](infezioni.md#root-language) |
| SS High Gold | J5C-III THR:45 BTL:50 1d10+1 MDMG SYS:60 CREW:89 | [Navi e colossi](navi_colossi.md#ss-high-gold) |
| The Sea of Silence | I:90 | [Infezioni](infezioni.md#the-sea-of-silence) |
| Sally in the Screen | C:45 3d10 DMG; I:55; immune alle armi | [Anomalie](anomalie.md#sally-in-the-screen) |
| Spore Clouds | I:35; Body Save o infezione (3d10 giorni) | [Infezioni](infezioni.md#spore-clouds) |
| The Stain | C:25 Pseudopod 2d10 DMG; I:20 W:X(200) | [Mostri](mostri.md#the-stain) |
| Star Shades | Light 2d100 DMG; I:75 W:5(50); danneggiabili solo da laser cutter | [Mostri](mostri.md#star-shades) |
| Stickmen | C:35 Grasp 3d10 DMG; I:25 W:2(10) | [Mostri](mostri.md#stickmen) |
| Succubus | C:65 Unarmed 3d10 DMG; I:65 AP:5 W:3(30) | [Umanoidi](umanoidi.md#succubus) |
| Throat Leeches | C:15 Bite 1d10 DMG; I:10 W:1(10); infezione | [Infezioni](infezioni.md#throat-leeches) |
| Unpersons | C:35 I:45 W:2(10); invisibili | [Umanoidi](umanoidi.md#unpersons) |
| Vitalizing Field | Emitter 1/3/5d10 DMG; I:15/45/75 AP:0/3/10 W:1/3/5(10/20/50) | [Mostri](mostri.md#vitalizing-field) |
| Whitevine | C:45 Vine 2d10 DMG; I:15 W:X(20); Strangulation | [Mostri](mostri.md#whitevine) |
| Womb | 1% di gravidanza a ogni manipolazione | [Anomalie](anomalie.md#womb) |
| The World Worm | J9C-X THR:20 BTL:65 2d10 MDMG SYS:5 HULL:3 | [Navi e colossi](navi_colossi.md#the-world-worm) |
| You | Stat del personaggio | [Umanoidi](umanoidi.md#you) |
| Zombies | C:25 Bite 1d10 DMG; I:10 W:1(10); Infectious Bite | [Infezioni](infezioni.md#zombies) |
