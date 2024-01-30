I Was Thrown Into a Messed up Labyrinth by My Landlord to Pay Off My Rent Also I Can Use The Force 
                            (Based on the light novel of the same name)                            


_____________________
LAUNCH

The launch file is main.py. Type the command 'python main.py' to kickstart the program.
_____________________
SCREEN SETUP

The game is best played when the terminal is very tall because maps will be partially hidden otherwise
_____________________
MAIN MENU

This game is played entirely with single character keyboard inputs. The possible inputs will be shown in square brackets. E.g. [w][a][s][d]
_____________________
GAMEPLAY

USE THE TUTORIAL MODE!!!!!!!!
USE THE TUTORIAL MODE!!!!!!!!
USE THE TUTORIAL MODE!!!!!!!!
USE THE TUTORIAL MODE!!!!!!!!
USE THE TUTORIAL MODE!!!!!!!!
It will teach you how the game works.

But here it is in plain text:
- You will be put into a map. This is the map.
- You can move using i,j,k,l and w,a,s,d.
  ██████████████████████░░█████ - In the map are tiles, diamonds, an exit, and the player
  ██ ▄░░▄▄ ▄▄▄▄▄ ▄░░▄▄ ▄▄▄▄▄ ██ - Tiles are the large 3x3 blocks. You move them using the letters i,j,k,l or their uppercase.
  ██ █<>██ █<>░░ █<>░░ █████ ██   ▄▄▄▄▄
  ██ █░░██ █░░██ █░░██ █████ ██   ░<>██
  ██ ▄░░▄▄ ▄▄▄▄▄ ▄░░▄▄ ▄▄▄▄▄ ██   █░░██
  ██░░<>██ █████░░<>░░░░<>██ ██ - You can only move tiles that are next to the large 3x3 hole in the map.
  ██ █████ █████ █░░██ █░░██ ██                                                           ┃
  ██ ▄░░▄▄ ▄░░▄▄ ▄░░▄▄       ██                                                           ┃
  ██░░<>██░░<>░░ █<>██    <━━██━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
  ██ █████ █████ █████  This ██ - Some tiles contain pathways in them. Pathways are the lightly   
  ██ ▄▄▄▄▄ ▄░░▄▄ ▄░░▄▄ ▄▄▄▄▄ ██   shaded blocks ░░░░░░░. The player can walk on these pathways
  ██ █:3░░░░<>██░░<>░░ █████ ██ - The player CANNOT walk in between the small gaps between tiles. Those  
  ██ █████ █████ █░░██ █████ ██   are purely there for visual clarity
  ██ █████ █████ █░░██ █████ ██ - Inside each tile is a diamond. They give you points when grabbed.
  ██▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄██ - You grab diamonds by moving the player. The player is 😔. You move  
  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀   the player using the letters w,a,s,d or their uppercase.
                                - The player can exit by moving to the pathway on the outer boundary
                                - Tiles with the player inside of them can also be moved
In the main menu, select "Start Game" to play the actual game. You can also choose "Level Select" to choose which of the 4 levels you would like to go to.
_____________________
SCORING SYSTEM

Stars are gained at the end of the level based on the number of diamonds grabbed.
0% - 49%  : 1★
50% - 99% : 2★
100%      : 3★
You also get a score at the end of each level. It is calculated by the equation: 
           2 ^ diamonds taken 
  score =  —————————————————— * 20
               tile moves 
Note that the score increases exponentially to the number of diamonds taken to incentivize grabbing diamonds.
Also note that the score is only reduced by the number of tile moves, this is to encourage players to slide the tiles into a well connected maze before moving around

ENJOY THE GAME
