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
    - The function will return the discounted array with values [50, 100, 150].

9. What will happen at line 11 and why? If the code causes an error, explain why.
    - There will be an error because *i* would not be in scope by being declared using *let*.

10. What will happen at line 12 and why? If the code causes an error, explain why.
    - It will print "3" because there are 3 elements in the prices array. 

11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
    - The function will return the discounted array with values [ 50, 100, 150 ]. The *discountedPrice* after each loop is pushed to the *discounted* array.

12. Objects
    - A - student.name
    - B - student["Grad Year"]
    - C - student.greeting()
    - D - student["Favorite Teacher"].name
    - E - student.courseLoad[0]

13. Arithmetic
    - A - ‘3’ + 2 = '32'
    - B - ‘3’ - 2 = 1
    - C - 3 + null = 3
    - D - ‘3’ + null = '3null'
    - E - true + 3 = 4
    - F - false + null = 0
    - G - '3' + undefined = '3undefined'
    - H - '3' - undefined = NaN

14. Comparison
    - A - '2' > 1 = true
    - B - '2' < '12' = false
    - C - 2 == '2' = true
    - D - 2 === '2' = false
    - E - true == 2 = false
    - F - true === Boolean(2) = true

15. == is used for comparing two variables, but ignoring datatype
    === is used for comparing two variables, but it checks datatype

16. *Coding Question*

17. The result will be an array with elements [ 2, 4, 6 ]. First, there is a for loop that pushes elements to *newArr* based on the passed in *array* length. The elements pushed in are called on the passed in *callback* function which doubles the values in the passed in *array*.

18. *Coding Question*

19. 1
    4
    3
    2