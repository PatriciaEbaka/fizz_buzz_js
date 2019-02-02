


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
