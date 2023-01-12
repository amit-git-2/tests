# Javascript Quiz - 2

1. How will you represent/store the current temperature in code ?

1. Temperature readings get done once per hour. How will you model hourly temperatures in a single day ?

1. Find the bug in this code. What's missing ?
    - sumEvens([2, 4, 5, 6, 8])

            function sumEvens(nums) {
              var agg = 0;
              var i = 0;
              while (i < nums.length) {
                if (nums[i] % 2 == 0) {
                  agg += nums[i];
                }
              }
              return agg;
            }

1. What's the value of this expression ?
    - om(namah(shivay(8)))
              

           function om(n) {
             return n * 4;
           }
           function namah(n) {
             return n / 4;
           }
           function shivay(n) {
             return n * 2;
           }

1. What is the decimal value of a binary number `1010` ?  
   Hint: 245 decimal is 2 * 10^^2 + 4 * 10^^1 + 5 * 10^0


1. How will you represent/store a point in 2D space (x, y coordinates) ?

1. What's the return value of the following expression ?
    - justDoItForNike("shoes")


        function justDoItForNike(item) {
          let price = 10;
          if (item == "tshirt") {
            price = 50;
          } else if (item == "shoes") {
            price = 100;
            console.log("Checking out shoes. Please pay " + price + " amount")
          } else {
            console.log("invalid item. But please pay " + price + "anyways")
          }
        }

