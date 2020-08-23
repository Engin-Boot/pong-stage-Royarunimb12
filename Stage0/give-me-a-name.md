# Game Rules

## Feature

This module specifies the protocols that determine the game

## Acceptance Criteria

### Scenario: a point

Given the game is started and the system conditions are working fine

When the paddle moves in a direction other than ball

Then the ball collides with the wall and a point is scored

### Scenario: a winner is declared

Given the game has started and the system conditions are working fine

When in final lap, any player hits the opposite wall

Then that player wins
