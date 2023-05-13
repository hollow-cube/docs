---
sidebar_position: 1
---

# Synopsis

Map Maker is a place where people can create Minecraft maps of three archetypes: Building, Parkour, and Adventure. 
It is not a place for custom minigames or full-on gamemode experiences. It takes the archetypal concept of the map 
types and builds upon them. We offer a platform where people can share their work, get feedback, improve by seeing 
others' work, and find other users to connect with and play or build things together. There is no true end goal or 
objective. People can climb leaderboards or aim for the best stats, but the main gimmick of the mode is just to have 
fun. And seeing how this gamemode relies on mostly user-generated content, there is theoretically infinite fun - 
everything will be community-driven and maintain itself.
## Building Maps
We allow people to create fine art builds with our many custom-building utilities. 

### Building Tools
In Terraform, our custom rendition of WorldEdit, Arceon, MetaBrushes, and so on, you can have multiple tools at once, each with its own custom name to reference in command syntax. For each tool, you can bind a selection type to them, such as bezier surface (loft), cuboid, convex, fuzzy, and so on, or even brushes like boulder, cube, etc. Every point you set, everything you create, copy, move, set, and whatever else, is all in a separate session bound to the tool that you used. For example, if I have a brush boulder tool named “terrain” and work on making a mountain with it, but realize halfway through that I forgot to move a house out of the way, I can create another tool of type cuboid called “temp” and set a pos1 and pos2 to cut the house. That clipboard and its history will be saved under the same name (//undo 1 temp, //paste -a temp, etc). As such, any undo or other commands for my original tool named “terrain” will be completely separate, but I can use both tools in tandem. This opens up a lot more possibilities when it comes to building, especially since there will be clipboard rotations, better and more diverse masking capabilities, and faster performance, among a bunch of other cool new stuff.

## Parkour Maps
We have built-in features that offer more than vanilla gameplay, such as checkpoints, timers, course leaderboards, mechanics like only sprint that reset people if they stop sprinting, custom blocks like moving platforms or crumbling blocks, executors that give people potion effects or do other unique things, and so on. All of these extend off of the parkour archetype and only attempt to enhance it. 

## Adventure Maps
