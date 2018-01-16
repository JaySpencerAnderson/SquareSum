# SquareSum
## Arrange a sequence of monotonicall increasing ordinal numbers from 1 to N so that
##  each pair of adjacent numbers adds to a square.

[The Numberphile youtube channel suggested this exercise.](https://www.youtube.com/watch?v=G1m7goLCJDY&t=457s)

As an introduction to graph theory, try sorting the numbers from 1 to 15 so that each
pair of adjacent numbers sums to a square.

Warning: Here comes the spoiler...
Start with either 8 or 9.
8, 1, 15, 10, 6, 3, 13, 12, 4, 5, 11, 14, 2, 7, 9
End of spoiler.

I didn't yet complete watching the video.  I just charged ahead and wrote a Javascript
program that uses a brute force method of calculating every possible path.  The one
caveat is that if the sequence is a loop and can start with any number, I always start
on 1 to limit the number of combinations.  I also limit how high you can go as this gets
slower and slower the larger the number is.

So future plans are
- Watch the remainder of the video.
- Figure out how to implement a graph theory way of working this out and graph.
- Keep working with graph theory.  This could lead to generative design and thence to 3D printing.

[Try out the page](http://htmlpreview.github.io/?https://github.com/JaySpencerAnderson/SquareSum/blob/master/SquareSum.html)
