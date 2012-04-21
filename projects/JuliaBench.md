JuliaBench
==============================================================
http://julialang.org/

"Julia is a high-level, high-performance dynamic programming language for technical computing, with syntax that is familiar to users of other technical computing environments."

 "Julia’s LLVM-based just-in-time (JIT) compiler combined with the language’s design allow it to approach and often match the performance of C/C++."

Julia is a promising and HOT project. However, its benchmark code is suboptimal, in particular its C++ code which servced as the base of its benchmark:
1. There are tons of malloc()/free() that could be avoided. Search for myrand() and its callers.
2. Compile time computation. Search for pisum().

Ref: https://github.com/JuliaLang/julia/blob/master/test/perf/perf.cpp

This inititive is to improve Julia's C++ benchmark code.

In addition to adding your name in the MEMBERS section, please also fork my repo: https://github.com/kennethho/julia

PROPONENT
---------

Thinker

http://www.codemud.net/~thinker/GinGin_CGI.py

MEMBERS
-------

fr3@K

DETAILS
-------


