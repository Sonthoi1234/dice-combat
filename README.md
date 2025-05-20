# dice combat
i don't know when to stop. ideas just keep passing by. i mean, it's a good way to test my Scratch skills after some time not touching it, but you know... Scratch. it's a easy language by itself.
and i get to write more English descriptions that surely no one will ever read! nice!

anyways, the goal of this game is to take all your opponent's tiles.

## starting out
each player starts with a random amount of tiles of their color on a 12x7 board.

the number on a tile indicates their level - that is, how many d6's they will roll when attacking other tiles (or be attacked).
all tiles start with a random level from 1 to 4, and can go up to 9 naturally (where they willhave a crown instead - kind of like, a capital i guess?).

## basic moves
on your turn, you can:
- select a tile and attack neighboring enemy tiles (excluding corners).
- use a skill on one of your tiles.
- if you don't want to do anything else, you can pass to your opponent's move. passing will randomly give your tiles +1 level (and sometimes +2).

## skills
the game has 4 skills with different abilities:

|name|ability|cooldown|
|---|---|---|
|(1st) 1up|level up a tile of your color by +1. 1upping a level 9 tile to level 10 will deal -2 damage to all neighboring enemies, resetting itself back to level 7|20s|
|(2nd) explode|deal -1 level of damage to all neighboring enemy tiles.|30s|
|(3rd) doubling|give 1 of your tiles "double" status. when attacking/defending, double your total damage|60s|
|(4th) advantage|give 1 of your tiles "golden" status. when attacking/defending, roll twice and take the highest of 2 rolls|60s|

for explosion-type skills, if damaged tiles have only 1 level, they become tiles of your color instead (and start from level 1).
