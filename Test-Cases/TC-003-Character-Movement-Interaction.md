# TC-003 — Character Movement & Interaction Test Suite

## Game

Bloodborne

## Platform

PlayStation 5

## Game Version

Unknown

## Test Objective

Verify that the player's character movement and environmental interaction systems function correctly during normal gameplay, including movement, dodging, climbing, interacting with objects, and transitioning between areas.



## Test Case 001 — Basic Character Movement

### Preconditions

- Player is in the game world.
- Player has control of the character.

### Steps

1. Move the character forward.
2. Move the character backwards.
3. Move the character left.
4. Move the character right.
5. Observe the character's movement.

### Expected Result

The character should move correctly in each direction in response to the player's inputs without unintended movement or animation issues.

### Actual Result

The character moves correctly in each direction prompted by the player, in accordance to the inputs, without unintended movement or animation issues.

### Status

PASS


## Test Case 002 — Character Sprinting

### Preconditions

- Player is in an area where movement is possible.
- Player has sufficient stamina to sprint.

### Steps

1. Move the character normally.
2. Activate the sprint input.
3. Observe the character's movement speed and animation.
4. Release the sprint input.

### Expected Result

The character should transition into the appropriate sprinting movement and animation and return to normal movement when the sprint input is released.

### Actual Result

The character transitions into the appropriate running speed for sprinting, along with the sprinting animation, and correctly returns to normal movement when the sprint input is released.

### Status

PASS


## Test Case 003 — Character Dodging

### Preconditions

- Player is in an area where dodging is possible.
- Player has sufficient stamina.
- Player is locked-in on an enemy NPC.

### Steps

1. Lock-in on an enemy NPC.
1. Move the character.
2. Perform a dodge.
3. Observe the character's movement and animation.

### Expected Result

The character should perform the appropriate dodge animation and move in the direction indicated by the player's input.

### Actual Result

The character peforms the dodge animation correctly and moves in the dirrection indicated by the player's input successfully.

### Status

PASS

## Test Case 004 — Character Rolling

### Preconditions

- Player is in an area where rolling is possible.
- Player has sufficient stamina.
- Player is not locked-in to an enemy NPC.

### Steps

1. Move the character.
2. Perform a roll.
3. Observe the character's movement and animation.

### Expected Result

The character should perform the appropriate rolling animation and move correctly in the intended direction.

### Actual Result

The character performs the appropriate rolling animation correctly and moves in the intended diretion successfuly.

### Status

PASS


## Test Case 005 — Climbing Stairs

### Preconditions

- Player is near a staircase accessible to the character.

### Steps

1. Approach the staircase.
2. Walk up the stairs.
3. Walk back down the stairs.
4. Observe the character's movement and animations.

### Expected Result

The character should move smoothly up and down the staircase without becoming stuck, falling through the environment, or displaying incorrect movement behaviour.

### Actual Result

The character moves smoothly up and down the staircasae without any issues such as becoming stuck, falling through the environment or displaying incorrect behaviour successfully.

### Status

PASS


## Test Case 006 — Environmental Collision

### Preconditions

- Player is in an area containing walls, objects, or other environmental obstacles.

### Steps

1. Approach an environmental obstacle.
2. Move directly towards the obstacle.
3. Attempt to move through the obstacle.
4. Move away from the obstacle.

### Expected Result

The character should correctly collide with the environmental obstacle and should not pass through it or become stuck inside it.

### Actual Result

The character collides with obstacles successfully, without passing through them or becoming stuck in them.

### Status

PASS


## Test Case 007 — Interact With an Environmental Object

### Preconditions

- Player is near an interactive environmental object, such as an openable door. 

### Steps

1. Approach the interactive object.
2. Observe whether an interaction prompt is displayed.
3. Use the appropriate interaction input.
4. Observe the resulting behaviour.

### Expected Result

The interaction prompt should appear when appropriate, and the interaction should perform its intended function.

### Actual Result

The interaction prompt appears when close to the interactable object, and interacting with it carries out the intended function successfully.

### Status

PASS


## Test Case 008 — Open a Door

### Preconditions

- Player is near an accessible door.

### Steps

1. Approach the door.
2. Observe whether an interaction prompt appears.
3. Interact with the door.
4. Observe the door and player's resulting state.

### Expected Result

The door should respond correctly to the interaction and transition to the appropriate opened state

### Actual Result

The door respons correctly to the interaction, and transitions to the correct opened state successfully, as well as no issues with the door opening animation.

### Status

PASS


## Test Case 009 — Transition Between Areas

### Preconditions

- Player has access to an area transition or loading point.

### Steps

1. Approach the area transition.
2. Interact with it or activate the appropriate transition.
3. Wait for the transition to complete.
4. Observe the player's position and surrounding environment.

### Expected Result

The game should transition the player to the intended area successfully without losing player control, becoming stuck, or displaying unintended environmental or character behaviour.

### Actual Result

The game transitions the player character to the intended area successfully without any issues such as becoming stuck, unintended envionmental or character behavior, or losing player control

### Status

PASS


## Test Case 010 — Character Movement After Area Transition

### Preconditions

- Player has access to an area transition.

### Steps

1. Enter the new area through the appropriate transition.
2. Wait until the area has finished loading.
3. Move the character in multiple directions.
4. Perform a dodge, jump and roll.
5. Interact with a nearby environmental object if available.

### Expected Result

The character should regain normal movement and interaction functionality after transitioning to the new area.

### Actual Result

The character maintains normal movement and interaction functionality after transitioning to the new area successfully.

### Status

PASS
