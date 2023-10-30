---
layout: page
title: 17-423/723 Designing Large-scale Software Systems
subtitle: Spring 2024
---

# Course Description

Design plays a crucial role in the success of a software product, as decisions made during the design stage have a long-lasting impact on qualities such as reliability, robustness, maintainability, scalability, and security. With the increasing use of AI-based programming tools (such as ChatGPT and Copilot), being able to effectively design large, complex software and reason about systems at scale will become highly sought-out skills in the software industry. 

This course teaches students how to design complex, large-scale software systems that are reliable, robust, and built to last. It introduces fundamental concepts and techniques for designing software to achieve qualities of a successful product (such as maintainability, scalability, and robustness) and to avoid catastrophic failures. After taking this course, students will be able to (1) systematically generate and explore design alternatives, (2) specify and evaluate design options using appropriate abstractions, and (3) communicate and critique design decisions with other members of large, multi-team organizations. The discussions of these concepts will be driven by case studies of past failures and successes in real-world software systems. The course will be hands-on and involve a semester-long project where the students will work in teams and collaborate with other teams to design, test, and deploy a complex software system. This course is aimed at both undergraduate and graduate students who are interested in the role of a software architect or designer in an organization.

## Prerequisite

- Intermediate programming skills and/or experience with building medium-size programs (e.g., 17-214)
- Experience with unit tests and version control systems (e.g., Git)
- An interest in learning from failures and a growth mindset

# Learning Objectives

After taking this course, students will be able to: 
- Describe, recognise, and apply software design principles for: design for reuse, design with reuse, design for change, design for robustness, design for testability, and design for scale
- Explain how to adapt the software design process to fit different domains, such as robotics, web apps, mobile apps, and medical systems
- Collaborate across teams to design & build complex software that cannot be built by a single development team
- Identify, describe, and prioritize relevant requirements for a given design problem
- Generate a list of viable design solutions given prioritized requirements 
- Apply appropriate abstractions & modeling techniques to communicate and document design solutions
- Evaluate design solutions based on their satisfaction of common design principles and prioritized requirements

# Course Philosophy 

## Hands-on Experience in Multi-Team Project
Interesting design challenges usually only arise in complex systems and can only be fully understood via first-hand experience. Therefore, teams in this course will work together on a single project to cooperatively build a complex system that involves interesting design decisions and discussions of interfaces between different teams. We will provide support structures to help you navigate potential cross-team issues. 

## Growth Mindset & Learning from Failure 
When working on complex design problems, especially when working in large teams over a longer time, design issues will inevitably arise. So no worries, in this course, we embrace a growth mindset and encourage students to see challenges in the course project as an opportunity to learn based on the motto: “If you fail and you know why you succeeded. If you succeed and you don’t know why you failed”. When grading the course project, we focus more on the semester-long continuous growth and end-of-semester learning outcome rather than perfection in the first attempt.    

## Active Student Participation  
Educational research shows that active student participation in lectures is crucial for ensuring a deep understanding of the material \[MIS\]. So rather than just presenting design principles in a traditional lecture, our lectures are based on real-world case studies from which we will derive design principles together.

## Interleaving of Course Topics
Learning science has shown that interleaving different topics throughout a course is more effective than discussing topics individually in large blocks \[MIS\]. Furthermore, the process of software design requires optimizing the trade-off between multiple quality attributes at the same time. Therefore, this course is structured to interleave design principles and other design objects throughout the semester. While this type of course design has been shown to objectively increase retention of knowledge and forming connections, it has also been shown that students subjectively feel that they learn less. **So don’t be discouraged! Even though it might feel like your learning progress is slower, you’re actually learning more this way!**

## Exit Tickets after each Lecture
Research in learning science has shown that student retention of learned material is most strongly impacted by the number of times students try to recall the material, such as in the format of after-lecture quizzes \[MIS\]. To support student learning, we will establish a short quiz to let students summarize each lecture. This helps us to identify common misconceptions right after each lecture and helps you to form long-term memories. The completion of weekly summaries will contribute to your participation grade.

\[MIS\]: Brown, Peter C., Henry L. Roediger III, and Mark A. McDaniel. Make it stick: The science of successful learning. Harvard University Press, 2014.

# Multi-Team Course Project
Students will be split into teams of five. All teams will collaborate with each other to work on a single software system to develop a social media platform. Each team will focus on one part of the system and needs to discuss interfaces and system-wide concerns with other teams. To simplify cross-team communication, we recommend that each team designates one team member to serve as a “facade”. Some parts of some recitations will be used as a platform for all students to collectively discuss and reflect on the overall system-wide design and teamwork. 
While each team is responsible to write their own unit tests and consider quality attributes in their decisions, one team, the “*quality team*”, will be responsible to design and implement a testbed infrastructure to assess system-level quality attributes of the system, and identify shortcomings of the evolving system.

