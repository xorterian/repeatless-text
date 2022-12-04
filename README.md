# repeatless-text
How to write a book without repeated characters?


Let's put all the characters we wish to use into a grid including 28 edges.

Then let's have the xor-chaining of a given text like the following:

1. The first character remains or be inverted.

2. The grids of the n-th and (n-1)-th characters is xored edgewisely: the edges at the same place xor each other out, the single edges at a place remains, and the emptyness does so.


# Reading


You can read the repeatless text bi-character-wisely: you just need to xor them with each other to get the original character. It can be done by mental skills instead of computer. Of course, needs some practise.


# How repeatless?


If you use 28-edge-grids, 2^28 = 268,435,456 characters can be made. And the expected length when a repeatition comes is its halve.

It means a whole book can be written without repeated characters.

It is also possible to use different grids with more edges, with dots and with curves.

Good luck!
