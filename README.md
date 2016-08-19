# gerbuls



Which language to use for gameplay code? Existing engine is C++ 

c++:

+1 I am already an expert with C++, and C++ is already used for engine

+2 much better editor than lua/rust

+2 debugger with editor integration vastly better than lua/rust

+1 built in profiler in VS with editor integration

+1 existing types created for engine can be reused

-1 header/src is irritating shit

rust

+3 better lang than lua/c++

+1 more enjoyable to write, since less legacy BS in lang(vs C++), and statically typed(vs lua)

+1 safe from some errors that C++ is not

-1 terrible C API required to communicate with C++ engine


lua

+1 already integrated into project

+1 easy to write

-1 dynamically typed, code can be wrong, but it isn't immediatly obvious. 
I find dynamically typed code more confusing than statically typed code, when I revisit it after some time has passed.

+1 fastest compilation

-0.5 worst performance of the lot, although this shouldn't matter too much for if only used for gameplay

-0.5 GC and type system are severly out of sync with C++'s, causing needless complication

+1 easiest for users to script 

C++: 6

Rust: 4

lua: 2

It seems I should use C++ based on these results:(

