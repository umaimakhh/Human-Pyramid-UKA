# Human-Pyramid-UKA

A human pyramid is a way of stacking people vertically in a triangle. With the exception of the people in
the bottom row, each person splits their weight evenly on the two people below them in the pyramid. For
example, in the pyramid above, person A splits her weight across people B and C, and person H splits his
weight – plus the accumulated weight of the people he is supporting – onto people L and M. It can be
mighty uncomfortable to be in the bottom row, since you'll have a lot of weight on your back! In this
assignment, you will explore just how much weight that is. Let us assume that everyone in the pyramid
weighs exactly 128 pounds.


Write a recursive function – def humanPyramid(row, column): – that takes as input the row and column
number of a person in a human pyramid, then returns the total weight on that person's back. The row and
column are each zero-indexed, so the person at row 0, column 0 is on top of the pyramid, and person M
in the above picture is at row 4, column 2.
Your implementation of humanPyramid must be implemented recursively and must not use any loops.
You may be surprised how little code is required!
