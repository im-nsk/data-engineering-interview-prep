## `list` (Deep Understanding)

1. How is a Python list implemented internally?
2. Why is list append amortized O(1)?
3. What happens internally when a list grows beyond its capacity?
4. Difference between `append()` and `extend()`?
5. Why does `extend()` take more time than `append()`?
6. What is the time complexity of inserting an element in the middle of a list?
7. Why is random access in a list O(1)?
8. What is the difference between `a = b` and `a = b[:]` for lists?
9. Does list slicing create a deep copy or shallow copy?
10. Why does modifying a nested list affect both original and sliced list?
11. What is the difference between `a + b` and `a += b` for lists?
12. Why is deleting an element from the front of a list expensive?
13. How does list resizing affect performance?
14. When should you avoid using lists in data pipelines?
15. Why are lists not thread-safe by default?

---

## `tuple` (Immutability & Tricks)

16. What does immutability mean for tuples?
17. Are tuples completely immutable?
18. Why are tuples faster than lists?
19. Why can tuples be used as dictionary keys?
20. When is a tuple NOT hashable?
21. What happens if a tuple contains a mutable object?
22. Why would you choose a tuple over a list?
23. How does tuple immutability help in performance optimization?
24. Can tuples be modified indirectly?
25. How does Python store tuples internally?

---

## `set` (Hashing & Uniqueness)

26. How is a Python set implemented internally?
27. How does a set guarantee uniqueness?
28. Why are duplicate elements ignored in a set?
29. What happens internally when you add an element to a set?
30. Why can’t mutable objects be stored in a set?
31. What happens if two elements have the same hash?
32. Are sets ordered or unordered?
33. Why are set lookups O(1) on average?
34. When should you use a set over a list?
35. What are the limitations of sets in data engineering use cases?

---

## `dict` (Hashing, Collisions, Keys)

36. How is a Python dictionary implemented internally?
37. Why is dictionary lookup O(1) on average?
38. What is hashing and how is it used in dictionaries?
39. What is a hash collision?
40. How does Python handle hash collisions?
41. Why do collisions not cause data loss in dictionaries?
42. Why must dictionary keys be immutable?
43. What happens if a dictionary key changes its hash value?
44. Can a tuple be used as a dictionary key? When not?
45. Why can’t a list be used as a dictionary key?
46. What is the worst-case time complexity of dictionary operations?
47. How does Python maintain performance even with many keys?
48. What are common mistakes developers make with dictionary keys?
49. How does dictionary resizing affect performance?
50. Why are Python dictionaries heavily used in data pipelines?