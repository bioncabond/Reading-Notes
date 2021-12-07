Class Reading 02:  
Testing and Modules

##In test We Trust

- Unit test are some pieces of code to exercise the input, the output and the behavior of our code.
- Test Driven Development (TDD) is a strategy to think(and write) test first.
- Some details to pay attention to:
  - Test name: be descriptive and state what is expected and what we are testing.
  - The test file name should follow the same name of module name.
    - i.e name.py should have the test file of test_name.py
      mymodule/
      — module.py
      — another_folder/
      — — another_module.py
      tests/
      — test_module.py
      — another_folder/
      — — test_another_module.py
  - Structure: widely used the the AAA:
    - Arrange: organize the data needed to execute that piece of code(input)
    - Act: here you will execute the code being tested (exercise the behavior)
    - Assert: after execution the code, you will check if the result (output) is the same as you were expecting
- The Cycle is made my 3 steps:
  - 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
  - ✅ Write the feature and make the test pass! (you can dance after that)
  - 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)
- When/if the test fails just focus on making the test work and no the entirety of the feature and get the right answer.
- Code is more reliable if you run you test as you develop

##What does the if **name** == “**main**”: do?

- Before executing code, Python interpreter reads source file and define few special variables/global variables.
- If the python interpreter is running that module (the source file) as the main program, it sets the special **name** variable to have a value “**main**”. If this file is being imported from another module, **name** will be set to the module’s name. Module’s name is available as value to **name** global variable.
- A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended.
- You can test whether your script is being run directly or being imported by something else by testing **name** variable.
- Every Python module has it’s **name** defined and if this is ‘**main**’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
- If you import this script as a module in another script, the **name** is set to the name of the script/module.
- Python files can act as either reusable modules, or as standalone programs.
- if **name** == “main”: is used to execute some code only if the file was run directly, and not imported.
  Recursion
- The process in which a function calls itself directly or indirectly
- The base case has to be reached for defined or the stack overflow problem will surface.
- Direct recursive if the function calls the same function
- Indirect recursive calls another function and if it is called directly or indirectly.
- A recursive function is tail recursive when recursive call is the last thing executed by the function.
- When any function is called from main(), the memory is allocated to it on the stack
- Main disadvantage: recursive programming has greater space requirement than iterative program as all functions will remain in the stack until the base case is reached
- Main advantage: recursive programming is coal and simple. We can write codes iteratively with the help of a stack data structure.

##What on Earth is Recursion?

- Recursion would not work if there was not more that 1 n(parameter/argument).
- These all have to be treated and kept separately
- As the computer runs or organizes the stack, it funnels down until it recognizes a value to help discern the value of the next level down/preceding in the stack. At that point it works its self back up to the original n in input (in this example factorial 4)
- In the pending multiplier in this example, each frame of the stack is holding onto a different value of n
