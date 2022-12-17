# Ray Tracing
This repo is meant to host implementations of the simple ray tracer from [RTOW](https://raytracing.github.io/) in all the languages that I'm at least half-decent in. A ray tracer is a perfect candidate for language anthologies IMO for a couple of reasons,

1. Most similar endeavors that I've come across are done with simple algorithms that rarely span multiple files. This flattens out the differences between some languages e.g., C and C++. 
1. The ray tracer from RTOW is especially fun in that you get to play with all kinds of polymorphism to your heart's content. I can't remember the last time I saw a generic implementation of FizzBuzz that makes justified use of operator overloading. 
1. I try to follow the idioms and conventions specific to the languages to the best of my ability. I think a ray tracer written this way is a decent way to benchmark languages, as opposed to making 1:1 copies of some original code snippet and ultimately just measuring the performance of runtimes.
1. I just really, really like these books. The first one was the most fun I've ever had with any programming book, period. 

None of the implementations are complete, and I haven't actually gone through all the books yet. But I hope to get done with 5+ languages by the end of 2023.

# Line-up
1. **C++ (g++)**
1. Python (CPython) 
1. Go (gc)
1. TypeScript (Deno)
1. C# (.NET Core)
1. A single `docker-compose.yml` to build, run, and benchmark all versions.  
1. Output in SVG instead of PPM for ease of sharing and viewing? 
1. Rust? (rustc) 
1. Clojure? (JVM)
1. Haskell? (GHC)
