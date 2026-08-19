# SESSION-003 — Silent Hill 2 Remake Gameplay & Environmental Exploration

## Game

Silent Hill 2 Remake

## Platform

PlayStation 5

## Game Version

1.07

## Testing Session

### Duration

60 minutes

### Test Area

Chapters 1 & 2 / Eastern South Vale & Woodside Apartments

### Testing Objective

Explore Silent Hill 2 Remake's gameplay and environmental systems, with a focus on player movement, combat, enemy behaviour, environmental interaction, puzzles, item interaction, audio, visual presentation, and scripted events.

## Testing Approach

The session was carried out using the method of exploratory testing rather than predetermined test cases over 60 timed minutes.
Testing focused on interacting with the game's gameplay and environmental systems while observing for unintended, unexpected, inconsistent, or incorrect behaviour.
The session placed large focus visual presentation, animations, collision, enemy behaviour, environmental interactions, and the consistency of scripted gameplay events.

The following areas were explored:

- Player movement
- Environmental interaction
- Item collection and inventory
- Combat
- Enemy behaviour
- Weapon interaction
- Puzzle interaction
- Audio presentation
- Visual presentation
- Scripted events and transitions



## Exploration Log

### Exploration 1 — Player Movement

**Action:**

Explore the environment using normal player movement, including walking, running, turning, crouching, and navigating around obstacles and uneven terrain.

**Observation:**

The player character moves in all tested directins correctly. Turning and crouching was smooth and did not have any animation issues. 
Navigating around obstacles and around uneven terrain is accurate with no unexpected issues such as clipping through environmental objects. 

**Result:**

Normal Behaviour



### Exploration 2 — Environmental Interaction

**Action:**

Interact with environmental objects and investigate how the player character interacts with doors, obstacles, furniture, walls, windows, and other accessible objects.

**Observation:**

The player character is able to succesffully interact with interactable objects such as dors, windows or swtiches with no unexpected behaviour. 
Non-Interactable Objects such as walls or furniture correctly prevented interactions, and did not display any unexpected behaviour such as button prompts.
**Result:**

Normal Behaviour

---

### Exploration 3 — Item Collection & Inventory

**Action:**

Collect available items and observe how they are added to the player's inventory. Open the inventory and inspect the collected items and available information.

**Observation:**

Collected items were successfully transferred to the player's inventory and could be inspected correctly. The inspection animation is smooth and does not show any visual issues.
The available information about each object is displayed clearly with no issues.

**Result:**

Normal Behaviour



### Exploration 4 — Combat

**Action:**

Engage enemies using available weapons and observe attacks, hit reactions, damage, animations, movement, and enemy defeat behaviour.

**Observation:**

Enemy NPCs become hostile when the player enters their detection range as expected. Attacks were smooth and did not show any animation issues.
Enemy NPCs get staggered with each hit to indicate that damage dealt has been registered correctly.
The dodging mechanic works as intended and does not have any visual issues. Defeated enemies create audio and visual feedback when defeated by making a noise and dropping to the ground.

**Result:**

Normal Behaviour



### Exploration 5 — Enemy Behaviour

**Action:**

Observe enemy behaviour during encounters, including detection of the player, movement, attacks, reactions to damage, navigation around the environment, and behaviour after the encounter.

**Observation:**

Enemiy NPCs detect the player when in their detection range and become hostile as expected. Movement is jerky and sudden as intended based on the enemy's design.
Enemy NPCs rect to damage taken by being staggered with each hit and creating audible feedback.
Enemies follow their intended movement path around the environment, with their behaviour changing when the player approached them. Enemy NPCs displayed their convulsing animation before remaining on the ground.

**Result:**

Normal Behaviour



### Exploration 6 — Weapon Interaction

**Action:**

Use available weapons against enemies and interact with the weapon system, observing weapon animations, attacks, hit detection, ammunition or durability where applicable, and weapon switching.

**Observation:**

Early weapons include a handgun and a wooden plank which can be smoothly switched between with no animation issues. The weapons can be inspected successfully in the player inventory.
Attacks with them are smooth and work accordingly with the handgun creating the appropriate sound and visual effects when fired, and the wooden plank creating the appropriate animation when used on an enemy NPC.
Handgun responded correctly to player input when used at a range. Wooden plank also responds to button input successfully. Handgun mmunition is correctly updated after each shot.
The durability of the wooden plank is also correctly updated after each use. 

**Result:**

Normal Behaviour



### Exploration 7 — Puzzle Interaction

**Action:**

Interact with environmental puzzles and puzzle-related objects. Observe how clues, interactable objects, puzzle states, and successful or unsuccessful interactions are handled.

**Observation:**

Puzzle interactions functioned correctly, with puzzle objects such as keys responding appropriately when interacted with and successfully solved puzzles, allowing for expected game progression.
Puzzle states updated correctly after completion.

**Result:**

Normal Behaviour



### Exploration 8 — Audio

**Action:**

Explore different environments while observing ambient sounds, environmental audio, character sounds, enemy sounds, music, and audio changes during gameplay events.

**Observation:**

Audio elements functioned properly with environmental, characer, weapon, enemy audios and the background music being played correctly and appropriately. The audio responded correctly to the environments and the gameplay 
with no missing or delayed sounds.

**Result:**

Normal Behaviour



### Exploration 9 — Visual Presentation

**Action:**

Explore different environments and observe lighting, textures, character models, animations, objects, shadows, reflections, and visual effects.

**Observation:**

Visual elements and effects rendered correctly and appropriately. Character models, objects, textures, lightning, shadows and animations appeared as expected and intended. No graphical issues, missing textures, partially loaded textures
or clipping was present.

**Result:**

Normal Behaviour



### Exploration 10 — Scripted Events & Transitions

**Action:**

Progress through the game and observe transitions between gameplay, cutscenes, scripted events, exploration areas, and combat encounters.

**Observation:**

The scripted events and transitions functioned correctly such as the transitions from cutscenes into gameplay, with the player regaining control of the player character correctly after uncontrollable scripted events.
Transitions between combat and exploration also resumed correctly.

**Result:**

Normal Behaviour


## Issues Identified

No defects or unexpected behaviours were identified during this exploratory testing session.
The tested gameplay and environmental systems, such as player movement, environmental interaction, combat, enemy behaviour, weapon interaction, audio and visual presentation, behaved consistently with their expected functions.
No observed behaviour required further bug reports for this session.
