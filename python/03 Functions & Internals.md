## Function Call Stack

1. How does Python manage function calls internally?
2. What is a stack frame in Python?
3. Why does deep recursion cause a stack overflow?
4. What information is stored in a function’s call frame?
5. How does Python know where to return after a function finishes?
6. Is Python function execution stack-based or heap-based?
7. How does the call stack differ between recursion and iteration?
8. Can you inspect the call stack at runtime?

## Scope (Local / Global / Nonlocal)

9. What are the different variable scopes in Python?
10. Explain LEGB rule with an example.
11. What happens if a local variable has the same name as a global variable?
12. Why is using `global` discouraged in production code?
13. What problem does `nonlocal` solve?
14. What happens if you modify an enclosing variable without `nonlocal`?
15. How does Python decide whether a variable is local or nonlocal?
16. When would you prefer `nonlocal` over returning values?


## Default Argument Evaluation

17. When are default function arguments evaluated in Python?
18. Why are default mutable arguments dangerous?
19. Explain the default mutable argument bug with an example.
20. How do you safely define default values for lists or dictionaries?
21. Why does Python not reevaluate default arguments on every call?
22. How does default argument behavior impact long-running services?
23. What happens if a default argument is modified inside a function?


## 🔹 `*args` and `**kwargs`

24. What are `*args` and `**kwargs`?
25. How does argument packing and unpacking work?
26. What is the order of arguments in a function definition?
27. Can you mix positional, keyword, `*args`, and `**kwargs`?
28. How do `*args` and `**kwargs` help in API design?
29. What happens if unexpected keyword arguments are passed?
30. How would you forward arguments from one function to another?


## Keyword-Only Arguments

31. What are keyword-only arguments?
32. How do you enforce keyword-only parameters in Python?
33. Why are keyword-only arguments useful in large codebases?
34. What kind of bugs do keyword-only arguments prevent?
35. How do keyword-only arguments improve readability and safety?

## Function Annotations (Conceptual)

36. What are function annotations?
37. Does Python enforce type annotations at runtime?
38. How are annotations used in production systems?
39. What tools benefit from function annotations?
40. Why do product companies encourage type hints in Python?


## Lambda vs Named Functions

41. What are lambda functions in Python?
42. What are the limitations of lambda functions?
43. When should lambdas be avoided?
44. Why are lambdas discouraged for complex logic?
45. How do lambdas affect debugging and readability?


## Closures (HIGH SIGNAL)

46. What is a closure in Python?
47. How does a closure differ from a normal function?
48. How do closures retain access to outer variables?
49. What is the role of `nonlocal` in closures?
50. Why do closures not lose data after the outer function exits?
51. How are closures implemented internally (conceptually)?
52. What are real-world use cases of closures?
53. How do closures help avoid global state?
54. What problems can closures introduce if misused?

## System / DE Context

60. Why do default argument bugs cause serious issues in ETL pipelines?
61. How can closures be used in retry or rate-limiting logic?
62. How do function scopes affect concurrency and shared state?
63. How does misuse of globals impact data consistency?
64. Why do product companies test closures heavily?
