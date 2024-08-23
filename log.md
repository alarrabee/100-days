# 100 Days of Code Log

### Day 0: August 19th, 2024
It sure has been a wild 6 months. Let the debugging (and excitement) begin! 🪲

<img src=https://github.com/user-attachments/assets/b02b7ea0-1eb9-4112-b201-4ce0cef47bb0 width='300' />


### Day 01: August 20th, 2024
**Today's Progress:** Created repository for portfolio. Initialized Vite for React project setup. Installed necessary dependencies including React, ReactDOM, and Vite plugins.


### Day 02: August 21st, 2024
**Today's Progress:** Started a new course called "Git for Distributed Software Development" through Verizon/edX. Chapters 1-4 of 13 chapters have been completed:
- Chapter 1: Introduction to Git
- Chapter 2: Git Installation
- Chapter 3: Git and Revision Control Systems
- Chapter 4: Using Git: An Example

Topics covered included a general overview of Git. How to install Git (with Linux - I currently have Windows and use Git Bash). Revision control systems. Basic git commands. Setting up a repository, making changes and commits.

**Thoughts:** During my coding bootcamp, I gained a basic understanding of Git as part of my coursework. I found myself utilizing Git more frequently than many of my peers, and I often helped others learn key Git operations such as pulling, pushing, creating branches, and making commits. My goal is to gain more hands-on experience using Git and the command line so I can better understand version control and how I can use it to assist in troubleshooting and optimizing my workflow.


### Day 03: August 22nd, 2024
**Today's Progress:** Continued the course "Git for Distributed Software Development" through Verizon/edX. Chapters 5-7 completed.
- Chapter 5: Git Concepts and Architecture
- Chapter 6: Managin Files and the Index
- Chapter 7: Commits

Topics covered included object stores and index. Blobs, trees, commits and tags. Tracked, untracked, and ignored file categories. Basic Git file commands. Viewing the commit history. Reverting and resetting commits. Bisecting.

**Thoughts:** The Git ability to bisect using a logarithm to the base of 2 in order to find where a bug was introduced is such an invaluable tool. One you hope you never need to use but will be waiting in the toolbox for when that day inevitably comes.

1. Start the Bisect Process
- Begin by telling Git which commit is good and which is bad
```
$ git bisect start
$ git bisect bad      # marks the current commit as bad
$ git bisect good <commit>   # marks a known good commit
```
2. Test the Middle Commit
- Git will check out a commit in the middle of the range. You'll need to test this commit to see if the issue is present.
- If the commit is good (no bug), tell Git:
```
$ git bisect good
```
- If the commit is bad (bug present), tell Git:
```
$ git bisect bad
```
3. Repeat
- Git will continue to move through the commit history, narrowing down the range of potential problematic commits. You repeat the testing and marking of each commit as either good or bad.
4. Identify the Problematic Commit
  - Eventually, Git will narrow it down to a single commit, which is the one that introduced the bug.
5. End the Bisect
- Once the problematic commit is found, end the bisect session.
```
$ git bisect reset
```
