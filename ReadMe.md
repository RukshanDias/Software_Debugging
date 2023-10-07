# Software Debugging

-   Most of software dev tasks involes bug fixing.
-   in order to get the bug fix, you have to investigate aka debug on that.

## Types of bugs

-   Syntax errors
-   Tyops / other simple errors
-   Implementation errors
-   Logical errors

## Things to get know before start debugging

-   Recreate the issue & observe
-   confirm it is not the normal behaviour.
-   Have a basic logical solution on how to fix it.

To fix the bug, you have to narrow down the process.

## Debugging techniques [(view)](https://www.shakebugs.com/blog/app-debugging-methods/#Brute_force_method)

-   Brute force - going through line by line
-   Backtracking - start from the bug & go to the root. better for smaller codebase.
-   Binary search - divide & conquer the bug
-   bug clustering - cluster similar patterns
-   Cause elemination method

## Technical debugging tools

-   Debuggers - use to step through code line by line & inspect state of the program.
-   Profilers - Tracks the performence of the application. Speed and effiency
-   Loggers - Records events & msg send by app.
-   Memory analyzers - Track app memory to identify memo leaks & optimize memo usage.
-   Network analyzers - Track & analyse network traffic.
-   Code coveraage tools - test coverage
