# Programming

*All programs have to manage the way they use a computer’s memory while running*

- Some languages have garbage collection that constantly looks for no longer used memory as the program runs; 
- in other languages, the programmer must explicitly allocate and free the memory. 

Rust uses a third approach: 

- memory is managed through a system of ownership with a set of rules that the compiler checks at compile time. 
- None of the ownership features slow down your program while it’s running.
