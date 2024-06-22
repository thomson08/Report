# A Table of Programming Languages

| Language     | Static/Dynamic | Strong/Weak | Subtyping     | Type Inference | Polymorphism                   | Garbage Collection | Concurrency         | Compiled/Interpreted    | Performance  |
|:------------:|:--------------:|:-----------:|:-------------:|:--------------:|:------------------------------:|:------------------:|:-------------------:|:-----------------------:|:------------:|
| ML/SML       | Static         | Strong      | No            | Yes            | Parametric                     | Yes                | No                  | Both***                 | High         |
| OCaML        | Static         | Strong      | Yes           | Yes            | Parametric + Ad-hoc            | Yes                | Threads             | Both***                 | High         |
| Haskell      | Static         | Strong      | Yes*          | Yes            | Parametric + Type Classes      | Yes                | Async               | Both***                 | High         |
| Java         | Static         | Strong      | Yes (OO)      | Limited**      | Parametric + Subtype           | Yes                | Threads             | Just-In-Time            | Medium       |
| C#           | Static         | Strong      | Yes (OO)      | Limited**      | Parametric + Subtype + Ad-hoc  | Yes                | Async               | Just-In-Time            | Medium       |
| Swift        | Static         | Strong      | Yes (OO)      | Yes            | Parametric + Subtype + Ad-hoc  | Yes                | Async               | Compiled                | High         |
| Go           | Static         | Strong      | No            | Yes            | Parametric                     | Yes                | Goroutines          | Compiled                | High         |
| Rust         | Static         | Strong      | No            | Yes            | Parametric + Ad-hoc + Traits   | No                 | Async + Threads     | Compiled                | High         |
| Scala        | Static         | Strong      | Yes (OO)      | Yes            | Parametric + Subtype + Type Classes | Yes            | Actors             | Just-In-Time            | Medium       |
| C            | Static         | Weak        | No            | No             | No                             | No                 | No                  | Compiled                | High         |
| C++          | Static         | Weak        | Yes (OO)      | Limited**      | Parametric + Subtype + Ad-hoc  | No                 | Threads             | Compiled                | High         |
| Elixir       | Dynamic        | Strong      | No            | Yes            | Ad-hoc                         | Yes                | Actors              | Interpreted             | Medium       |
| Lisp         | Dynamic        | Strong      | Yes           | No             | Ad-hoc                         | Yes                | No                  | Both***                 | Medium       |
| Python       | Dynamic        | Strong      | Yes (OO)      | Yes            | Ad-hoc                         | Yes                | Threads + Async     | Interpreted             | Low          |
| Ruby         | Dynamic        | Strong      | Yes (OO)      | Yes            | Ad-hoc                         | Yes                | Threads             | Interpreted             | Low          |
| JavaScript   | Dynamic        | Weak        | No            | No             | Ad-hoc                         | Yes                | Async               | Just-In-Time            | Low          |
| Perl         | Dynamic        | Weak        | Yes (OO)      | No             | Ad-hoc                         | Yes                | Threads             | Interpreted             | Low          |

\*Note: Haskell’s type class system provides a form of polymorphism that differs from traditional subtyping found in object-oriented languages.

\**Note: Java, C#, and C++ have limited type inference capabilities, such as the use of the `var` keyword in Java and C# or `auto` in C++.

\***Note: Depending on the implementation, these languages can be either compiled or interpreted, offering flexibility for development and production environments.

## Definitions

### Polymorphism

- **Ad-hoc**: Polymorphism achieved via function overloading or operator overloading.
- **Parametric**: Polymorphism achieved through generics or templates.
- **Subtype**: Polymorphism achieved through inheritance and interface/trait implementations.
- **Type Classes**: Polymorphism achieved through type classes (common in functional programming languages).

### Concurrency

- **Threads**: The language provides built-in support for concurrency using threads.
- **Async**: The language supports asynchronous programming for concurrency.
- **Actors**: The language uses the actor model for concurrency.
- **Goroutines**: The language supports lightweight threads called goroutines.
- **Green Threads**: The language uses green threads for concurrency.
