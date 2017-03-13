This project is intended for sound designers, a library-game-project, where everything but sounds are read-only.

## Usage
1. Create an empty Defold Project and remove all assets but the [game.project.](https://github.com/adamwestman/debeat_example/blob/master/game.project)
2. Modify dependancies to this: ``https://github.com/adamwestman/debeat_example/archive/master.zip,https://github.com/adamwestman/debeat/archive/master.zip``
3. Create a new folder named sounds, [containing a sounds.collection.](https://github.com/adamwestman/debeat_example/blob/master/sounds/)
4. Start adding Debeat, event_handlers, queues and sound components, reacting to the [available sound events.](https://github.com/adamwestman/debeat_example/blob/master/sounds/sound_events.txt)


# RULES
Here's how the game is played!
-----

The level consists of a set of columns with bricks.

The player can link bricks of the same color, up, down, left, right and diagonally.

Linked bricks disappear.

A MAGIC BRICK with move sideways if an opening appears. It will fall down if the brick below
disappears, even if there is a hole to the side.

If there are holes to either side of a MAGIC BRICK, it will slide to the left.

MAGIC bricks automatically link.

The player is done with the level when all the MAGIC BRICKS are linked.

