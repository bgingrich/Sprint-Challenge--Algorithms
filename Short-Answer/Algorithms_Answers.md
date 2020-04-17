#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - while loop is just dependent on the value of n. 1n for while and 1n for a= would make it 2n which reduces to 0(n).


b) O (log n) as loop continues to grow and multiply by 2 0(n) becomes 0(log n).


c) O(n) - initialize (1n), then recursive case (2n), then base case (3n) reduces to O(n).

## Exercise II


number of floors is f
if number of floors is 1
return egg
if number of floors is f + 1
return broken egg

Start by dropping an egg on floor 1 and continue to go up a floor until the egg breaks recursively returning to the floor that is the (broken egg floor - 1)

Runtime complexity should be O(n) as we are only ever looking at the value of f to determine if the egg will be broken or safe.


