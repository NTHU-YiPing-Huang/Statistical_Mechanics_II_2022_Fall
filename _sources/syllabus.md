# Syllabus for Statistical Mechanics (II) -- PHYS522000

[//]: <> (> 盡信書不如無書。--孟子 道可道，非常道。--老子The quotes above are very elegant descriptions about the attitude of learning. If one completely believe what a book says, it is better not to read any books. Any books should not become an obstacles for thinking. )

## Basic information
* Time: Thursday 13:20-16:20
* Classroom: Physics building, Room 208 
* Instructor: Yi-Ping Huang
* Office hours: After the course or by appointment (Online or at Room 517)
* **Final project presentation date: 12/22~1/12**
* The course will be offered in English.
	* We encourage everyone to interact in English. If some conceptual questions are difficult to be described in English, one can ask the question in Mandarin, and I will translate that into English. If I forgot to do that, please remind me to do so.
* Teaching method: Lectures with live video streaming. 
* Please join the google classroom.
	* Course code: please contact the instructor.
	* Course-related information(*e.g.*, homework) will be posted in the google classroom.
	* Access to the live video streaming will be provided in the google classroom.
	
## Evaluation:

**Homework (60%), Final project (40%)**

## Final projects

[Final project guideline](https://hackmd.io/@yihu3230/HkjbMnjIt)

## Homework policies

* It is **encouraged** to discuss homework or the content of the lectures with your classmates. However, the point of discussion is to form one's own opinion instead of following someone's idea. **Don't copy the homework**.
* Copied homework will get no points. That is, we will use a very one-sided rule. If two homework looks very similar, both of them get zero points.
* Copied homework from the **internet** is also **disallowed**. If the homework looks similar to any online resources: solution manual or anything, the homework will also get zero points.
* I will put the pdf file of the homework on google classroom. The pdf file will specify the due date of the homework. One-day delay is allowed (**By Friday 5 pm**). If you need more time to finish the homework, please send an email to me and explain why you need an extension and when you expect to turn in your homework. Late homework(**within a week**) without reasoning gets 70% of the scores. Late homework without reasoning for more than a week will get 0 points.
* **The purpose of homework is to help you learn the subject.** Please give yourself some time to think independently first, then discuss with your classmates or TA. TA has no responsibility to do the homework for you. **Please start doing the homework early.**

### How to do the homework 
* Bring your pen, blank paper, and the assignment. Find a place where you can think. Start working on the assignment. Think about the meaning of the problem. If you don't know what to do, that's fine. Propose possible ways to yourself first. Develop the logic to solve the problem first, ignore the details of the calculation. Focus on the strategy of your approach. 
* Then, start to carry out your strategy. If you get stuck, found you are confused about some concept. Check the note and see if you can figure out what's going on. 
* If you still cannot figure it out, try to describe your confusion to yourself. Try to narrow down the concept that you don't feel you understand. Construct specific examples to show why it is confusing to you. Then you can bring your confusion to discuss with your classmates or TAs. 
	```{admonition} Example (A possible workflow of doing homework)
	:class: tip
	**Assignment**: Calculate the specific heat of model X:
	
	1. What is the physical meaning of specific heat? Did we learn how to calculate specific heat during the course? Thermodynamic quantities are usually related to thermodynamic potential. Can we calculate the free energy of the system and get specific heat from there?
	2. What is model X? What is the energy spectrum of model X? How knowing the energy spectrum helps me to construct the expression of thermodynamic potential?
	3. If I find a way to derive the thermodynamic potential and if I understand how to calculate specific heat from thermodynamic potential. Then I should be able to solve this problem. So I should understand how to construct thermodynamic potential from scratch and how the thermodynamic potential is related to the specific heat.
	4. Carry out the detail of the calculation.
	```
## Textbook

None

## Prerequisites

Basic knowledge in statistical mechanics (I)

## Course Description

Statistical mechanics (II) will focus on interacting effects in the many-body system. The course will cover topics beyond Statistical mechanics (I) and focus on different phases of matter beyond equilibrium interacting-free systems. The course will start with the discussion of phases of matter using the Ginsburg-Landau theory. After introducing the Ginsburg-Landau theory, we will introduce the spirit and the physical meaning of the renormalization group. Equipped with the renormalization group technique, we will revisit the phases of matter in Fermionic/ Bosonic systems and discuss exotic phases of matter beyond the conventional Ginsburg-Landau paradigm. 

## References

1. *Lectures on phase transitions and the renormalization group*, Nigel Goldenfeld {cite:p}`goldenfeld2018lectures`
2. *Principles of condensed matter physics*, P. M. Chaikin and T. C. Lubensky {cite:p}`chaikin1995principles`
3. *Statistical Mechanics in a Nutshell*, Luca Peliti {cite:p}`peliti2011statistical`
4. *(2nd Edition)Statistical Mechanics: Entropy, Order Parameters, and Complexity: Second Edition (Oxford Master Series in Physics)*, James P. Sethna {cite:p}`sethna2021statistical`

A good reference is the one that you are willing to read.


## Outline of the course

```{figure} /images/outline.pdf
---
width: 750px
name: outline-fig
---
Outline of the course.
```

### Course plan (2022-spring)

| Date   | Contents                                                                                                                                                                                                                                                                                                                                                                                                                    |
| :----- | :-------                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 09.15  | Course overview -- Basic information, course description, and review of essential physics in statistical mechanics (I).                                                                                                                                                                                                                                                                                                     |
| 09.22  | Review of mean field theory: Ising model and the Van der Waals equation. Motivation for a more general framework: Landau theory. Landau theory: Postulates, construction of Landau free energy, discrete and continuous phase transitions in Landau theory, coarse graining and the microscopic meaning of Landau theory.                                                                                                   |
| 09.29  | (Continue) Landau theory: Landau free energy as a functional of the coarse grained field. Correlation functions for Landau theory. Critical exponents for Landau theory.                                                                                                                                                                                                                                                    |
| 10.06  | (Continue) Microscopic meaning for the phenomenological constants in Landau theory. Correlation function for Landau theory in general $d$ dimensional systems. Fluctuations and the breakdown of Landau theory.                                                                                                                                                                                                             |
| 10.13  | (Discussion) How to understand fluctuations in mean-field theory? How to calculate the probability distribution for interacting systems in principle? How to tell whether probability distribution for many-body system can be factorized into one-body problem? How to estimate the fluctuation for a distribution function and the Ginsburg criteria in different dimensions. Introduction of the Gaussian approximation. |
| 10.20  | The Gaussian approximation and its correction to the Landau theory.                                                                                                                                                                                                                                                                                                                                                         |
| 10.27  | (Continue) The Gaussian approximation and its correction to the Landau theory. Perturbation theory for the $\phi^4$ theory in $d$ dimensions. Concept of asymptotic series. **HW1 due**                                                                                                                                                                                                                                     |
| 11.03  | Dimension analysis and the critical exponents. Conflicts between the dimension analysis and the experiment and the need to have a deeper theoretical understanding. The scaling hypothesis.                                                                                                                                                                                                                                 |
| 11.10  | The scaling hypothesis and the Kadanoff's renormalization group: the postulates and the insights.                                                                                                                                                                                                                                                                                                                           |
| 11.17  | Review of what we have done till now. From mean field theory, to fluctuation, to Landau theory and its breakdown, the anomalous dimension and the conflicts between common dimension analysis to Kadanoff's insight. The formal structure/idea of renormalization group transformation: Why renormalization group idea is useful? Including fluctuations systematically on different scales.                                |
| 11.24  | Renormalization group step, renormalization group flow, the concept of fix points, the local and global structure of renormalization group flow.                                                                                                                                                                                                                                                                            |
| 12.01  | stable fix points, critical fix points, relevant, irrelevant and marginal couplings. The renormalization group flow near critical fix points and its relation to the critical exponents.                                                                                                                                                                                                                                    |
| 12.08  | Renormalization group transformation for two-dimensional ferromagnetic Ising model. **HW2 due**                                                                                                                                                                                                                                                                                                                             |
| 12.15  | <++>                                                                                                                                                                                                                                                                                                                                                                                                                        |
| 12.22  | <++>                                                                                                                                                                                                                                                                                                                                                                                                                        |
| 12.29  | <++>                                                                                                                                                                                                                                                                                                                                                                                                                        |
| 01.05  | Final presentation (1/2)                                                                                                                                                                                                                                                                                                                                                                                                    |
| 01.12  | Final presentation (2/2)                                                                                                                                                                                                                                                                                                                                                                                                    |
