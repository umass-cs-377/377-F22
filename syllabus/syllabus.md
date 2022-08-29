# Syllabus

## General Information

- **Semester**: Fall 2022
- **Start Date**: September 6, 2022
- **End Date**: December 12, 2022
- **Credits**: 4
- **Lectures**: **01-LEC (44864)**: TuTh 10:00AM - 11:15AM, Goessmann Lab. Add rm 64 Tim Richards
- **Labs**: **01AA-DIS(44865)**: Fr 12:20PM - 1:10PM, Goessmann Lab. Add rm 64 Staff
- **Prerequisites**: COMPSCI 230 Computer Systems Principles. This course assumes a solid understanding of the C programming language, command line, basic Unix skills, the ability to learn new programming languages, how to compile programs, how to build programs using make, and general use of typical Unix commands and environment.
- **Instructors**: Tim Richards
- **Staff**: Dave Dirnfeld (TA), Calvin Chai (TA), Bochen Xu (TA), Matthew Weiner (TA), Stuart Lustig (UCA), Meghana Kaki (UCA), Eugene Mak (UCA), Rohit Rangan (UCA), Sage Chircu (UCA), Yichong Liu (UCA), Ronan Salz (UCA), Zhiyang Zuo (UCA), Vinh Le (UCA)

## Description

In this course we examine the important problems in operating system design and implementation. The operating system provides a well-known, convenient, and efficient interface between user programs and the bare hardware of the computer on which they run. The operating system is responsible for allowing resources (e.g., disks, networks, and processors) to be shared, providing common services needed by many different programs (e.g., file service, the ability to start or stop processes, and access to the printer), and protecting individual programs from one another. The course will start with a brief historical perspective of the evolution of operating systems over the last fifty years, and then cover the major components of most operating systems. This discussion will cover the tradeoffs that can be made between performance and functionality during the design and implementation of an operating system. Particular emphasis will be given to three major OS subsystems: process management (processes, threads, CPU scheduling, synchronization, and deadlock), memory management (segmentation, paging, swapping), file systems, and operating system support for distributed systems.

## Statement of Inclusivity

The staff for this course support the UMass commitment to diversity, and welcome individuals regardless of age, background, citizenship, disability, sex, education, ethnicity, family status, gender, gender identity, geographical origin, language, military experience, political views, race, religion, sexual orientation, socioeconomic status, and work experience. In this course, each voice in the classroom has something of value to contribute. Please take care to respect the different experiences, beliefs and values expressed by students and staff involved in this course.

## Course Objectives

- The objectives of this course are to learn and understand operating system concepts including:
- Processes and Process API
- System Calls
- Direct Execution
- CPU Scheduling
- Concurrency and Threads
- Locks and Event-based Concurrency
- Condition Variables, Semaphores, and Monitors
- I/O Devices, Disks, Files and Directories, and File System Implementation
- Address Spaces and the Memory API
- Address Translation and Segmentation
- Free Space Management and Paging
- Translation Lookaside Buffers and Page Tables

## Course Format

- **Lecture** will provide an overview of the topics concerned with operating systems. Typical classes will follow a lecture-style presentation of the material with interaction from students based on examples covered. Occasionally, there may be an in-class activity that is graded. You are expected to attend lectures regularly. Lectures will also be available live on zoom and recorded for viewing after class. We provide this flexibility for your busy lives, but please do not abuse it. We do expect you to attend class on a regular basis.

- **Discussion** will have an associated exercise that you are required to complete. You are expected to begin these exercises during the lab working with others taking the course. Course staff will be available to answer questions and help guide you through the assignment. You are expected to attend the discussion. Discussions will not be recorded.

## How to Succeed

Your success in this class is important to us. We all learn differently and bring different strengths and needs to the class. If there are aspects of the course that prevent you from learning or make you feel excluded, please let us know as soon as possible. Together we’ll develop strategies to meet both your needs and the requirements of the course. There are also a range of resources on campus, including:

