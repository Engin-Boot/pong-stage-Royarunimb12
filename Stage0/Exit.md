# Exit module

## Feature

This module specifies the exit mechanism

## Acceptance Criteria

### Scenario: the game has ended with Winner declaration

Given the game has started and the system conditions are working fine

When the point limit has been reached and winner has declared

Then the exit option and replay option is shown and
game can be terminated by choosing the exit option

### Scenario: the players choose to quit the game while playing

Given the game has started and the system conditions are working fine

When the players choose to terminate the game whilst playing

Then the exit option on the top right hand corner is clicked
and the game is terminated
