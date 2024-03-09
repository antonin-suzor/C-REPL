# C-REPL
A wrapper-shell around gcc

### The goal
Obtain a fluid C shell (somewhat similar to IDLE for Python), without interpreting the C language. It remains a compiled language, we simply provide a playground/sandbox for it.

### How it works
The user is prompted for C language input, which is put together is C source files, then compiled with gcc, and executed, before prompting the user again.
