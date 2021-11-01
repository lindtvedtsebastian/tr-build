# tr-build
The executable files for 'the-unravelling'.

You can find the repo on my profile.

# Playtest - The Unravelling

At the beginning of the game you are in Day mode. This means that you can harvest resources from trees, stone, copper and iron. Harvesting these lets you build turrets and walls, which you need to protect yourself duting Night mode when enemy waves spawn. 

The game does not "end" at its current state, meaning you cannot win or lose. They day count will only keep increasing until you don't get any more enemies during Night mode.

### Controlling the player

- WASD for moving in different directions

- Right mouse click to destroy trees, stone, copper and iron

- TAB for opening the inventory

- Left mouse click to select an active craft object to place on the map

- Left mouse click to place a selected craft object, you will see a preview of the object

- ESC to cancel an action, i.e., when having a crafting object selected and you regret picking it.

### Game mechanics

- HUD information, Day count and seconds until next game state

- You will start in Day mode to gather resources

- Trees, stone, copper and iron have health and will give loot once destroyed

- Day mode lasts 120 seconds

- You can place turrets and walls from gathering resources

- These can be picked from the inventory and will be active with a number if they can be built

- When Night mode starts, everything will look darker and enemies will spawn

- Enemies calculate a path towards the player

- If they get stuck, they will recalculate their path after 7 seconds

- Turrets will fire at the enemies if they get within range

- If an enemy gets to the player, nothing happens right now.
