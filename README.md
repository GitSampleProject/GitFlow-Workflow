# GitFlow-Workflow
Case Study Solution for Git workflow

Branches used in this workflow:
1.master - Production Ready code is available in this branch
2.develop - Serves as integration branch for features
3.feature - New features are added by creating feature branches
4.release - QA team will verify developed features and bug fixes are done in this branch
5.hotfix - hotfixes are done in this branch.

Steps:
1.Initialised git repo and created single file "main.c" in master.
2.Created develop branch.
3.Created 2 branches feature1 and features2 from develop branch.
4.Edited main.c in both feature1 and feature2 branches and merged with develop branch.
5.release branch is created from develop branch to test added features functionality.
Note:After release branch is created no features are added to develop branch.
6.If QA team find any issues with added features they will be fixed in release branch.
Note:It is best practice to deploy release branch in staging server QA testing.
7.For this demo,I am(QA team) fixing the bug in release branch(but in real time QA team will report the bug and development team will fixing it).
8.Merged release branch with both develop and master branches.
9.In master created a mile stone with date 25th of this month and taged this as release 1.0.
10.Create a mile stone every month 25th i.e a realsed will be expected on 25 th of every month and this cycle repeats.
11.If there are any minor issues with production ready code it will be solved by creating a hotfix branch.
12.Created a hotfix branch from master and added some code and merged with both master and develop branches.
13.For the next release new feature branch will be created from develop branch as develop branch is in sync with master branch.
