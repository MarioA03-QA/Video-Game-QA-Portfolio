# TC-004 — Character & Realm Management Test Suite

## Game

Crusader Kings III

## Platform

PC

## Game Version

1.19.0.6

## Test Objective

Verify that character and realm management systems function correctly, including character information, titles, resources, decisions, relationships, and changes to the player's realm state.



## Test Case 001 — Open Character Information

### Preconditions

- Player is in an active game.
- The player controls a character.

### Steps

1. Open the character information panel.
2. Observe the character's displayed information.
3. Navigate through the available character information tabs.

### Expected Result

The character information panel should open correctly and display the character's relevant information without missing or incorrectly displayed elements.

### Actual Result

The character information panel opens correcrtly and displays the character's relevant information successfully.

### Status

PASS


## Test Case 002 — View Character Attributes

### Preconditions

- Character information panel is accessible.

### Steps

1. Open the character information panel.
2. Locate the character's attributes.
3. Observe the displayed attributes of the character.

### Expected Result

The character's attributes should be displayed correctly and should reflect and impact the character's decisions and choices.

### Actual Result

The character's attributes are displayed correctly and accurately reflect and impact the decisions made with the character such as dialogue options.

### Status

PASS


## Test Case 003 — View Character Traits

### Preconditions

- Player controls a character with at least one visible trait.

### Steps

1. Open the character information panel.
2. Locate the character's traits.
3. Select or hover over a trait.
4. Observe the information provided.

### Expected Result

The character's traits should be displayed correctly, and selecting or hovering over a trait should provide the appropriate information.

### Actual Result

The character traits are displayed correctly and by selecting or hovering over them, they provide the appropriate information about them.

### Status

PASS


## Test Case 004 — View Realm Information

### Preconditions

- Player controls a character with a realm.

### Steps

1. Open the realm information interface.
2. Observe the displayed realm information.
3. Navigate through the available realm management sections.

### Expected Result

The realm interface should open correctly and display the relevant information about the player's realm.

### Actual Result

The real interface opens correctly and displays relevant information about the player's controlled realm.

### Status

PASS


## Test Case 005 — View Available Decisions

### Preconditions

- Player is in an active game.
- The character has access to at least one decision or decision category.

### Steps

1. Open the Decisions interface.
2. Review the available decisions.
3. Select a decision that is currently available.
4. Observe the displayed requirements and effects.

### Expected Result

Available decisions should be displayed correctly, with their requirements and potential effects clearly presented.

### Actual Result

The available decisions are displayed correctly with their prequisites and potential effects being clearly presented.

### Status

PASS


## Test Case 006 — Execute an Available Decision

### Preconditions

- Player has access to a decision that can currently be completed.
- The character meets the requirements for the decision.

### Steps

1. Open the Decisions interface.
2. Select an available decision.
3. Review the requirements and expected effects.
4. Confirm the decision.
5. Observe the resulting character and realm state.

### Expected Result

The decision should be completed successfully and the intended effects should be applied to the concerned character or realm state.

### Actual Result

The decision is completed successfully, and the intended effects are applied correctly to the concerned character or realm state.

### Status

PASS


## Test Case 007 — View Character Resources

### Preconditions

- Player is in an active game.

### Steps

1. Observe the character's currently available resources.
2. Open the relevant character or realm interface.
3. Compare the displayed resource values across the relevant interfaces.

### Expected Result

Resource values should be displayed consistently and should accurately reflect the character's current state.

### Actual Result

The resources available such as the player character's piety are displayed consistently and accurately based on usage, and accurately reflect the player character's current state.

### Status

PASS

---

## Test Case 008 — Character Appearance Rendering

### Preconditions

- Player is in an active game.
- The game contains visible characters with rendered character models.

### Steps

1. Enter the game world.
2. Observe characters displayed in the game world or character management interfaces.
3. Observe the characters' faces and other visible character model components.
4. Move between different interfaces where characters are displayed.
5. Observe whether character facial features and models continue to render correctly.

### Expected Result

Character models should render correctly, including facial features, eyes, mouth, hair, and other visible character components.

Character models should remain visually complete when viewed in the game world and relevant interfaces.

### Actual Result

Most character models remain accurate, and render correctly including their facial features and other components.

Some characters do not have their entire facial structure rendered fully, with most of the face missing, and only having the eyes and inside of the mouth (teeth) present. This issue persists throughout the whole playthrough and does not change on reloading the save, or closing and reopening the game

### Status

FAIL


## Test Case 009 — Save and Verify Character State

### Preconditions

- Player has an active game.
- The game has reached a state where progress can be saved.

### Steps

1. Record the character's current relevant state.
2. Save the game using the available save function.
3. Make a noticeable change to the character or realm state.
4. Load the previously created save.
5. Compare the character and realm state with the state recorded before saving.

### Expected Result

The loaded game should restore the character and realm to the state represented by the selected save.

### Actual Result

The loaded game restores the player character and realm to the state represented by the selected save successfully.

### Status

PASS


## Test Case 010 — Verify Interface Navigation

### Preconditions

- Player is in an active game.
- Multiple character and realm management interfaces are available.

### Steps

1. Open the character information interface.
2. Navigate between the available interfaces several times.

### Expected Result

The player should be able to navigate between the available interfaces without the interface becoming unresponsive, displaying incorrect information, or preventing further interaction.

### Actual Result

The interfaces available are successfuly responsive, display correct information and do not prevent further information.

### Status

PASS
