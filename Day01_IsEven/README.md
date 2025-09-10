# Day 01 - IsEven

### Problem
Write a function that checks if a given integer is even or odd.

- Function name: `IsEven`
- Input: `input1` (integer)
- Output:  
  - Return **2** if `input1` is even  
  - Return **1** if `input1` is odd  

### Solution (Java)
```java
public int IsEven(int input1) {
    if (input1 % 2 == 0) {
        return 2;  // Even
    } else {
        return 1;  // Odd
    }
}
