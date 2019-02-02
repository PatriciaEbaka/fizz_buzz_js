


Question 1:
    let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
    eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
    The first line reads the fizzBuzz file content
    The second line adds a module export statement for fizzBuzz using the content from line 1

Question 2: 
     let fizzBuzz = new FizzBuzz outside the it block?
     It is outside the context of the the `it` block so that 
     the fizzBuzz instance is accessible to within the whole 
     expect block

Question 3. In your README to the best of your knowledge please explain the difference between using === and == in JS?
    When using triple equals === in JavaScript, we are testing for strict equality. This means both the type and the value we are comparing have to be the same.
    When using double equals in JavaScript we are testing for loose equality. e.g. 77 == '77' // true.


Question 4. In your README to the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?
    The check is moved to the top so that the check for divisibilty by 5 and 3 is fo first
Question 5. In your README to the best of your knowledge please explain the difference between feature and unit test
There are different types of tests you can run on your application. There is unit testing, which focuses on testing the functionality of a little part of your application like a handful of methods or a class.

Question 6. In your README to the best of your knowledge please explain what this following code does
When creating a test, the developer sets what the result SHOULD be when the implemenation code is run with the inputs provided. Expectations link what the developer is expecting to the results of running the implementation code.

Question 7. In your README to the best of your knowledge please explain what expectations in the context of testing are

Question 8. In your README to the best of your knowledge please write a line to line explanation of what is happening in this code

Question 9. In your README to the best of your knowledge please explain what a CDN (Content Delivery Network) is?

