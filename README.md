A pointer is a variable that stores the address of another variable. In C programming, `int *p` declares a pointer, and `&` is used to get the address of a variable.

In the swapping program, `p = &a` and `q = &b` store the addresses of variables `a` and `b`. The statement `temp = *p` stores the value of `a` in a temporary variable.

Next, `*p = *q` copies the value of `b` into `a`, and `*q = temp` copies the original value of `a` into `b`. Thus, the two numbers are swapped using pointers.
# c-programming-pointers