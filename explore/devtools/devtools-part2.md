**1.**
The calculateSum() function was receiving num1 and num2 as strings, because .value from an input element returns a string.
JavaScript then did string concatenation ("2" + "3" = "23") instead of numeric addition.

**2.**
Use Number() to convert the values
```
let num1 = Number(document.getElementById("num1").value);
let num2 = Number(document.getElementById("num2").value);
```