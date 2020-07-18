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
        
1. Using variable 'menu', how will you 
    - print out what's for lunch on Friday ? (Hint. console.log('...') function prints the output)
    - Write code to swap Saturday and Sunday lunch since Chick-fill-e is closed on Saturday.

            var menu = {
                'Mon' : {
                   'breakfast' : 'pohe',
                   'lunch' : 'eggs',
                   'dinner' : 'khichadi'
                },
                'Tue' : {
                    'breakfast' : 'eggs',
                    'lunch' : 'salmon',
                    'dinner' : 'salad'
                },
                'Wed' : {
                    'breakfast' : 'eggs',
                    'lunch' : 'chicken',
                    'dinner' : 'daal-rice'
                },
                'Thu' : {
                    'breakfast' : 'oats',
                    'lunch' : 'daal-rice',
                    'dinner' : 'chicken'
                },
                'Fri' : {
                    'breakfast' : 'pohe',
                    'lunch' : 'pasta',
                    'dinner' : 'daal-rice'
                },
                'Sat' : {
                    'breakfast' : 'eggs',
                    'lunch' : 'veggie-grill',
                    'dinner' : 'khichadi'
                },
                'Sun' : {
                    'breakfast' : 'eggs',
                    'lunch' : 'Chick-fill-e',
                    'dinner' : 'noodles'
                }
            }

