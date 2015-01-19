# Arena
Arena Software for CodeBattleground.com

This is very much still in development.

This is the "arena" front-end for CodeBattleground.com.  It should:

  - Allow an administrator to enter a URL for the game server container
  - Allow an administrator to enter URLS for two or more player containers
  - "run" the game by:
     - Launching the Docker containers for the game server and each player container
     - Calling /setup on the game server  (Contains Game ID, URLs for each player container)
     - Calling /runTurn on the game server repeatedly until the game is finished
     - Displaying the winner of the game when it is finished
     - Provide some visualization for the above while a game is in progress
