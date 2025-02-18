# Unity Group Project - CPSC 24500

Current game title: **The Great Snake Escape**

https://drive.google.com/drive/u/2/folders/17kbOsfnRxNpTotrICLqFp98jklPLAv7Y

## Instructions 
To run this project, first `pull` this repository (or `clone` it if you are doing this for the first time). Then, open Unity Hub, browse to the project folder `unity-group-project/Unity Group Project`, and open it.

To commit to `README.md`, do the instructions above and `pull` the repository, make changes, and run `git commit -m "README" README.md` then `git push`.

## Role-specific instructions 
To **test the game**, you should `pull` the repository, build the project to a .exe, and test it (or play it in Unity).

To **design a map**, [to be determined]

For the **pixel art designer**, here are some of the 16x16 pixel art sprites that we need (make it kind of simple, similar to the ones that we have):
- Snake body sprite 
- Snake head sprite 
- Gold sprite 
- Exit sprite 
- Item sprites 
- Player sprite 
- Golden door sprite 
- Map-related sprites 

For the **sound effect searcher**, the following is maybe neeeded:
- Title screen music 
- Game music 
- Lose sound effect (or snake capture sound effect)
- Item collection (or usage) sound effects 
- Gold collection sound effect 
- Golden door opening sound effect 
- Exit reached sound effect (optional)
- Player movement sound effect (optional)
- Snake movement sound effect (optional)
- Health reduction sound effect (optional)
- Healing sound effect (optional)
- Menu sound effect (optional)

