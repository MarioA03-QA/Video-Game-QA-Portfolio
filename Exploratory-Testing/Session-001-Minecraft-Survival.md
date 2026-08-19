# SESSION-001 — Minecraft Survival Gameplay Exploration

## Game

Minecraft

## Platform

PlayStation 5

## Game Version

1.21.132

## Testing Session

### Duration

60 minutes

### Test Area

Survival Mode

### Testing Objective

Explore Minecraft's survival gameplay with a focus on item interaction, crafting, environmental interaction, inventory behaviour, and unexpected gameplay behaviour.



## Testing Approach

The session was carried out using the method of exploratory testing, rather than predetermined test cases, for 60 timed minutes.

The testing focused on interacting with various intended game mechanics, whilst looking out for unintended, unexpecteded and inconsistent behaviours 

The following areas were explored:

- Inventory management
- Item collection
- Combat
- Crafting
- Environmental interactions
- NPC Interactions
- Player movement
- Survival mechanics
- World loading



## Exploration Log

### Exploration 1 — Item Collection

**Action:**

Collected wood from several trees and observed the player's inventory.

**Observation:**

Upon striking the trees, the wood log item dropped to the ground and entered the player's inventory upon walking in the item's collection range as expected.

**Result:**

Normal Behaviour



### Exploration 2 — Inventory Interaction

**Action:**

Moved items between inventory slots and attempted to reorganise the inventory.

**Observation:**

When enough inventory space is availble, items moved to the selected inventory slot, and items of the same type combined into a single stack in the inventory as expected.
Items dropped were not picked up in the inventory if there was not enough space in the inventory as expected.

**Result:**

Normal Behaviour



### Exploration 3 — Crafting

**Action:**

Opened the crafting interface and attempted to create several available items.

**Observation:**

Available crafting recipes successfully produced their intended items. For example, a single wooden log item converted into a wooden plank item and a single wooden plank items could be used to craft a sitck item.

**Result:**

Normal Behaviour



### Exploration 4 — Environmental Interaction

**Action:**

Interacted with different blocks and environmental objects.

**Observation:**

Striking a cobblestone block with the player character's hand resulted in no item drop, as an expected game mechanic reflecting the need of tools. 
Striking and destroying blocks of sand resulted in the sand blocks above it to fall down. Striking and destroying grass blocks resulted in recieving soil block item rather than the grass block item.

**Result:**

Normal Behaviour



### Exploration 5 — Combat

**Action:**

Engage hostile mobs using available weapons and observe combat interactions, including attacking, taking damage, enemy reactions, and defeating enemies.

**Observation:**

Enemy mobs become hostile and engage in combat upon approaching them. They take damage upon striking them with either the player character's hand, weapon, tool, item or block, and react appropriately by being pushed back and flashing red to indicate that they have taken damage. 
Defeating enemies results in occasional item drops relative to the type of mob defeated and experience point orbs being dropped per each defeat.

**Result:**

Normal Behaviour



### Exploration 6 — NPC Interactions

**Action:**

Approach and interact with NPCs encountered during the session. Observe available interactions, trading, and NPC reactions to the player's actions.

**Observation:**

Interactable NPC characters are made up of Villagers or Wandering Traders. Each villager can trade items depending on the villager's profession and react accordingly when being hit by the player by becoming agitated and making appropriate sounds.

**Result:**

Normal Behaviour



### Exploration 7 — Player Movement

**Action:**

Test the player's movement across different environments, including walking, sprinting, jumping, swimming, climbing, and moving across uneven terrain.

**Observation:**

Player character's movement responds correctly to directional inputs including moving forwards, backwards, left and right successfully without any unexpected behaviours. 
Sprinting only works when moving forwards, jumping, swimming and climbing as intnded. Jumping works as intended by using the appropriate input.
Swimming works as intended in any body of water deep enough to support swimming. Climbing ladders also works as intended with no unexpected behaviour. 
Moving forward on uneven terrain leading upwards is impossible without jumping and therefore consistent with the intended game mechanics.

**Result:**

Normal Behaviour



### Exploration 8 — Survival Mechanics

**Action:**

Explore Minecraft's survival mechanics by monitoring health, hunger, damage, environmental hazards, and the effects of consuming food or taking damage.

**Observation:**

The player's health gets depleted upon taking various sorts of damage such as suffocating under water, being hit by an enemy mob, making contact with fire or falling from a high place.
Health can also be refilled by maintaining the hunger bar or consuming certain items such as a golden apple. The hunger bar depletes if eating is neglected, eventually causing damage.


**Result:**

Normal Behaviour



### Exploration 9 — World Loading

**Action:**

Exited the world and reloaded the save.

**Observation:**

Exiting and rentering the world loads the palyer into the last automatically saved world state. 
Saving and exiting the world returns the player to the location and world state present at the time of the save when the player loads back into the world.
No loss of player or world progress occured during the manual save and exit test.
Slight loss of player and world progress occured during the atomatic save and exit test.

**Result:**

Normal Behaviour



## Issues Identified

No unexpected behaviours were identified during this exploratory testing session wuth tested gameplay mechanics, such as item collection, crafting, inventory interaction, combat, and player movement.
The observed behaviour was consistent with the expected gameplay behaviour during the session.
No unexpected behaviour was observed that justify a bug report.
