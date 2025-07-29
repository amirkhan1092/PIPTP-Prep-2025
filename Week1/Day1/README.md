# Week1 - Day 1

## Problems
- Problem 1

What will be the output of the following pseudocode of fun for w = 40 and x = 4?

```pseudo
1. void fun( Integer w, Integer x )
2.   Integer y
3.   Set y = 0
4.   if (x mod w EQUALS 0 || w mod x EQUALS 0)
5.     y = y + 1
6.   Else
7.     y = y + 10
8.   End if
9.   Print y
10. End function fun()
```

## Given:

* `w = 40`, `x = 4`

## Step-by-Step Evaluation:

### Step 1: Initialize y

```pseudo
y = 0
```

### Step 2: Evaluate the condition

```pseudo
x mod w = 4 mod 40 = 4
w mod x = 40 mod 4 = 0
```

Now evaluate:

```pseudo
(4 mod 40 == 0) || (40 mod 4 == 0)
=> (4 == 0) || (0 == 0)
=> FALSE || TRUE
=> TRUE
```

### Step 3: Condition is TRUE

So the control goes to:

```pseudo
y = y + 1 = 0 + 1 = 1
```

### Step 4: Print y

```pseudo
Output = 1
```

## Final Answer:

A. 1

## Summary:

The key to solving this question was to:

1. Understand how `mod` works.
2. Apply the logical OR condition correctly.
3. Plug in the values of `w = 40` and `x = 4`.
4. Evaluate each part of the condition separately and apply logical OR.
5. Follow the flow of the pseudocode accordingly.

- Problem 2

## 📄 Question:
Consider the pseudocode mentioned below. For how many times will the `while` loop be executed?

```plaintext
1.  Integer a  
2.  Set a = 1  
3.  while (a < 5)  
4.      a = a + 2  
5.  end while  
6.  Print a  
```

## 🔍 Options:
- A. 1  
- B. 4  
- C. 2  
- D. 3  

---

## ✅ Correct Answer: **C. 2**

---

## 🧠 Approach:

We need to count how many times the condition `a < 5` is true, and how many times the loop body gets executed.

### Initial value:
- `a = 1`

### Loop condition:
- `while (a < 5)`

Each time the loop runs:
- We increment `a` by 2: `a = a + 2`

---

## 🧾 Conclusion:
The loop is executed **2 times** before the condition becomes false.

So, the correct option is:

### ✅ **C. 2**
