# Updating User Interface changes

## Feature

This module explains all changes that happen in User Interface

## Acceptance Criteria

### Scenario: User Interface is updated for ball position

  Given the game has started and the system conditions are working fine

  When the ball position moves via the move function

  Then the ball position in the User Interface is updated

### Scenario: User Interface is updated for paddle position

  Given the game is started and the system conditions are working fine

  When the paddle position moves via  move function

  Then the paddle position is updated in the User Interface
  
### Scenario: User Interface is updated for Score Board

  Given the game has started and the system conditions are working fine
  
  When the ball collides with either the left wall or the right wall

  Then the opposite side player scores a point, the Score Board is updated 
  
  and the User Interface Score system is also updated


