Part1:
    - Style-wise, it looks clean to me. Good job!
    - A small problem I noticed is that you don't filter out the single quote punctuation mark, which is not a major thing, but you were supposed to take it out.
    
Part2:
    - Again, I'm really glad to see good code style.
    - Mean and standard deviation work as expected, which is really good. However, you had a small issue with median. The line to get the median in case the length of the array was even had a small issue. It was calculating 2 indexes, but these indexes were floats, so Python was complaining about that. I fixed it by adding "int(...)" to the values that were causing issues.
    
Part3:
    - Clean way of printing!