# Mathbot

I used JavaScripts built in math object to tackle more complex challenges such as : 

1. Math.random(), which generates a random floating-point number between 0 (inclusive) and 1 (exclusive). This means the possible output can be 0 but it will never actually reach 1. 

2. Math.floor() rounds down to the nearest whole integer. 

3. To generate a random integer between two values i made use of the formula Math.floor(Math.random() * (max - min + 1)) + min. The goal is to generate a random number between the min and max values (including both). Math.random() gives a random decimal always between 0 and 0.99999... (max - min + 1) calvulates how many numbers are in the range. Math.random() * (max - min + 1) stretches the random decimal to the right size (0 - 5.999...). Math.floor(...) removes the decimal and rounds down. Now the numbers start at 0 but we want it to start at 5 which is the min value.

4. Math.ceil() rounds up to the nearest whole integer.

5. Math.min() and Math.max() both take a set of numbers and return the minimum and maximum value respectively.
