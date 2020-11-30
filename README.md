# benford-collatz-experiment
This one's a doozy.

The collatz sequence goes like this:
  1. Take a number
  2. If number is even, divide by two.
  3. If number is odd, multiply that number by three, then add one.
For SOME REASON, this sequence will always return to one.

Benford's law dictates that for data sets, a large portion of the numbers will start with one.

This little piece of code, completes the collatz sequence for all numbers in a range.
Now we have the number of steps it took to get there for each number.
We then graph the first digit for each of those "step-numbers" on a bar graph.

It looks real weird, I'll tell you that.
But unfortunately it doesn't follow benford's law.
