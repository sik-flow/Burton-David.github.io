---
layout: post
title:      "CS History"
date:       2019-02-28 01:50:40 +0000
permalink:  cs_history
---

### First MIT open course experience
> Albert Meyer, and Adam Chlipala. 6.042J Mathematics for Computer Science. Spring 2015. Massachusetts Institute of Technology: MIT OpenCourseWare, https://ocw.mit.edu. License: Creative Commons BY-NC-SA.
This is a great course so far.  The first 4 lessons in Unit one took an entire day to go through. 

[Link to course](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/#)

Click the link on the left sidebar for “lecture slides” and begin!<br>

Albert Meyer is a professor of CS at MIT and the way he goes through the material is easy to understand and the language he uses is very precise which is necessary when learning something such as Computer Science.  He starts the course by introducing the word “discreet”.  A word that we all think we know the meaning to.  He asks us to look up the word.<br>

discreet-careful and circumspect in one’s speech or actions, especially in order to avoid causing offense or to gain an advantage.<br>

This is the perfect way to describe Mr. Meyer’s teaching style.  The words he chooses to use are chosen for a reason.  I have worked in a variety of fields and the first few months are always difficult not just because I am learning a new job but because the people I need to communicate within the field are using a language I am unfamiliar with.  I cannot even count the number of times that I have had somebody explain a new concept to me while using acronyms or referenced a reference which I was already supposed to know yet that day was my first day.<br>

When learning any new vocation or skill I have found that learning the jargon of the industry is 90% of the battle.  This course will help with that, I want to learn all of the important facts and jargon that anybody who went to school for computer science || statistics and probability will be speaking in.  Python or Java is great for programming data, but I need to speak the language of the industry.<br>

**1.1 Intro to Proofs**<br>
The reason that we learn proofs is that memorizing everything is impossible and a waste of brain space.  Being able to derive something or prove it is a skill that will help us work in math and it is very similar to the coding logic that is used throughout data science.<br>

The first example is the explaining of the Pythagorean theorem as “proof by picture.”  While a cool example to help understand how the Pythagorean theorem was probably conceived, “proof by picture” or “proof by diagram” is flawed by the inaccuracies inherent in a visual representation due to how we perceive or misperceive dimensions and shapes.<br>

 

**corollary**– a proposition that follows in just a few logical steps from a theorem<br>

**lemma**– a preliminary proposition useful for proving later propositions<br>

**theorem**– an important true proposition<br>

**proof**– a sequence of logical deductions from axioms and previously proved statements that concludes with the proposition in question<br>

**axiom**– a proposition that is simply accepted as true<br>

**predicate**– a proposition whose truth depends on the value of one or more variables<br>

**proposition**– a statement that is either true or false<br>

**modus ponens**- the rule of logic stating that if a conditional statement (“if p then q ”) is accepted, and the antecedent ( p ) holds, then the consequent ( q ) may be inferred.<br>

**1.2 Proof By Contradiction**<br>
Some proofs can be validated by simply showing how the opposite would not be true.  The square root of 2 is irrational is easy to prove by showing that the square root of 2 cannot be a rational number.

**Proof by cases**- you break a proof up into smaller cases then put them together to show that it is logical in all cases.

> The example uses the Java Logical Expression

> if x >0

> ((x>0) || (x <= 0 && y>100))<br>

**Proof by cases**- breaks a complicated problem into easier subproblems.<br>

**Intutionists** are **philosophers** that believe this is a troublesome leap in logic. Since intuitionists believe that mathematics is a mental construct and not an objective truth waiting to be discovered.<br>

**The question:**  Is P = NP ?  is a proposition that’s proof is worth $1,000,000  and Mr. Meyer claims to have the answer for his in-class students to see… I no longer feel guilty about not paying for this information. Hopefully, he won the prize money.<br>

**P = NP**  rabbit hole (using wikipedia in spite of how all teachers are supposed to hate the use of it as a source)  

It asks whether every problem whose solution can be quickly verified (technically, verified in polynomial time) can also be solved quickly (again, in polynomial time).

The concept of polynomial time leads to several complexity classes in computational complexity theory. Some important classes defined using polynomial time are the following.

P: The complexity class of decision problems that can be solved on a deterministic Turing machine in polynomial time.
NP: The complexity class of decision problems that can be solved on a non-deterministic Turing machine in polynomial time.
ZPP: The complexity class of decision problems that can be solved with zero error on a probabilistic Turing machine in polynomial time.
RP: The complexity class of decision problems that can be solved with 1-sided error on a probabilistic Turing machine in polynomial time.
BPP: The complexity class of decision problems that can be solved with 2-sided error on a probabilistic Turing machine in polynomial time.
BQP: The complexity class of decision problems that can be solved with 2-sided error on a quantum Turing machine in polynomial time.
P is the smallest time-complexity class on a deterministic machine which is robust in terms of machine model changes. (For example, a change from a single-tape Turing machine to a multi-tape machine can lead to a quadratic speedup, but any algorithm that runs in polynomial time under one model also does so on the other.) Any given abstract machine will have a complexity class corresponding to the problems which can be solved in polynomial time on that machine.

**The Turing Machine** is a thought machine Alan Turing developed as a solution to Entscheidungsproblem. (More copy an paste from Wikipedia for future studies)

In mathematics and computer science, the Entscheidungsproblem (pronounced [ɛntˈʃaɪ̯dʊŋspʁoˌbleːm], German for “decision problem”) is a challenge posed by David Hilbert in 1928.[1] The problem asks for an algorithm that takes as input a statement of a first-order logic (possibly with a finite number of axioms beyond the usual axioms of first-order logic) and answers “Yes” or “No” according to whether the statement is universally valid, i.e., valid in every structure satisfying the axioms. By the completeness theorem of first-order logic, a statement is universally valid if and only if it can be deduced from the axioms, so the Entscheidungsproblem can also be viewed as asking for an algorithm to decide whether a given statement is provable from the axioms using the rules of logic.

In 1936, Alonzo Church and Alan Turing published independent papers[2] showing that a general solution to the Entscheidungsproblem is impossible, assuming that the intuitive notion of “effectively calculable” is captured by the functions computable by a Turing machine (or equivalently, by those expressible in the lambda calculus). This assumption is now known as the Church–Turing thesis.

 

**The take-away**

Proof by cases might be used when a complicated proof could be broken into cases, where each case is simpler to prove and the cases together cover all possibilities.

1.3 Well Ordering Principle and 1.4
Every nonempty set of non-negative integers has a least element

Watch out! you cannot replace integers with rationals!!!

We are going to dive into order theory a bit here.

Order theory is a branch of mathematics which investigates the intuitive notion of order using binary relations.

Teaching myself Binary Mathematics
When I tried to figure out what number theory was I ended up realizing that I did not actually fully understand Binary.  I knew that Binary was the original programing language.  It speaks in 1’s or 0’s that essentially mean yes or no, true or false.  But, this was probably even wrong and I wanted to learn how to write in Binary since it is the basis for computers.

In digital electronics and mathematics Binary is a base 2 system as opposed to the base 10 system we are taught in elementary school called The Decimal System.  The Binary System is expressed in bit-strings that are read from right to left.  Starting at 1, 2, 4, 8, 16, 32,64, 128, 256, 512… 1 means yes, 0 means no.

example

001100 is a 6 bit string that represents the number 12.  I can calculate the number it represents by adding 0+0+4+8+0+0=12  from right to left.

Adding binary numbers

010110+011110=110100 (remember that 1+1=2 since 2 does not exist as an answer 2 means that you carry the one and 1+1+1=1 and you carry a 1 (since 3 does not exist either) )

This example is the same as saying that 22+30=52

Back to the lesson

Theorem: Every integer > 1 is a product of primes

Proof:(by contradiction) Suppose {nonproducts} is nonempty.  By WOP, (Well Ordering Principal)


