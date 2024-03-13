# WritingTestSpecifications
          Unit tests:
  
      multiplication Function:
  
  1, Expect multiplication of two positive integers to be correct:
      Expect multiplication(3, 5) to be 15
  
  2, Expect multiplication of a positive and a negative integer to be correct:
      Expect multiplication(3, -5) to be -15
  
  3, Expect multiplication of zero and a positive interger to be zero:
      Expect multiplication(0,7) to be 0

  4, Expect multiplaiction of zero and negative inteher to be zero:
      Expect multiplication(0,-6) to be 0
  
  5, Expect multiplication of positive integer and zero to be zero:
      Expect multiplication(7,0) to be 0

  6, Expect multiplication of two negative integers to be positive:
      Expect multiplication(-4,-6) to be 24

        concatOdds Function:
  1, Expect odd numbers from two arrays to be concatenated and sorted:
      Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be [-1, 1, 3, 9, 15]

  2, Expect an empty array if both input arrays contain only even numbers:
      Expect  concatOdds([2,4,6],[,7,8,4]) to be []
  
  3, Expect odd numbers from only one array to be sorted:
      Expect  concatOdds([1,3,5],[]) to be [1,3,5]

  4, Expect duplicated odd numbers to be included in the result array:
      Expect  concatOdds([3,3,3,5,5],[5,5,5,3,3]) to be [3,3,3,3,3,5,5,5,5,5]

  5, Expect only odd numbers to be concatenated and sorted:
      Expect  concatOdds([2,4,6,7],[8,10,13,15]) to be [7,13,15]

        Functonal Test: 
