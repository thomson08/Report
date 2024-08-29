# Syllabus

(under construction)

## General Information
- Class: CPSC 354 Programming Languages (all sections)
- Instructors: [Alexander Kurz](https://alexhkurz.github.io/), [Jonathan Weinberger](https://sites.google.com/view/jonathanweinberger)
- Lectures: 
  - 354-01: TuTh 11:30AM - 12:45PM, Keck 153 (Alexander) 
  - 354-02: TuTh 1PM - 2:15PM, Keck 153 (Alexander) 
  - 354-03: TuTh 11:30AM - 12:45PM, Keck 156 (Jonathan)
  - 354-04: TuTh 8:30AM - 9:45PM, Hashinger 150 (Jonathan)
- Office Hours: 
  - Alexander: TuTh 2:30 - 4PM in Swenson N206
  - Jonathan: TuTh 3 - 5PM in Swenson (3rd floor, huddle spaces)

## Course Description 

**The aim of the course** is to have a look under the hood of programming languages. How do programming languages work? Could you design your own programming language? Instead of looking at particular examples of programming languages, we will build our own. 

A companion course, CPSC 402 Compiler Construction, might be taught in the future, adapting the material of this semester to industrial-scale programming languages such as C++.

**Prerequisites:** (MATH 250 ( Discrete Mathematics I), CPSC 350) It is assumed that you know at least one programming language, ideally a few more. It would also be good to have learned something about computer architecture. One theme of the course is how to bridge the gap between a programming language and the actual machine, so some awareness of how actual machines work is needed to fully appreciate the material. Finally, while the mathematics that we need to engineer our programming languages is introduced in the course, some ability in manipulating formal mathematical models will be needed---as typically acquired in a discrete mathematics or introductory logic course.[^coursecatalogue] 

[^coursecatalogue]: From the [course catalog](https://catalog.chapman.edu/): Prerequisites, MATH 250, CPSC 350. Students develop an understanding of the organization and design of programming languages through writing interpreters for three different toy languages illustrating a range of programming concepts from pure functional languages to imperative languages with memory management. Moreover, the course will open windows into topics of programming languages research such as parsing, operational and denotational semantics, term rewriting, Hoare logic, verification, and theorem proving. Letter grade with Pass/No Pass option. 

## Course Learning Outcomes

See also the [Fowler School of Engineering Program Learning Outcomes](https://docs.google.com/document/d/1OESCtPUolnWFV_qRFuRzNrzxmUtYr5H-dFaYVmPUKY0/edit?usp=sharing) (requires Chapman login).

After completing this course, students will be able to

- use an interactive theorem prover (Lean) to program proofs in discrete mathemtics
- explain how interpreters for functional and imperative programming languages work
- use a context-free grammar and a parser generator such as BNFC 
- explain syntax and semantics of various calculi and programming languages
- understand lambda-calculus as a foundation of programming languages and the concepts of operational and denotational semantics
- explain various features of programming languages based on the computational model of term-rewriting
- understand the significance of abstract and algebraic data types
- depending on the available time various theoretical topics will be introduced (program verification, term-rewriting systems, use of well-founded orders in termination proofs, use of invariants in partial correctness proofs)

Moreover, students will be able to acquire the basic ideas of advanced topics such as theorem proving, dependent types and mathematics as a specification and programming language.

Finally, students will learn to appreciate that mathematics is not only important for developers who create the tools used in everyday engineering practice, but also that the knowledge of the mathematical concepts and results underpinning these engineering tools impact everyday engineering practice (and increase your chances to pass a coding interview). 

## Overview 

The course will have a practical and a theoretical component.

- *The theoretical component* will teach some of the mathematics underpinning the design of programming languages such as logic, rewriting, ordered structures, universal algebra, category theory, and type theory. We will cover just enough theory to help the writing of interpreters, and to gain an outlook on some of the questions guiding programming languages research.  

- *The practical component* will be about building interpreters for small programming languages. We will start with a calculator, that is, an interpreter for the language of high-school arithmetic, then go on to the smallest proper programming language known as lambda calculus. Lambda calculus provides variables and functions. Other programming languages can be seen as extensions thereof. Once we have an interpreter for lambda caclulus, we will extend it to larger functional and/or imperative programming languages.

## Required Text

The technical content of the course will be distributed via a git repository. Hofstadter's book *Gödel, Escher, Bach* is assigned as supplementary reading to provide general background. Students are expected to read the book to deepen their understanding of the course themes.

## Course Materials 

All course materials will be made available via a git repository.

## Assessment

Assessment will be divided into a total of 200 points.

- 3 programming [assignments](assignments.md) and a programming project worth 20 + 20 + 20 + 40 points.

- [Participation](participation.md) worth 10 points.

- A [report](report.md) worth 90 points. This also contains weekly homework.

## Course Grade Breakdown

Grading scale used for the course:

| Percentage | Letter |
|---|---|
| 90 | A |
| 80-89 | B |
| 70-79	| C |
| 60-69	| D |
| < 60 |	F |

You must score a 70 or above to receive a P when taking the course P/NP.

## Late Policy

If you need more time for an assignment 
- convince the instructor that you already have done substantial work (for example by showing me the code in your GitHub repository);
- explain the special circumstances that would allow the instructor to justify giving you more time.

(The two items above need to be acted upon before the deadline.)

## Participation

- It is expected that students attend every lecture. 
- The instructor also appreciates if students make use of the office hours, giving valuable feedback on how the class is going.

## Policies required to be listed via University guidelines

#### Chapman University’s Academic Integrity Policy

Chapman University is a community of scholars that emphasizes the mutual responsibility of all members to seek knowledge honestly and in good faith.  Students are responsible for doing their own work and academic dishonesty of any kind will be subject to sanction by the instructor/administrator and referral to the university Academic Integrity Committee, which may impose additional sanctions including expulsion.  Please see the full description of Chapman University's policy on [Academic Integrity](https://www.chapman.edu/academics/academic-integrity/index.aspx).

#### Chapman University’s Students with Disabilities Policy

In compliance with ADA guidelines, students who have any condition, either permanent or temporary, that might affect their ability to perform in this class are encouraged to contact the Office of Disability Services.  If you will need to utilize your approved accommodations in this class, please follow the proper notification procedure for informing your professor(s).  This notification process must occur more than a week before any accommodation can be utilized.  Please contact [Disability Services](https://www.chapman.edu/students/health-and-safety/disability-services/index.aspx) at (714) 516–4520 if you have questions regarding this procedure or for information or to make an appointment to discuss and/or request potential accommodations based on documentation of your disability.  Once formal approval of your need for an accommodation has been granted, you are encouraged to talk with your professor(s) about your accommodation options.  The granting of any accommodation will not be retroactive and cannot jeopardize the academic standards or integrity of the course.

#### Chapman University’s Equity and Diversity Policy

Chapman University is committed to ensuring equality and valuing diversity. To access information part of Chapman's DEI (Diversity, Equity, and Inclusion) initiative, including on-campus resources, student-driven clubs, faculty and staff advocates, and how to report a concern or incident, please view the [Diversity and Inclusion Resources](https://www.chapman.edu/diversity/resources/index.aspx). Students and professors are reminded to show respect at all times as outlined in Chapman’s [Discrimination, Harassment, and Retaliation Prevention Policy](https://www.chapman.edu/faculty-staff/human-resources/_files/eodo/dhrp-policy.pdf). Any violations of this policy should be discussed with the professor, the Dean of Students and/or otherwise reported in accordance with this policy.


#### Student Support at Chapman University

Over the course of the semester, you may experience a range of challenges that interfere with your learning, such as problems with friend, family, and or significant other relationships; substance use; concerns about personal adequacy; feeling overwhelmed; or feeling sad or anxious without knowing why.  These mental health concerns or stressful events may diminish your academic performance and/or reduce your ability to participate in daily activities.  You can learn more about the resources available through Chapman University’s [Student Psychological Counseling Services](https://www.chapman.edu/students/health-and-safety/psychological-counseling/).

Fostering a community of care that supports the success of students is essential to the values of Chapman University.  Occasionally, you may come across a student whose personal behavior concerns or worries you, either for the student’s well-being or yours.  In these instances, you are encouraged to contact the Chapman University ][Student Concern Intervention Team](https://www.chapman.edu/students/dean-of-students/student-outreach-support/index.aspx) who can respond to these concerns and offer assistance. While it is preferred that you include your contact information so this team can follow up with you, you can submit a report anonymously.  24-hour emergency help is also available through Public Safety at 714-997-6763.

#### Religious Accommodation

Religious Accommodation at Chapman University Consistent with our commitment of creating an academic community that is respectful of and welcoming to persons of differing backgrounds, we believe that every reasonable effort should be made to allow members of the university community to fulfill their obligations to the university without jeopardizing the fulfillment of their sincerely held religious obligations. Please review the syllabus early in the semester and consult with your faculty member promptly regarding any possible conflicts with major religious holidays, being as specific as possible regarding when those holidays are scheduled in advance and where those holidays constitute the fulfillment of your sincerely held religious beliefs.

#### Changes
This syllabus is subject to change. Updates will be posted on the course website.

