# factorio_tricks_iceberg
speedrun tricks and notes about Factorio 

Based on the [thread](https://discord.com/channels/260103071017730048/1435625958576226405) of the same title in the [Steel Axe discord](https://discord.gg/AntiElitz)

The save file found in [saves/Factorio_Tricks.zip](saves/Factorio_Tricks.zip) has some of the examples listed below along with various useful blueprints available. The mods that are used in the save file are ones that have generally been found useful to plan runs, please read about them on the mod portal or feel free to ask about them in the Steel Axe discord.


- Blueprint to logi request
- Z to single drop (hotkey `z`)
- Combinations of control and left / right click for all inventory or held stack
- Inserter dragging over entities
- Standard 
- Double bindings of keybinds
  - extremely useful for 
- Standard layouts (common smelter, gc build, labs, mall)
- Dropping things into another player’s inventory
- Integer overflow
- Double readings of circuits
- Filter order dependant on item id
- Dropping stuff on ground and building over it
- Using item production as counters / limiters for other assemblers in very weird mall setups (like using assemblers in chest and taking them out as a signal, new 100p design)
- Fast replace of belt with splitters or ugs
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
- dragging the flag

- poledancing or poledrag 
  - performed by holding down LMB to drag a power pole, switch to inserter, and then switch back power pole.
  - In 1.1 this was about 14 frames to swap between the two hotkeys, [in 1.1 Anti had power pole bound to RMB](https://www.youtube.com/watch?v=97EaNC_NftA&t=607s) so he could drag with one extra key and have the double binding help him.
  - In 2.0 it's MUCH more precise and is largely not considered worthwhile to perform. This is because it changed to about 7 frames and it now ignroes the first tile you move holding the LMB so it feels extra awkward. [Antipatience explanation](https://discord.com/channels/260103071017730048/260103071017730048/1400352750839009290)
  - [clip](https://www.youtube.com/watch?v=LDg2hQjODmk)
- hogan hook (hooker) and paperclip
  - paperclip performed by drawing a paperclip shape a half stack will look like a letter `U`, `C`, `J` depending on orientation.
  - the hook is then performed by using a flip or double rotate in the middle to place the lane next to you.
  - [clip](https://www.twitch.tv/zaspar_/clip/TacitEphemeralNuggetsChefFrank-QCtG5Hzet-gSjLif) of Zaspar performing hook
  - ![paperclip example](example_images/paperclip.png)
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
- pullution & chunk mechanics