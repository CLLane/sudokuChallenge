sudoku = [
         [4,3,5], [2,6,9], [7,8,1],
         [6,8,2], [5,7,1], [4,9,3],
         [1,9,7], [8,3,4], [5,6,2],
         [8,2,6], [1,9,5], [3,4,7],
         [3,7,4], [6,8,3], [9,1,5],
         [9,5,1], [7,4,3], [6,2,8],
         [5,1,9], [3,2,6], [8,7,4],
         [2,4,8], [9,5,7], [1,3,6],
         [7,6,3], [4,1,8], [2,5,9]
         ]

//Vertical Check
  //Take the 0, 3, 6, 9, 12, 15, 18, 21, 24, 27 indecies of the sudoku array.
    //push the first index of each of those arrays into an array if the number doesnt already exist within the array we have pushed too.
    //check that the length of that array is 9 if so return true
      //repeat for indecies 1, 2 of inner arrays,
  //Repeat the above process for indecies 1, 4, 7, 10, 13, 16, 19, 22, 25
  //Repeat the abobve process for indecies 2, 5, 8, 11, 14, 17, 20, 23, 26


//Horizontal Check
  // Push the contents of sudoku[0,1,2] into an array and on every push run a check to see if the integer already exists in the destination array.  If so dont push, and once you have gone through all 9 iterration check the length of the pushed array if 9 then return true. 
    // repeat for the sodoku[3, 4, 5], sodoku[6, 7, 8] etc.

//If at anytime either of these checks return false, break out of the function and return that the puzzle is incomplete/failed. 
