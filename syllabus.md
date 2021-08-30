---
title: Syllabus
layout: default
---

## Introduction to Compiler Construction
(*CIS 400* (a Special Topics course) at Syracuse U)

**Note**: parts of this syllabus are subject to change with adequate
notice to students.

An introduction to the design and engineering of compilers for modern
(particularly functional) programming languages. The course will
consist of a semester-long (through five automatically-graded and one
final) project wherein students build a compiler from (a significant
subset of) Scheme to LLVM assembly code. Course delivery will be
lecture-based, with occasionaly-assigned videos (from the companion
course CIS352) but classtime will also focus significantly on helping
students develop their engineering and debugging skills along with
giving directed help (i.e., hints) about how to achieve the project.

## Grading

- 5 autograder projects (50% total, 10% each)
  - Projects will be handed out and graded via autograder.org. Students will receive a password in the first week of class. If you have not yet received a password and need one, please email me (kkmicins@syr.edu).
- 2 take-home midterms (30% total, 15% each)
  - Consisting of several open-ended questions to be answered in professionally-written thoughtful prose, relying upon examples when necessary.
  - Students _may collaborate_ with *up to two other* students (i.e.,
    max group size of three students) under the following policy. Each
    student submitting an answer collaboratively will be briefly
    quizzed (via Zoom or Slack) to explain portions of their solution.
    I (instructor) reserve the right to lower a group member's grade
    if they are not able to sufficiently explain their solution. I
    will specifically not be adversarially quizzing students on all
    fine-grained details of the solution, nor do I expect every
    student to do a precisely-equal amount of the work, but I expect
    that every student can at least explain the work they submit as
    part of a group.
- 1 final project (20%)
   - This project is a wrap-up of your previous project milestones
   into an end-to-end compiler. Each of the autograder projects is
   tested independently to avoid penalizing students for compound
   error induced by a bug in a part of their compiler not being
   assessed on the project at hand. Thus, the final project will have
   students combine each of these passes into an end-to-end compiler
   along with adding a feature of their choosing (will be discussed in
   class, must be approved by instructor).
 - Bonus +5% participation
   - I will sporadically announce various opportunities for 1%
     participation credit. You may earn up to 5% this way. You will
     earn no additional points once you saturate your 5% for the
     semester.

## Grade cutoffs

I anticipate this will be course that will require a serious (but not
overwhelming) amount of work from you, but I think there are many
paths to getting a good grade. Below are projected rough grade
cutoffs. However, I am making no guarantees about these at all for now
(although I will likely not make grading any harder than this). I will
announce final grade cutoffs roughly two weeks before the end of the
term on Slack (and then update them here).

- 91% -- A
- 88% -- A-
- 84% -- B+
- 80% -- B
- 76% -- B-
- 73% -- C+
- 68% -- C
- 64% -- C-
- 55% -- D
- 0%  -- F


## Autograder

Projects in this course will be graded by an automatic grader. I may
adjust projects so that portions of the projects include style-based
grading, though I will *not* employ subjective grading. More
pointedly: I will *not* award partial credit for solutions that have
the right ideas but do not pass our tests.

## Late Projects and Extensions

I used to extend project deadlines, but I have found that it severely
limits course pacing in a seriously detrimental way. Therefore,
project extensions will be rare--and only in the event of things such
as university closures. Project extensions for students will not be
granted except for religious observances and extenuating circumstances
(family illness, etc..). However, there is a late policy, written as follows:

- Projects turned in on time will earn a maximum of 100%

- Projects turned in up to 72 hours late will have a 15% penalty
  applied.

- Projects turned in after 72 hours late (until the end of the term)
  will have a 30% penalty applied.

- Your project grade always be the maximum possible. For example,
  let's say you make an on-time project submission for 60%, but the
  next day you turn in a project which earns an 75%. This submission
  would earn a 63.75%. Five days after the deadline you turn in a
  project earning 100%. Your final score is 70%, as the 70% (100% with
  a 30% penalty) still got the maximum grade of any submission.

You *should* be able to earn **at least** a 70% on all of the projects
with enough work.

<!-- ## Topics -->

<!-- We will plan to cover all of the following, though some may be dropped -->
<!-- for time: -->

<!-- - Programming in Racket -->
<!-- - Higher-order functions -->
<!-- - Execution models and their impact on the stack -->
<!-- - Pattern matching -->
<!-- - Immutable data structures -->
<!-- - Okasaki-style immutable queues -->
<!-- - Immutable binary trees -->
<!-- - Quad-trees -->
<!-- - Static scope -->
<!-- - Dynamic scope -->
<!-- - Lambda calculus -->
<!-- - Textual-reduction semantics -->
<!-- - Big-step semantics (CE-style evaluators) -->
<!-- - Metacircular interpreters -->
<!-- - Church encoding -->
<!-- - Control and continuations -->
<!-- - Abstract machines -->
<!-- - The CEK machine -->
<!-- - A-Normal Form -->
<!-- - Continuation-passing style -->
<!-- - Top-down parsing -->
<!-- - State-passing style -->
<!-- - Simply-typed lambda calculus -->
<!-- - Type inference -->
<!-- - Hygienic macros -->
<!-- - Logic programming -->
<!-- - MiniKanren -->

<!-- ## Projects and Labs -->

