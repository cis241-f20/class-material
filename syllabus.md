# CIS 241 Syllabus

## Instructor Information
Instructor: Erin Carrier

Office Hours: TBA

Contact:

* [Piazza](https://piazza.com/class/kdru22j5k4n3si) **preferred**
* [erin.carrier@gvsu.edu](mailto:erin.carrier@gvsu.edu?subject=[CIS241]) ^^^in almost all cases use Piazza

## Course Description
Introduction to software infrastructure underlying development of
computer programs. Topics include Linux utilities, shell scripting,
processes, facilities for programming, the C programming language,
libraries, structures, pointers, dynamic memory management, and
system calls.

Prerequisite: CIS 163 or CIS 260

Credits: 3

## Piazza
We will be using Piazza for **all class related communication**.
Please read the [Piazza FAQ](piazza-faq.md) for more details.  
In particular, note that important announcements will be posted
to Piazza and you are responsible for monitoring it and
that **all questions and concerns**
should be posted to Piazza (instead of emailed).  Emails
will likely be redirected to be posted to Piazza and then
answered there.  Piazza is available
both web-based and as a phone app.


## Textbooks - None Officially Required
The following textbooks are available for free online through
GVSU’s library.  You may find a combination of them useful:

* [Linux Pocket Guide, 3rd edition by Barrett (2016)](https://www.oreilly.com/library/view/linux-pocket-guide/9781491927557/)
* [The Linux Command Line, 2nd edition by Shotts (2019)](https://www.oreilly.com/library/view/the-linux-command/9781492071235/)
* [Linux in a Nutshell, 6th edition by Love, Figgins, Siever and Robbins (2009)](https://www.oreilly.com/library/view/linux-in-a/9780596806088/)
* [Understanding and Using C Pointers by Reese (2013)](https://www.oreilly.com/library/view/understanding-and-using/9781449344535/)
* [C in a Nutshell by Crawford and Prinz (2005)](https://www.oreilly.com/library/view/c-in-a/0596006977/)
* [Head First C by Griffiths and Griffiths (2012)](https://www.oreilly.com/library/view/head-first-c/9781449335649/)
* [C Programming Absolute Beginner’s Guide, 3rd edition by Miller and Perry (2013)](https://www.oreilly.com/library/view/c-programming-absolute/9780133149869/)


## Course Objectives
After successful completion of the course a student should be able to:

* Application/Use: Use command-line interface to do basic system operations
  such as create a directory, modify file permissions, create a link, manage
  processes, and access a computer remotely.
* Mechanism/Manipulate: Manipulate basic features of a command-line
  environment such as the 'PATH', which specifies the locations of
  executable programs, and the 'CLASSPATH', which specifies the
  locations of Java classes.
* Synthesis/Write: Write basic meta-programs in a shell or scripting language,
  e.g. to compile statistics for numbers stored in text files.
* Application/Use: Use build-system utilities such as 'make'/'cmake',
  'gdb', or 'SCons' to edit, compile, test, time, debug, and profile a
  C program.
* Synthesis/Construct: Construct programs that access data by using the
  range of pointer operations and manual dynamic memory management to
  implement basic ordered binary trees a.k.a. binary search trees (BSTs).

## Grade Breakdown

| Activity   | Estimated # | Percentage | Other notes |
| ---------- | ----------- | ---------- | ----------- |
| Mini-labs            | ~15 | 20% | the lowest minilab score will be dropped |
| Programming Projects | ~4  | 35% | |
| Exams                | 2 (1 midterm, 1 final)  | 45% | |

## Grading Scale
| % Range   | Grade | % Range   | Grade | % Range   | Grade |
| --------- | ----- | --------- | ----- | --------- | ----- |
| [93, 100] | A     | [90, 93)  | A-    |           |       |
| [87, 90)  | B+    | [83, 87)  | B     | [80, 83)  | B-    |
| [77, 80)  | C+    | [73, 77)  | C     | [70, 73)  | C-    |
| [67, 70)  | D+    | [60, 67)  | D     | [0, 60)   | F     |

## Extra Credit
There will be two opportunities for extra credit.  

* Extra credit will be awarded for good questions (as marked by the
  instructor) and good answers (as endorsed by the instructor).  The
  exact formula is not yet determined, but the extra credit will
  be capped at 1% of the overall course grade.
* In this course we'll use a system called
  [ClassTranscribe](https://classtranscribe.com/offering/2eda65cf-d00f-4a0b-bb00-7bba2f88ccc6)
  for lecture videos that allows students to caption videos.
  The goal of this is to:

  1. Provide accessibility for those who may benefit from accurate captions.
  2. Encourage actively watching the lectures and paying
     attention to the content of the video lectures.  In a sense, this
     should be viewed as encouragement to take notes while watching the
     lectures.

  In order to encourage this, extra credit will be awarded to students
  based on contributions to the captioning of the videos.  The
  exact formula is not yet determined, but the extra credit will
  be capped at 1% of the overall course grade.

## Course Policies
This course is subject to the GVSU policies listed at
[http://www.gvsu.edu/coursepolicies/](http://www.gvsu.edu/coursepolicies/).

### General Course Policies
* Assignments and minilabs requiring submission will be submitted through
  [PrairieLearn](https://prairielearn.engr.illinois.edu/pl/) and, in
  some cases, also through Github Classroom.  More details will be
  provided with the first assignment, but you will need to create a github
  account.  Some minilabs will be awarded credit based on participation
  in the asynchronous Friday meetings.
* All code submitted should be properly commented.
* Late assignments will generally not be accepted,
  except in extenuating circumstances (e.g. severe illness, etc.).
  Any work done on an assignment
  after the posted due date and time will not be counted for credit.
* If health issues for you or someone you care for, longer term internet issues,
  childcare issues, etc. arise, please post
  a private Piazza note to the instructor ASAP so we can work together to
  identify a solution.
* There may be a need for changes to happen midsemester, so this
  information is tentative and the
  instructor reserves the right to modify course policies, the course
  calendar, due dates, number of assignments, etc.

### PrairieLearn Policies
PrairieLearn (PL) will be used for coding projects, some minilabs, and exams.
PL is an online system that will allow you to submit code for
autograding.  You will be able to submit, see your grade, and resubmit
prior to the due date/time to improve your grade without penalty as
many times as you wish.  Except in cases of academic integrity violations,
in which case your score may be lowered after the fact,
your score for autograded problems will be the score reported by PrairieLearn
prior to the due date/time.  If you submit code that does not run or compile,
you will receive a 0.  Any partial credit will be awarded by the autograder; no
additional partial credit will be awarded.  For projects, there
may be a manually graded portion as well -- these points will be
awarded manually.

The goal of using PL is to, as a whole, improve grades by
allowing you to assess your solution and continue to refine it.
For coding problems, there are often both visible test cases and hidden
test cases.  For many problems, the hidden test cases are edge cases
that may not be something that was considered when you first developed
your approach to the problem.  The goal of the autograder is to

1. Let you see when your solution is correct
2. Help you become a better programmer by forcing you to think
   carefully about what scenarios may arise.

While the autograders have been tested, it is possible that
there are bugs.  If you believe there is an issue
with the autograder, please post a private note on Piazza ASAP.

### Minilabs
The Friday synchronous class sessions will be set aside to
complete minilabs and ask questions regarding the asychronous material
for the week.  Attendance is expected, and, in many cases, the
grade may be based on attendance, but minilabs later in the semester
that focus more on
C may have autograders to help you make sure your code is correct.
 
These minilabs will be short activities designed
to allow you a chance to apply the concepts discussed in asynchronous
video lectures in an environment where help is easily available.
For some minilabs, I may ask a couple students to walkthrough their
attempt with the class.

One minilab will be dropped -- think of this like a free
miss day for the Friday session.  Please don't use this just to
skip, save it for when you need it (e.g. oversleep alarm clock,
forget to hop on, etc.).

### Exam Policies
Exams will be taken on PrairieLearn and consist of both
non-coding (multiple choice, fill-in-the-blank, etc.) questions 
and one or more coding questions.  Exams will be taken on a
specific day, but at the time of your choice.  However, once
you start your exam you will have only a set amount of time 
to complete it (not the whole day).

### Academic Honesty Policies
All students are expected to adhere to the academic honesty standards
set forth by Grand Valley State University. In addition, students
in this course are expected to adhere to the [academic honesty
guidelines as set forth by the School of Computing and Information
Systems](https://www.cis.gvsu.edu/academic-honesty/)

For this course:
* **Mini-labs**:  you are welcome to collaborate with classmates
  on the mini-labs as these are designed
  solely as a checkpoint for you to apply the material.
* **Projects**:  should be completed individually.  This means that
  each student will turn in their own solution for the project, and that
  solution must be their own work.  You are more than welcome to discuss
  your approach with other students and bouncing ideas off of one another
  and discussing issues is encouraged, but you should not be sharing your
  code.
* **Exams**:  Exams are to be completed individually.  Exams are open-book,
  open-note, open-internet.  You are free to consult your project solutions,
  examples used in class, and lecture videos while taking your exams.
  **You cannot, however, discuss or share any portion of the exam with another
  individual (whether or not they are taking this class)**.  Doing so will
  be considered an academic integrity violation and may result in disciplinary
  action up to failure in the course.

FAQs:
* Can I seek help through sites like upwork? *No, this would generally be
  considered an academic integrity violation*
* Can I have help from a tutor?  *You may seek help from a tutor, but the work
  you submit for projects in the end must be your own.  You may not consult
  tutors when taking exams.*
* Can I use sites like stackoverflow?  *Yes, this is allowed in this course,
  so long as you are not simply posting your entire problem and asking
  for a solution.*

## Financial Difficulties
Financial hardship funds are available to help student's meet
their basic needs, and help cover educational costs (such as
housing, food, and textbooks) that a student could not otherwis
pay out of pocket. Please visit the
[GVSU Special Circumstance & Financial Hardship Requests web page](https://www.gvsu.edu/financialaid/financial-hardship-requests-226.htm)
for more information.

## Special Assistance
If there is any student in this class who has special
needs because of learning, physical or other disability,
please contact me and Disability Support Services (DSS)
at 616.331.2490.
