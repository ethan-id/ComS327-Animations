# ComS327-Animations (1.10)
### Author:
Ethan Hancock, ehancock@iastate.edu
### TA Notes: 
> 

### Description:
#### Major Changes:
 - Added 'animations' to game
    - New opening animation when game is run
    - new animations when encountering pokemon
 - Pokemon HP is now additionally represented with an HP bar that is filled based on the pokemon's percentage of health.
    - The HP bar changes in 10% increments, each 'O' represents 10%.
        - A full HP bar looks like this: {0000000000}
        - A 50% HP bar looks like this: {00000     }


#### Method Changes/Additions
 - Added openingSreen()
    - Plays animation at start of game
 - Added firstDigit()
    - Helps with logic for HP bar calculations
 - Added encounterAnimation()
    - Plays animation when encountering a wild pokemon
 - Added blackCurtains() animation
    - Updated pokemonBattle() to use blackCurtains() before trainer fights
 - Updated battleSequence() to have some animations
    - The enemy pokemon and player's pokemon's HP and name float in from the left and right side of the screen before a fight
    - An alert is flashed telling the player what pokemon they are fighting before the battle begins.
