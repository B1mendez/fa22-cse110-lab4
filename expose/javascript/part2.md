1. What will happen at line 12 and why? If the code causes an error, explain why. 
- The console log will return 3 because the for loop went through three iterations. The length of prices was three therefore the for loop went through 3 iterations. 

2. What will happen at line 13 and why? If the code causes an error, explain why. 
- The console log will return 150. The price will go through the list and at the end of the list (300), will discount 50 percent of 300 which will store 150 in discountedPrice. Therefore the console log will return discountedPrice.  

3. What will happen at line 14 and why? If the code causes an error, explain why. 
- The console log will return 150. The price will go through the list and at the end of the list (300), will discount 50 percent of 300 which will store 150 in finalPrice. Therefore the console log will return finalPrice.  

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.  
-The console log will return [50,100,150] because the for loop will split each value in the list. The discounted price is 50% and the loop will go through three iterations. 

5. What will happen at line 12 and why? If the code causes an error, explain why. (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)). 
- The terminal will return an error because the variable i is declared as a let variable which is a scope of the block statement. 

6. What will happen at line 13 and why? If the code causes an error, explain why. 
- The terminal will return an error because the variable discountedPrice is declared as a let variable which is a scope of the block statement. This variable is intialized in the for loop thus will not stay a variable outside of the for loop. 

7. What will happen at line 14 and why? If the code causes an error, explain why. 
- The console log will return 150 because the variable finalPrice is declared as a let variable which stays in the same scope. 

8. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
- The function will return [50,100,150] since each variable initialized with a let variable stays in the same scope of block. The discounted price is 50% and the loop will go through three iterations and store them in the discounted list. 

9. What will happen at line 11 and why? If the code causes an error, explain why. 
- The terminal will return an error because the variable i is declared as a let variable which is a scope of the block statement. 

10. What will happen at line 12 and why? If the code causes an error, explain why. 
- The console log will return 3 because the length is initialized as a const so maintains that value throughout the function. 

11. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
- The function will return [50,100,150] because the for loop will split each value in the list. The discounted price is 50% and the loop will go through three iterations. 

12. Given the above Object, write the notation for: (These should be in your part2.md) 
 - A. console.log(student.name); 
 - B. console.log(student['Grad Year']); 
 - C. console.log(student.greeting());
 - D. console.log(student['Favorite Teacher'].name); 
 - E. console.log(student.courseLoad[0]);

13. Arithmetic 
- A. 32 because 2 is converted to string 
- B. 1 because 3 is converted to int 
- C. 3 because null is converted to 0 
- D. 3null since both are considered strings
- E. 4 because true is converted to 1 
- F. 0 because false is converted into 0 and null is nothing. 
- G. 3undefined because undefined is converted to string 
- H. NaN because undefined is converted to NaN when converted

14. Comparison 
- A. True because 2 is converted to int 
- B. False because both are strings 
- C. True because it is unstricted 
- D. False because it is strict 
- E. False because true is equivalent to 1
- F. True because Boolean(2) is true

15. Explain the difference between the == and === operators. 
- A strict equality operator === checks the equality without type conversion but === performs type conversion before equality check.

16. Given the above Object, write a for...in loop that will iterate through it and print out the value of the property if the property starts with the letter r, or if the value of that property is an odd number. 
```
for (const property in statistics) {
    if (property.charAt(0) == 'r' || statistics[property] % 2 == 1){
        console.log(`${statistics[property]}`);
    }
}
    
 ```

17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result. (This should be in your part2.md). 
- ModifyArray is started of by passing a function as a parameter, doSomething. The function will enter modifyArrays' for loop which will prompt the callback function for the necessary parameter needed in doSomething(num). This will essentially multiply each value is the list by two therefore the returning value will be [2,4,6]. 

18. The above program only prints out the time once when executed. Modify this code such that the program prints out the time every second. 
```
var date = setInterval(() => { 
    console.log(new Date().toLocaleTimeString());
 }, 1000);
 
```

19. What is the output of the above code? (This should be in your part2.md) 
- 1 4 3 2
