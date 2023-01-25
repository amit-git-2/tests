# Weekly coding practice - 1

1. Find maximum number from a list of numbers
    > findMax([2, 4, 6, 100, 2, 8]) => 100
  
1. Return a list of keys from object
    > getKeys({"name" : "A", "age" : 44"}) => ["name", "age"]

1. Check if all numbers in an array are below a threshold (second parameter)
    > checkThreshold([4, 5, 67, 100, 6, 9], 50) => false
    > checkThreshold([4, 5, 67, 100, 6, 9], 500) => true

1. Add all even numbers from the list of numbers
    > addEvens([4, 5, 67, 100, 9]) => 104

1. Add all numbers from the list of numbers, even or odd based on second parameter (onlyEven)
    > addNums([4, 5, 67, 100, 9], true) => 104
    > addNums([4, 5, 67, 100, 9], false) => 81

1. Add two lists. Assume that the first array is shorter in length.
    > addLists([2, 4], [5, 6]) => [7, 10]
    > addLists([2, 4], [5, 6, 100]) => [7, 10]

1. Check if a list has any duplicates
    > hasDups([4, 5, 67, 100, 9]) => false
    > hasDups([4, 5, 67, 4, 100, 9]) => true

1. Return a map (hashtable/object) of number as the key, and value as the number of times it occurs in a list
    > buildFrequencyMap([4, 5, 4, 5, 6]) => { 4: 2, 5: 2, 6 : 1}
    > buildFrequencyMap([4, 5, 8, 5]) => {4 : 1, 5: 2, 8 : 1}




