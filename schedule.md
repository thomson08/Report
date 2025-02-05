# Schedule

## Overview

- In Part 1 of the course, we learn how to write from scratch an interpreter for a simple functional programming language. This interpreter will be built on top of powerful mathematical theories including algebraic data types, recursion, context-free grammars and lambda-calculus. On the way, we will also encounter topics such as structural induction, dynamic programming, interactive theorem proving, dependent types, higher-order functions, Curry-Howard correspondence, Church numerals, Turing completeness, intuitionistic logic, natural deduction and more.
- In Part 2, we will venture into one or more advanced topics. Possible topics include (but are not limited to) concurrency, term rewriting, memory management, type checking and inference, etc. Students will form groups and each group will explore some advanced topic in a project of up to 4 students per group.

## Programming Assignments 

There will be 4 programming assignments: calculator, lambda-caluclus, a functional programming language, and a project. The first two will be individual work, the last two will be done in groups of 4 students.

## Schedule Part 1

The Discrete Mathematics column refers to page numbers of Dr Moshier's lecture notes made available on Canvas. 

|Wk|Big Idea| Technical Notions | Software Tools | Skills |Topic|Homework|Videos|Readings|  Planning| Discrete Mathematics 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | Proof=Program (assuming familiarity with discrete math) || Lean (tactics) || [NNG Tutorial World](https://adam.math.hhu.de/#/g/leanprover-community/nng4) | Finish Tut. World, explain one level in the report | [The Shell, Shell Tools](https://missing.csail.mit.edu/) | [GEB, Ch.1, p.41 (formal system)](https://www.physixfan.com/wp-content/files/GEBen.pdf)| Start on Tue, Lab on Thu | 16, 42-45, 54
|||||
| 2 | Recursion |Algebraic Data Types |Shell| Proof by Induction | [NNG Addition World](https://adam.math.hhu.de/#/g/leanprover-community/nng4/world/Addition/level/0) | Finish NNG2, write levels 4 and 5 out in math notation | [Dynamic Programming, Part I](https://www.youtube.com/watch?v=oBt53YbR9Kk) |[GEB, Ch.5, p.111/135 (recursion)](https://www.physixfan.com/wp-content/files/GEBen.pdf)| Theory on Tue, Lab on Thu | 
|||||
| 3.1 | Programming with LLMs (LLMs as Compiler)  || Git, LLM || Calculator in Python | Calc in Python (individual) | [Git](https://missing.csail.mit.edu/2020/version-control/) | [GEB, Ch.6, p.166 (meaning)](https://www.physixfan.com/wp-content/files/GEBen.pdf)|  Lab |
| 3.2 ||||| [NNG Multiplication World](https://adam.math.hhu.de/#/g/leanprover-community/nng4/world/Multiplication/level/0) |||| Lab  | 
|||||
| 4.1 | Parsing, Abstract Syntax, | CST, AST, LALR, Earley, CYK || Context Free Grammars | parsing pen and paper | Calc via CFG (individual)| [CFGs](https://youtu.be/jf1xhZSpCvg), [parse trees](https://youtu.be/3ZLkPwB_c9g) | [Parsing Timeline](https://jeffreykegler.github.io/personal/timeline_v3) | Theory| 
|4.2|||[Lark](https://lark-parser.readthedocs.io/en/stable/) (parser generator)||Calc with Lark||||Lab
|||||
| 5.1 | Propositions as Types, Dependent Types || Lean (programming language) | $\wedge$ Logic | [Lean logic game ($\wedge$)](https://adam.math.hhu.de/#/g/trequetrum/lean4game-logic) | Finish ($\wedge$) | |[GEB, Ch.7, p.189 (prop.log.)](https://www.physixfan.com/wp-content/files/GEBen.pdf), [Avigad, Heule, and Nawrocki: Logic and Mechanized Reasoning, §3](https://avigad.github.io/lamr/using_lean_as_a_programming_language.html)| Theory |
| 5.2 |||| Calc ||||| Lab |
|||||
| 6 | Higher-order functions, Curry Howard correspondence |free and bound variables|| $\lambda$ - calculus (syntax) | Lean logic game (implication) | Finish (implication) | [^lambda1] | [GEB, p.83, breaking phonographs](https://www.physixfan.com/wp-content/files/GEBen.pdf) | Theory on Tue, Lab on Thu |
|||||
| 7.1 | Operational Semantics |$\alpha$ and $\beta$ rule, capture avoiding substitution|| $\lambda$ - calculus (semantics)  ||| [^lambda2] | [GEB, Ch.8, p.212 (arithmetic)](https://www.physixfan.com/wp-content/files/GEBen.pdf) | Theory |
|7.2|||[VSCode Debugger](https://code.visualstudio.com/docs/python/debugging)|Modules, Unit Tests|Interpreter for $\lambda$ - calculus|  Interpreter for $\lambda$ - calculus |||Lab
|||||
|8.1| Turing Completeness, Church-Turing Thesis | Y-combinator, `let rec`|| Church Encodings | Scope, implementing recursion ||| [GEB, Ch.13, p.413 (while programs)](https://www.physixfan.com/wp-content/files/GEBen.pdf) | Theory|
|8.2|||[VSCode Live Share](https://code.visualstudio.com/learn/get-started/basics), [Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)||Interpreter for a functional PL (group, 2 weeks) |||Lab|
|||||

[^lambda1]:
	- [Syntax of Lambda Calculus](https://youtu.be/D0kH1BpNr14)
	- [Parsing Lambda Calculus Expressions 1](https://youtu.be/eYstx7uuE6c)
	- [Parsing Lambda Calculus Expressions 2](https://youtu.be/yls1NEUlzZA)

[^lambda2]:
	- [Operational Semantics of Lambda Calculus](https://www.youtube.com/watch?v=h4aT42t7v9c#t=0m)
	- [Reducing Lambda Expressions](https://youtu.be/for3Meg1Lbc)
	- [Fixed Point Combinator](https://youtu.be/XvDOwbSh3xE)
    
    