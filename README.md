# Debugging Assessment 7

These are the bug that I found:

1. Syntax error: js line 3 to 6
   Found on the first sight to the code. Missing # to call correctly the id in HMTL.

2. Syntax error: js line 3
   Found error in console pointing to incorrect line. It was used two different quotes " and '.

3. Syntax error: js line 4
   Found error in console pointing to incorrect line. querySelector wasn't written correctly.

4. Runtime error: js line 17
   Found on console data.temp is undefined because we need to follow the order of the object: data.main.temp
   Moreover, it's better to use Math.round() to avoid decimals in out temperature.

5. Syntax error: js line 19
   Found reading the code. If we write the name of the function with ${} then we will have to write this quotes specifically ``.

6. Logical error: js line 28
   Found reading the conditionals. Below 0 is <.

7. Logical error: js line 30
   Found reading the conditionals. Correct the conditional and finish it to make it between 0 and 10.

8. Logical error: js line 32
   Found reading the conditionals. Correct the conditional and finish it to make it more than 10 until 20.

9. Syntax error: js line 40
   Found error in console pointing to incorrect line. Parameter without parenthesis.

10. Runtime error: js line 41
    Used the console.log to find out that the parameter wasn't use.
