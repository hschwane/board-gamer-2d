# generic_fork_of_Board_Gamer_2d_name

Fork of thejoshwolfe's 2d multiplayer html5 board game simulator.

## Status

Working:

 * Create and join rooms. Empty rooms are deleted after an hour.
 * Some objects are supported out of the box: Deck of 52 playing cards, d6 dice, checker board and checkers.
 * Decent controls to manipulate objects: Examine, group together, spread apart, move around, flip over.
 * RNG Controls: Shuffle a stack, roll objects to show a random side.
 * Multiplayer experience is synced when you let go of the mouse, requiring fairly low network traffic.
 * Objects can be "locked" to serve as a background, and they can define a snap-to-grid area.
 * Individual players can have a special area where only they can see all sides of the objects in it;
   in other words, their hand of cards is hidden from opponents.
 * Undo/redo history is maintained server-side per room, and is accessible by any client even after joining late or refreshing the page.


