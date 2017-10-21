# Multi_Stack
This program keeps track of multiple stacks within a specified array size.
Stack sizes are changed when overflow occurs and adjusted depending on usage.
User inputs the upper and lower array bounds, the number of stacks to be within this array, and the upper and lower bounds for the space the stacks will take within the array.
The inputs for the first execution are names. Usable names are specified as an enumeration within code.
    The correct structure for inserting is:
        I1 Smith
        I3 Cho
    And deleting is:
        D1
        D2
    ('I' is "insert" and the number following is the stack number, likewise for 'D' being "delete" then stack number)
The inputs for the second execution are dates,
    The correct structure is:
        I1 January 1 1996
        I4 May 23 1919
    And deleting is:
        D1
        D2
    (same logic as with names)
The current execution will stop upon incorrect input, if the user types "EX", or if the space for all stacks is completely full.
The program will write to a file all operations and the contents of every stack before and after reallocation occurs.
