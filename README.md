# Pointer-operations
Aim

To study and implement pointer operations (call by refernce and call by value) in C++.
Tools

Visual Studio Code
Theory
Call by Value:

Mechanism: When an argument is passed by value, a copy of the actual argument's value is made and passed to the function's formal parameter. Effect on Original Data: Any modifications made to the formal parameter within the function do not affect the original variable in the calling scope, as the function operates on a separate copy. Syntax: Standard parameter declaration (e.g., void func(int x)).
Call by Reference:

Mechanism: When an argument is passed by reference, the address (or a reference/alias) of the actual argument is passed to the function's formal parameter. This means the formal parameter directly refers to the same memory location as the original variable. Effect on Original Data: Modifications made to the formal parameter within the function do affect the original variable in the calling scope, as both refer to the same data. Syntax: Using the reference operator (&) in the parameter declaration (e.g., void func(int& x)). Alternatively, passing a pointer to the variable allows for similar behavior, where the pointer holds the address of the original variable.
image
Algorithms
Swapping numbers using Call by Value

    Start.

    Input two numbers a and b.

    Call swap(x, y) (values passed).

    Swap occurs inside function but does not affect original variables.

    Print values (remain unchanged).

    End.

Swapping numbers using call by reference

    Start.

    Input two numbers a and b.

    Use a function swap(&x, &y) with references.

    Store x in temp.

    Assign y to x.

    Assign temp to y.

    Print swapped values (original variables get swapped).

    End.

Reversing a string

    Start.

    Input a string.

    Count its length.

    Swap characters from start and end moving towards the center.

    Print the reversed string.

    End.

Salary hike

    Start.

    Input: years completed, research projects, new research projects, company profit.

    Initialize conditions_met = 0.

    Check each condition:

    If years > 1 → increment conditions_met.---If research projects ≥ 1 → increment.---If new projects ≥ 1 → increment.---If profit > 100000 → increment.

    If conditions_met ≥ 3:

    Input current salary.

    Increase it by 20% (using bonus function).

    Print new salary.

    If conditions not met → Print "Not eligible for salary hike".

    End.

Conclusion
We learnt to use pointers in different types of operations . We learnt about 'call by refernce ' and 'call by value' methods .
