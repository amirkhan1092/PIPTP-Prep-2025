# Week1 - Day 2

## Question 1

**Approach**:  
a = (10+9)+c → 27  
if (c+b > a-c) → false
Output = a + b + c = 27 + 6 + 8 = 41

**Java**
int a = 2, b = 6, c = 8;
a = (10 + 9) + c;
if ((c + b) > (a - c)) {
    a = b + c;
}
System.out.println(a + b + c); // Output: 41


## Question 2

**Approach**
b = 7, a = 10, b = (7+7)+10 = 24, c = 1+24 = 25
Output = 10 + 24 + 25 = 59


**Java**
int a = 0, b = 2, c = 10;
b = 7 + a;
a = (a + c) + a;
b = (b + b) + c;
c = 1 + b;
System.out.println(a + b + c); // Output: 59


## Question 3

**Approach**
Bitwise operations:
pp = 7, then pp = (7 & 4) ^ 7 = 4 ^ 7 = 3
(6 & 3 & 7) < (7 & 6) = 2 < 6 ⇒ true
(6 ^ 3) < (7 + 6) = 5 < 13 ⇒ true
rr = 4 ^ 3 = 7

Output = pp + qq + rr = 3 + 6 + 7 = 16


**Java**

int pp = 0, qq = 6, rr = 4;
pp = 7 + pp;
pp = (pp & rr) ^ pp;
if ((qq & pp & 7) < (7 & qq)) {
    if ((qq ^ pp) < (7 + qq)) {
        rr = rr ^ pp;
    }
}
System.out.println(pp + qq + rr); // Output: 16



## Question 4

**Approach**
Two if blocks both false.
Final output = 9 + 6 + 10 = 25

**Java**

int a = 9, b = 6, c = 10;
if ((b ^ a ^ c) > (c ^ b)) {
    b = 3;
}
if ((b ^ b ^ c) > (a ^ 4)) {
    a = 7;
}
System.out.println(a + b + c); // Output: 25


## Question 5

**Approach**
First if false
In else, nested if true ⇒ pp = 1 + 8 = 9
Output = 9 + 2 + 17 = 28


**Java**
int pp = 13, qq = 2, rr = 17;
if (pp < (qq + 2)) {
    pp = qq + rr;
} else {
    if ((qq + 2 - 8) < (rr + 1)) {
        pp = qq + 8;
    }
}
System.out.println(pp + qq + rr); // Output: 28


## Question 6
**Approach**
if ((5+4)<(4-5) || (8>4)) ⇒ false || true ⇒ true
q = (4 & 8) & 5 = 0
Output = 8 + 0 + 5 = 13


**Java**
int p = 8, q = 4, r = 5;
if ((5 + 4) < (4 - 5) || (8 > 4)) {
    q = (q & p) & r;
}
System.out.println(p + q + r); // Output: 13



