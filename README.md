# Var-Let-Const

ES2015 Global Constants

const PI = 3.14;
PI = 42; //Uncaught TypeError: Assignment to constant variable


Quiz

1)We can reassign and redeclare with var, but we can not redeclare using let. We can hoist a variable with “var”.

2) We can reassign and redeclare with “var”, but we can not redeclare or reassign using the const keyword. We can hoist a variable with “var”. “Const”,  creates a block-scope.

3) We can reassign with “let”, but we can not redeclare or reassign using the “const” keyword.

4) It’s the way that we explain how the JS compiler works. Variables are ”lifted” or “hoisted” to the top of the scope they are declared in. When using “var”, we can access the variable name and it’s undefined value before it is used later on.
