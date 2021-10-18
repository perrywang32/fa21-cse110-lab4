Questions and Answers for Part 2
1) 3 is printed since i is a var type, meaning that it is a global variable and that there were only 3 elements in the parameter prices, hence only printing 3, the value of i.
2) 150 is printed since it's the last discounted price that is calculated and stored in the discountedPrice variable while going through the for loop.
3) 150 is printed since it's the last final price that is calculated and stored in the finalPrice variable while going through the for loop.
4) Nothing is printed since all the printing messages within the function are commented out. discounted variable will be returned from this function. 
5) An error is caused as the message displays as an uncaught referenceError: i is not defined. i is only defined within the scope of the for loop as a let type and therefore is not accessible outside of the for loop, causing the error to occur.
6) The same error occurs at line 13 as line 12 with the uncaught referenceError saying that discountedPrice is not defined. discountedPrice is only defined within the scope of the for loop as a let type and therefore is not accessible outside of the for loop, causing the error to occur.
7) 150 is printed since it's the last final price that is calculated and stored in the finalPrice variable while going through the for loop. It does not run into an error since it is declared within the scope of the function and the print call occurs within the function. If it wasn't called within the scope of the function, as a let type, finalPrice will also cause an error.
8) Nothing is printed since all the printing messages within the function are commented out. discounted variable will be returned from this function.
9) 
