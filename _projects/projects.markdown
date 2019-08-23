---
layout: page
permalink: /projects/
---

# Capstone Project List


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Monday (14 Jan) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BEFORE the next Capstone class on Friday (18 Jan). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Last semester, every student got into one of their top three (and a majority into their #1 choice), although I do not make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - ????

### Viz - Lightweight Open Web Analysis [3-4 students]

Most web analysis systems are proprietary and heavyweight, meaning that most of their algorithms is hidden and unable to be validated. It leads to a misunderstanding of the answers.  

This project proposes to develop a lightweight open system that does web analysis in the most straightforward and modular way.  It will not hide the implementation and make it available for understanding.  It will be able to be selected as needed and not the heavy-weight requirements. This will be used not only for proper validation, but also as a platform to make web analytics more inclusive.  It should allow for the processing of data without an integration of required hooks that forces users to be locked in simply because of the effort needed to change.  

The application should be developed to provide reusable components that can be used in many types of web analysis as well as other forms of analytics.  We will be using a form of agile software development as it has proven successful in the past for the students as well as the customer. Rather than having to install an application on our systems (which require lots of paperwork, etc.) it would be easier to just have a web-based system that we can use.  One of our first attempts was "too clever" and "too big" to be able to be used and certainly difficult to extend.  

We’ve had a Pitt project that started this and has done a great job, and this project would continue on with the project.

POC: Mike Bigrigg


## Faculty Projects

# Waiting on Babichenko


### Improving Energy Efficiency via Heterogeneous-aware Scheduling [2-3 students]

Computer systems are increasingly being used to support a wide variety of applications such as web browsers, social networks, email clients, audio and video players. Chips with heterogeneous cores have been widely adopted by hardware vendors such as Samsung and Qualcomm to balance performance and power efficiency on mobile devices. Still, the main research challenge for runtime systems is to carefully allocate execution threads to the heterogeneous cores, while meeting strict user-facing performance targets with minimal energy consumption.

This research project will propose to enhance runtime resource management decisions by leveraging existing hardware-assisted performance data. We will explore state-of-the-art machine learning algorithms for online workload characterization to guide task assignment. This work will automatically learn an optimal scheduling policy that can determine energy-efficient resource allocations in the computing platforms. It will continuously track application phases at a fine-grained level and perform application mapping decisions without requiring any application-specific manual-tuning or any modification in the deployed applications. We will conduct an experimental investigation using real development boards running mobile and cloud benchmarks and workloads.

General Areas of Interest: Operating Systems, Computer Architecture, Compilers

Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning

POC: Vinicius Petrucci

### Panos


### Mobile application for medication adherence [4-5 students]

This team will work with SCI faculty researching technology’s potential to improve medication adherence.  Over the course of the semester, the students will build a mobile application for collecting and summarizing medication information and dosing instructions.  While scope is flexible, the application should provide mechanisms for users to manually enter medication name, prescribing doctor, and medication schedule.  Dosing information should be presented in a visual interface; perhaps using different representations (e.g. list and calendar view).  The application should provide a clean user interface and user experience for identifying when medications need to be taken and the user’s actions.  Summary interfaces, for the day, week, and/or month should summarize medication adherence performance (e.g. overall number of doses taken and missed, performance by prescription, performance by day of week).  

For the right team, advanced features could be built into the application.  These include leveraging OCR libraries or online APIs for automatic recognition of medication, dose, and doctor from the medication label.  Implementation will likely require creative user interface design and interaction segmentation to capture information on a cylindrical bottle. Teams could also implement location tracking functionality into the application, leveraging existing toolkits like iBeacon and Eddystone.  These features could power location-based medication reminders.  Students could also push on functionality to allow family members or medical staff to perform lightweight interventions and encouragement (e.g. sending motivating notifications and messages).   

Students can choose programming language and development frameworks that best fit their expertise and interest. Preference would be the construction of a native Android or iOS application, as these platforms are broadly in use. Further, sponsoring faculty are experienced in these platforms and thus can be a resource for the students.

POC: Jacob T. Biehl


### ong

### Dynamic performance scaling for heterogeneous processors [2-3 students]

Processes typically have different resource needs. With the availability of hardware CPU performance counters and kernel tracking mechanisms, the use of resources can be tracked on a per process basis allowing for better scheduling decisions that save time, improve performance, or decrease energy consumption (that’s why your laptops and cellphones run for a long time--but not long enough). One resource that is of interest is main memory usage. As retrieving data from  main memory takes time (and causes many stalled cycles), energy is wasted if a highly memory-bound process is executing on a very powerful (high frequency) core. With heterogeneous cores or DVFS, these processes can be better treated to do the same computation with much less energy by running on a core that is operating at a lower frequency. The CPU frequency governors in Linux will lower the frequency of a core if the core is underutilized (if it spends enough time without a process to run), but it misses the potential benefit of lowering the frequency while a process is running.

Whether it is worth migrating a process to a less powerful core or lowering the frequency of the processor depends on several factors, such as how long the memory bound phase of a process will last. Profiling is needed to determine at what granularity (and is there a pattern?) processes phases change phases. After profiling, a model is needed to determine when it is worth taking action. Additionally, is it enough to react to process phases or can this be improved by predicting phases using the tracked performance counters and in-kernel events. If so, what counters are the best predictors for which types of phases? Can this be extended to take advantage of other types of phases that cause stalled cycles, or can cache usage be predicted to reduce contention through better placement of processes? There are many tools for tracking performance counters. This project would involve writing C and working with the linux kernel. cs1550 is required, cs1541 would be useful.

POC: Nathan Ackerman

### CS Course Grading App [2-3 students]


This program is a web application to be  used by graders to display Java code that has been submitted for assignments in cs007  cs401 cs445 etc.  Students’ java code will be displayed to a grader who will compare that code against a rubric. The grader then enters feedback and scoring for those assignments.

Part of the App has already been developed. Most of the written code simply calls upon PERL scripts written by Tim Hoffman that gather the data files and copy them into a temporary directory for examination and then capture feedback from the grader.
Completion of this application is critical because currently graders must log into the elements machines via terminal and invoke PERL scripts to grade student submissions.  This is undesirable since those running the scripts have to have AFS accounts and need full privilege on directories containing student code and grades. We want to move away from this model and replace it with a carefully limited access application that does not require AFS login.

Needed: Web programmers to complete a project written in (mostly) PHP and (a little) Javascript. You will be handling data stored in JSON format, and may need to implement a database (noSQL, mySQL, ...).  Some experience with PERL would be helpful but not a must.

POC: Tim Hoffman

### A match-making website for capstones [2-3 students]

This project entails building a match-making website for students projects, like the capstone project you're bidding on.  We need to develop 3 components:

  1. a nice interface for two different stakeholders, namely (a) project providers, such as faculty and NGOs, and (b) project seekers, such as students.  We will need to interview stakeholders and create a requirements document describing the needed elements.
  2. a database to save the information and metadata created by item 1.  We will need to figure out what type of database to use (SQL, noSQL, ...) and design the schema for the database.
  3. an algorithm for matching the two stakeholders.  We will need to define metrics and use existing (or develop new) algorithms that attempt to optimize such metrics; for example, maximize happiness of all stakeholders, minimize extra effort, maximize learning, etc.  The metrics may be multi criteria (that is, more than one metric, with weights.

The students in this project will need to:
  - create a proposal and schedule by the 3rd week
  - meet with the clients once a week to show progress,
  - demo the project 3 weeks before the end of the term, and
  - write a user manual, document the code, and create help functions for the user interface

POC: Daniel Mossé

# Bioinformatics-Focused Projects
