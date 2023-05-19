---
sidebar_position: 4
---

# Custom Blocks

## Explanation
Custom blocks are unique implementations added by the server that offer convenient ways to streamline gameplay for specific 
map types. Such an example would be a pressure plate that teleports a player somewhere or gives them specific potion effects.

## How to Obtain
When building a map, you may obtain any block by using `/give`, with the exception of barriers. This includes custom
blocks, which are all prefaced with `mapmaker:` For example, to get a checkpoint for parkour, you would type `/give mapmaker:checkpoint_plate`

## Checkpoints
Marks a new progress point on a parkour map. Once reached, players can manually teleport back at any time, or they will
automatically be teleported back if they fall below the reset height of the checkpoint. By default, this value is set to 
be 5 Y levels lower than the checkpoint, but this can be manually overridden. Note that the value cannot exceed the Y
level of the checkpoint plate itself. 

## Finish Plates
Marks the completion of a parkour map. Once stepped on, the player will finish the course and enter a free-roam 
mode where they can fly and rate the map.