- [Academic Calendar](https://www.umass.edu/registrar/calendars/academic-calendar)
- [Learning Resource Center](https://www.umass.edu/lrc/)
- [Center for Counseling and Psychological Health (CCPH)](https://www.umass.edu/counseling/)
- [English as a Second Language (ESL) Program](https://www.umass.edu/esl/)

## Required Materials

- **Textbook**: [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP), Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dussea. This is a free textbook available online. While the entire textbook is available for free from this site, if you so wish, a hard copy may be purchased on Amazon.

- **Laptop Computer**: It is highly recommended that you have a laptop computer for the discussion section. If you do not have a portable machine (not Chromebook, not tablet), you should work with another student during the discussion section. Please inform the course staff so we can ensure that you are paired up with another student.

## Learning Management Systems

- **Moodle**: We will use the Moodle Learning Management System (LMS) as the primary hub for course content. You will be able to access readings, lecture material, assignments, and any other important material pertaining to this course. We may use Moodle and Gradescope to submit assignments. You will be able to access your latest grades and comments for assignments using the Moodle Gradebook.

- **GitHub Classroom**: Project assignments are distributed and managed using [GitHub Classroom](https://classroom.github.com). GitHub Classroom uses Git to organize assignments that are stored in Git repositories. We use Git and GitHub classroom to get you familiar and comfortable using version control and to encourage good software development practices. It also allows us to easily identify the changes you have made to projects, see your progress as you make changes to your code, and make comments directly to your git repositories to offer help and guidance.

- **Gradescope**: We use Gradescope for automatically grading programming projects. Gradescope allows us to provide fast and accurate feedback on your work. Before the deadline you can submit as many times as you need, so submit early and often to ensure you have something in before the deadline. Become familiar with Gradescope and verify that your submission has been properly uploaded before the deadline. Use OneDrive, DropBox, Google Drive, or some other backup software to ensure that your work is not lost in the event of a computer failure. The Gradescope autograder will provide you with some limited feedback on your submissions: does it compile, does it pass automated tests, what your score is, etc. The autograder does not provide detailed feedback. We will help you get familiar with Gradescope as the course progresses.

## Course Development Environment

The course development environment is Linux in the Edlab environment, C/C++, command line, and console-based editors such as emacs, vim, and nano. All assignments are based on this and is what the course and its staff support. If you use any other tool you are on your own.

### Edlab

We will be using the [EdLab](http://www-edlab.cs.umass.edu/) Linux environment for all programming tasks in this course. To access the EdLab you must use [ssh](https://en.wikipedia.org/wiki/Secure_Shell) (secure shell) to remotely login to the EdLab. Your account has already been created by [CSCF](https://www.cics.umass.edu/about/computing-facilities) (Computer Science Computing Facility). We will also be using [sftp](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) (secure file transfer protocol) to transfer files from and to the EdLab environment - this will be necessary to submit programming assignments to Gradesope.

### Logging In**

Your username is generally the same as your UMass username. The initial password for a new account is in the following:

```
ELxxxaaa
```

where `xxx` = last 3 digits of your 8-digit student ID, `aaa` = 1st 3 letters of your username. If you had an account on the EdLab system last year and changed your password, then the password will be whatever you changed it to. You should also take a look at Logging Into the EdLab for the First Time. After you successfully log in to the EdLab environment you will be in your user/home directory. You should also notice a directory named `cs377`. You should use this directory for all your programming work associated with this course.

**Note: if you used the edlab environment in a previous semester and forgot your password or have other account issues please email CICS IT & Facilities (CSCF) at system@cs.umass.edu.** 

## Programming Editors

There are several different programming editors available for you to choose from that allow you to edit your code on the Edlab. The easiest way to do this is logging in to the Edlab and use one of the following available editors from the command line:

- [Emacs](https://www.gnu.org/software/emacs/) - An extensible, customizable, free/libre text editor - and more. At its core is an interpreter for Emacs Lisp, a dialect of the Lisp programming language with extensions to support text editing.
- [Vim](https://www.vim.org/) - A highly configurable text editor built to make creating and changing any kind of text very efficient.
- [Nano](https://www.nano-editor.org/) - A text editor for Unix-like computing systems or operating environments using a command line interface.

Another great option is [VSCode](https://code.visualstudio.com/) that can be used locally to edit code remotely on the Edlab. This is an excellent editor, but it does require some setup to use [Remote Development using ssh](https://code.visualstudio.com/docs/remote/ssh).

There are many short tutorials out there. We recommend that you do a quick search to find an introductory tutorial to become acquainted with at least one of these editors if you are not already familiar with one of them. You will have some guidance in the first lab!

## Communication

- **Email**: Email should not be used. Please post privately to Instructors on Piazza. In the unlikely event that you are unable to post to Piazza, please send an email to the instructor teaching your course section.

- **Piazza**: We will be using Piazza for all other communication. This online discussion forum should be your first choice for asking questions. You should check the discussion forum before asking your question to see if the same question has already been posted. We will not answer questions that have already been answered in the discussion forum. Think before you post. We expect you to do a reasonable amount of thinking to try to solve your problems before posting for help. Make sure you are articulate and clear with your post (i.e., think before you post). You should post questions related to assignments early rather than wait until the last minute. Questions that are posted very near an assignment deadline may not be answered. Course staff are expected to answer questions Monday through Friday. Do not expect prompt answers on Saturday, Sunday, and scheduled holidays and breaks.

  **Please post with respect and kindness. Posts that are disrespectful, crude, inappropriate, or mean will not be tolerated and will be reported and result in your immediate removal from the course and a failure for the course.**

## Course Format

### Lectures

Lectures will be led by the professor and provide a high-level overview of the course material. The presentation format will include a variety of slides, written notes, programming examples, activities, etc. All material will be available through the course learning management system site or website. You are expected to attend every lecture for your section and arrive promptly so you do not disturb others. You may use electronic devices during class, however, its use must pertain to the activity at hand. If your use of an electronic device is distracting to yourself or others, you will be asked to turn the device off.

**What happens if I can’t attend a lecture in person?**

Although we want you to attend the lecture for your section in person, we understand that sometimes that isn’t always possible. For that reason, we provide flexible options that allow you to participate.

- **Remote Synchronous**: attend the lecture remotely on Zoom and ask questions through the chat system.
- **Asynchronous**: watch the recorded lecture at a time that is convenient for you.

### Lab

The Lab section is led by teaching assistants (TAs) for this course. There will also be undergraduate course assistants (UCA) assigned to your lab section. You are expected to attend every lab section. Labs are used to begin lab assignments and get help completing those assignments. Missing a lab section does not excuse you from any activities that occur during that time. Do not ask to make up any missed work during lab section time.

**What happens if I can’t attend a lab in person?**

Although we want you to attend labs in person, we understand that sometimes that isn’t always possible. For that reason, we provide flexible options that allow you to participate.

- **Remote Synchronous**: attend the lab remotely on Zoom and ask questions through the messaging system.
- **Asynchronous**: labs will not be recorded, however, you must still complete the lab activity by the assigned due date.

## Rules for Success

### Student Responsibilities

If you follow these rules, your odds of learning the material and achieving a good grade in this course will improve greatly.

- Read the assignment documentation early and carefully.
- Do your work on time, submit your work on time, and make sure you submitted the correct work.
- Communicate with other students in the course, the professor, and other course staff for help.
- Be honest in the work you do and the submissions you make.
- Communicate with me and others in the course with respect and understanding.
- Do not ask to submit assignments after the due date.

### Instructor Responsibilities

You can expect from us:

- Timely release of course assignments.
- Timely release of scores achieved on course assignments.
- To respond to questions in the discussion forums in a reasonable amount of time during the week and normal working hours.
- Be respectful of your ideas and value the diversity you bring to the virtual classroom.
- Be open to dialogue that challenges me.
- Be present during my stated office hours.
- Ensure the proper running of the course in the online format.

## Grading Policy

The anticipated breakdown of course grades is as follows; this is subject to change.

- Project Assignments (45%)
- Topic Quizzes (20%)
- Final Exam (20%)
- Discussion Exercises (15%)

### Grading Notes

- The numerical cutoff for final course letter grade assignment will be made after all grading is completed. As a rough guide, expect to require at least a 93 to get an A, a 90 to get an A-, an 87 to get a B+, an 83 to get a B, an 80 to get a B-, etc.
- Individual projects/assignments/labs will not be scaled (curved).
- The instructor may or may not choose to scale final grades.
- Final grades are assigned based on the overall weighted average as defined by the grading policy. Grades will be rounded up. For example, if you achieve an 89.93 then the final letter grade will be (for example) an A-, not a B+.

## Assessment/Work

- **Project Assignments**: There are approximately 6 projects that are hands on with programming as it relates to the material. You will be provided a “starter” project, but will require additions, modifications, or tasks to complete it. Most projects come with some tests (but not all) to guide you. You submit your projects to Gradescope which will run our auto-grader and apply additional private tests.
  
- **Topic Quizzes**: Topic quizzes will test your knowledge of the material. There will be approximately 6 of these assessments. They will be multiple choice, true/false, etc. They will be available on Moodle during a 24 hour period. Once you start a topic quiz you will have 50 minutes to complete it.

- **Final Exam**: There will be a final exam for this course that you will complete during the final examination period. The final exam will be cumulative and will include a certain percentage of the questions you have already seen on the topic quizzes. The final exam will also include some open response questions in addition to multiple choice, true/false, etc. style questions. You will have 2 hours to complete the final exam once you start.
  
- **Discussion Exercises**: A discussion exercise is a short activity that will focus on expanding your knowledge in a particular topic area. They are often designed to provide guidance for an upcoming project or to enhance your understanding of the content for that week. They are graded both automatically and manually.

## Assignment Submission

Assignments will be submitted electronically. You are responsible for submitting your assignments by the assigned due date. The due dates for assignments will be clearly indicated on Moodle and it is your responsibility to update your own calendar so you are aware of due dates.

## Late Submissions

- It is your responsibility for maintaining your own schedule and being prompt with your submissions. We expect that you become familiar with the course submission software and verify that your submission has been properly uploaded. Instructors will not grant late submissions due to lack of checking on this. The course staff assumes:
- You are an adult and have the ability to check and verify your work has been received properly.
- You are capable of using OneDrive, DropBox, Google Drive, or some other backup software to ensure that your work is not lost in the event of a computer failure.
- You have a back-up plan in place in the event that your computer fails or your internet connection is unavailable. Make sure you have a plan B and C if your computer crashes or your internet is unavailable. This is your responsibility.
- To ensure that you submit assignments on time you should begin them early and not wait until the last minute to submit. For some assignments you may be able to submit multiple times so submit early and often to ensure you have something in before the deadline.

## Exemptions

- There may be situations when you cannot take an exam, or submit an assignment by the due date. You may ask for an extension by posting privately to Instructors on Moodle, religious or funerary events, university-related events (athletic event, field trip, or performance), and extenuating non-academic reasons (military obligation, family illness, jury duty, automobile collision). For religious reasons, you must provide us with a written list of such dates within one week of your enrollment in the course. In all other instances, please provide us with written documentation as soon as possible.
- If you add the class late, you are responsible for notifying us when you join the course and arranging for any deadline extensions with the instructors.
- We understand that sometimes you may be unable to complete course requirements within the allotted time because of severe medical or personal problems. In these cases, you may request a grade of Incomplete from the instructor of the course. Otherwise, the recommended course of action is to withdraw and retake the course in the future. Please see the Academic Regulations Section IV Grading System and Credit Guidelines for further details.

## Course Support


### Office Hours

Office hours are times when we provide real-time access to the instructor, TAs, and UCAs. You do not need an appointment to attend office hours, attendance is optional, and all questions you have about the course are welcome. These sessions will be held at several different times during the week. Office hours will be posted on Moodle.

### Accommodations

The University of Massachusetts Amherst is committed to providing an equal educational opportunity for all students. If you have a documented physical, psychological, or learning disability on file with Disability Services (DS), you may be eligible for reasonable academic accommodations to help you succeed in this course. If you have a documented disability that requires an accommodation, please notify me as soon as possible so that we may make appropriate arrangements. For further information, please visit Disability Services (https://www.umass.edu/disability/).

### Title IX

If you have been the victim of sexual violence, gender discrimination, or sexual harassment, the university can provide you with a variety of [support resources](http://www.umass.edu/titleix/node/448) and accommodations. UMass is committed to providing these resources with minimal impact and costs to survivors on a case-by-case basis. Resources are available to survivors with or without them filing a complaint. No upfront costs are charged to any currently enrolled students for University Health Services or the Center for Counseling and Psychological Health, and no fees exist for services in the Dean of Students Office, the Center for Women and Community, Student Legal Services, or by live-in residential staff.

## Attendance and Participation

You are expected to attend class and lab regularly, read any assigned readings before class, and participate in class discussions and activities. Your participation will be evaluated in a variety of ways. This includes any in class activities or activities that may be given during class or lab sections. You are responsible for maintaining your own schedule and ensuring that you are present during these activities and/or complete them in a timely manner. It is generally not possible to make up missed activities.

## Course Incompletes

Students who are unable to complete course requirements within the allotted time because of severe medical or personal problems only may request a grade of Incomplete from the instructor of the course. Incomplete grades are warranted only if a student is passing the course at the time of the request and if the course requirements can be completed by the end of the following semester. Furthermore, an incomplete will be granted if at least 75% of the work has been completed for the course. Otherwise, the recommended course of action is to withdraw and retake the course in the future. Please see the Academic Regulations Section IV Grading System and Credit Guidelines for further details.

**Note: an incomplete means you are on your own to complete the material agreed upon by the instructor of this course. Do not expect additional help or one-on-one teaching of the material past the course completion date. It is your responsibility to complete the remaining material.**

## Academic Honesty

Since the integrity of the academic enterprise of any institution of higher education requires honesty in scholarship and research, academic honesty is required of all students at the University of Massachusetts Amherst. Academic dishonesty is prohibited in all programs of the University. Academic dishonesty includes but is not limited to: cheating, fabrication, plagiarism, and facilitating dishonesty. Appropriate sanctions may be imposed on any student who has committed an act of academic dishonesty. Instructors should take reasonable steps to address academic misconduct. Any person who has reason to believe that a student has committed academic dishonesty should bring such information to the attention of the appropriate course instructor as soon as possible. Instances of academic dishonesty not related to a specific course should be brought to the attention of the appropriate department Head or Chair. Since students are expected to be familiar with this policy and the commonly accepted standards of academic integrity, ignorance of such standards is not normally sufficient evidence of lack of intent (http://www.umass.edu/dean_students/codeofconduct/acadhonesty/).

### Overview

It is very important in all courses that you be honest in all the work that you complete. In this course, you must complete all assignments, quizzes, exams, etc. on your own unless otherwise specified. If you do not, you are doing a disservice to yourself, the instructors for the course, the College of Information and Computer Sciences, the University of Massachusetts, and your future. We design our courses to provide you the necessary understanding and skill that will make you an excellent computer scientist. Assignments and exams are designed to test your knowledge and understanding of the material. Plagiarism and academic honesty of any sort may seem like an easy way to solve an immediate problem (which it is not), however, it can have a substantial negative impact on your career as a computer science student. There are many computing jobs out there and many more people working hard to get those positions. If you do not know your stuff you will have a very difficult time finding a job. Please take this seriously.

We will carefully review your submissions automatically and manually to verify that “cheating” has not taken place. If you are suspected of plagiarism we will follow an informal path to determine if academic dishonesty has taken place. If you are found guilty you will receive an F for the course and it will go on your permanent record at UMass. This will disrupt your schedule for completing courses and may lead to you not completing your degree in a timely fashion. You should carefully review the Academic Honesty Policy, Avoiding Plagiarism, and the Academic Honesty Flowchart to understand what academic honesty is, how you can avoid it, and the procedure we will follow if you are under suspicion. In general, you should review all documentation described by UMass’ Academic Honesty Policy and Procedures.

### Specifics for this course:

- Unless otherwise specified, assignments in this course are individual, not group, and direct collaboration is inappropriate. Any group work we will clearly mark as such.
- While we support learning from your peers, the rule of thumb is that any learning will be in your head. Therefore, you should not leave an encounter (in person or electronic) with anything written down (or electronically recorded) that you did not have before. Thus, giving or receiving electronic files is specifically considered cheating.
- Use of materials from previous offerings of this course, no matter the source and even if you are retaking the course, is prohibited.
- We will employ various means, electronic and otherwise, to check for compliance with these course policies. We will pursue sanctions vigorously and the usual sanction we will pursue is an F in the course.
