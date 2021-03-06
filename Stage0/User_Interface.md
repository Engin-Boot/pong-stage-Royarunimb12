# Updating User Interface changes

## Feature

This module explains all changes that happen in User Interface

## Acceptance Criteria

### Scenario: User Interface is updated for ball position

  Given the game has started and the system conditions are working fine

  When the ball position moves via the move function

  Then the ball position in the User Interface is updated.

### Scenario: User Interface is updated for paddle position

  Given the game is started and the system conditions are working fine

  When the paddle position moves via  move function

  Then the paddle position is updated in the User Interface.
  
### Scenario: the UI is updated for the Score Board

Given the game is started and the system conditions are working fine

When the ball collides with the left wall or right wall

Then The Score Board is updated based on the player who scored.

 User Interface Score system is also updated.

### Scenario: the main menu is displayed when game loads

Given the game is loading and the system conditions are working fine

When the game loads

Then the main menu is displayed in User Interface

### Scenario:On pressing play button, game elements get drawn

Given the main menu is displayed

When the play button is displayed

Then ball, paddle and initial score initializes and get rendered

### Scenario:On winning the winner is displayed

Given the game has started and the system conditions are working fine

When any player scores the upper limit of scores

Then he is displayed as winner
