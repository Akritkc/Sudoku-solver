# Sudoku-solver using backtracking

  # our puzzle is a list of lists, where each inner list is a row in our sudoku puzzle
  
  # step 1: choose somewhere on the puzzle to make a guess
  # step 1.1: if there's nowhere left, then we're done because we only allowed valid inputs
  # step 2: if there is a place to put a number, then make a guess between 1 and 9
  # step 3: check if this is a valid guess
  # step 3.1: if this is a valid guess, then place it at that spot on the puzzle
  # step 4: then we recursively call our solver!
  # step 5: it not valid or if nothing gets returned true, then we need to backtrack and try a new number
  # step 6: if none of the numbers that we try work, then this puzzle is UNSOLVABLE!!
