# Homework 0

**Due date for registering your GitHub account**: Friday, 12 February
  at 11:59 PM SAST

**Due date for submission**: Monday, 15 February at 11:59 PM SAST

The purpose of this assignment is for you to learn the tools that you
will be using when working on and submitting COMS4037 assignments.

## Instructions

1. If you don't have a GitHub account, create one.

2. Register your GitHub username with this course by filling out [this
form](http://goo.gl/forms/TyzIBhX0tK).  This has to be done by Friday,
12 February -- **you will not be able to submit any assignments,
including this one, if this is not done**.

3. On your local machine, create a repository whose name is your
student number. Create a file `done.txt` in a subdirectory 'hw0' of
that repository and commit it.

4. Once notified that your repository for this course has been
created, push your local repository to your GitHub repository for this
course. 

5. You have submitted your assignment by having completed the previous
step.

# `git` and GitHub

To be able effectively work on your assignments and submit them, you
need to learn to use both `git` and GitHub.

`git` is a version control tool that helps you to keep track of
different versions of your files, synchronize them across different
machines, and collaborate with others while working on
them. [GitHub](https://github.com) is a hosting service for git
repositories with a convenient web interface.

It is worth your while investing your time in effort in using git and
GitHub effectively. A good place to start learning about them is
[this](http://git-scm.com/book/en/v1/Getting-Started) book. Additional
resources are suggested at the course's web-page.  GitHub's help page
also contains numerous links to resources for learning about both
`git` and GitHub.

## Creating and registering your GitHub account

If you don't yet have a GitHub account, create one by following the instructions [here](https://help.github.com/articles/set-up-git/).

Once you have an account, register it with this course by filling out
[this form](http://goo.gl/forms/TyzIBhX0tK).  After you've registered
your account, you will receive an email message with a link to your
personal GitHub repository for this course; this email will be sent to
the email address associated with your GitHub account.

# Submitting assignments in COMS4037

All assignments will be submitted by pushing the relevant commit to
your to a branch in your private repository.

For the duration of the course, you will have access to two
repositories in the `WITS-4037` GitHub organization:

1. [A homework repository](https://github.com/berkeley-cs186/course)
containing public information about the homework assignments. You only
have the read access to this repository.  All the assignments and
updates will be posted here. You should regularly check the course's
web-site and Wit-e for announcements related to homework assignments.

2. A personal repository whose name will coincide with your student
number.  This repository is private to you -- only you and the course
staff can read from this repository: you should keep the contents of
this repository private and secure.  You will be using this repository
to submit your assignments.

Each assignment will reside in a separate top-level directory. Each
assignment has a `README` containing instructions as well as the files
you are going to need to complete the assignment.

At the start of the course, your personal repository will be empty,
except for the `README.md` file at its root.

# Suggested workflow

In this section, we are going to suggest a workflow for completing
your assignments; if you find an alternative workflow more convenient,
you are welcome to use it.

We suggest that you create a repository on your local machine and link
it up with both of your remote repositories for this course; you might
want to tag the public repository containing the assignments as
"course" and your private repository as "origin". Assuming you have
adopted this naming convention, before starting work on your
assignment, you will pull (or fetch and merge) from "course" into your
local repository, and once you've completed your work, you will push
your work to "origin". To make pulling from "course" easier, you might
want to set up a branch in your local repository that tracks
"course/master". 

The details of how this is done are left to you as your first
assignment. Your are welcome to seek help on this both from your
fellow students and from the course staff. A brief presentation on
using `git` and GitHub will be given at the first tutorial.

** This assignment has been adapted from an assignment for UC Berkeley
   CS186 course with their gracious permission **

