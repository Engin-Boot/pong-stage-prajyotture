# -Game-Crash

## Feature

What happens when the Game Crashes?

## Acceptance Criteria

### Scenario:Game Crash due to storage problem

  Given -The pong game is running properly

  When -The phone storage place is full due to
  cache overload the app runs poorly

  Then -Force Quit the app and ask user to
  restart only after unloading or clearing the cache
  
### Scenario:Game Crash due to drivers

  Give-The pong game is starting to load

  When-THe drivers or software version of game is not compatible to the current mode

  Then-Ask permission to update the driver and after update restart the game again
