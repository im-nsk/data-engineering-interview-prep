## Dynamic Typing vs Static Typing

1. Is Python dynamically typed or weakly typed?
2. What does “type is bound to object, not variable” mean in Python?
3. Can a variable change its type at runtime? Give an example.
4. Why does Python allow dynamic typing but still fail at `"5" + 5`?
5. What are the risks of dynamic typing in large production systems?
6. How do product teams mitigate issues caused by dynamic typing?
7. Does Python perform implicit type conversion like JavaScript?
8. How is Python’s typing model different from Java or C++?

---

## Mutable vs Immutable

9. What does mutability mean in Python?
10. Name common mutable and immutable data types.
11. Why are strings immutable in Python?
12. Why can’t a list be used as a dictionary key?
13. Are tuples always immutable?
14. What happens if a tuple contains a mutable object?
15. Why are immutable objects safer in multithreaded systems?
16. How does mutability affect performance and memory usage?

---

## Object References

17. What actually happens when you assign one variable to another in Python?
18. Do variables store values or references?
19. Why does modifying one variable sometimes affect another?
20. How is object assignment different from copying?
21. What is the difference between shallow copy and deep copy?
22. When does Python create a new object vs reuse an existing one?
23. Why does `a = a + [1]` behave differently from `a += [1]`?
24. How do references impact bugs in ETL pipelines?

---

## `id()` and Memory Model

25. What does the `id()` function return?
26. Is `id()` always a memory address?
27. Why can two variables with the same value have different `id()`s?
28. Why do small integers sometimes share the same `id()`?
29. Does same value always mean same object in Python?
30. Can `id()` change during the lifetime of an object?
31. Why does Python intern some objects?
32. How does Python optimize memory for immutable objects?

---

## `is` vs `==`

33. What is the difference between `is` and `==`?
34. When should `is` be used?
35. Why is `x is None` preferred over `x == None`?
36. Can `==` be overridden? What about `is`?
37. Why should `is` never be used for numeric comparison?
38. Why does `256 is 256` return True but `257 is 257` may return False?
39. Is `is` a value comparison or reference comparison?
40. What problems can arise from misusing `is`?

## System / Real-World Framing

47. Why do mutability and object references matter in data pipelines?
48. How can misunderstanding references corrupt data in ETL jobs?
49. How does Python’s memory model impact performance at scale?
50. What bugs have you personally seen due to mutability or references?