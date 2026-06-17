# Established: game loop and falling physics

User understands the animation loop pattern: `requestAnimationFrame` calling `update()` and `draw()` at 60fps. User can model gravity-driven falling motion using three variables: `birdY`, `birdVelocity`, and `gravity` -- where gravity accumulates into velocity, and velocity accumulates into position. User demonstrated this through the live sandbox, console experimentation, and quiz answers.

Evidence: User watched the falling bird demo, manipulated gravity via buttons and browser console, and completed three quiz questions about variable updating and acceleration.
Implications: Next lesson introduces keyboard input (`keydown` event) to let the bird flap upward -- this is the final core ingredient needed before building the full game.
