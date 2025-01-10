---
layout: page
title: 17-423/723 Designing Large-scale Software Systems
subtitle: Spring 2025
---

# Course Description

Design plays a crucial role in the success of a software product, as decisions made during the design stage have a long-lasting impact on qualities such as reliability, robustness, maintainability, scalability, and security. With the increasing use of AI-based programming tools (such as ChatGPT and Copilot), being able to effectively design large, complex software and reason about systems at scale will become highly sought-out skills in the software industry. 

This course teaches students how to design complex, large-scale software systems that are reliable, robust, and built to last. It introduces fundamental concepts and techniques for designing software to achieve qualities of a successful product (such as maintainability, scalability, and robustness) and to avoid catastrophic failures. After taking this course, students will be able to (1) systematically generate and explore design alternatives, (2) specify and evaluate design options using appropriate abstractions, and (3) communicate and critique design decisions with other members of large, multi-team organizations. The discussions of these concepts will be driven by case studies of past failures and successes in real-world software systems. The course will be hands-on and involve a semester-long project where the students will work in teams to design, test, and deploy a complex software system. This course is aimed at both undergraduate and graduate students who are interested in the role of a software architect or designer in an organization.

# Logistics

### Prerequisites

- Intermediate programming skills and/or experience with building medium-size programs (e.g., 17-214, 17-313)
- Experience with unit tests and version control systems (e.g., Git)
- An interest in learning from failures and a growth mindset

### Time & Location
- Lectures: Mon & Wed, 9:30-10:50 AM SH 238
- Recitation: Friday, 10:00-10:50 AM HH B103

### Course Staff

