# GIT & CLI: Assignment

## Brief 

This is a research assignment where students will be given time for research and put into group for discussion.

Version control tools are plenty and have wide range of practices. This research assignment aims to help learners expand their choice of version control tools (Part 1) and being acquainted with the branching strategies best practices in the industry (Part 2).

| Time    | Item          |
|---------|---------------|
| 40 mins | Self readings |
| 10 mins | Q&A           |
| 10 mins | Break         |
| 30 mins | Discussion    |
| 30 mins | Presentation  |

### Part 1

Problem Statement: GIT is not the only version control tool in the industry. 

[Reference Link](https://www.softwaretestinghelp.com/version-control-software/) or search online with key word "Version Control Tool".

Discussion Points:

1. What are the version control tools used in the industry?

1. Why are they being used?


### Part 2

Problem Statement: Branching strategy varies largely across companies’ practices and there are not fixed way of doing this.

Reference Links:
- https://launchdarkly.com/blog/git-branching-strategies-vs-trunk-based-development/
- https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy 
- https://www.creativebloq.com/web-design/choose-right-git-branching-strategy-121518344

Discussion Points:

1. How many branching strategies are there? What are they?
1. Which branching strategy looks the most practical for you personally?
1. Consider the following scenarios, recommend a branching strategy suitable for the scenario, and explain why?
    a. Startup with less than 5 developers
    b. Startup with multiple small team of developers (3 teams of 3 developers)
    c. Startup with no specific team make up. It’s just a group of 8 developers.
    d. SME with multiple small team of developers (4 teams of 3 developers)
    e. MNC & Banking with multiple large team of developers (10 teams of 12 developers)


## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
- Submit your assignment to black board.
====================================================================================================================
====================================================================================================================

### Part 1

Assignment answer:

Skills Union Project Group 1 Group 1 Members

•	CP
•	Maniraja
•	Keith
•	Leslie
•	Charles
•	Liew


Ref: 

https://docs.google.com/presentation/d/1I1fyFkicvfwVYgA6kXQCbAJEmT_RfdgE3En_oZ8s8Ls/edit#slide=id.g1096b5c8c1b_3_45


Discussion Points:

1. What are the version control tools used in the industry?

Git
CVS
SVN
Mercurial
Monotone
Bazaar
TFS
VSTS
Perforce Helix Core 
IBM Rational ClearCase
Revision Control System 
Visual SourceSafe(VSS) 
CA Harvest Software Change 
Manager
PVCS 
Darcs
Bitbucket
AWS CodeCommit



2. Why are they being used?

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

Sometimes we write code or make changes to the code but later, we  realize it was a mistake and want to revert back to the last code,  Version Control will do that for you.
If you have to maintain multiple versions of a project or want to see  the difference between two (or more) versions of your code or want to  review the history of particular code, Version Control maintains it all.
Sometimes we have to submit or merge our code with the development  team member's code or want to share our code and let your team member  work on that code, you can do that using the version control.
If you want to do an experiment with a new feature or R & D without  interfering with the working code, version control gives us the  flexibility.
This will give great confidence to the development team to do  experiments with the code as we can rollback at any time to last code.
With the automated feature, Version Control helps to automate  testing, code analysis, and deployment when new versions are saved to  version control. This will save the development team's time.
Two types of version control are supported by Visual Studio Team  System, Git, and TFVC. Now as a developer we always have a question,  which version control system should I use?

Version Control Benefits:
Collaboration
Storing Versions
Restoring Previous Versions
Figure Out What Happened
Backup
Managing and Protecting the Source Code
Keeping Track of All the Modifications Made to the Code
Comparing Earlier Versions of the Code
Supports the Developers’ Workflow and Not any Rigid Way of Working

Ref: https://www.simplilearn.com/tutorials/devops-tutorial/version-control



### Part 2

1. How many branching strategies are there? What are they?


GitFlow:-

Created by Vincent Driessen, GitFlow works with two main branches – master and develop – over the lifetime of the project. It also uses three supporting branches: feature-*, hotfix-*, and release-*. It’s the most complex model.

GitHub Flow:

A simpler strategy promoted by Scott Chacon of GitHub mandates keeping a continuously deployable main branch. A feature branch is created to work on any feature or bug fix. Each feature branch must be finished and fully tested before being merged with the main branch.

Trunk-Based Development:

Very similar to GitHub Flow except that Trunk-Based Development suggests deployment after production code is merged to the main branch to minimize chances for regression.

GitLab Flow:

Created by GitLab, this strategy is like an extension of GitHub Flow with master and feature branches. However, it adds environment and release branches to better support SaaS and mobile projects.

OneFlow:

Formulated by Adam Ruka, OneFlow proposes to be a simplification of GitFlow with the use of rebase options some consider controversial.



Comparing Version Control Strategies

GitFlow: 
Enterprise
Heavy
Complex
Hard
Releases
Convoluted
Slow

GitHub Flow:
Startups
Light
Simple
Easy
Continuous
Clean
Fast

GitLab Flow:
All
Variable
Simple
Easy
Both
Clean
Fast

OneFlow:
Enterprise
Light
Medium
Easy
Releases
Variable
Fast



2. Which branching strategy looks the most practical for you personally?

How to Choose the Best Git Branching Strategy for Your Team?
Down to three – GitHub, GitLab, and OneFlow. The best version control branching strategy depends on the type of project and the size, structure, experience of your team, as noted by Mike Kaufmann.
However, when first starting out, it’s best to stay simple and keep it simple until the project reaches a point where additional complexity is needed. For this reason, the GitHub Flow (or Trunk-Based Development) is the best strategy for the early stages of most projects. It’s ideal for solo developers and small teams working on software projects requiring only a single version of a release to be maintained. In such cases, they may be able to stay with the GitHub Flow for the life of their project.



3. Consider the following scenarios, recommend a branching strategy suitable for the scenario, and explain why?

a. Startup with less than 5 developers
GitHub Flow 
Simple work  process and light
Fast Feedback and ease of merging 
Continuous delivery

b. Startup with multiple small team of developers (3 teams of 3 developers)
GitLab Flow
Basic team structure
Continuous delivery

c. Startup with no specific team make up. It’s just a group of 8 developers.
Trunk Based Development
No structural team framework
Continuous delivery
Small organizations or those with strong internal testing practices find this strategy useful because it reduces complexity and encourages the development organization to swarm on the problem.

 d. SME with multiple small team of developers (4 teams of 3 developers)
OneFlow
Better team structure
Release delivery

e. MNC & Banking with multiple large team of developers (10 teams of 12 developers)
GitFlow
More inherent (stricter) control for merging from junior developers
Release delivery
More complicated branches that possibly meet enterprise large software development requirements





