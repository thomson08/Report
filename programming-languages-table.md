# A Table of Programming Languages

| Language     | Static Typing  | Strong Typing | Type Inference | Polymorphism                   | Garbage Collection | Concurrency       | Compiled/Interpreted | Performance  |
|:------------:|:--------------:|:-------------:|:--------------:|:------------------------------:|:------------------:|:-----------------:|:--------------------:|:------------:|
| Fortran      | Static         | Strong        | No             | Ad-hoc, Parametric             | No                 | No                | Compiled             | Native       |
| Go           | Static         | Strong        | Yes            | Parametric                     | Yes                | Green Thread      | Compiled             | High         |
| Rust         | Static         | Strong        | Yes            | Ad-hoc, Parametric, Traits     | No                 | Async + Threads   | Compiled             | Native       |
| ML/SML       | Static         | Strong        | Yes            | Ad-hoc, Parametric             | Yes                | No                | Both*                | High         |
| OCaML        | Static         | Strong        | Yes            | Ad-hoc, Inheritance, Parametric | Yes               | Threads           | Both*                | High         |
| Haskell      | Static         | Strong        | Yes            | Ad-hoc, Parametric, Type Classes | Yes              | Async             | Both*                | High         |
| F#           | Static         | Strong        | Yes            | Ad-hoc, Inheritance, Parametric, Type Classes | Yes | Async + Threads   | Both*                | High         |
| Simula       | Static         | Strong        | No             | Inheritance                    | No                 | No                | Compiled             | Native       |
| Eiffel       | Static         | Strong        | No             | Ad-hoc, Inheritance, Parametric | Yes               | No                | Compiled             | Native       |
| Java         | Static         | Strong        | No*            | Ad-hoc, Inheritance, Parametric | Yes               | Threads           | Just-In-Time         | Medium       |
| C#           | Static         | Strong        | No*            | Ad-hoc, Inheritance, Parametric | Yes               | Async             | Just-In-Time         | Medium       |
| Objective-C  | Static         | Strong        | No*            | Ad-hoc, Inheritance           | Yes                 | Threads           | Compiled             | Medium       |
| Swift        | Static         | Strong        | Yes            | Ad-hoc, Inheritance, Parametric | Yes               | Async             | Compiled             | High         |
| Nim          | Static         | Strong        | Yes            | Ad-hoc, Inheritance, Parametric  | No               | Threads           | Compiled             | Native       |
| Scala        | Static         | Strong        | Yes            | Ad-hoc, Inheritance, Parametric, Subtype, Type Classes, Traits | Yes  | Actors | Just-In-Time  | Medium       |
| COBOL        | Static         | Weak          | No             | No                             | No                 | No                | Compiled             | Native       |
| C            | Static         | Weak          | No             | No                             | No                 | No                | Compiled             | Native       |
| C++          | Static         | Weak          | No*            | Ad-hoc, Inheritance, Parametric, Subtype | No       | Threads           | Compiled             | Native       |
| Erlang       | Dynamic        | Strong        | No             | Ad-hoc                         | Yes                | Green Threads     | Compiled             | Medium       |
| Elixir       | Dynamic        | Strong        | Yes            | Ad-hoc                         | Yes                | Actors            | Interpreted          | Medium       |
| Lisp         | Dynamic        | Strong        | No             | Ad-hoc, Subtype                | Yes                | No                | Both*                | Medium       |
| Smalltalk    | Dynamic        | Strong        | No             | Inheritance                    | Yes                | Threads           | Interpreted          | Medium       |
| Python       | Dynamic        | Strong        | Yes            | Ad-hoc, Inheritance, Parametric| Yes                | Threads + Async   | Interpreted          | Low          |
| Ruby         | Dynamic        | Strong        | Yes            | Ad-hoc, Inheritance            | Yes                | Threads           | Interpreted          | Low          |
| JavaScript   | Dynamic        | Weak          | No             | Ad-hoc, Inheritance            | Yes                | Async             | Just-In-Time         | Low          |
| Perl         | Dynamic        | Weak          | No             | Ad-hoc, Inheritance            | Yes                | Threads           | Interpreted          | Low          |


**Note:**
- Yes*: Haskell has a form of subtyping through type classes.
- No**: Some languages like Java, C#, and Objective-C provide type inference in local contexts but not globally (eg, the use of the `var` keyword in Java and C# or `auto` in C++).
- Both*: Capable of being both compiled and interpreted depending on the implementation.

## Definitions

### Polymorphism

[Polymorphism](https://en.wikipedia.org/wiki/Polymorphism_(computer_science)) is the use of a single symbol to represent multiple different types

- [Ad-hoc](https://en.wikipedia.org/wiki/Ad_hoc_polymorphism): Polymorphism via function overloading or operator overloading.
- [Inheritance](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)): Polymorphism through inheritance.
- [Parametric](https://en.wikipedia.org/wiki/Parametric_polymorphism): Polymorphism through generics or templates.
- [Subtype](https://en.wikipedia.org/wiki/Subtyping): Polymorphism through subtyping.
- [Traits](https://en.wikipedia.org/wiki/Trait_(computer_programming)#Supported_languages): 
- [Type Classes](https://en.wikipedia.org/wiki/Type_class): Polymorphism achieved through type classes (common in functional programming languages).

### Concurrency

- [Threads](https://en.wikipedia.org/wiki/Thread_(computing)#Programming_language_support): The language provides built-in support for concurrency using threads.
- [Async](https://en.wikipedia.org/wiki/Asynchrony_(computer_programming)): The language supports asynchronous programming for concurrency.
- [Actors](https://en.wikipedia.org/wiki/Actor_model#Programming_with_actors): The language uses the actor model for concurrency.
- [Green Threads](https://en.wikipedia.org/wiki/Green_thread#Green_threads_in_other_languages): The language uses green threads for concurrency.

### Performance

- **Native**: Native languages are compiled to the machine code specific to the target architecture. These languages usually offer the highest performance because they can take full advantage of the underlying hardware capabilities.