- Instructor: [Eunsuk Kang](https://eskang.github.io/) (eunsukk)
- TA: Shivam Bansal (shivamb)

### Readings

There is no single official textbook for this course. Instead, readings will be assigned from academic and industry articles, book chapters, blog posts, and videos. Please see Canvas for more information about the readings.

# Class Schedule (tentative)

Date | Topic | Reading | Assignment
-| - | - | -
Jan 13 Mon | Introduction and motivation | [Just Enough Architecture](https://www.georgefairbanks.com/e-book/) Ch. 3 |  
Jan 15 Wed |  Problem vs. solution space| [The World and the Machine](https://scholar.google.com/scholar?cluster=1090758480873197042)  | 
Jan 17 Fri | Exercises: Design activities  | | 
Jan 20 Mon | **MLK Jr Day - No classes** | | 
Jan 22 Wed |  Design abstractions | [Just Enough Architecture](https://www.georgefairbanks.com/e-book/) Ch. 6 & 9 | HW1 out
Jan 24 Fri |  Exercises: Modeling | | 
Jan 27 Mon | Quality attributes & trade-offs |  |
Jan 29 Wed | Design space exploration | | HW1 due; M1 out
Jan 31 Fri | Teamwork guidelines | | 
Feb 3 Mon | Design for change| Information hiding: ([IEEE Software article](https://stevemcconnell.com/articles/missing-in-action-information-hiding/)) ([Parnas 1972](https://dl.acm.org/doi/pdf/10.1145/361598.361623)) | 
Feb 5 Wed | Design for change (continued) | [Clean Architecture](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019696543704436) Ch. 7, 10, 11, 22 | M1 due; M2 out
Feb 7 Fri | Exercises: Changeability | | | 
Feb 10 Mon |  Design for testability | [Chaos Experiments at Netflix](https://medium.com/@haasitapinnepu/how-netflix-embraced-chaos-b1f054ab9892) | 
Feb 12 Wed | Design for testability (continued) | | |
Feb 14 Fri |  Exercises: Testability | | |
Feb 17 Mon |  Midterm | | |
Feb 19 Wed |  Design for interoperability | | |
Feb 21 Fri |  Midterm discussion | | |
Feb 24 Mon | Design with reuse | | |
Feb 26 Wed | | | |
Feb 28 Fri | | | M2 due; M3 out |
Mar 3 Mon | **Spring break - No classes** | | 
Mar 5 Wed | **Spring break - No classes** | |
Mar 7 Fri | **Spring break - No classes** | | 
Mar 10 Mon | Arguing for and reviewing designs | [Improving Design Reviews at Google](https://research.google/pubs/improving-design-reviews-at-google/) | | 
Mar 12 Wed | Cross-team interface design session | | HW2 out |
Mar 14 Fri | | | |
Mar 17 Mon | Design for scalability | [Designing Data-intensive Applications](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019578119704436) Ch. 1, 5, 6 | 
Mar 19 Wed | Design for scalability (continued) | [Monolith first](https://martinfowler.com/bliki/MonolithFirst.html) | HW2 due |
Mar 21 Fri | Exercises: Scalability | | 
Mar 24 Mon | Design for robustness| [Why software quality matters](https://web.mit.edu/6.033/www/papers/Nothing_Wrong.pdf) | M3 due; M4 out |
Mar 26 Wed | Design for robustness (continued) | | | 
Mar 28 Fri | Exercises: Robustness | | 
Mar 31 Mon | Design Processes | | |
Apr 2 Wed | Design for security | | M4a due
Apr 5 Fri | **Spring Carnival - No classes** | |
Apr 7 Mon | Design for usability | [Mental Models](https://www.nngroup.com/articles/mental-models) | 
Apr 9 Wed | Ethical and responsible design | [Algorithmic Accountability](https://datasociety.net/wp-content/uploads/2018/04/Data_Society_Algorithmic_Accountability_Primer_FINAL-4.pdf) | M4b due; M5 out
Apr 11 Fri | Exercises: Security | HW3 out
Apr 14 Mon | Software design & AI | | 
Apr 16 Wed | Software design & AI (continued) |  | Project Presentation out 
Apr 18 Fri | Project work time | | M5 due 
Apr 21 Mon | Course review | | HW3 due 
Apr 23 Wed | Project presentations | | 

# Learning Objectives

After taking this course, students will be able to:
- Describe, recognise, and apply principles for: Design for reuse, design with reuse, design for change, design for robustness, design for testability, and design for scale
- Explain how to adapt a software design process to fit different domains, such as robotics, web apps, mobile apps, and medical systems
- Identify, describe, and prioritize relevant requirements for a given design problem
- Generate viable design solutions that appropriately satisfy the trade-offs between given requirements 
- Apply appropriate abstractions & modeling techniques to communicate and document design solutions
- Evaluate design solutions based on their satisfaction of common design principles and  trade-offs between different quality attributes


# Course Philosophy 

### Hands-on Experience in a Collaborative Project
Interesting design challenges usually arise in complex systems and can only be fully understood via first-hand experience. Therefore, teams in this course will work together on a single project to collaboratively build a complex system that involves interesting design decisions and discussions of interfaces between different teams. We will provide support structures to help you navigate potential cross-team issues. 

### Growth Mindset & Learning from Failures 
When working on a complex software project, design issues and challenges will inevitably arise. In this course, we embrace a growth mindset and encourage students to see challenges in the project as an opportunity to learn based on the motto: “If you fail and you know why, you've succeeded. If you succeed and you don’t know why, you've failed”. We will focus on continuous, semester-long improvements, rather than achieving perfection in the first attempt.    

### Active Student Participation  
Educational research shows that active student participation in lectures is crucial for ensuring a deep understanding of the material \[MIS\]. So rather than just presenting design principles in a traditional lecture style, our lectures are based on real-world case studies from which we will derive design principles together.

\[MIS\]: Brown, Peter C., Henry L. Roediger III, and Mark A. McDaniel. Make it stick: The science of successful learning. Harvard University Press, 2014.

# Assessments
- **20% Homework**: 3-4 individual homeworks mostly focusing on software design problems from case studies discussed in class.
- **50% Project**: Multiple milestones involving development of a fully functional system, along with design documents and reflections, critiques, and a final project presentation. 
- **20% Exams** : In person, open-book midterm & final. 
- **10% Participation**, Active participation in class discussions, completion of end-of-lecture exit tickets. Each submission that shows a reasonable effort gets 100%, even if there are misunderstandings. Everyone gets 3 free passes.

# Course and Grading Policies

### Late Work Policy and Resubmissions
We understand that studying during a pandemic is challenging and that some students have conflicting deadlines or are distracted by interviewing for jobs. We therefore build flexibility and a safety net directly into the rubric. If you need additional accommodations, please contact us.

Every student receives 7 tokens that they can spend throughout the semester in the following ways:
- For each token a student can submit a homework assignment 1 day late.
- For three tokens a student can redo an individual homework assignment and resubmit. The earlier submission is discarded and the regraded assignment counts toward the final grade. Resubmissions must be received before the final presentation.
- For example, with 7 tokens a student can submit multiple homeworks one day late each or redo one homework twice and submit another homework one day lat. 
- Remaining tokens at the end of the semester are counted as one participation day each.

If a student runs out of tokens, individual assignments receive a penalty of 15% per day.
Exceptions to this policy will be made at the discretion of the instructors in important circumstances, almost always involving a family or medical emergency — you can ask your academic advisor or the Dean of Student Affairs requesting the exception on your behalf. For accommodations related to remote class attendance, we try to be flexible: please contact the instructors. Please communicate also with your team about potential timing issues.

### Participation Policy
Class participation will be graded by in-class engagement, including asking relevant questions based on a critical review of required readings and lectures, preparation for any in-class exercises, and responses on the class discussion board. 

### Time Management
This is a 12-unit course, and it is our intention to manage it so that you spend close to 12 hours a week on the course on average. In general, 4 hours/week will be spent in class, 1-2 hours on readings, and 6-7 hours on assignments and the project. Please give the course staff feedback if the time the course is taking for you differs significantly from our intention. We are happy to provide tips on time management and will adjust the course load if we notice that many students are raising issues.

### Academic Integrity
Honesty and transparency are important to good scholarship. Plagiarism and cheating, however, are serious academic offenses with serious consequences. If you are discovered engaging in either behavior in this course, you will earn a failing grade on the assignment in question, and further disciplinary action may be taken. 
For a clear description of what counts as plagiarism, cheating, and/or the use of unauthorized sources, please see the [University’s Policy on Academic Integrity](https://www.cmu.edu/policies/student-and-student-life/academic-integrity.html).

In this course you are allowed to **discuss potential solution ideas** to individual homework with other students in order to practice brainstorming and communication between software engineers. However, your solution still has to be your own and should not be identical to the solution of your discussion partners. You may not show your final solution to other students before you both have submitted your solution. This applies to source code as well as write-ups. 

The use of **generative AI** has to be explicitly marked as such, including your prompts and a screenshot of the result. While we encourage you to critically engage with generative AI and use it for idea generation, the submitted solution has to be your own and differ significantly from responses of generative AI. Generative AI is not allowed on exams or exit tickets. 

If you have any questions regarding plagiarism or cheating, please ask us as soon as possible to avoid any misunderstandings. For more information about Carnegie Mellon’s standards with respect to academic integrity, you can also check out the Office of Community Standards & Integrity website.

# Student Wellness
As a student, you may experience a range of challenges that can interfere with learning, such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating and/or lack of motivation. These mental health concerns or stressful events may diminish your academic performance and/or reduce your ability to participate in daily activities. CMU services are available, and treatment does work. You can learn more about confidential mental health services available on campus at the Counseling and Psychological Services website. Support is always available (24/7) from Counseling and Psychological Services: 412-268-2922.



