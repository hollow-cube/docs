---
sidebar_position: 5
---

# Useful Build Tools

## Terraform
Terraform is our custom rendition of WorldEdit, VoxelSniper, and so on. It has faster performance, bigger selections, 
clipboard rotations, better and more diverse masking capabilities, among many other complex things that are discussed below.

### Custom Tools
For any item, you can bind a selection type to them with `/tool create <type>`, such as loft (bezier surface), cuboid, convex, 
fuzzy, and so on, or even brushes like boulder, cube, etc. Once done, you can choose to add a name to it through `/tool name <name>`. 

### Multiple Clipboards
Let's say that I have a brush boulder tool named “terrain”, and am work on making a mountain with it, but realize halfway 
through that I forgot to move a house out of the way. I can create another tool of type cuboid called “temp” and set a pos1 
and pos2 to cut the house, then, save that cut into a separate clipboard by referencing the name of the tool (//cut temp, 
//paste -a temp, etc). Being able to use multiple tools and clipboards in tandem will open up a lot more building possibilities. 

### Debugging States
Certain block states are unobtainable with our systems, since we do not allow block updates, redstone pulses, and so on. 
To get them, there are a few available methods. First, you can `/give minecraft:debug_stick` to obtain a state editor for 
blocks. Alternatively, with terraform, you can bind that functionality to any item with `/tool create debug_stick`. Lastly, 
there are custom interactions for some blocks to change their states: You can `Shift + Right Click` iron trapdoors, iron 
doors, redstone torches, redstone lamps, campfires, candles, candle cakes, cakes, composters, barrels, pistons, sticky pistons, 
lecterns, and slabs. Furthermore, breaking a full slab block will only delete the half you are looking at, and destroying any block 
that is greater than a 1x1 (tall grass, extended piston, bed, etc.) will only get rid of the half that you clicked.