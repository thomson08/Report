# A Table of Programming Languages


| Language     | Static/Dynamic | Strong/Weak | Subtyping | Garbage Collection | Type Inference | Concurrency         |
|:------------:|:--------------:|:-----------:|:---------:|:------------------:|:--------------:|:-------------------:|
| ML/SML       | Static         | Strong      | No        | Yes                | Yes            | No                  |
| OCaML        | Static         | Strong      | Yes       | Yes                | Yes            | Threads             |
| Haskell      | Static         | Strong      | Yes*      | Yes                | Yes            | Async               |
| Java         | Static         | Strong      | Yes       | Yes                | Limited**      | Threads             |
| C#           | Static         | Strong      | Yes       | Yes                | Limited**      | Async               |
| Swift        | Static         | Strong      | Yes       | Yes                | Yes            | Async               |
| Go           | Static         | Strong      | No        | Yes                | Yes            | Goroutines          |
| Rust         | Static         | Strong      | No        | No                 | Yes            | Async + Threads     |
| Scala        | Static         | Strong      | Yes       | Yes                | Yes            | Actors              |
| C            | Static         | Weak        | No        | No                 | No             | No                  |
| C++          | Static         | Weak        | Yes       | No                 | Limited**      | Threads             |
| Elixir       | Dynamic        | Strong      | No        | Yes                | Yes            | Actors              |
| Lisp         | Dynamic        | Strong      | Yes       | Yes                | No             | No                  |
| Python       | Dynamic        | Strong      | Yes       | Yes                | Yes            | Threads + Async     |
| Ruby         | Dynamic        | Strong      | Yes       | Yes                | Yes            | Threads             |
| JavaScript   | Dynamic        | Weak        | No        | Yes                | No             | Async               |
| Perl         | Dynamic        | Weak        | Yes       | Yes                | No             | Threads             |

\*Note: Haskell’s type class system provides a form of polymorphism that differs from traditional subtyping found in object-oriented languages.

\**Note: Java, C#, and C++ have limited type inference capabilities, such as the use of the `var` keyword in Java and C# or `auto` in C++.

- **Threads**: The language provides built-in support for concurrency using threads.
- **Async**: The language supports asynchronous programming for concurrency.
- **Actors**: The language uses the actor model for concurrency.
- **Goroutines**: The language supports lightweight threads called goroutines.
- **Green Threads**: The language uses green threads for concurrency.