<!-- This course will have five autograder projects and a final -->
<!-- project. The first five will be completed using the course's -->
<!-- autograder. Projects will be handed out every few weeks, starting -->
<!-- after the first week of class. All projects are due at 11:59PM, their -->
<!-- specific deadline days are displayed on the autograder. -->

## Collaboration and the Honor Code

- Assignments and exams must be completed alone, without exception.

- Specifically, you must never send your code to anyone or allow
  anyone to watch you code, obtain your code, study your code, copy
  your code, etc... We expect you will take reasonable precautious to
  ensure the secrecy of your solutions.

- The autograder employs elaborate cheat-detection techniques. These
  techniques will compare your code to other students' submissions,
  along with students from previous years. The TAs will be using these
  features to periodically scan for students who are cheating. Past
  experience shows us that this system is very robust, and has allowed
  us to detect several large clusters of collaborating students. We
  hope that specification-based grading will assuage this.

- All apparent cases (with credible evidence, as determined by lead
  instructor) of academic dishonesty will be reported, even if the
  student believes they made an honest mistake, or no mistake at
  all. We understand honor violations are stressful processes, and
  thus we strive to only submit honor code cases when we believe there
  is clear evidence that the honor board should review our findings
  independently.

- You may collaborate, to any degree you want, with anyone (even
  outside of your group) on participation coding exercises. These will
  be clearly labeled, and are specifically not the course projects
  (which explicitly disallow any form of collaboration).

- While we recommend you discuss the project specification with your
  peers, you should basically never be getting help from peers about
  your code. In particular, you should never be showing another
  student your project code. If you do discuss coding about the
  project with another student, it should only be in the abstract
  (e.g., "can you use operator overloading to implement that?" or "do
  you think it would be sensible to implement this with `map`?") and
  not particularized to your codebase. We understand that this can be
  a challenging line to walk, and thus, we recommend the following
  heuristic: when talking to other students about code, discuss mostly
  the in-class exercises and participation coding exercises.

- Cite all help other than the professor, T.A., and
  required/recommended text (you are allowed to cite those if you
  wish, but it is not required unless you are specifically told
  otherwise); note that proper citation is sufficient to avoid any
  charge of academic dishonesty, and we will not be particularly
  focused on copyright law during lab work.

**Again**: You should **never** share code with another student. This
  includes both sending a file to another student and "over the
  shoulder" copying (even when, e.g., variable names are changed,
  etc..). In the eyes of the instructor, these are both equally
  bad. You should never be sitting and helping another along by
  writing their code. By doing so you are both violating the honor
  policy and disadvanting the student you are helping (as they may not
  then properly learn the material).

## Student Support

Syracuse University values diversity and inclusion; we are committed
to a climate of mutual respect and full participation. There may be
aspects of the instruction or design of this course that result in
barriers to your inclusion and full participation in this course. I
invite any student to meet with me to discuss strategies and/or
accommodations (academic adjustments) that may be essential to your
success and to collaborate with the Office of Disability Services
(ODS) in this process.

If you would like to discuss disability-accommodations or register
with ODS, please visit their website at
http://disabilityservices.syr.edu. Please call (315) 443-4498 or email
disabilityservices@syr.edu for more detailed information.

ODS is responsible for coordinating disability-related academic
accommodations and will work with the student to develop an access
plan. Since academic accommodations may require early planning and
generally are not provided retroactively, please contact ODS as soon
as possible to begin this process.

## Accreditation

As part of the regular ABET accreditation process for the
undergraduate program in computer science, I may be collecting samples
of students' work in each of our undergraduate classes.  As a result,
some of your labs/homeworks/exams may be photocopied/scanned (or
electronically copied) to be presented for accreditation at some later
point.

## Student Mental Health

Mental health and overall well-being are significant predictors of
academic success. As such it is essential that during your college
experience you develop the skills and resources effectively to
navigate stress, anxiety, depression and other mental health
concerns. Please familiarize yourself with the range of resources the
Barnes Center provides (https://ese.syr.edu/bewell) and seek out
support for mental health concerns as needed. Counseling services are
available 24/7, 365 days a year, at 315.443.8000.

## Discrimination and Harassment

The University does not discriminate and prohibits harassment or
discrimination related to any protected category including creed,
ethnicity, citizenship, sexual orientation, national origin, sex,
gender, pregnancy, disability, marital status, age, race, color,
veteran status, military status, religion, sexual orientation,
domestic violence status, genetic information, gender identity, gender
expression or perceived gender.

Any complaint of discrimination or harassment related to any of these
protected bases should be reported to Sheila Johnson-Willis, the
Universitys Chief Equal Opportunity & Title IX Officer. She is
responsible for coordinating compliance efforts under various laws
including Titles VI, VII, IX and Section 504 of the Rehabilitation
Act. She can be contacted at Equal Opportunity, Inclusion, and
Resolution Services, 005 Steele Hall, Syracuse University, Syracuse,
NY 13244-1120; by email: titleix@syr.edu; or by telephone:
315-443-0211.

If you notice any incidents of harassment or discrimination, however
minor, please email me. You may wish to use an anonymous email service
such as https://anonymousemail.me/. Please feel free to tell me as
much as you feel comfortable.  I am a mandatory Title IX reporter and
must report incidents such as sexual harassment, relationship
violence, stalking, etc...

## Slack

Slack is an instant messaging app for teams. We'll be using it for
most course management. This is the best place to get in touch with me
for one-off questions, ask for an appointment for office hours,
etc.. Email me if you have not been invited to the course Slack.
