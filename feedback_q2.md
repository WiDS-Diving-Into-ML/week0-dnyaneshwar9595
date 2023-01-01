# Feedback for Problem 2

* The standard csv way to read a file is to use the reader class in the csv module, but if you observe the data, it's almost like a text file, just that it's structured column-wise as well.
* So a nice way to read this (especially since it has no header, which csv files usually have) is to treat it like a text file and read it line by line into a list, and then split the string with the ',' character, and you get what you want.

* About grouping, your solution is the one that I expected, and that's the 10 iterations loop one. Nice use of the np.where function.
* To completely avoid loops, there are these stack-overflow posts : https://stackoverflow.com/questions/49372918/group-numpy-into-multiple-sub-arrays-using-an-array-of-values and https://stackoverflow.com/questions/49141969/vectorized-groupby-with-numpy?noredirect=1&lq=1, which both talk about grouping an array using another array's values. Have a look at them and feel free to message me incase you don't understand.

* Nice that you used a dictionary, just a question that I'll pose : If you know that the number of images in each group is the same, would you have tried something else to speed up the process? (You probably know it since that's why you used a dictionary, but just checking :) 

* Overall, I think you've done all that I wanted you to do, so good job! Hope that you learnt something (or will learn something from the groupby thing :) ) and looking forward to your submissions for the next assignments!
