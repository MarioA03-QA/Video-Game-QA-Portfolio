# TC-001 — Weapon & Equipment System Test Suite

## Game

Mafia III

## Platform

PlayStation 5

## Game Version

Unknown

## Test Objective

Verify that the weapon and equipment system functions correctly when acquiring, equipping, switching, using, and managing weapons and equipment.

---

## Test Case 001 — Access Weapon Selection

### Preconditions

- Player is in the open world.
- Player has access to at least one weapon.

### Steps

1. Enter the open world.
2. Use the designated controller input to access the weapon selection system.
3. Observe the available weapons.

### Expected Result

The weapon selection system should open correctly and display the weapons currently available to the player.

### Actual Result

Weapon selection system works as intended, displaying available weapons, as well as locked/unlocked features such as the arms dealer, and the ability to use the appropriate button prompt to select desired options.

### Status

PASS 


## Test Case 002 — Equip a Weapon

### Preconditions

- Player has access to at least one weapon.

### Steps

1. Access the weapon selection system.
2. Select an available weapon.
3. Equip the selected weapon.

### Expected Result

The selected weapon should equip successfully and become the player's active weapon.

### Actual Result

Selected weapon becomes equipped by the player character and is available to be used

### Status

PASS


## Test Case 003 — Switch Between Available Weapons

### Preconditions

- Player is in the open world.
- Player has at least two available weapons.

### Steps

1. Access the weapon selection system.
2. Select a different available weapon.
3. Equip the selected weapon.
4. Switch back to the previously equipped weapon.

### Expected Result

The player should be able to switch between available weapons successfully, with the selected weapon becoming the active weapon.

### Actual Result

Player is able to switch betwen available weapons successfully, with the selected weapon becoming the active weapon.

### Status

PASS



## Test Case 004 — Fire a Weapon

### Preconditions

- Player has a firearm equipped.
- The weapon has ammunition.

### Steps

1. Aim the equipped weapon at a suitable target.
2. Fire the weapon.
3. Observe the weapon's behaviour and ammunition count.

### Expected Result

The weapon should fire correctly, ammunition should decrease appropriately, and the weapon should produce the expected firing effects and animations.

### Actual Result

The weapon fires correctly, with no visual or auditory issues. The weapon's firing effects are appropriate with no issues. The ammunition is depleted accordingly to the bullets being shot.

### Status

PASS



## Test Case 005 — Reload a Weapon

### Preconditions

- Player has a firearm equipped.
- The weapon has ammunition remaining in reserve.
- The weapon's magazine is not full.

### Steps

1. Fire the weapon until the magazine is partially depleted.
2. Initiate a reload.
3. Observe the reload animation and ammunition count.

### Expected Result

The weapon should perform the reload animation and replenish the magazine using available reserve ammunition.

### Actual Result

The weapon performs the appropriate reload animation and replenishes the magazine correctly using the available ammunition, wether all or some of the bullets have been used.

### Status

PASS



## Test Case 006 — Fire Until Ammunition Is Depleted

### Preconditions

- Player has a firearm equipped.
- The weapon has ammunition available.

### Steps

1. Fire the weapon repeatedly until the magazine is empty.
2. Attempt to fire the weapon again.
3. Observe the weapon's behaviour.

### Expected Result

The weapon should stop firing once the magazine is empty and provide the appropriate empty-ammunition behaviour and animation
### Actual Result

The weapon stops firing once the magazine has been emptied and it provides the appropriate behaviour and animations, such as clicking sounds.

### Status

PASS



## Test Case 007 — Acquire a Weapon

### Preconditions

- Player is in the open world.
- A weapon is available to be acquired.

### Steps

1. Approach an available weapon.
2. Interact with the weapon or obtain it using the appropriate interaction.
3. Observe the weapon selection system.
4. Attempt to equip the acquired weapon.

### Expected Result

The weapon should be acquired successfully and become available through the weapon selection system via any available means.

### Actual Result

The weapon is successfully added to the weapon selection system and is available to be used.

### Status

PASS



## Test Case 008 — Use Throwable Equipment

### Preconditions

- Player has access to throwable equipment.

### Steps

1. Access the throwable equipment selection.
2. Select an available throwable.
3. Aim at a suitable location or target.
4. Use the throwable.
5. Observe the resulting behaviour.

### Expected Result

The throwable should be selected, deployed, and produce the expected effect.

### Actual Result

The throwable can be successfully selected, aimed, and used, as well as producing the expected effect such as fire dispersing on the ground from a molotov cocktail being thrown.

### Status

PASS



## Test Case 009 — Switch Weapons During Combat

### Preconditions

- Player has at least two available weapons.
- Player is engaged in combat.

### Steps

1. Equip a weapon.
2. Engage an enemy.
3. Access the weapon selection system during combat.
4. Select a different available weapon.
5. Continue combat using the newly selected weapon.

### Expected Result

The player should be able to switch weapons during combat, and the newly selected weapon should become available for use without causing unwanted behaviour.

### Actual Result

The player can switch between weapons correctly during combat, with the newly switched weapon working accordingly.

### Status

PASS



## Test Case 010 — Verify Weapon State After Loading a Save

### Preconditions

- Player has access to at least one weapon.
- A save can be created.

### Steps

1. Equip a weapon.
2. Record the currently equipped weapon and its current ammunition.
3. Create a save.
4. Make a change to the player's weapon state, such as switching weapons or firing them.
5. Load the previously created save.
6. Observe the player's weapon state.

### Expected Result

The game should restore the weapon state associated with the loaded save correctly.

### Actual Result

The game successfully restores the weapon's state once the save was created, and loaded back once the weapon was used, prior to the reloading of the save.

### Status

PASS
