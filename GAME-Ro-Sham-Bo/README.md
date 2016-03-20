# Ro-Sham-Bo

Name Of Game: Ro-Sham-Bo
Created By: Claes Cummings
Twitch.tv/ClaesCummings

About Ro-Sham-Bo:
  Ro-Sham-Bo is another name for Rock, Paper, Scissors. I chose to use it as the title for this game as it is shorter and looks/works better as an !command.

Features:
  - Costs Points to challenge other viewers.
  - Tie: Returns Challenger's Points - Rewards Challengee Points for Survival
  - Challenger Wins - Rewards Challenger Points - Challengee, loses nothing.
  - Challengee Wins - Rewards Challengee Points - Challenger, loses challenge cost.
  - Bot Text Highlighted with /me.

Setting Up:
  
  Create text files ChallengeRoShamBo.txt & RoShamBo.txt using the;
  RO-SHAM-BO TEXT FILE 1
  RO-SHAM-BO TEXT FILE 2
  files within GAME: Ro-Sham-Bo branch.
  
  Changes To Text Files;
  FILE 1:
  Change the "min","max" amounts under $removepoints parameter to the desired amount of points you wish to charge per challenge.
  File 2"
  Change the "min","max" amounts under each $addpoints parameter to the desired amount of points you wish to to award.
  
  In Commands Tab;
  - Command: !roshambo
  - Permission: Everyone
  - C/D: 0
  - User C/D: 3
  - Enabled: True
  - Usage: Chat
  - Response:

    /me : Ro-Sham-Bo!
    $readline(RO-SHAM-BO TEXT FILE 1 LOCATION)
    $readrandline(RO-SHAM-BO TEXT FILE 2 LOCATION)
