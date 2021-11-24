# LOOP
## Property

**This feature is still a work in progress.**

When an object is LOOP, it considers tiles at opposite edges of the level to be adjacent to each other.

**Example:** When ROCK IS LOOP and ROCK IS PUSH, and ROCK is on a tile in the right-most column of the level, and the tile in the left-most column on the same row is a valid destination to be pushed to, ROCK can be pushed to the right.  Rather than entering the level border, it will appear in the corresponding tile in the left-most column.

Conditions like NEAR and FACING work with LOOP to consider tiles on looped edges. **(NOT YET IMPLEMENTED)**

When TEXT IS LOOP, sentences can be formed across looped edges. **(NOT YET IMPLEMENTED)**

When LEVEL IS LOOP, all objects within the level will consider edges to be looping. **(NOT YET IMPLEMENTED)**
