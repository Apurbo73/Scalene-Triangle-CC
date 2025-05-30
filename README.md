### Scalene Triangle CC:

This C++ program checks whether three numbers are **all different** for multiple test cases. Here's a simple explanation:

---

### 🔄 **Step-by-step Explanation:**

1. **Input Test Cases:**
   It first reads an integer `t`, which tells how many test cases will be checked.

2. **Loop Through Each Test Case:**
   For each test case, it reads three integers: `a`, `b`, and `c`.

3. **Check Uniqueness:**

   * It checks if **all three numbers are different** using the condition:
     `a != b && b != c && c != a`
   * If all three are different, it prints `"Yes"`.
   * Otherwise, it prints `"no"`.

---

### 🔍 **Example:**

* Input: `3 4 5` → All different → Output: `Yes`
* Input: `2 2 3` → Two same → Output: `no`

This C++ program checks if three numbers are all different in multiple test cases. It first takes the number of test cases (`t`), then for each case, it reads three numbers: `a`, `b`, and `c`.

If all three numbers are different from each other, it prints "Yes". If any two or more numbers are the same, it prints "no". This helps to quickly check for uniqueness among three values in each test case.
