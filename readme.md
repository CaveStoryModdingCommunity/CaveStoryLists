# Cave Story Lists

It's every entity/bullet/song in Cave Story!

In the future it'll also include stuff from Cave Story+.

## Entity List

It's the list of every entity in the game.

[`CaveStoryEntities.tsv`](CaveStoryEntities.tsv) has all the entities in the base game.

Later there will be another file with the entities that Cave Story+ adds.

### PXE/TSC Compatibility

Not all entities work correctly when spawned in using TSC/placed in a PXE file using an editor.

- "Partial" - The entity has reduced functionality when spawned using these methods, such as a lack of direction for projectiles
- "Dummy" - The entity does nothing (returns from the function) if it has no parent
- "Crash" - The game will crash once this entity's code is run


# Credits

- txin - Made the list
- Enlight - Help with ANP, reorganization, research
- Milon Luxy - Help with NPC health
- Cyber - Help with Effects
- Brayconn - Helped reorganize the document