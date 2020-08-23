# Game Rules

## Feature

This module specifies the protocols that determine the game

## Acceptance Criteria

### Scenario: a point is scored

Given the game is started and the system conditions are working fine

When the paddle moves in a direction other than ball

Then the ball collides with the wall and a point is scored

### Scenario: a winner is declared

Given the game has started and the system conditions are working fine

When in final lap, if any player hits the opposite wall

Then that player is declared as winner

### Scenario: the ball hits on the paddle

Given the game has started and the system conditions are working fine

When the ball hits the paddle

Then the ball moves in the opposite direction of the paddle
towards opponent player

### Scenario: the ball hits the wall

Given the game has started and the system conditions are working fine

When the ball hits the wall

then the player's score is  incremented and Score board
is updated
