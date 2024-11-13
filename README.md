# Assignment about Loops

1. Write a for loop to print the numbers 1 through 10.
2. Write a for loop that prints the numbers 10 through 1.
3. Explain the code below. Write a comments to each line.
    ```js
    let sum = 0;
    for (let i = 1; i <= 50; i++) {
        sum += i;
    }
    console.log(sum);
    ```
4. How many iterations are in the loop below? Explain.
    ```js
    for (let i = 0; i < 10; i += 2) {
        console.log(i);
    }
    ```
5. What does the break statement do? Explain and give an example.
6. What does the continue statement do? Explain and give an example.
7. Generate and print a random number between 1 adn 100 until you get the number 27;
8. Generate Random Password. HINT - Use ASCII codes to generate random characters.
9. "There is a man somewhere, Find him", Below code generates string with 2 possible characters, `" "` and `"?"`. Write a code that will find the position of `"?"`.
    ```js
    let str = "";
    for (let i = 0; i < 10; i++) {
        str += Math.random() > 0.5 ? " " : "?";
    }
    console.log(str);

    // write code that finds the position (index) of "?".
    // do not use indexOf method!
    // HINT: You can iterate strings' characters using for loop.
    // and you can access each character by using str[i]
    ``` 
10. "Mystery Room", Write a code that will generate 2d representation of a room. you should generate an empty space, wall or a mystery box. You can use any characters you want. The room should be 10x10. The room should have 10 walls, 1 mystery boxes and the rest should be empty space, mystey box location should be random!. The room should look something like this:
    ```
    ##########
    #?       #
    #        #
    #        #
    #        #
    #        #
    #        #
    #        #
    #        #
    ##########
    ```
11. write a program that prints the numbers from 1 to 100. But for multiples of three print "Fizz" instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz".
12. write a program that prints 100 random numbers (each random number should be in the range 1-100).
13. write a program that prints the sum of all even numbers between 1 and 1000.
14. write a program that prints the sum of all numbers between 1 and 1000 that are divisible by 3 or 5.
15. write a program that prints the sum of all numbers between 1 and 1000 that are divisible by both 3 and 5.