# Javascript Quiz - I

1. Find values of the variables at the end of this program ?
    - c = ?
    - d = ?

            var a = 4;
            var b = a;
            var c = b * 4;
            var d = b;
  
1. What is the output of the program ?

        var a = 4;
        if (a < 10 && a > 5) {
           console.log("Good Job")
        } else if (a < 4) {
           console.log("Need to work harder");
        } else {
            console.log("Stop gaming so much");
        }
            
1. Find the number of iterations in this loop ?
    
        var n = 1;
        while (n < 32) {
           console.log(" I am N = " + n);
           n = n * 2;
        }
        
1. What is the output of the following program ?

        function foo(nums) {
           var s = 0;
           for (var i = 0; i < nums.length; i++) {
              s = s + nums[i];
           }
           return s;
        }
        
        var values = [5, 5, 5, 7];
        val retValue = foo(values);
        console.log("Returned value is " + retValue);
        
1. Object
