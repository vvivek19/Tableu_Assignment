# Tableu_Assignment
1. Say True or False for the below statements:
• Prescriptive Analytics used to predict the future outcomes?
No
• Base R packages installed automatically? 
No
2. What is Recycling of elements in a vector?

When applying an operation to two vectors that requires them to be the same length, R automatically recycles, or repeats, the shorter one, until it is long enough to match the longer one. Here is an example:
> c(1,2,4)+c(1,6,7,8)
[1]  2  8 11  9
Warning message:
In c(1, 2, 4) + c(1, 6, 7, 8) :
  longer object length is not a multiple of shorter object length
> c(1,2,4,5)+c(1,6,7,8)

The shorter vector was recycled, so the operation was taken to be as follows:
> c(1,2,4,1)+c(1,6,7,8)

[1]  2  8 11  9

3. Give an example of recycling of elements.
When performing vector operations in R, it is important to know about recycling. If you perform an operation on two or more vectors of unequal length, R will recycle elements of the shorter vector(s) to match the longest vector
