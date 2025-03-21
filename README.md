# Tower Defense Game - Design Document

## Overview
This is an isometric tower defense game with a mix of magic and mechanics. The game features a single round wizard tower that players must defend against waves of cute but demonic enemies. The gameplay consists of two phases: the planning phase, where players configure magical modules in a grid to modify tower behavior, and the evaluation phase, where waves of enemies attack, and the tower executes its predefined defenses. 

## World and Setting
- Bright fantasy world with grassy fields and magical landscapes.
- The wizard's tower is built of stone, with a magical engine at its base that eventually lifts it into the sky.
- The land is divided into a grid where modules can be placed, connecting to the tower via magical pipelines.
- Players gather elemental resources from the environment (e.g., burning trees for fire, collecting water from rivers, mining minerals).
- Enemies build bridges, fortifications, and even bases to strengthen their attacks.

## Core Mechanics
### Phases of Each Level
1. **Planning Phase**
   - Players place magical modules on a grid connected to the tower.
   - Modules process signals and elements to control fire rate, shape, and element type of the tower’s attacks.
   - Players configure how resources flow into the tower (e.g., fire from burning trees, water from rivers, mined minerals).
   - (Test runs are possible to see module interactions before committing.)

2. **Evaluation Phase**
   - Enemies attack in waves based on pre-set conditions.
   - The tower executes its planned attacks.
   - Players can cast spells, slow down or speed up time, and react to environmental changes.
   - If fire spreads uncontrollably, it may destroy resources or create hazards.
   - Water can form barriers but also aid certain enemy types.
   - Some enemies are immune to certain elements or use the environment strategically (e.g., ice monsters freezing ponds, enemies building over obstacles).
   - Spells can be used to influence battle outcomes, such as extinguishing fires, freezing enemies, or redirecting elemental flows.
   - Players have full control over game speed, allowing for slow-motion strategic play or fast-forwarding through less intense moments.

3. **Post-Wave Phase**
   - Rewards are given based on performance.
   - The world map opens, allowing progression choices.
   - Shops and upgrade stations become available for purchasing new modules and tower enhancements.

## World Map and Progression
- The game features a world map where players choose levels to tackle.
- Between levels, players can visit shops to buy modules and upgrade the tower.
- Some levels contain unique environmental challenges, requiring adaptation.
- Completing key levels unlocks new abilities and resources.
- Some enemy bases persist across levels, influencing future battles.

## Modules and Signals
- **Elemental Deliverers:** Transport elements (fire, water, earth, air) into the tower.
- **Signal Processors:** Modify timing and targeting logic.
- **Elemental Combiners:** Merge elements for advanced effects (e.g., water + ice = freezing attack).
- **Storage Modules:** Hold elements and release them based on conditions.
- **Converters:** Change one element into another through processing (e.g., cooling water into ice).

## Environmental Interactions
- **Fire:** Can spread, destroy forests, and modify terrain.
- **Water:** Can create barriers but be manipulated by enemies.
- **Ice:** Can be formed and used for attacks but melts over time.
- **Enemy Construction:** Some enemies reinforce their positions, build bridges, and establish bases.
- **Resource Availability:** Elemental resources are dynamic, influenced by both player and enemy actions.

## Story
- One day, the wizard wakes up and sees a horde of demons coming towards his tower from mysterious portals. He quickly decides to fire up the tower’s engines and escape. While the tower is preparing for flight, the player must defend it from incoming enemy waves.
- After the first battle, the wizard attempts to use his crystal ball to uncover the identity of his attackers. However, his magic backfires, summoning even more portals and enemies.
- Realizing he needs more power, the wizard embarks on a journey to collect new input controls and modules to enhance his tower’s capabilities.
- Throughout his quest, he uncovers new elemental sources, learns to harness them, and faces increasingly difficult challenges. Each time a new input control or module is introduced, a tutorial mission is played to showcase its function.
- Once his tower is sufficiently powered, the wizard sets out to retrieve a powerful artifact that will reveal the identity of his nemesis.
- Upon retrieving the artifact, the wizard learns who is behind the attacks. However, to confront them, he must first activate ancient elemental energy stones, leading to additional battles centered around mastering elemental forces.
- With the energy stones activated, the final world becomes accessible. The wizard embarks on a final series of missions, culminating in an epic showdown with his ultimate foe.


## Strategy and Playstyle
- Deep elemental system with synergies and feedback loops.
- Adapting to enemy tactics by controlling environmental factors.
- Balancing offense (attacks) with resource management (gathering and storage).
- Experimenting with different module configurations to create unique defenses.
