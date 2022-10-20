# Lab Week 4: Part 2

1. What will happen at line 12 and why? If the code causes an error, explain why. 
    - It will print "3" because after the loop *i = 3* and since the *i* was declared using *var*, it is still in scope.

2. What will happen at line 13 and why? If the code causes an error, explain why.
    - It will print "150" because right the for loop ends, the discounted price is equal to 300 * 0.5 = 150. The variable was also declared using *var*, so it is still in scope.

3. What will happen at line 14 and why? If the code causes an error, explain why.
    - It will print "150" because right before the for loop ends, the discounted price is equal to 300 * 0.5 = 150. Then, the final price is equal to (150 * 100) / 100 = 150. The variable was also declared using *var*, so it is still in scope.

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
    - The function will return the discounted array with values [50, 100, 150]. The *finalPrice* after each loop is pushed to the *discounted* array. 

5. What will happen at line 12 and why?  If the code causes an error, explain why.
    - There will be an error because *i* would not be in scope by being declared using *let*.

6. What will happen at line 13 and why? If the code causes an error, explain why.
    - There will be an error because *discountedPrice* would not be in scope by being declared using *let*.

7. What will happen at line 14 and why? If the code causes an error, explain why.
    - It will print "150" because right before the for loop ends, the discounted price is equal to 300 * 0.5 = 150. Then, the final price is equal to (150 * 100) / 100 = 150. The variable was also declared using *let* while being in the same scope.

8. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
    - The function will return the discounted array with values [50, 100, 150] because the functions iterates over each item and applies at 50% discount. 

9. What will happen at line 11 and why? If the code causes an error, explain why.
    - There will be an error because *i* would not be in scope by being declared using *let*.

10. What will happen at line 12 and why? If the code causes an error, explain why.
    - It will print "3" because there are 3 elements in the prices array. 

11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
    - The function will return the discounted array with values [ 50, 100, 150 ]. because the functions iterates over each item and applies at 50% discount. The *discountedPrice* after each loop is pushed to the *discounted* array.

12. Objects
    - A - student.name
    - B - student["Grad Year"]
    - C - student.greeting()
    - D - student["Favorite Teacher"].name
    - E - student.courseLoad[0]

13. Arithmetic
    - A - ‘3’ + 2 = '32'
      - Since a string comes first, the equation becomes string concatenation 
    - B - ‘3’ - 2 = 1
      - Since you cannot subtract in string concatenation, the equation becomes integer arithmetic
    - C - 3 + null = 3
      - Null is converted to zero
    - D - ‘3’ + null = '3null'
      - Since a string comes first, the equation becomes string concatenation
    - E - true + 3 = 4
      - True is converted to 1
    - F - false + null = 0
      - False and Null are converted to 0
    - G - '3' + undefined = '3undefined'
      - Since a string comes first, the equation becomes string concatenation
    - H - '3' - undefined = NaN
      - Since you cannot subtract in string concatenation, the equation becomes integer arithmetic. Then, undefined becomes NaN and subtracting anything with NaN is NaN

14. Comparison
    - A - '2' > 1 = true
      - The string is converted to an integer
    - B - '2' < '12' = false
      - First char "2" is greater than the first char "1"
    - C - 2 == '2' = true
      - The string is converted to an integer
    - D - 2 === '2' = false
      - === checks compares the two by checking datatype
    - E - true == 2 = false
      - True is converted to 1
    - F - true === Boolean(2) = true
      - Boolean(2) is converted to true

15. == is used for comparing two variables, but ignoring datatype
    === is used for comparing two variables, but it checks datatype

16. *Coding Question*

17. The result will be an array with elements [ 2, 4, 6 ]. First, there is a for loop that pushes elements to *newArr* based on the passed in *array* length. The elements pushed in are called on the passed in *callback* function which doubles the values in the passed in *array*.

18. *Coding Question*

19. 1  
    4  
    3  
    2  