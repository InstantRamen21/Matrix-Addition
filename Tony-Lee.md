How many total thread blocks do we use?
We used [1000/16] = 63. 63 times 63 = 3969 blocks.

Are all thread blocks full? That is, do all threads in the thread block have data to operate on?
No, because 1000/16 was not evenly divisible.

How can this basic Matrix Addition program be improved? (What changes do you think can be made to speed up the code?)
