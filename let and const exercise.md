- What is the difference between **_var_** and **_let_**?

with var you can redeclare and follows a unction scope of rules vs let which you can not redeclare and is viewed in block scope however both var and let you can reassign.

- What is the difference between **_var_** and **_const_**?
  with const you can not reassign or redeclare your variables and must be viewed in block scope also using const, however you can use var to acces a hoisted variable
- What is the difference between **_let_** and **_const_**?
  You can reassign with let while const is a bit more strict on it's rules where you can only mutate the variable
- What is hoisting?
  It’s the way that we explain how the JS compiler works. Variables are lifting or “hoisted” to the top of the scope they are declared in. When using **_var_**, you can access the variable name and it’s undefined value before it is used later on.
  Function declarations are also hoisted and can be invoked “before” they are defined in a codebase.
