---
layout: page
title: Course Syllabus
description: >-
    Course policies and information.
nav_order: 1
---

# Course Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Resources

Go to [Resource Tab](/ds5110-spring25/resources).


## Reading

There are no official textbooks. Required readings are (most
frequently) in the form of seminal 
[research papers](/ds5110-spring25/reading_list), online documentations, 
and/or selected textbook chapters There are several books that
*might* be useful:

* [Operating Systems: Three Easy Pieces (OSTEP)](http://pages.cs.wisc.edu/~remzi/OSTEP/), 
by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau, Aug, 2018 v 1.00
(**free book**).

* [Designing Data-Intensive Applications (1st Edition)](https://dataintensive.net/), by Martin Kleppmann (see instruction below how to access the free version via UVA Library). 

* [Distributed Systems 3rd edition
(2017)](https://www.distributed-systems.net/index.php/books/ds3/),
by Maarten van Steen and Andrew S. Tenenbaum (**free book**).

To access the O'Reilly text book ([Designing Data-Intensive Applications (1st Edition)](https://dataintensive.net/), by Martin Kleppmann), you just need to do the following:

1. Access the [UVA Library website](https://www.library.virginia.edu/).
2. Search the title of the textbook: Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems.
3. Click on *Library Catalog (Access Online)*, and sign into the O'Reilly website with your UVA email address. 
	* If the O'Reilly link brings you to an audiobook, search for the textbook in O'Reilly website and find the ebook. 



## Class participation and required readings

Class participation is required. We will discuss the design and the
use (application) of a variety of modern big data systems that we'll
cover during this semester.  Most of these systems have research
papers, if not, online docs, which present the original/evolved
design of them. One of the many great examples is Google's MapReduce
(and later the open-source implementation of MapReduce: Apache
Hadoop), which opens a new era of what we call **Big Data
Systems** today.

Specifically, the instructor (prof or the invited guest speaker) will
lead the lecture. In some lectures we will have moderate
discussions about the readings that you will have read
before the class. You are encouraged to participate in discussions.
To stimulate better discussion, you need to complete the assigned reading
assignments, e.g., a research paper about a topic. One way to test your
understanding is to read the assigned reading matetial with questions in mind.
The instructor will provide reading questions a few days before the lecture.

I also strongly encourage you to discuss the assigned/optional
readings (papers/tech reports/online documentations) with other students
in the class — you may have insights that others do not, and vice
versa.  Oftentimes, students form reading groups, which I encourage;
on the other hand, I would like to point out that group discussion is
**not an effective substitute for actually reading the paper**.


## Programming assignments

We will have three Programming Assignments during the first half of the
semester:

* [Assignment 0](/ds5110-spring25/assignments/a0): Using AWS Academy, EC2, and Linux shell.
* [Assignment 1](/ds5110-spring25/assignments/a1): Parallelizing Python processing with Dask.
* [Assignment 2](/ds5110-spring25/assignments/a2): A tour of Apache HDFS and Spark.
* [Assignment 3](/ds5110-spring25/assignments/a3): A deeper dive with Ray.
* [Assignment 4](/ds5110-spring25/assignments/a4): Fine-tuning a GPT2 with one tiny cloud thread.



## Course projects

Probably the most exciting part of this course is to complete an
interesting project related to big data systems.  I will provide you
with a list of ideas around Week 4.



## Grading

Your grade will be calculated as follows:

* 5%  quizzes
* 5%  assignment 0
* 10% assignment 1
* 15% assignment 2
* 15% assignment 3
* 20% assignment 4
* 15% midterm exam
* 15% final exam
* (Extra credit) 5% participation (in-class Q&A)


### Midterm and final exams

There will be a midterm exam scheduled around Week 7 (taken online on gradescope).
There will be a final exam scheduled on May 8 (taken online on gradescope).


### Quizzes

There will be a short quiz due at the end of some lectures. Make sure
you know the rules regarding what is allowed and what is not.

#### Allowed

* However much time you need.
* Discussing answers with classmates who are taking the quiz **at the same time**.
* Referencing texts, notes, or provided course materials.
* Searching online for general information.
* Running code.

#### NOT allowed

* Taking it more than once.
* Discussing answers with anybody outside of the course.
* Discussing with classmates who have already completed the quiz when you haven't completed it yourself yet.
* Posting anything online about the quizzes.
* Using such material potentially posted by other students who broke the preceding rule.
* Getting TA/instructor help on quiz questions prior to the quiz deadline.


### Grading rules

The final grade is computed according to the following rules:

* A+: >= 98%; A: \[93%, 98%); A-: \[90%, 93%)
* B+: \[87%, 90%); B: \[83%, 87%); B-: \[80%, 83%)
* C+: \[77%, 80%); C: \[73%, 77%); C-: \[70%, 73%)
* D+: \[67%, 70%); D: \[63%, 67%); D-: \[60%, 63%)
* F: < 60%


## Late policy

Students must work individually on all programming assignments. We
encourage you to have high-level discussions with other students in
the class about the assignments, however, we require that when you
turn in an assignment, it is only your work. That is, copying any
part of another student’s assignment is strictly prohibited, and
repercussions for doing so will be severe (up to and including
failing the class outright). You are free to reuse small snippets of
example code found on the Internet (e.g. via StackOverflow) provided
that it is attributed. If you are concerned that by reusing and
attributing that copied code it may appear that you didn’t complete
the assignment yourself, then please raise a discussion with the
instructor.

Your work is late if it is not turned in by the deadline.

* **10% will be deducted for late assignments each day after the due date**.
That is, if an assignment is late, we’ll grade it and scale the score by 0.9 if it is up to one day late, by 0.8 if it is up to two days late, and by 0.7 if it is up to three days late.
* **Late assignments will only be accepted for 3 days after the due date.** Assignments submitted more than 3 days late will receive a zero. If you’re worried about being busy around the time of a HW submission, please plan ahead and get started early.
* **Assignment that does not compile or run will receive at most 50% credit.**

> **IMPORTANT:** Please plan ahead and get started early! Debugging distributed systemscan be time-consuming.

**For fairness to all, there are no exceptions to the above rules.**



## Academic Integrity

The School relies upon and cherishes its community of trust. We
firmly endorse, uphold, and embrace the University’s Honor principle
that students will not lie, cheat, or steal, nor shall they tolerate
those who do. We recognize that even one honor infraction can destroy
an exemplary reputation that has taken years to build. Acting in a
manner consistent with the principles of honor will benefit every
member of the community both while enrolled in the School of Data
Science and in the future.  Students are expected to be familiar with
the [university honor code](https://honor.virginia.edu/), including
the section on [academic
fraud](https://honor.virginia.edu/academic-fraud).


**Citing ChatGPT (or other LLMs):** 
It's allowed with proper citation.

* Use of the tools is permitted, with proper citation.
* A "chats" directory should contain screenshots or PDFs of any chats, in their entirety. Name them as chat1.png, chat2.png, etc. PDF and JPG formats are also permitted.



## Students with disabilities or learning needs

It is my goal to create a learning experience that is as accessible
as possible. If you anticipate any issues related to the format,
materials, or requirements of this course, please meet with me
outside of class so we can explore potential options. Students with
disabilities may also wish to work with the Student Disability Access
Center to discuss a range of options to removing barriers in this
course, including official accommodations. Please visit 
[their website](https://sdac.studenthealth.virginia.edu)
for information on this process and to apply for services online. If
you have already been approved for accommodations through SDAC,
please send me your accommodation letter and meet with me so we can
develop an implementation plan together.

