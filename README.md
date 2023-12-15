# monty


[EXTERN] 
extern - used to declare a variable/function that is defined in another source file or compilation unit.

// file1.c
#include <stdio.h>

int count;

void increment() {
    count++;
}

// file2.c
#include <stdio.h>

extern int count;

int main() {
    count = 0;
    increment();
    printf("Count: %d\n", count);
    return 0;
}

[stack] - LIFO
linear data structure that follows <Last In First Out>
insertion& deletion takes place from one end(top)
Statically - array
dynamically - linked list



[queue] - FIFO
linera data structure that follows <First In First Out>
insertion is done from the back(rear end) & deletion is done from the front