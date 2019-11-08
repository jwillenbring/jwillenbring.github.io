## CS 330 - Software Engineering
College of St. Benedict / St. John's University, Fall 2019 

### Course Information:

  * Instructor: Jim Willenbring
  * Time: 10:40 am to 11:35 am MWF
  * Location: Main 154, St. Ben’s.

### Contact Info:

  * X5536 (CSB Office)
  * jwillenbr001 (SJU email username)
  * 505-238-8744 (Mobile Phone)

### Office Hours:

  * Monday & Friday 11:30 am-12:00 pm
  * Wednesday 12:00–12:55 pm
  * By appointment
  * Usually when I am in my office with the door open

### Class Resources:

  * [Syllabus](https://docs.google.com/document/d/1aHQAjYF2F9A7HYHoO2fWsvXyY8fD9ANGAgoNhgfA7YM/edit?usp=sharing)
  * [Pro Git book](https://progit2.s3.amazonaws.com/en/2016-03-22-f3531/progit-en.1084.pdf)
  * [Scrum Body of Knowledge book](http://www.scrumstudy.com/SBOKGuide/download-free-buy-SBOK)
  * [Example Product Pitch](https://docs.google.com/presentation/d/1cK4iz2XqTZsL9Bin_4V94KVZ3z6o3KoE4XzHwCBgo-U/edit?usp=sharing)
  * How to sync your GitHub Fork
    * [1. Configure a remote (1 time)](https://help.github.com/en/articles/configuring-a-remote-for-a-fork)
    * [2. Sync your fork (every time you want to update your fork's master)](https://help.github.com/en/articles/syncing-a-fork)
    * Note: You can also add classmate's forks as remotes for collaborative efforts as well as sync branches other than master.
  * How to create and use a new feature branch (make sure your master branch on your fork is up-to-date)
    * From your fork on GitHub, create a new branch based on the master branch
      * From your fork's GitHub homepage, click on "Branch: master", type your new \<branch_name\> in the text field and hit enter
    * From the command line, checkout your new branch
      * git checkout --track origin/\<branch_name\>
    * Develop locally on this branch.
    * Push your changes when done, and issue a pull request back to the master branch of the main repository (not your fork)

  
### Class Links:

  * [Class GitHub Organization](https://github.com/CSBSJU-CS330-F19)
  * [Agile Manifesto](http://agilemanifesto.org/)
  * [Principles Behind the Agile Manifesto](http://agilemanifesto.org/principles.html)
  * [Agile Basics and Comments on Principles from 8/30 - see through slide 6](https://press3.mcs.anl.gov/atpesc/files/2019/08/ATPESC_2019_Track-7_5_8-8_130pm_Willenbring-Agile_and_GitHub.pdf)
 * [Mountain Goat Scrum overview from 8/30 and 9/2](https://www.mountaingoatsoftware.com/uploads/presentations/English-Redistributable-Intro-Scrum.ppt)
  * [Requirements Elicitation from 9/9](https://www.slideshare.net/vivacemente/requirement-elicitation)
  * [Requirements Analysis, Specification, Validation from 9/11](http://csis.pace.edu/~marchese/CS775/Lectures/775L4.ppt)
  * [CollabNet Backlog Refinement Meeting video - 9/20](https://www.youtube.com/watch?v=b_WeHcZcx1w)
  * Design patterns
    * [Overview presentation](https://www.slideshare.net/abhisheksagi/design-patterns-10468437)
    * [Singleton](https://www.geeksforgeeks.org/singleton-design-pattern/)
    * [Facade](https://medium.com/@andreaspoyias/design-patterns-a-quick-guide-to-facade-pattern-16e3d2f1bfb6)
    * [Iterator](https://www.tutorialspoint.com/design_pattern/iterator_pattern.htm)
  * [CollabNet Sprint Review Meeting video](https://www.youtube.com/watch?v=cbJinz6TieI)
  * [CollabNet Sprint Retrospective Meeting video](https://www.youtube.com/watch?v=rZ8I0ATrauM)

<!---

* [Mountain Goat Introduction to User Stories from 1/23](https://www.mountaingoatsoftware.com/presentations/introduction-to-user-stories)
  * [XP123 article on good stories and smart tasks from 1/23](https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/)
  * [PDCA Process Checklist presentation](https://drive.google.com/open?id=1hiaJ49tem0HYaEm4ggLuAwkxgYQnEDLs)
  * [Anti-Patterns](https://www.slideshare.net/ExigenServices/antipatterns-part-1)
  * [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html)
  * [Relaxed Intensity for High-Performing Teams](https://www.inc.com/scott-mautz/want-a-high-performing-team-create-an-atmosphere-of-relaxed-intensity-heres-how.html)

--->

### Assignments:

<!---

* [Final Presentation - on 5/1](https://docs.google.com/document/d/19UUXf-ah293z68AOSYpc6_Bxl-72Ba8rkS38EyfD1gQ/edit?usp=sharing)
  * [Assignment 9 - Due 5/7](https://docs.google.com/document/d/1q2FYjLXzxHgV9Bq8NwifvI56RbAO2IE3G27v5exdnok/edit?usp=sharing)
  * [Assignment 8 - Due 5/1](https://docs.google.com/document/d/1qHdd0PPpDpN5nLxG5FzZP8Dv4lDcvks4wpOseyQ6u-Q/edit?usp=sharing)
  * [Assignment 7 - Due 4/5](https://docs.google.com/document/d/1JKsRgKEA5P42Ib-syufIuizq7U1vVNP5C6XizI3FluM/edit?usp=sharing)
  * [Assignment 6 - (Team effort, Due end of Sprint 3)](https://docs.google.com/document/d/1j4xuLKDnGQbRJQoeYHsuNeN1qwu8wkzimHFN2kbuT2k/edit?usp=sharing)
  * [Assignment 5 - Due 3/15](https://docs.google.com/document/d/1IB8wwsvNxnzVtpl4GH7OYbsORGqDNDZ7JxtnJGklxSg/edit?usp=sharing)
  * [Prior to 2/15](https://docs.google.com/document/d/1aUt_qCkUm85SAW-Mv0euDdT4HVJ0DVzJGabyEOisnsU/edit?usp=sharing)
  * [Week of 2/6, part 1 (team effort)](https://docs.google.com/document/d/1tBvBdat4ed733REYO-G7vf9TCRedSBalI1-yD2-Ql9Y/edit?usp=sharing)
  * [Assignment 4](https://docs.google.com/document/d/1yVoDU3Cr5I6UdifJUDVFdZQk2ccgquESmWWw76RE7Gs/edit?usp=sharing)
  * [Assignment 3](https://docs.google.com/document/d/1H5yB4RRquzRVuXMq6Uv0JUHTwefB0l9FCqGbqpV3xIA/edit?usp=sharing)
  * [Assignment 2](https://docs.google.com/document/d/1Ycs53TRkT9QI_DIns3zQpjRV1QyF8MLNa-nli_E3AG4/edit?usp=sharing)
  * [Assignment 1](https://docs.google.com/document/d/1A3nLetRegs6evCSDBRJzgz8DtqXDmCwNA4Lo3mNs8Ok/edit?usp=sharing)

--->

  * [Assignment 1, Due 8/30](https://docs.google.com/document/d/16bApEEE3z-OekdzmFvMxDyEfOEdoJCP55Lu1BaizH3Q/edit?usp=sharing)
  * [Assignment 2, Due 9/13 (note change)](https://docs.google.com/document/d/19_srRYyAVWS7BezA376_74CRRzoeMXxQ-jHVSUJA-xM/edit?usp=sharing)
  * [Assignment 4, Due 10/25](https://docs.google.com/document/d/1cGbXBpPqqIosuqfzvd5mMZRAs9hMXuvzE8gHD_hplbU/edit?usp=sharing)
  * [Assignment 5, Due 11-15](https://docs.google.com/document/d/1xppkmeF8kHQATXsK8jDZISii9TGjnjJSE6rWIRwhqkA/edit?usp=sharing)

### Assigned Reading/Viewing:

  (The reading/video assignment should be completed prior to the date listed.)

<!---
* [CollabNet Sprint Planning Meeting video - 3/15](https://www.youtube.com/watch?v=wPvG9NZNUa4)
  * [CollabNet Backlog Refinement Meeting video - 3/13](https://www.youtube.com/watch?v=b_WeHcZcx1w)
  * [Splitting a Story into Tasks - 2/20](http://agilebutpragmatic.blogspot.com/2012/04/splitting-story-into-tasks-how-to-write.html)
  * [Agile Alliance Definition of Done - 2/8](https://www.agilealliance.org/definition-done-user-stories/)
  * [SEGUE Agile Acceptance Criteria - 1/30](https://www.seguetech.com/what-characteristics-make-good-agile-acceptance-criteria/)
  * [Leading Agile Acceptance Criteria - 1/30](https://www.leadingagile.com/2014/09/acceptance-criteria/)
  * [Agile for Growth Acceptance Criteria Tips and Examples - 1/30](http://agileforgrowth.com/blog/acceptance-criteria-checklist/)
  * [Existek Acceptance Criteria Tips and Examples 1/30](https://existek.com/blog/what-are-acceptance-criteria/)

--->

  * [Mountain Goat User Story overview - 8/30](https://www.mountaingoatsoftware.com/agile/user-stories)
  * [Mountain Goat User Stories for Requirements - 8/30](https://www.mountaingoatsoftware.com/articles/advantages-of-user-stories-for-requirements)
  * [INVEST in User Stories and SMART Tasks - 9/9](https://agilecircle.wordpress.com/2016/05/17/invest-in-user-stories-and-smart-tasks/)
  * [Existek Acceptance Criteria Tips and Examples 9/23](https://existek.com/blog/what-are-acceptance-criteria/)
  * [Mountain Goat Non-functional Requirements as User Stories 9/23](https://www.mountaingoatsoftware.com/blog/non-functional-requirements-as-user-stories)

