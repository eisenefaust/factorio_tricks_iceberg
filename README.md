# factorio_tricks_iceberg
speedrun tricks and notes about Factorio 

Based on the [thread](https://discord.com/channels/260103071017730048/1435625958576226405) of the same title in the [Steel Axe discord](https://discord.gg/AntiElitz)

The save file found in [saves/Factorio_Tricks.zip](saves/Factorio_Tricks.zip) has some of the examples listed below along with various useful blueprints available. The mods that are used in the save file are ones that have generally been found useful to plan runs, please read about them on the mod portal or feel free to ask about them in the Steel Axe discord.


- Blueprint to logi request
- Z to single drop (hotkey `z`)
  - spamming `z` on belts to drop items faster
- Combinations of control and left / right click for all inventory or held stack
- Inserter dragging over entities
- Standard 
- Double bindings of keybinds
  - extremely useful for double rotate in 1.1 before they added flip keybinds 
- Standard layouts (common furnace stack, green chip build, labs, mall)
  - standard furnace stack
    - ![standard_furnace_stack](images\standard_furnace_stack.png)
      - Also note that you can partially upgrade the input and output to reduce material cost like this:
      - ![standard_furnace_stack_partial_upgrade](images\standard_furnace_stack_partial_upgrade_red_belt.png)
      - or like this with yellow undergrounds instead:
      - ![standard_furnace_stack_partial_upgrade_undergrounds](images\standard_furnace_stack_partial_upgrade_undergrounds.png)
  - standard steel furnace stack
    - ![standard_steel_furnace_stack](images\standard_steel_furnace_stack.png)
    - partial upgrade works for steel as well, but since slow to produce, don't need to deal with output on this stack build:
    - ![standard_steel_furnace_stack_partial_upgrade](images\standard_steel_furnace_stack_partial_upgrade.png)
  - standard green chip build just before mall
    - ![standard_green_chip](images\standard_green_chip.png)
- Dropping things into another player’s inventory
- Integer overflow
- Double readings of circuits
- Filter order dependant on item id
- Dropping stuff on ground and building over it
- Using item production as counters / limiters for other assemblers in very weird mall setups (like using assemblers in chest and taking them out as a signal, new 100p design)
- Fast replace of belt with splitters or undergounds
  - [Mazmot's trick](https://discord.com/channels/260103071017730048/1435625958576226405/1435649420594122813)
- Prerotate with entities that dont have a rotation
- Belt prio of closer side
  - In combi with that: mixed mining
- When is belt faster than diagonal at blue tier
- Counting items with burner inserters
- Logic requests multiplier
- Storage of item in recipe changed assembler (manual and auto)
- Liquid ouput goes into input when recipe changed and same liquid
- Pumpthrough with chemplant
- Speed modules being soletimes better for quality
- Pppppp (Pantabo's Performant Power Pole Placement Plan) or blipi (Belt Lock Interrupt Placement Interpolation)
  - belt lock 
  - must click and hold on belt as if you are going to drag it, bring cursor out of range, switch entities to what you want to place and then back to original belt. The game will place new entities between where you started to drag belts to where your cursor is, until it is out of range to place the new entity. you switch back to  the belt to have your movement make your cursor attach to the new position of the new belt position so you can place the next row or column of entities. In the example video, a belt is selected and the new entity is yellow inserter or power poles depending on the row, the furnaces are already placed to prevent new entities from being placed in those positions. The upgrade planner is used to prevent placing belts in the empty gaps.
  - [clip](https://discord.com/channels/260103071017730048/260103071017730048/1399409772633260032)
  - [AntiElitz Explaining it](https://www.twitch.tv/videos/2156553379) also \!pppppp or \!blipi in the discord linked above
- Quality filter for nutrients
- Higher tier items not being used as often
- Auto crafter
- Using raw ingedients instead of bulk in rockets
- Common targets in early game
- Scaling fast and balance of mall / Production / science 

- underground belt sideloading

- Using accumulators for speed control
- Speed change of inserters depening on target / giver
- Mixed smelting
- Smoothie pipes
- dragging the flag in a blueprint

- poledancing or poledrag 
  - performed by holding down LMB to drag a power pole, switch to inserter, and then switch back power pole.
  - In 1.1 this was about 14 frames to swap between the two hotkeys, [in 1.1 Anti had power pole bound to RMB](https://www.youtube.com/watch?v=97EaNC_NftA&t=607s) so he could drag with one extra key and have the double binding help him.
  - In 2.0 it's MUCH more precise and is largely not considered worthwhile to perform. This is because it changed to about 7 frames and it now ignroes the first tile you move holding the LMB so it feels extra awkward. [Antipatience explanation](https://discord.com/channels/260103071017730048/260103071017730048/1400352750839009290)
  - [clip](https://www.youtube.com/watch?v=LDg2hQjODmk)
- hogan hook (hooker) and paperclip
  - paperclip performed by drawing a paperclip shape a half stack will look like a letter `U`, `C`, `J` depending on orientation.
  - the hook is then performed by using a flip or double rotate in the middle to place the lane next to you.
  - [clip](https://www.twitch.tv/zaspar_/clip/TacitEphemeralNuggetsChefFrank-QCtG5Hzet-gSjLif) of Zaspar performing hook
  - ![paperclip example](images/paperclip.png)
- smart belt turn off (with pipette and place)
- pick placing or Q placing (hotkey `q`)

- Recyclers adding to total production count
- zippering from Zaspar's TAS
- bot queue management
- Using achievment for esrly warning of attack
- Decon planner specifics in general: ghost types, fruits, items etc
- land mine spam
- wall ship
- Thruster stacking
- Manual wiring of power poles, especially to isolate power networks, like in the old 100% power plant for pumps, and Aquilo for the water bootstrap
- Quality ice
- Trees on vulcanus for achievment
- Nukes for cliffs
- moving the storage chest for faster bot beacon decon
- Cars to bridge lava
- Construction belt
- using boilers to filter fuel from mixed lanes 
- prerotate in general
- inventory compressing with handrafting
- fast feeding personal asm with craftingqueue canceling
- quality speedmodules cutting energy comsumption
- filtering of chests with middle mouse
- inserting modules into beacons with inserters
- Tank requester chests
- Compressors >>> balancers
  - compressor blueprint book in save game and in discord by \!compressorbp
  - ![compressor example](https://i.imgur.com/lzoj6iL.png)
- Landfill in blueprints for outlines and guidelines
- impact of low power on UPS
- Snap to grid for big base alignment 
- power alarm
- impact of changing RAM clock speed on UPS
- pumpless advanced oil setups
- 100+% productivity exploit
- Positive feedback loop of plastic auality with lds
- Using artillery in space to shoot asteroids
  - After like 80 levels of artillery speed and damage, and like 100 artillery with multiple shells each, you can kill a huge asteroid at like 10km/s (From [GlassBricks](https://discord.com/channels/260103071017730048/1435625958576226405/1435632309083705424))
  - can't quite skip railgun yet with it
- Map manipulation; moisture area and dark spots etc
- Aquilo map gen beinh rotational
- P2P trains with only normal rail signals
- Circle station
- Silo chest
- spawn ship chest
- Using red belt for lowered belt delay (as opposed to higher throughput)
- Belt corners being faster
- inserter chain instean of belt
- pollution & chunk mechanics
  - manipulating biter expansion by placing entities in unclaimed chunks (more useful for Death World challenges).
  - great [video explaining this (at 4:40)](https://www.youtube.com/watch?v=SPfP9LN1o8o&t=280s) by Michael Hendriks
- how to enable grid/more hotkey rows/alt mode/disable subgroups/flat inventory etc
- how to disable decoratives

- Color shading for better visibility
 
- Hotkeys and why they (kind of) dont matter
 
- Shooting shipwreck parts in tas
- Mining progress being kept
 
- replays how to enable them and use them 
 
- how to setup several instances
 
- setup shared savegames
 
- The rest settings
 
- Reducing explosions and gun sounds
 
- change preview chunks
 
- unsorting your inventory for more flexibility, very advanced strat
- 1:1 monitor for max visiblility
- Stellar parallax alignment

- The scaling difficulties in factorio: [you cant just build bigger](https://discord.com/channels/260103071017730048/1435625958576226405/1435642406006558881)
  - Going twice as fast requires building twice as much in half the time, so 4 times the building speed
  - The quadratic scaling law

- Micro gaps in belt to allow for sideloading

- [Sushi builds that don't use any circuitry](https://discord.com/channels/260103071017730048/1435625958576226405/1435644090963460346)
- Train tracks vs belt
- Worm dancing or worm wiggle
  - hold `a`/`w` and tap `d`/`s` to wiggle between the two directions. Since spitters target where you are going and not where you are, you will be prevented taking hits from spitters while taking on the biter nests 
- Stacking guns in your gun slots
- 400k steel in one assembler
- Fluid void by recipe change
- skipping the cutscene
- Gravitational pull at halfway point and oddity with the target changing this behavior
- Space platform hub only being sorted when you look at it (causes inserters to grab items in different order from hub if you have looked or not)
- Deconstruction of stuff on space platform voiding it

- Building large basic oil and only doing advanced for lubricant/rocket fuel, skipping cracking
- segmenting your nuclear power plant to mitigate the effects of adding nuclear reactors causing dramatic temperature drops.

- Circuitry being usable via imported blueprint without unlocking circuit network
- research construction bots before you'll get entity ghosts for destroyed entities (biters, Anti running into them with a car, etc)
- shift click for fast research queuing
- the various ways of killing trees instead of mining them
- limit production rate by inserter amout/inserter capacity limiting
- nuking landfill for increased pollution absorption
- lab chaining/boiler chaining
- landfilling offshore pumps
- Zig zag belts for shorter belt delay

- car belts
- abusing biter pathfinding with wall funnels
- offensive land mines
- discharge defense for segmented enemies

- Melee attacking
  - unequip ammo or otherwise attempt to shoot without ammo

- blocking nest spawns with pipe
  - ![nest_pipe_block](images\nest_pipe_block.png)
- use turrets with target filtering set to make your life easy
  - ![turret_nest_filtering](images\turret_nest_filtering.png)
- Double reach when placing belts
  - [clip](https://discord.com/channels/260103071017730048/1435625958576226405/1435654333898293332)
- placing inserters inside stationary cargo wagons
  - [clip](https://discord.com/channels/260103071017730048/1435625958576226405/1435652850398003271)

- demolisher baiting to destroy cliffs
- thruster underfueling for better fuel efficiency
- building rail while driving locomotive
- turret creep
- crafting queue black hole storage
- /permissions to disable handcrafting for lazy bastard
  - can also unset the hotkey
- car driving mode in controls settings

- tips and tricks has lots of good information
  - ![tips_and_tricks](images\tips_and_tricks.png)
- as does Factoriopedia
  - ![factoriopedia](images\factoriopedia.png)
- `e` will confirm the window you are on, useful to quickly accept recipe or set filters or many other things. very useful for "Default Settings" speedruns
- in multiplayer can use `[armor=name]` where name is the player in the chat (press \` to open the chat to enter a command by default)
- `/editor` or `Ctrl + shift + F11`
- `Ctrl + Shift + E` to open prototype explorer to see what is your current game.
  - will open browser to relevant pages in the wiki as needed
- `Ctrl + Shift + F` to open prototype page of entity you are hovering over with your mouse.
  - Can see how much heat something consumes on Aquilo this way!
  - will open browser to relevant pages in the wiki as needed

- [autocrafter circuitry explanation](https://www.twitch.tv/videos/2613056573)


- inserter item throughput and base handsize
  - yellow is 5/6 (0.8333333333) items/s (handsize 1)
  - red is 1.2 items/s (handsize 1)
  - blue is 2.4 items/s (handsize 1)
  - bulk (green) is 2.4 items/s (handsize 2)
  - stack (white) is 2.4 items/s (handsize 6)

- https://www.reddit.com/r/factorio/comments/1oucpvl/psa_you_can_get_33_more_science_for_free_by/


- not speedrun oriented, but a generically useful new player focused video can be found [here](https://youtu.be/E7ShDWXvD4M?si=eOPzi3Ld4NxOTDuR)