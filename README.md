Based of of skavinger's mod in TTS, this mod aims to create extra tables in order to facilitate extra games of play. 
Main changes made:
  Cerated new game baords. Changed properties of game boards since tables could not be reproduced
  Re-mapping Player hands to new boards
  Original control operated "Red" and "White" player decks since they were on the same side of the board. Now each control is for its own player. Red Player to Red Control and White Player to White Control
  Global script needed to have all extra players added to reflect newly defined functions.
  Added new scripting zones that were specific to each player

Player Teal has each function labled   

All in all, this was a copy and paste job but I ran into a hanful of problems with the scripting zones. The script will check for cards in a scripting zone and then move them into another zone. The issue was, the scripting zone had the game board object in it so when you
click the check button, it would see the board object and move it. This cuold have been solved by making the script only move card objects found within the zone but by the time I realized it, it was finished. Moving the Scipting zone so that it was just above the game
board solved the problem. 
