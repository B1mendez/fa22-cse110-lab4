1. What was the bug?
- The bug was with the num1 and num2 because they were being treated as strings therefore the function was acting as string addition rather than integer addition. 

2. How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use)
- I fixed the following issue by parsing num1 and num2 as integers like let result = parseInt(num1) + parseInt(num2). This allows the variables to change to an int when running the function.