# Assessments
Students learn more by applying and explaining ideas to others, thus, the course requires the following activities that determine the final grade:
- **25% Homework**: 5-6 light-weight homeworks mostly focusing on software design problems from case studies discussed in class
- **45% Project**: Individual reflection (via final report), design critiques, design documents, project presentation, functionality of the final result. Adjustments can be made based on outstanding effort or lack of effort
- **20% Exams** : Handwritten notes are allowed, no digital devices or printouts 
- **10% Participation**, Active participation in class discussions, completion of end-of-lecture exit tickets. Each submission that shows a reasonable effort gets 100%, even if there are misunderstandings. Everyone gets 3 free passes

# Course and Grading Policies

## Late work policy and resubmissions: 
We understand that studying during a pandemic is challenging and that some students have conflicting deadlines or are distracted by interviewing for jobs. We therefore build flexibility and a safety net directly into the rubric. If you need additional accommodations, please contact us.
Every student receives 7 tokens that they can spend throughout the semester in the following ways:
-  For each token a student can submit a homework assignment 1 day late (with 7 tokens a student can submit multiple homeworks one day late each or a single homework up to 7 days late).
- For three tokens a student can redo an individual homework assignment and resubmit. The earlier submission is discarded and the regraded assignment counts toward the final grade. Each homework can be resubmitted only once. Resubmissions must be received before the final presentation.
- For one token a student can submit a reading quiz late (any time before the final presentation) or resubmit a graded reading quiz.
- Remaining tokens at the end of the semester are counted as one participation day each.

If a student runs out of tokens, individual assignments receive a penalty of 15% per day.
Exceptions to this policy will be made at the discretion of the instructors in important circumstances, almost always involving a family or medical emergency — you can ask your academic advisor or the Dean of Student Affairs requesting the exception on your behalf. For accommodations related to remote teaching, we try to be flexible: please contact the instructors. Please communicate also with your team about potential timing issues.

## Regrading policy
If you have objections regarding the assigned points for a certain assessment, please email the grader of your assignment and/or instructor directly within one week of the grades being posted, or no later than one week before final grades are due in the case of regrading the final homework. Your email should contain well-grounded reasons for why the points do not seem to reflect your learning outcome in the submitted assignment. 

## Participation policy
Class participation will be graded by in-class engagement, including asking relevant questions based on a critical review of required readings and lectures, preparation for any in-class exercises, and responses on the class discussion board. Giving wrong answers during in-class sessions does not negatively affect your grade, because we don’t expect you to do perfect but to try to get better.

## Time management
This is a 12-unit course, and it is our intention to manage it so that you spend close to 12 hours a week on the course, on average. In general, 4 hours/week will be spent in class and 1-2 hours on readings, and 6-7 hours on assignments and the project. Please give the course staff feedback if the time the course is taking for you differs significantly from our intention. We are happy to provide tips on time management and will adjust the course load if we notice that many students are raising issues.

## Academic Integrity
Honesty and transparency are important to good scholarship. Plagiarism and cheating, however, are serious academic offenses with serious consequences. If you are discovered engaging in either behavior in this course, you will earn a failing grade on the assignment in question, and further disciplinary action may be taken. 
For a clear description of what counts as plagiarism, cheating, and/or the use of unauthorized sources, please see the [University’s Policy on Academic Integrity](https://www.cmu.edu/policies/student-and-student-life/academic-integrity.html).

In this course you are allowed to **discuss potential solution ideas** to individual homework with other students in order to practice brainstorming and communication between software engineers. However, your solution still has to be your own and should not be identical to the solution of your discussion partners. You may not show your final solution to other students before you both have submitted your solution. This applies to source code as well as write-ups. The use of **generative AI** has to be explicitly marked as such, including your prompts and a screenshot of the result. While we encourage you to critically engage with generative AI and use it for idea generation, the submitted solution has to be your own and differ significantly from responses of generative AI. Generative AI is not allowed on exams or exit tickets. 
If you have any questions regarding plagiarism or cheating, please ask us as soon as possible to avoid any misunderstandings. For more information about Carnegie Mellon’s standards with respect to academic integrity, you can also check out the Office of Community Standards & Integrity website.

## Student Wellness
As a student, you may experience a range of challenges that can interfere with learning, such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating and/or lack of motivation. These mental health concerns or stressful events may diminish your academic performance and/or reduce your ability to participate in daily activities. CMU services are available, and treatment does work. You can learn more about confidential mental health services available on campus at the Counseling and Psychological Services website. Support is always available (24/7) from Counseling and Psychological Services: 412-268-2922.

## Instructors

- [Eunsuk Kang](https://eskang.github.io/)
- [Tobias Dürschmid](https://tobiasduerschmid.github.io/)

