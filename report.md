# Report

The report will be written in Latex. A template for your LaTeX source file [`report.tex`](report/report.tex) and the compiled [pdf](report/report.pdf). See also [`latex-example.tex`](report/latex-example.tex) and [`latex-example.pdf`](report/latex-example.pdf).

- You will keep both report.tex and report.pdf in a personal private Github repository. 
- Unless specified otherwise your repo should only contain the following files
    ```
    .gitignore
    report.pdf
    report.tex
    README.md
    ```
    The readme should contain name and email.
- For example, if a homework requires programming, make a subdirectory `src` where you store the relevant program files; if you want to include images in your report, make a subdirectory `img`; etc.
- Always use the same repository for all submissions of the course (get in touch if you think an exception is appropriate).
- Do not name different versions of your report, instead rely on the version control of git.
- Give me access to your private github repo by inviting me as a collaborator (my GitHub name is alexhkurz).
- Submission info below.

## Point Distribution

Out of a total of 200 points the report is worth 90 points and divided approximately up as follows. 

- (2 points): Organization of the github repo (respecting naming conventions, etc).
- (4 points): Organization of the report, layout, typesetting.
- (4 points): Quality of writing, style, references.
- (13x2=26 points): 2 points per week for timely submission of homework.
- (13x3=39): 3 points per week for quality of homework in the full report.
- (12 points:) Lessons from the assignments.
- (3 points): Conclusion 

## Organization, etc

For organization of the github repo see [Git Best Practices](git-best-practices.md). In particular,
- respect my naming conventions,
- do not put machine-generated files in the repo,
- do not keep different versions of the report.

For organization of the report, layout and typesetting, take your favourite textbooks or scientific articles as examples. In CS, they are more often than not produced with \Latex. Learning \Latex is one of the aims of the course. You will be graded also on your proficiency in \Latex. See also comments below.

For quality of writing and style, in addition to common norms on writing in general, also make sure that technical content is as easy to follow as possible. Learning to learn and document your learning is one of the aims of the course. I thus expect you over the run of the semester to explore the subject on your own. Add *interesting* references to the bilbliography and cite them throughout your report.

## Homework

**Deadlines:**
- Weekly deadlines. Most weeks have 2 points upon completion (approx 26 in total). 
    - To make your reports more self-contained, state the homework question before you give your answer. 
    - Deadline are Sunday at midnight. This hopefully gives me time to look over your answers on Monday. 
    - I will discuss the questions Tuesday in class and you will have an opportunity to improve your answers. 
- Final deadline. Further points are awarded after the final deadline at the end of final examination week:
    - You are expected to improve upon your weekly submissions for the final version of the report. 
    - The full report is due on the Sunday immediately after the Saturday of finals week. 

**Submission:**  After completing the homework, each weak, **submit the URL of your github repo** (containing report.tex and report.pdf) **via Canvas** before the deadline. Make sure that you share access to your private repo with me.

Do not keep different copies of your report in the repo. I will use git to verify timestamps and git's version control if I need to go back to an earlier version.

## More on Layout and Typesetting

Good layout and typesetting [^goodLayout]
- makes it as easy as possible for the reader to navigate a document and extract the relevant information; 
- is uniform and even in the sense that it is free from distracing details and "same function" is represented by "same form" (["form follows function"](https://en.wikipedia.org/wiki/Form_follows_function) ... btw, software engineering has a lot to learn from architecture, see for example [Christopher Alexander](https://en.wikipedia.org/wiki/Christopher_Alexander) who influenced the design of Wikipedia, design patterns in object oriented programming, agile software development, and the [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) architectural style underlying much of the WWW).
- takes a lot of time polishing the content and how it is presented[^polishing].

Some concrete examples following from the general principles above:

- Adapt the template in a meaningful way. Don't leave empty sections or trailing "..." in the paper.
- The table of contents should have clickable links (hyperrefs).
- Make sure that the way you use whitespace adheres to the principle of form follows function. In particular, there should be no pages that are largely empty.
- If you use pictures of handwritten solutions, make sure  
    - that your handwritten solutions also show a nice layout and typesetting and that they fit together in style across the whole report;
    - (if you use paper with lines) that your writing fits into the lines;
    - the pictures show no distracting details such as your fingers, or irrelevant background, or the shadow of your phone, etc;
    - that you do not put the first draft of your answer in the report, rather carefully rewrite your draft answer to eliminate potential mistakes.[^firstDraft]

Finally, do not change the general layout specified in the template. Do not change the margins or the line spacing. In case of doubt get in touch. 

[^goodLayout]: I don't want to consider myself as overly strict when it comes to good typesetting, but my experience from grading is that most students produce reports without paying enough attention to layout. 

[^polishing]: Note that the human eye is very good at spotting small visual inconsistencies related, for example, to the use you make of space on the page. While these inconsistencies are not relevant to the content, they are distracting from the content, since they consume some attention of the reader. In other words, they are relevant to the relationship you as an author are trying to build with the reader.

[^firstDraft]: Mathematics is rather similar to programming in this respect. The first draft is (almost) never correct.

## Lessons from the Assignments

On 3 pages you describe lessons you learned from the assignments and the group project. Be as technical and detailed as possible. I am mainly interested in examples where you connect concrete technical details with interesting general observations. I am also interested in examples in which the theory discussed in the lectures helped with the design or implementation of the project.

I recommend that you write this **while working on the assignments**. This is only a few paragraphs per week and the material should come from the work you do anyway on the project. Just keep your eyes open for interesting lessons while working on the project.

## General Remark on Grading

Grading will not only be checking boxes. But as long as students want precise guidelines, grading will always involve some checking of boxes. So please make sure that you take on board the points I listed above. Some will seem minor to you (like the ones on typesetting) but experience shows that work that has more carefully crafted form typically also has better content (for example, while improving the typesetting of your report, you will likely spot actual mistakes in the math).

## Teaching Rationale

Self-explaining can have a profound effect on problem-solving, in particular during early knowledge acquision. In particular, self-explanation helps the learner to build their own mental model and to revise it over time. 

Concretely, for your report, I expect that you keep revising what you wrote during the semester to reflect the progress you make on updating your mental model.

For more on the value of self-explanations see Chapter 6 of Craig Barton, How I Wish I’d Taught Maths, and references therein.
