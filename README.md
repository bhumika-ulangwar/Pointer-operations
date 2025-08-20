##  Aim
To study and implement pointer operations (*call by reference* and *call by value*) in C++.

---

##  Tools
- *Visual Studio Code*
- C++ Compiler (G++/MSVC)

---

##  Theory

### Call by Value
- *Mechanism*: A copy of the actual argument’s value is passed to the function.  
- *Effect on Original Data: Changes inside the function **do not affect* the original variables.  
- *Syntax*:  
  cpp
  void func(int x);
  

### Call by Reference
- *Mechanism*: The function receives a reference (alias) or pointer to the variable, pointing to the same memory location.  
- *Effect on Original Data: Changes inside the function **directly affect* the original variables.  
- *Syntax*:  
  cpp
  void func(int& x);   // using reference
  void func(int* x);   // using pointer
  

---

##  Algorithms

### 1. Swapping numbers using Call by Value
1. Start  
2. Input two numbers a and b  
3. Call swap(a, b) (values passed)  
4. Swap occurs inside the function but *does not affect* original values  
5. Print original values (unchanged)  
6. End  

### 2. Swapping numbers using Call by Reference
1. Start  
2. Input two numbers a and b  
3. Call swap(&a, &b) (address passed)  
4. Swap occurs and *affects* original variables  
5. Print swapped values  
6. End  

### 3. Reversing a String
1. Start  
2. Input a string  
3. Find its length  
4. Swap characters from start and end, moving towards the center  
5. Print reversed string  
6. End  

### 4. Salary Hike Program
1. Start  
2. Input: years completed, research projects, new projects, company profit  
3. Initialize conditions_met = 0  
4. Check conditions:  
   - If years > 1 → increment  
   - If research projects ≥ 1 → increment  
   - If new projects ≥ 1 → increment  
   - If profit > 100000 → increment  
5. If conditions_met ≥ 3 → Input salary and increase by *20%*  
6. Else → Print "Not eligible for salary hike"  
7. End  

---

## Conclusion
We learned how to use *pointers* in different types of operations.  
We understood the difference between *Call by Value* (no effect on original data) and *Call by Reference* (affects original data).
