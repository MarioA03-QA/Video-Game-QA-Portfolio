# TC-002 — Save & Load System Test Suite

## Game

Dark Souls II

## Platform

PlayStation 5

## Game Version

Unknown

## Test Objective

Verify that player progress, equipment, inventory, character state, and world state are correctly preserved and restored through the game's save and load system.


## Test Case 001 — Verify Automatic Save Behaviour

### Preconditions

- Player is in the game world.
- Player has access to an area where progress can be made.

### Steps

1. Enter the game world.
2. Perform an action that changes the player's state, such as defeating an enemy.
3. Observe the game's save indicator or other indication that the game has saved.
4. Close the game.
5. Reopen the game and load the player's character.

### Expected Result

The game should automatically save the player's progress, and the saved state should be available when the game is reopened.

### Actual Result

The game automatically saves the player's progress successfully, and the new saved state is automatically available when the game is reopened. 

### Status

PASS


## Test Case 002 — Save After Acquiring an Item

### Preconditions

- Player is in the game world.
- An obtainable item is available.

### Steps

1. Acquire an item.
2. Allow the game sufficient time to save the current progress.
3. Close the game.
4. Reopen the game and load the character.
5. Check the player's inventory.

### Expected Result

The acquired item should remain in the player's inventory after loading the character.

### Actual Result

The newly acquired item remains in the player's inventory after loading the character successfuly after some time was given for the game to automatically save

### Status

PASS


## Test Case 003 — Save After Changing Equipment

### Preconditions

- Player has at least two usable pieces of equipment.
- Player is able to change equipment.

### Steps

1. Equip a different weapon, armour piece, or other equipment.
2. Allow the game to save the current progress.
3. Close the game.
4. Reopen the game and load the character.
5. Check the player's currently equipped equipment.

### Expected Result

The equipment state should be correctly preserved after reloading the character.

### Actual Result

The new equipment state is correctly preserved after reloading the character

### Status

PASS


## Test Case 004 — Save After Changing Character State

### Preconditions

- Player is in the game world.
- Player is able to change their character's state.

### Steps

1. Perform an action that changes the player's state, such as consuming an item or changing equipment.
2. Allow the game to save the current progress.
3. Close the game.
4. Reopen the game and load the character.
5. Observe the player's state.

### Expected Result

The player's saved state should be correctly preserved after reloading the character.

### Actual Result

The player's saved state is correctly preserved after reloading the character

### Status

PASS


## Test Case 005 — Save After Progressing Through an Area

### Preconditions

- Player has access to an area containing enemies, items, or other interactive elements.

### Steps

1. Enter the selected area.
2. Progress through the area either by defeating enemies, collecting an item, or reaching a new location.
3. Allow the game to save the current progress.
4. Close the game.
5. Reopen the game and load the character.
6. Return to the previously visited area.

### Expected Result

The player's relevant progress should be preserved after reloading the character.
Enemies may respawn after reloading the character as part of the game's intended mechanics. This does not inerfere with the player's saved progress, acquired equipment, or other forms of progressions such as defeated bosses.

### Actual Result

The player's relevant progress is preserved after reloading the character, with the game's intended mechanics working as expected.

### Status

PASS


## Test Case 006 — Die and Verify Saved Character State

### Preconditions

- Player has a saved character.
- Player has an amount of in-game currency available (Souls) that can be lost upon death.

### Steps

1. Record the player's current Soul count and relevant character state.
2. Allow the game to save.
3. Die in the game.
4. Observe the resulting character state.
5. Close the game.
6. Reopen the game and load the character
7. Return to the game world and observe the player's saved state.

### Expected Result

The game should correctly apply its intended death and respawn mechanics while preserving the appropriate character and world state.

### Actual Result

The game correctly applies its intended mechanics in which the player character loses the acquired souls upon death and preserves the newly saved state of the character upon death.

### Status

PASS


## Test Case 007 — Close and Reopen the Game

### Preconditions

- Player has made progress in the game.
- The game has had sufficient time to automatically save.

### Steps

1. Make a noticeable change to the player's game state.
2. Allow the game to save.
3. Close the game completely.
4. Reopen the game.
5. Load the player's character.

### Expected Result

The game should load the most recently saved character state without losing saved progress.

### Actual Result

The game successfuly loads in the newest saved data without unintentinally losing any progress made

### Status

PASS


## Test Case 008 — Load Character After Restarting the Game

### Preconditions

- Player has an existing character with saved progress.

### Steps

1. Record the player's current location, equipment, and inventory items.
2. Allow the game to save.
3. Close the game.
4. Reopen the game
5. Load the existing character.
6. Compare the loaded character's state with the state recorded before closing the game.

### Expected Result

The loaded character should retain the previously saved location, equipment, inventory, and relevant progress.

### Actual Result

The game succesfully uses its intended mechanics to reload the player character into the world, with all progress saved.
Depends on where the game was exited due to inteded mechanic where the player character is spawned back at the area's last used bonfire (checkpoint). 

### Status

PASS


## Test Case 009 — Verify Equipment After Loading

### Preconditions

- Player has multiple weapons or pieces of equipment.
- Player has a saved character.

### Steps

1. Equip a specific weapon or piece of equipment.
2. Allow the game to save.
3. Close the game.
4. Reopen the game.
5. Load the character.
6. Check the player's equipment.

### Expected Result

The player's equipment should match the state that was saved before closing the game.

### Actual Result

The player's equipment matches the state in which it was saved before closing the game successfuly.

### Status

PASS


## Test Case 010 — Verify Inventory and Progress After Loading

### Preconditions

- Player has an existing character with saved progress.
- Player has items or progress that can be checked after loading.

### Steps

1. Record multiple items in the player's inventory and the player's current progression.
2. Allow the game to save.
3. Close the game.
4. Reopen the game.
5. Load the character.
6. Check the player's inventory and progression.

### Expected Result

The player's inventory and relevant progression should match the state that was saved before closing the game.

### Actual Result

The player's inventory and relevant progression successfully matches the state it was in, prior to closing the game.

### Status

PASS