## Game Progress 
- **(9/24/24)** Made a grid 
- **(9/25/24)** Made a player 
- **(9/26/24)** Made player movement 
- **(10/01/24)** Revamped tilemaps and made walls to work 
- **(10/01/24)** Made snake design and some core snake tile functionality 
- **(10/02/24), map designer** Added a room to the map as a test 
- **(10/04/24)** Made snake loading functionality 
- **(10/06/24)** Made snake moving functionality 
- **(10/06/24)** Made snake chase player in an easy manner 
- **(10/09/24)** Simple title screen prototype with scene switching 
- **(10/14/24)** Action tile prototype with gold counter 
- **(10/15/24)** Fail screen when snake catches you 
- **(10/21/24)** Made gold work better 
- **(10/21/24)** Started working without internet 
- **(10/21/24)** Made snake faster when more gold collected 
- **(10/22/24)** Made a map select prototype (which does not work yet)
- **(10/22/24)** Laid out a golden door idea (which does not work yet)
- **(10/23/24), image designer** Made custom sprites 
- **(10/23/24)** Imported custom sprites and refactored filesystem 
- **(10/25/24)** Made some prototype sprites and verified player alignment 
- **(10/25/24)** Swapped custom floor and wall sprites 
- **(10/25/24)** Made a great-looking title screen prototype 
- **(10/25/24)** Made a few changes to design, such as canvas world space 
- **(10/27/24)** Completely revamped gold system, made it all on one tilemap 
- **(10/27/24)** Fixed some other unrelated canvas issues 
- **(10/28/24), image designer** Made more custom sprites 
- **(10/28/24)** Added a "void" tilemap where you and the snake should not fall to 
- **(10/29/24)** Renamed that tilemap to "NonBackground" and made it work on player 
- **(10/29/24)** Added a "You Won!" screen prototype that does not work 
- **(10/29/24)** Made that and the fail screen look extra detailed 
- **(10/29/24)** Adjusted some details for the menu screen 
- **(10/30/24)** Added player health feature, and made no health equate to failure 
- **(10/30/24)** Made the map look a little better 
- **(10/30/24)** Added an "exit" tilemap that does not work 
- **(10/31/24)** Did lots of map experimentation 
- **(11/01/24)** Complete map overhaul, added URP and post-processing 
- **(11/01/24)** Decided on a more arcade-style map 
- **(11/01/24), undocumented start** We started really working on the project 
- **(11/08/24), undocumented end** More than half-way done with the presentation 
- **(11/08/24)** Made gold trigger its sound effect when collected 
- **(11/13/24), undocumented end** Two days after the demo 
- **(11/13/24)** Made fundamental item sprite structure 
- **(11/13/24), image designer** Designed lots of pixel art sprites 
- **(11/13/24)** Made gold and item functionality much better 
- **(11/17/24), undocumented end**
- **(11/17/24)** Made the first working prototype of the speedup item!
- **(11/20/24), undocumented end**
- **(11/20/24), image designer** Made inventory prototype sprite 
- **(11/20/24)** Transformed prototype inventory design into a more working one 
- **(11/20/24), at most** Made random item spawners with probabilities 
- **(11/20/24), at most** Made item collection really work 
- **(11/21/24)** Made inventory functional 
- **(11/21/24)** Made items usable from inventory, each with their own different functions...
- **(11/21/24)** ...and gave us a massive understanding of interfaces and abstract classes 
- **(11/22/24)** Made prototype better designs for title and map screen 
- **(11/25/24), undocumented end**
- **(11/25/24), idea maker as map designer** Provided a legacy cave-style map 
- **(11/27/24), undocumented end**
- **(11/27/24)** Extended the demo map a little 
- **(11/27/24)** Introduced a sound effect player 
- **(11/27/24)** Added lots of prototype sound effects 
- **(11/27/24)** Made internal item handling much better 
- **(11/28/24)** Improved title screen by a lot 
- **(11/29/24), undocumented end**
- **(11/29/24)** May not be in chronological order 
- **(11/29/24)** Made title screen so much better and functional 
- **(11/29/24)** Added new font and completely redesigned all of the text 
- **(11/29/24)** Made map look better 
- **(11/29/24)** Made golden doors fully functional 
- **(11/29/24)** Gathered more sound effects 
- **(11/29/24)** Replaced speedup with coffee; made revamped designs for coffee and cookie 
- **(11/29/24)** Made coffee work and have its intended effect 
- **(11/29/24)** Added lots of more scripts, many more features, and bugfixes 
- **(11/29/24)** Added fully working player health and stamina functionality 
- **(11/29/24)** Made snake correctly respond to one cookie or more 
- **(11/29/24)** Added almost fully working cookie drop functionality 
- **(11/30/24)** Added unoptimized prototype A* pathfinding 
- **(11/30/24)** Temporarily fixed some bugs for snake pathfinding, but not removed them 
- **(12/01/24), upper bound** Added a loading screen 
- **(12/01/24)** Redesigned title screen 
- **(12/01/24)** Made map screen fully function and probably finalized 
- **(12/01/24)** Made an interesting lose screen 
- **(12/01/24)** Made an interesting win screen with a questionable strange ending 
- **(12/01/24)** Replaced invisibility in favor of water balloon in favor of better gameplay...
- **(12/01/24)** ...and made a water balloon sprite 
- **(12/01/24)** Made working water balloon item that does nothing 
- **(12/01/24)** Almost implemented buggy water balloon (eleven-o-clock edition)
- **(12/02/24)** Started working on final presentation 
- **(12/03/24)** Implemented camera shake when health lost 
- **(12/03/24)** Fixed water balloon bug 
- **(12/03/24)** Added gold counter effect when all gold collected 
- **(12/03/24), sound designer** Made multiple menu screen song candidates 
- **(12/03/24)** Integrated one menu screen song candidate of choice 
- **(12/03/24)** Added menu screen "unallowed" sound effect 
- **(12/03/24)** Added a tutorial for the game 
- **(12/03/24)** Added an effect when all gold collected 
- **(12/03/24)** Adjusted some characteristics 
- **(12/03/24)** Integrated custom map by playtester as map designer 
- **(12/03/24)** Added the QWERTY cheat code 
- **(12/03/24)** Added snake body memory 
- **(12/03/24)** Added prototype snake difficulty increase over time 
- **(12/03/24)** Fixed an unusual crash bug with A* pathfinding 
- **(12/03/24)** Partially fixed an unusual crash bug with water balloon expansion...
- **(12/03/24)** ...but make sure not to include any horizontal or vertical gaps...
- **(12/03/24)** on your map!
- **(12/03/24)** Fixed an unusual crash bug with snake A* pathfinding failure 
- **(12/03/24)** Fixed an unusual crash bug snake body memory 
- **(12/03/24), undocumented end**
- **(12/04/24)** Fixed some last-minute bugs, presentation time!
- **(12/04/24)** Distributed the project 
- **(12/04/24)** Commit everything :)
- **(OBJECTIVE)** Export the first version of the game on Google Drive (after building it)

![alt text](./image.png)