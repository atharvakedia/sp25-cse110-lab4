**1.**
```values added:  20```

**2.**
```final result:  20```

**3.**
You should avoid using var because it is function-scoped and allows redeclaration within the same scope.

**4.**
```values added:  20```

**5.**
```ReferenceError: result is not defined```, The result variable was declared using let inside the if block. Since let is block-scoped, the variable is not accessible outside the block. Therefore, when line 13 tries to log result, it throws a ReferenceError.

**6.**
```TypeError: Assignment to constant variable.``` The variable result is declared using const, which means it cannot be reassigned. However, line 7 tries to reassign it with result = num1 + num2, leading to a TypeError. The program will crash at line 7 and never reach line 9.

**7.**
No Output, The function throws a TypeError at line 7 due to trying to reassign a const variable. Because of this runtime error, line 13 is never reached, and nothing is printed.
