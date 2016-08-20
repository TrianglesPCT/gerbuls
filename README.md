# gerbuls



Which language to use for gameplay code? Existing engine is C++

Choices are: C++, Rust, lua

c++:

+1 I am already an expert with C++, and C++ is already used for engine

+2 much better editor language support than lua/rust(Visual Studio/VAX vs sublime with pluggins)

+2 debugger with editor integration vastly better than anything I've found for lua/rust

+1 built in profiler in VS with editor integration

+1 existing types created for engine can be reused

-1 header/src is irritating shit



rust

+3 more modern lang than lua/c++(Rust has:  ADT's, traits, pattern matching)

+1 more enjoyable to write, since less legacy BS in lang(vs C++), and statically typed(vs lua)

+1 safe from some errors that C++ is not

+1 long term benefit of using rust: less mental tax, unsafety is explicit, thread safe without unsafe

+1 cargo build system is much nicer than the hodgepodge of shit C++ offers

-1 using rust will force 2 build systems instead of 1, negating much of the benefit of cargo

-1 terrible C API required to communicate with C++ engine




lua

+1 already integrated into project

+1 easy to write

+1 easiest for users to script 

+2 fastest compilation

-1 dynamically typed, code can be wrong, but it isn't immediatly obvious. 
I find dynamically typed code more confusing than statically typed code, when I revisit it after some time has passed.

-0.5 worst performance of the lot, although this shouldn't matter too much for if only used for gameplay

-0.5 GC memory management is severly out of sync with C++'s approach, causing needless complication

-0.5 callbacks into lua are complicated by lua VM's being single threaded



C++: 6

Rust: 5

lua:2.5

It seems I should use C++ based on these results:(

