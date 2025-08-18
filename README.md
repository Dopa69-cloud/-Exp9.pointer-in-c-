# Pseudocode algorithm

```
1. create array ar = [10, 20, 30]
2. print value at address ar (i.e., ar[0])
3. set ptr = address of first element of ar
4. for i from 0 to 2:
     a. print value pointed by ptr
     b. increment ptr to next element
5. exit

1.Code-
1.Start

2.Declare an integer variable x and initialize it to 10.

3.Declare a pointer to integer ptr (uninitialized yet).

4.Assign the address of x to ptr → ptr = &x.

5.Print "Value of x: " followed by x.

6.Print "Address of x: " followed by &x.

7.Print "Pointer (ptr) stores: " followed by ptr (should match &x).

8.Print "Value at ptr (*ptr): " followed by *ptr (dereference → current value of x).

9.Update via pointer: set *ptr = 20 (this changes x to 20).

11.Print "New value of x: " followed by x (now 20).

12.End
