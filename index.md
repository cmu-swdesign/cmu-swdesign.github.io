---
layout: page
title: 17-423/723 Designing Large-scale Software Systems
subtitle: Spring 2024
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
- Lectures: Mon & Wed, 9:30-10:50 AM Scaife Hall (SH) 236
- Recitation: Friday, 10:00-10:50 AM Scaife Hall (SH) 238

### Course Staff

- [Eunsuk Kang](https://eskang.github.io/) (co-instructor)
- [Tobias Dürschmid](https://tobiasduerschmid.github.io/) (co-instructor)
- [Parv Kapoor](https://parvkpr.github.io/) (TA)

### Readings

There is no single official textbook for this course. Instead, readings will be assigned from academic and industry articles, book chapters, blog posts, and videos. Please see Canvas for more information about the readings.

# Class Schedule 

Date | Topic | Reading | Assignment
-| - | - | -
Jan 17 Wed | [Introduction and motivation](slides/Lecture-1-Introduction.pdf) | [Just Enough Architecture](https://www.georgefairbanks.com/e-book/) Ch. 3 |  
Jan 19 Fri | [Teamwork guidelines](slides/Recitation-1-Teamwork.pdf)  | | 
Jan 22 Mon |  [Problem vs. solution space](slides/Lecture-2-Problem-Space.pdf) | [The World and the Machine](https://scholar.google.com/scholar?cluster=1090758480873197042)  | 
Jan 24 Wed |  [Design abstractions](slides/Lecture-3-Design-Abstractions.pdf) | [Just Enough Architecture](https://www.georgefairbanks.com/e-book/) Ch. 6 & 9 | [HW1](assignments/HW1-modeling.pdf) out
Jan 26 Fri |  [Exercises: Modeling](slides/Recitation-2-Modeling.pdf) | | 
Jan 29 Mon | [Quality attributes & trade-offs](slides/Lecture-4-Quality-Attributes.pdf) | **Required** [Topics in ROS](reading/ROSTopicReading.pdf) |
Jan 31 Wed | [Design space exploration](slides/Lecture-5-Design-Spaces.pdf) | **Required** ([Role of design spaces](reading/ShawDesignSpace-a.pdf)) ([How software designers use them](reading/ShawDesignSpace-b.pdf)) | HW1 due; [M1](assignments/Project-M1.pdf) out
Feb 2 Fri | [Exercises: Designing with QAs](slides/Recitation-3-ADD.pdf) | | 
Feb 5 Mon | [Generating design alternatives](slides/Lecture-6-Generate.pdf) | [Decision-Making Principles for Better Software Design Decisions](https://ieeexplore.ieee.org/iel7/52/9585138/09585145.pdf) [List of Some Design Patterns](https://sourcemaking.com/design_patterns)| 
Feb 7 Wed | [Design for change](slides/Lecture-7-Design-for-Change.pdf) | Information hiding: ([IEEE Software article](https://stevemcconnell.com/articles/missing-in-action-information-hiding/)) ([Parnas 1972](https://dl.acm.org/doi/pdf/10.1145/361598.361623))|
Feb 9 Fri | [Brainstorming design alternatives](slides/Recitation-4-Generate.pdf) | [Monopoly](https://www.youtube.com/watch?v=AuWvMgYv03g) | 
Feb 12 Mon | [Design for change (continued)](slides/Lecture-8-Design-for-Change-2.pdf) | [Clean Architecture](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019696543704436) Ch. 7, 10, 11, 22 | M1 due; [M2](assignments/Project-M2.pdf) out
Feb 14 Wed | [Design for interoperability](slides/Lecture-9-Interoperability.pdf) | **Required** [GDS](https://www.youtube.com/watch?v=1-m_Jjse-cs&pp=ygUMZ2RzIHdlbmRvdmVy)  **Recommended** [GDS API Example](https://developer.sabre.com/docs/rest_apis/digital_connect/stateless_services/air_exchange_search/v100/reference-documentation#/AirExchangeSearch/AirExchangeSearch)|
Feb 16 Fri | [Exercises: Changeability & interoperability](slides/Recitation-5-Changeability.pdf) | |
Feb 19 Mon | [Design for testability](slides/Lecture-10-Testability.pdf) | **Required** [Chaos Experiments at Netflix](https://medium.com/@haasitapinnepu/how-netflix-embraced-chaos-b1f054ab9892) |
Feb 21 Wed | [Design with reuse](slides/Lecture-11-DesignWithReuse.pdf)| |
Feb 23 Fri | [Midterm preparation](slides/Recitation-6-Exam-Prep.pdf) | |
Feb 26 Mon | [Arguing for and reviewing designs](slides/Lecture-12-Design-Review.pdf) | [Improving Design Reviews at Google](https://research.google/pubs/improving-design-reviews-at-google/)| 
Feb 28 Wed | Midterm | | 
Mar 1 Fri | Project office hour | | M2 due; [M3](assignments/Project-M3.pdf) out |
Mar 4 Mon | **Spring break - No classes** | | 
Mar 6 Wed | **Spring break - No classes** | |
Mar 8 Fri | **Spring break - No classes** | | 
Mar 11 Mon | [Cross-team interface design session](slides/Lecture-13-FeedbackAndProject.pptx.pdf) |  **Required** Please carefully read [M3](assignments/Project-M3.pdf) | 
Mar 13 Wed | [Design for reuse](slides/Lecture-14-DesignForReuse.pdf) | **Recommended** [A, T, AT, 0-Modules](https://icsa-conferences.org/series/WICSA/1999/final/fuchs.pdf) <br>  [Clean Architecture](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019696543704436) Ch. 8, 30, 31, 32 <br> Pipes & Filters: [Pattern-oriented Software Architecture V1](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019577802604436) Chapter 2.2 <br> Research: [Reusability affecting factors and software metrics for reusability: A systematic literature review](https://onlinelibrary.wiley.com/doi/pdf/10.1002/spe.2961?casa_token=5_UkbmA_PFUAAAAA:udiiG3KpCGsMOKaFfFQYGfnVAMQKHGZ4DlUP8InmftHh1hofjm7HSo-XZLGe-nTyoxf44ZFEv9lLVfMO)|  [HW2](assignments/HW2-Design-for-Reuse.pdf) out
Mar 15 Fri | [Midterm review](slides/Recitation-7-Midterm-Review.pdf) | | 
Mar 18 Mon | [Design for scalability](slides/Lecture-15-16-Design-for-Scalability.pdf)  | [Designing Data-intensive Applications](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019578119704436) Ch. 1, 5, 6 | 
Mar 20 Wed | [Design for scalability (continued)](slides/Lecture-15-16-Design-for-Scalability.pdf) | [Monolith first](https://martinfowler.com/bliki/MonolithFirst.html) | HW2 due
Mar 22 Fri | [Exercises: Scalability](slides/Recitation-8-Scalability.pdf) | | 
Mar 25 Mon | [Design for robustness](slides/Lecture-17-18-Design-for-Robustness.pdf) | [Why software quality matters](https://web.mit.edu/6.033/www/papers/Nothing_Wrong.pdf) | M3 due; [M4](assignments/Project-M4.pdf) out
Mar 27 Wed | [Design for robustness (continued)](slides/Lecture-17-18-Design-for-Robustness.pdf) | [Patterns for Fault Tolerant Software](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019576951304436) Ch. 1, 2 | 
Mar 29 Fri | [Design Tradeoffs Exercise](slides/Recitation-9-Design-Tradeoffs.pdf)  | | 
Apr 1 Mon | [Design Processes](slides/Lecture-16-Process.pdf)| **Required** [Agile Software Development with the Scrum Process](https://www.atlassian.com/agile/scrum)  | 
Apr 3 Wed | [Design for security](slides/Lecture-20-Design-for-Security.pdf)  | [Security Architecture of qmail](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=7858f98f9687be9f091b795c120ade835471c607) [Protection of Information in Computer Systems](https://ieeexplore.ieee.org/abstract/document/1451869) | M4a due
Apr 5 Fri |  [Project Risk Storming](slides/Recitation-10-Riskstorming.pdf) | [Risk Storming](https://riskstorming.com/) | [HW3](assignments/HW3-Design-for-Scalability.pdf) out
Apr 8 Mon | Design for usability| | 
Apr 10 Wed |  Ethical and responsible design |  | M4b due; M5 out
Apr 12 Fri | **Spring Carnival - No classes** | | 
Apr 15 Mon | [TBD] | | 
Apr 17 Wed | Designing AI-based systems | | 
Apr 19 Fri |  | | M5 due
Apr 22 Mon | Course review  | | HW3 due
Apr 24 Wed | Project presentations | |
May 3 Fri | Final exam (8:30 am - 11:30 am)| |

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
-  For each token a student can submit a homework assignment 1 day late (with 7 tokens a student can submit multiple homeworks one day late each or a single homework up to 7 days late).
- For three tokens a student can redo an individual homework assignment and resubmit. The earlier submission is discarded and the regraded assignment counts toward the final grade. Each homework can be resubmitted only once. Resubmissions must be received before the final presentation.
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



