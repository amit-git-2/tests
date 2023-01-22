# Coding quiz - 2

1. Design data structure to store customer order receipt at a retail store.
  
1. The following code is supposed to add numbers in the two arrays. Find a bug in this code
    > add([2, 4,] [5, 6]]) => returns [7,10]

            function add(arr1, arr2) {
              var result = []
              var i = 0
              while (i < arr1.length) {
                result.push(arr1[i] + arr2[1])
                i++
              }
              return result
            }

1. What's the value of this expression ?
    > mauli(lay(bhari(-8)))
              

           function mauli(n) {
             return n * -1
           }
           function lai(n) {
             return n * 1
           }
           function bhari(n) {
             return n * -1;
           }

1. What is the decimal value of a binary number `11011` ?  

   
1. What's the return value of the following expression ?
    > getImportantMessage(80)


            function getImportantMessage(n) {
              let msg = "Magnus is a genius"
              let i = 0
              for (i = 0; i < n; i++) {
                if (n < 50) {
                  msg = "Donald is a genius"
                } 

                if (n == 75) {
                  msg = "Elon is a genius"
                }

                if (n > 50) {
                  msg = "Narendra is a genius"
                }
              }
              return msg
            }
