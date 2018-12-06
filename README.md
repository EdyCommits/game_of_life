# TDD - Game of Life

* [] Install dependencies
* [] Setup test directory

* Cell State
  * [] Has an ALIVE state
  * [] Has a DEAD state
* Cell
  * [] Should be initialized with a cell_state
  * [] Should die if it has fewer than 2 live neighbours
    * [] next_state(number_of_neighbours)
  * [] Should live with 2 or 3 live neighbours
  * [] Should die with more than 3 neighbours
  * [] Should come alive with exactly 3 neighbours
* Game
  * [] Should be initialized with a given state
    * [] Array of arrays of states
  * [] Should retrieve a cell at a given row and column
  * [] Should get the number of alive neighbours for a given cell
  * [] Should create the next state of the game

## TODO

* [ ] Game set game state
* [ ] Cell set state
