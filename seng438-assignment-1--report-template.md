>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       |19 |
|-----------------|---|
| Student Names:  |   |
| Ryan Sommerville|   |
| Renno Eric      |   |
| Kaumil Patel    |   |
| Quinn Ledingham |   |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction


This lab was designed to explore how to test a software application made by someone else
through using the software and testing it's functions to find any faults in the system.

It also explores a few different methods of testing, including exploratory testing where
the tester just plays around with the program in order to try to find faults with the system,
manual testing where the tester conducts a set of well-documented tests, and regression testing
when testing a newer version of the system. Throughout the lab, the pros and cons of each of
these testing methods are explored. 

I had not even heard of exploratory or manual testing
before the lab, but throughout the assignment I came to know and understand them through
practical application, and understand what they were good and bad at.

# High-level description of the exploratory testing plan

Exploratory testing is testing done without pre documented tests or plan. While it
is usually not very thorough due to lack of organization, the adaptability it offers
to the tester allows testers to find faults in a program much quicker than other options
and explore the program, potentially finding faults that wouldn't have been found otherwise.

The exploratory testing that we performed on the ATM program had two main goals. First, to
confirm that the program met all requirements of the system that users require. To do this,
the tester will act as a user for the software and perform actions that normal users would.
The second goal is to check that the boundary cases work properly to restrict what the user
can do. To check this, the tester will also try to test these boundary cases through entering
values and performing actions that should not be allowed, such as entering 0 or a number that
is greater than should be allowed, and seeing if the system responds properly. This process
of trying various functions that should or should not be allowed will continue until the
tester is confident they have found most or all of the faults in the system.

# Comparison of exploratory and manual functional testing

Exploratory and Manual testing are very different, almost completely opposite in concept.
Manual testing is based off of well documented and thoroughly planned tests, intending to
check all of the necessary functionalities of the system. On the other hand, Exploratory
testing is completely free and flexible, without any prior documentation or a rigid structure
to follow. By allowing the tester to be flexible and try things out, it allows them to be 
adaptable and seek out flaws as they are using the system.

There are many pros and cons to either type of testing. Exploratory testing is much more
flexible than Manual, which allows the tester to play around and find faults they might
not have otherwise. Furthermore, the tests are decided in the moment, as the tester is
using the program, which allows them to have a perspective and come up with tests that
might not have come up in Manual testing since that is done from an objective, overall
view of the program rather than close up. On the other hand, because Exploratory testing
is done in the moment, there is a possibility for the tester to miss something that they
thought they had tested, or forgotten to test. This makes the testing far less thorough,
and as a result it is hard for the tester to be sure that they have found all of the bugs
in a system.

Manual testing provides a much more organized and thorough way of testing. By documenting
all of your tests first, attempting to cover all requirements and possible bugs of the program,
the actual testing is much more structured and is less likely to miss some factors due to the
testers forgetfulness or failure to see the whole picture and ignore certain functions. However,
it also has a flaw in that it is difficult to imagine that someone would be able to predict all
possible flaws from an objective view of the program, likely leaving some flaws undiscovered that
can only be discovered by playing around with the program.

In conclusion, both Manual and Exploratory testing have their own pros and cons, and are more
likely to find some flaws. The best testing method may therefore to perform best methods, as
the two methods can be used to cover up the flaws of each other and be more reliable in catching
any bugs in the system.

-   Note that you need to submit a report generated by your defect tracking
    system, containing all defects recorded in the system.

# Notes and discussion of the peer reviews of defect reports

Having peers review the defect reports helped to make it clear if the defect report could be understood
without having to see the bug in action. It also showed if the steps in the defect report could be followed
to recreate the bug. It seems possible to make a defect report that really only makes sense to yourself so
having someone else look at it makes sure that this is not a problem.

# How the pair testing was managed and team work/effort was divided 

For the pair testing the first pair was Kaumil and Ryan, the second pair was Quinn and Renno. Both pairs did
exploratory testing with one person looking for bugs and the other person recording them. The manual scripted
testing and the regression testing had someone doing to tests and others recording any defects that were found
during those tests. The lab report was written with collaboration from everyone.

# Difficulties encountered, challenges overcome, and lessons learned

This assignment introduced many unique challenges for our group. A large amount of these problems are 
related to the following main categories: teamwork, test design, defect reports, and test implementations. 
In regards to teamwork, with four group members with different time schedules we found it somewhat difficult 
to divide the work load between our team members. In addition to this, we were also challenged with dividing the 
work with our other group members efficiently. To deal with the issue of conflicting time schedules we maintained 
high level of communication using Discord. This made it easier for our group to plan meetings in advance. For the problem 
with dividing the work load between the other group members, we spent a sufficient amount of time to discuss our 
approach to the different requirements in the assignment, giving each member a chances to voice their opinions. In relation 
to the test design portion of the assignment, one of the difficulties we were challenged with was abstracting the high level 
requirements needed to complete our exploratory testing. To deal with this issue, we each tried to find and discuss potential
high level requirements needed for testing. We laid our ideas in a shared word document, which helped to speed up the process 
of peer reviews and to synchronise our work load. Writing defect reports is a relatively new skill that we have learnt in this 
course. This made it more difficult for us to understand the process of Writing a proper bug report. To deal with this issue 
our group spent some time to discuss the requirements of reporting defects in the program. We also gave other members constructive 
feedback making it easier to ensure the quality of defect reports as a whole. The final large issue we were dealt in this assignment 
was our test implementations. With many different states of the program and a large variety of potential function inputs, we were 
challenged with finding an effective way of performing our tests. To deal with these issues we tried to create tests that would 
encompass many of the high level requirements we defined in order to increase our chances of finding defects in the program. To deal with 
functions that could take a large number of inputs, we made an effort to handle the base cases for the different functions in the program 
in order to handle the more error prone parts of the program.



# Comments/feedback on the lab and lab document itself

During this assignment, we were faced with many problems ranging from implementing newly learnt testing techniques over to dividing 
the work load between between teammates. The application of these testing techniques was found to be very useful for increasing our skills
in developing test cases and test assessments. The assignment outline was very thorough in stating its requirements and also contained 
all the crucial information needed to complete the assignment. In addition, the group-work specifications laid out in the assignment 
made it easier for the work to be split up between all the group members. One word of criticism towards the assignment from one of our group members 
was that all though the assignment outline contained a lot of useful information, it was somewhat difficult to navigate to different points 
in the assignment using the numbered points. For example, when reviewing the assignment outline, point number 5 of the regression testing 
states "Execute steps 4 and 5 (Manual Scripted Testing)" with no number being associated to point number four. In conclusion, all though the 
assignment handout was a little difficult to follow, assignment one was beneficial in increasing our understanding of the course. 
