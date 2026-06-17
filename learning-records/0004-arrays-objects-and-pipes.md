# Established: arrays, objects, and scrolling pipes

User understands JavaScript objects (`{ x: 400, gapY: 200 }`) as a way to group related data, and arrays (`[]`) as ordered lists. User can manage a dynamic list of pipes: spawning new ones with `push()`, moving them left each frame, and removing off-screen ones with `filter()`. User understands `Math.random()` for random gap positions, `for...of` loops for iterating arrays, and the `%` (modulo) operator for timed spawning at intervals.

Evidence: User played the interactive sandbox with scrolling pipes, manipulated gapSize/spawnInterval/pipeSpeed via console, and answered three quiz questions about array push, off-screen cleanup, and pipe speed.
Implications: Only two features remain -- collision detection (bird hitting pipes) and score tracking.
