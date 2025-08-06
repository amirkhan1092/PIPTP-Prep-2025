# Java Function Outputs and Logic (1-15)

## 1
**Output:** `9`  
**Logic:** `add(2,3)` returns 5, then `add(5,4)` returns 9.

## 2
**Output:** `16`  
**Logic:** Inner `square(2)` returns 4, outer `square(4)` returns 16.

## 3
**Output:** `24`  
**Logic:** Recursive factorial calculation (4×3×2×1).

## 4
**Output:** `15`  
**Logic:** `add(1,2)=3` and `add(2,3)=5`, then `mul(3,5)=15`.

## 5
**Output:** `4`  
**Logic:** Three nested calls to `f()` increment 1 three times (1→2→3→4).

## 6
**Output:** `6`  
**Logic:** Recursive sum (3 + 2 + 1).

## 7
**Output:** `16`  
**Logic:** Recursively calculates 2⁴ (2×2×2×2×1).

## 8
**Output:** `12`  
**Logic:** First `process(3)=6`, then `process(6)=12`.

## 9
**Output:** `6`  
**Logic:** Three nested calls add 2 each time (0→2→4→6).

## 10
**Output:** `15`  
**Logic:** `calc(2)=5` (2²+1) + `calc(3)=10` (3²+1).

## 11
**Output:** `6`  
**Logic:** Recursively finds nearest even number ≤7.

## 12
**Output:** `8`  
**Logic:** `f(3)=4`, then `g(3)` returns 4×2=8.

## 13
**Output:** `15`  
**Logic:** `decide(3)=5` + `decide(6)=10`.

## 14
**Output:** `9`  
**Logic:** Mutual recursion between funA/funB with pattern:  
4 + funB(3) → 3 + funA(1) → 1 + funB(0) → 0.

## 15
**Output:** `true`  
**Logic:** Returns true since 6 is even.