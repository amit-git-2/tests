# Javascript Quiz - 2

1. What is the value returned from the following function call ?
    - dragonFire([2, 4, 5, 6, 8])

            function dragonFire(nums) {
              var agg = 0;
              for (var i = 0; i < nums.length; i++) {
                if (nums[i] % 2 == 0) {
                  agg += nums[i];
                }
              }
              return agg;
            }
              

