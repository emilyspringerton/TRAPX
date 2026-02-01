# TRAPX

TRAPX v1 — BLOCK ZERO
Acceptance Criteria (Frozen)
Product Definition

TRAPX v1 is a single-player systemic urban simulation where the player influences a neighborhood using a deck of operations, observing emergent outcomes over time through indirect control.

There is no avatar, no direct unit control, and no win condition in v1.

1. World & Scale

The game simulates exactly one neighborhood

Neighborhood is represented as a grid (10×10 or 12×12)

Each grid cell represents a city block

All cells are visible at all times

Camera is fixed orthographic / isometric

No camera rotation

Each cell must track:

alignment (Neutral / Player / Rival / Institutional)

pressure (signed influence value)

stability (0.0 – 1.0)

population (0–255)

2. Time & Simulation

Simulation advances in fixed ticks (e.g. every 2 seconds)

The simulation continues even if the player does nothing

Cell state changes must be rule-driven, not scripted

Local rules produce global outcomes (cellular automata behavior)

There is no pause-based planning mode.
Time pressure is part of the experience.

3. Player Interaction Model

Player interacts only via cards (operations)

Player cannot:

move characters

select individuals

issue direct commands

Player places pressure, not people

The player’s role is systemic intervention, not embodiment.

4. Deck System (v1)

Player has a hand of exactly 5 cards

Cards have:

cost

cooldown

valid placement rules

Cards are placed on grid cells via mouse interaction

Placement shows:

ghost preview

valid / invalid feedback

Cards trigger systemic effects, not instant outcomes

No card upgrades, combinations, or inventory systems in v1.

5. Progression & Outcomes

There is no victory screen

The game ends only if:

the neighborhood collapses into instability

or the player chooses to exit

Success is measured implicitly:

duration of stability

containment of pressure

resilience against institutional force

6. Observability

All key state changes must be visible:

color

intensity

animation

The player must be able to understand why something happened after the fact

No hidden dice rolls.
No opaque modifiers.

7. Explicit Non-Goals (v1)

Multiplayer

Roleplay

Narrative quests

Dialog

Characters with inventories

Driving / traversal

Combat simulation

Backpack-style inventory systems

These are not promised and not implied.

Red Garden → TRAPX Concept Mapping
Red Garden Term	TRAPX Term	Meaning
Grid Cell	City Block	Smallest unit of simulation
Player Alignment	Player Influence	Your organization’s reach
Enemy Alignment	Rival Influence	Competing groups
Corrupted	Institutional Pressure	Police, federal, regulatory force
Population	Activity	Foot traffic / economic energy
Stability	Community Cohesion	Resistance to collapse
Outpost	Operation Hub	Persistent pressure source
Militia	Street Presence	Informal enforcement
Influence	Capital / Reach	Resource spent to act

No mechanical changes implied — semantic only.

First 5 Operation Cards (v1)
1️⃣ Outreach

Cost: Low

Cooldown: Short

Effect:

Increases stability

Slightly increases player pressure

Use Case:

Prevent collapse

Build slow influence

2️⃣ Investment

Cost: Medium

Cooldown: Medium

Effect:

Increases population growth

Slight stability boost

Risk:

Raises institutional visibility over time

3️⃣ Enforcement

Cost: Medium

Cooldown: Medium

Effect:

Reduces rival pressure

Decreases local stability

Use Case:

Short-term control

4️⃣ Logistics

Cost: Low

Cooldown: Long

Effect:

Increases spread rate of player pressure to neighbors

Risk:

Makes patterns easier to detect

5️⃣ Suppression

Cost: High

Cooldown: Long

Effect:

Reduces institutional pressure temporarily

Risk:

Severe backlash later if overused

Pre-Simulation Seed (Critical for “Living World” Feel)

Before the player begins:

Run N simulation ticks (e.g. 50–100)

Randomly seed:

rival clusters

institutional hot zones

unstable blocks

Allow:

conversions

collapses

population drift

When the player starts:

The neighborhood is already in motion

No two starts feel the same

The player is entering a situation, not creating one

README — Required Language (Exact)

Progression systems in TRAPX are experimental and evolving.

The current version focuses on systemic simulation and indirect control.
Interfaces, progression models, and long-term structures may change as the simulation matures.

No roadmap promises are implied.

Final Lock Statement

TRAPX v1 is frozen as a single-neighborhood systemic simulation with a card-based intervention interface.

Anything not explicitly listed above is out of scope.


TRAPX factions are fictional systems inspired by historical dynamics.
They do not represent real ethnic, religious, or cultural groups.
