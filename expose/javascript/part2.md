**1.**
```3```

**2.**
```150```

**3.**
```150```

**4.**
```[50, 100, 150]```
The function applies a 50% discount to each price in the array and stores the result in the `discounted` array.

**5.**
```ReferenceError: i is not defined```
`i` is declared with `let`, which is block-scoped, so it is not accessible outside the `for` loop.

**6.**
```ReferenceError: discountedPrice is not defined```
`discountedPrice` is declared using `let` inside the loop, making it block-scoped. It cannot be accessed outside the loop.

**7.**
```150```

**8.**
```[50, 100, 150]```
Applies the discount, rounds the result, and returns the array of discounted prices.

**9.**
```ReferenceError: i is not defined```
`i` is block-scoped (due to `let`) and only accessible within the loop.

**10.**
```3```
`length` is declared in function scope with `const` and retains the value of the array length.

**11.**
```[50, 100, 150]```
Calculates discounted prices and returns the array as expected.

---

**12. Object Property Notation**

A. `student.name`  
B. `student["Grad Year"]`  
C. `student.greeting()`  
D. `student["Favorite Teacher"].name`  
E. `student.courseLoad[0]`

---

**13. Arithmetic**

A. ```'32'```  
String concatenation.  

B. ```1```  
String is coerced to number.  

C. ```3```  
`null` is coerced to 0.  

D. ```'3null'```  
`null` coerced to string.  

E. ```4```  
`true` is coerced to 1.  

F. ```0```  
Both `false` and `null` coerced to 0.  

G. ```'3undefined'```  
String concatenation.  

H. ```NaN```  
`undefined` coerced to NaN.

---

**14. Comparison**

A. ```true```  
`'2'` coerced to 2.  

B. ```false```  
String comparison.  

C. ```true```  
Loose equality with type coercion.  

D. ```false```  
Strict equality, different types.  

E. ```false```  
`true` coerced to 1, not equal.  

F. ```true```  
Both are strictly equal booleans.

---

**15.**
```==``` compares values after type coercion.  
```===``` compares both value and type without coercion.

**17.**
```[2, 4, 6]```
modifyArray takes an array and a callback function as parameters, It loops over each element in the array (1, 2, 3) and applies the callback to each, doSomething(num) doubles the input (num * 2).

**19.**
```
1
4
3
2
```