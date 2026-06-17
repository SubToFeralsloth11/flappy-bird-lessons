# Established: keyboard input and flap mechanics

User can listen for keyboard events with `addEventListener('keydown', fn)`, identify keys via `event.code`, and use `event.preventDefault()` to suppress default browser behavior (scrolling on Space). User understands the flap mechanic: resetting `birdVelocity` to a fixed negative value (`-7`) on each keypress, which gravity then pulls back downward. User also understands the game-over condition (hitting the ground) and how to restart the game state.

Evidence: User played the interactive flapping sandbox (game over + retry on Space), and completed three quiz questions about event listeners, negative velocity direction, and preventDefault.
Implications: The core game loop is complete. Next lesson introduces pipes -- the obstacles that scroll from right to left.
