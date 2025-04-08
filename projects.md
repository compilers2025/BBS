# forth

easiest and the most generic: write a forth compiler
compiler should read .fs files, generate .s files, call 'as' and 'ld' to create binaries.
can be written in any language, backend can be for x86_64 but also for any other cpu you'd like. 6502 would be very cool.
list of supported words: +, -, *, dup, swap, tack, neg, drop, over, mod, nip, ., .s

having variables is a plus. this can be supported:

```
variable a
variable b

5 a !       \ store 5 in a
3 b !       \ store 3 in b

a @ b @ + . \ fetch a and b, add them, print result (prints 8)
```

a @ → pushes the value stored in a onto the stack (e.g., 5).

b @ → pushes the value stored in b onto the stack (e.g., 3).

+ → pops 3 and 5 from the stack, pushes 8.

. → pops 8 from the stack and prints it.



# mad-pascal

add another 6502 platform (runtime, since code generator exists)
https://github.com/tebe6502/Mad-Pascal

# cc65
https://cc65.github.io/

add some 6502 machine support.

or, it can be support of cp/m or 6502: https://cowlark.com/2022-10-04-cpm65/index.html



# voc

close one of the following issues:

https://github.com/vishapoberon/compiler/issues/105

https://github.com/vishapoberon/compiler/issues/104

https://github.com/vishapoberon/compiler/issues/100

https://github.com/vishapoberon/compiler/issues/98

https://github.com/vishapoberon/compiler/issues/94


