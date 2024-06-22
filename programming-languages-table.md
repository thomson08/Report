# A Table of Programming Languages


| Language     | Static/Dynamic | Strong/Weak | Subtyping | Polymorphism                   | Garbage Collection | Type Inference | Concurrency         | Compiled/Interpreted | Performance  |
|:------------:|:--------------:|:-----------:|:---------:|:------------------------------:|:------------------:|:--------------:|:-------------------:|:---------------------:|:------------:|
| ML/SML       | Static         | Strong      | No        | Parametric                     | Yes                | Yes            | No                  | Compiled              | High         |
| OCaML        | Static         | Strong      | Yes       | Parametric + Ad-hoc            | Yes                | Yes            | Threads             | Compiled              | High         |
| Haskell      | Static         | Strong      | Yes*      | Parametric + Type Classes      | Yes                | Yes            | Async               | Compiled              | High         |
| Java         | Static         | Strong      | Yes       | Parametric + Subtype           | Yes                | Limited**      | Threads             | Both (JIT)            | Medium       |
| C#           | Static         | Strong      | Yes       | Parametric + Subtype + Ad-hoc  | Yes                | Limited**      | Async               | Both (JIT)            | Medium       |
| Swift        | Static         | Strong      | Yes       | Parametric + Subtype + Ad-hoc  | Yes                | Yes            | Async               | Compiled              | High         |
| Go           | Static         | Strong      | No        | Parametric                     | Yes                | Yes            | Goroutines          | Compiled              | High         |
| Rust         | Static         | Strong      | No        | Parametric + Ad-hoc + Traits   | No                 | Yes            | Async + Threads     | Compiled              | High         |
| Scala        | Static         | Strong      | Yes       | Parametric + Subtype + Type Classes | Yes            | Yes            | Actors              | Both (JIT)            | Medium       |
| C            | Static         | Weak        | No        | No                             | No                 | No             | No                  | Compiled              | High         |
| C++          | Static         | Weak        | Yes       | Parametric + Subtype + Ad-hoc  | No                 | Limited**      | Threads             | Compiled              | High         |
| Elixir       | Dynamic        | Strong      | No        | Ad-hoc                         | Yes                | Yes            | Actors              | Interpreted           | Medium       |
| Lisp         | Dynamic        | Strong      | Yes       | Ad-hoc                         | Yes                | No             | No                  | Both                  | Medium       |
| Python       | Dynamic        | Strong      | Yes       | Ad-hoc                         | Yes                | Yes            | Threads + Async     | Interpreted           | Low          |
| Ruby         | Dynamic        | Strong      | Yes       | Ad-hoc                         | Yes                | Yes            | Threads             | Interpreted           | Low          |
| JavaScript   | Dynamic        | Weak        | No        | Ad-hoc                         | Yes                | No             | Async               | Both (JIT)            | Low          |
| Perl         | Dynamic        | Weak        | Yes       | Ad-hoc                         | Yes                | No             | Threads             | Interpreted           | Low          |

\*Note: Haskell’s type class system provides a form of polymorphism that differs from traditional subtyping found in object-oriented languages.

\**Note: Java, C#, and C++ have limited type inference capabilities, such as the use of the `var` keyword in Java and C# or `auto` in C++.

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
