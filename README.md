# LEETCODE-Maths-2169
### Initial

num1 = 2
num2 = 3
count = 0

---

### Iteration 1

Condition: both > 0 (yes)

* num1 > num2?
  2 > 3 → no

* num1 == num2?
  2 == 3 → no

* else branch triggers → subtract smaller from larger
  num2 = num2 - num1 = 3 - 2 = 1
  count = 1

### State after iteration 1

num1 = 2
num2 = 1
count = 1

---

### Iteration 2

Condition: both > 0 (yes)

* num1 > num2?
  2 > 1 → yes
  num1 = num1 - num2 = 2 - 1 = 1
  count = 2

### State after iteration 2

num1 = 1
num2 = 1
count = 2

---

### Iteration 3

Condition: both > 0 (yes)

* num1 > num2?
  1 > 1 → no

* num1 == num2?
  yes
  count = 3
  break

### Final

num1 = 1
num2 = 1
count = **3**

---

Answer: **3 operations**
