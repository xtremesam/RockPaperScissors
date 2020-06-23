# Rock Paper Scissors x99

## Project Overview

In this project, you will build all of the logic needed for a more intense version of
Rock Paper Scissors (RPS). Rather than selecting just one of Rock, Paper, or Scissors - each player
will select three moves. Each move will consist of a type (Rock, Paper, or Scissors) as well
as a strength value. Each player will have 99 total points to use as strength between all
three of their moves. For example, an example set of moves might be:

- Move 1: Rock - 30 Strength Points
- Move 2: Rock - 60 Strength Points
- Move 3: Paper - 9 Strength Points

The strength for each move must be at least 1.

After each player's moves are chosen, they will compare moves in the order they were selected. If two moves have different types (for example, Rock vs Scissors), then normal RPS rules will apply (in this case, Rock beats Scissors).
However, if two types are the same, then the move with more strength will win. If both strength values are
equal, then a tie is declared.

The player that wins the majority of the three rounds will be the winner of the game.

## Testing

To run these tests, first open the root project directory in your terminal. Then run `npm install` to install
all necessary testing dependencies (you will only need to do this step once).
Finally, run `npm run test`. You will see a list of tests that ran with information
about whether or not each test passed. After this list, you will see more specific output
about why each failing test failed.

As you implement functionality, run the tests to
ensure you are creating correctly named variables and functions that return the proper values.
The tests will additionally help you identify edge cases that you may not have anticipated
when first writing the functions.
