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