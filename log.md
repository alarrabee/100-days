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


### Day 04: August 23rd, 2024
**Today's Progress:** Set up Portfolio page layout with CSS grids using [CSS Grid Generator](https://cssgridgenerator.io/). Created header and footer components.
![image](https://github.com/user-attachments/assets/d4aa3481-cc55-4309-90c9-7f71806a076f)


**Thoughts:** I've worked with multiple CSS frameworks like Bootstrap, Tailwind CSS, and Materialize throughout class. These frameworks are fantastic for building projects quickly, ensuring consistency, and utilizing pre-designed components, all while maintaining cross-browser compatibility. However, what we didn’t cover was CSS Grid Layout!

I recently came across CSS Grid in some web articles, and I couldn't wait to learn more about it. Unlike frameworks that require external libraries, CSS Grid is native to CSS, meaning you can use it without adding any extra dependencies. It provides a powerful grid system that allows you to design complex, custom layouts while keeping your codebase lightweight. It also helps to create responsive layouts that adapt to different screen sizes, sometimes without needing media queries AND you're no longer constrained by predefined classes and styles!


### Day 05: August 24th, 2024
**Today's Progress:**  Rearranged Portfolio CSS grids layout and added assorted images for layout and design enhancement. Images created using [Midjourney AI](https://www.midjourney.com/home)


<img src=https://github.com/user-attachments/assets/700b7e90-4fd0-41c7-ad98-4de0ae7a4ed9 width='300' />
<img src=https://github.com/user-attachments/assets/7b460dd3-94e6-47d0-a747-17f6c5993358 width='300' />
<img src=https://github.com/user-attachments/assets/2edfdb4d-1211-4412-a268-3f5e51318bca width='300' />


### Day 06: August 25th, 2024
**Today's Progress:** Continued the course "Git for Distributed Software Development" through Verizon/edX. Chapter 8 started.


### Day 07: August 26th, 2024
**Today's Progress:** Added content to the About section of my Portfolio.


### Day 08: August 27th, 2024
**Today's Progress:** Continued the course "Git for Distributed Software Development" through Verizon/edX. Chapters 8-10 completed.
- Chapter 8: Branches
- Chapter 9: Diffs
- Chapter 10: Merges

Topics covered included creating and checking out a branch, branch naming and tags, differencing files, merge commands and rebasing.


### Day 09: August 28th, 2024
**Today's Progress:** Completed the course "Git for Distributed Software Development" through Verizon/edX. Chapters 11-13 completed. Course Completed!
- Chapter 11: Managing Local and Remote Repositories
- Chapter 12: Using Patches
- Chapter 13: Advanced Git Interfaces: Gerrit

Topics covered included cloning, pulling, pushing, publishing. Patches and Emailing. Gerrit

**Thoughts:** Completed a Git for Distributed Software Development course and received my [certificate](https://courses.edx.org/certificates/2831f47b8e9c44c7a8ad21d994dbafbc)! I gained a deeper understanding of Git's inner workings and improved my confidence in navigating version control. This course has equipped me with advanced troubleshooting skills and will significantly enhance my efficiency in managing code repositories and collaborating on projects.


### Day 10: August 29th, 2024
**Today's Progress:** I spent my time today reviewing the Big O Notation. It is such an important concept and was only briefly touched on in bootcamp. I started reviewing the examples provided in Cracking the Coding Interview and really took my time to break down and work through each example. Key points I covered today include: 
- O(n) - Linear Time
- O(1) - Constant Time
- O(log n) - Logarithmic Time
- O(n log n) - Linearithmic Time

**Thoughts:** I feel confident in my ability to explain each of the listed concepts so far but will continue to work with examples and problems to be able to correctly identify the runtimes of different algorithms relative to input size.


### Day 11: September 4th, 2024
**Today's Progress:** Jumping back into it after an extended holiday break. Started HarvardX's Computer Science for Web Programming course. I enrolled for the self-paced option before I committed to bootcamp and never fully dived into it until now. I will not complete it in time but will get what I can out of it.

Computer science provides the foundational knowledge necessary for coding by teaching core concepts such as algorithms, data structures, and computational thinking. I would like to understand these principles to give myself a stronger foundation for writing more efficient and effective code as well as understand how different components of software interact.
Key points I covered today include: 
- Unary and Binary
- Bits and Bytes
- ASCII and Unicode
- Algorithms *(hello again big-O)*
- Pseudocode and Scratch

Despite earning a degree in Chemistry, I've found coding to be a fascinating and enjoyable extension of my skills, pushing me to explore new ways of problem-solving and critical thinking. It’s been a fun way to apply my analytical mindset in a different field!

In addition, I wanted to get more involved with the community. A [DEV Challenge](https://dev.to/challenges/frontend-2024-09-04) dropped today and I wanted to participate.

DEV Challenges are like mini hackathons that are divided into different domains, such as "The Frontend Challenge" or "The AI Challenge," allowing participants to gain experience with new tools or showcase their skills publicly. Each challenge lasts about two weeks and may restart based on community interest, sometimes with new prompts. Challenges are designed to be small, approachable, and showcase creativity.

If I submit it great, if I don't it will still be a good learning experience. 

**Thoughts:** I admittedly froze up when starting the challenge. I didn't know what the best way to start was. Do I use React? Plain HTML, CSS, JavaScript? Something else? What am I missing. Should it be more? Am I overthinking it?...and this was just on the tech stack. I reminded myself that it didn't matter. Just get your fingers on the keyboard. You can change it later. Start simple. MVP and all that. So HTML, CSS and JS it is.

Great! Done...and now...cool - my mind is suddenly a desert and it doesn't even have sand blowing around. It's hot and I can't think.

Ok just start with a wireframe. Things just kind of piece themselves together right. I've been really into tarot cards lately. Some of the artwork is so incredibly beautiful. I was already thinking of building a super simple tarot card generator. Just something easy. Flip a card get a card. Since that was already sitting around let's use it. 

Using AI I generated a couple of space themed tarot cards to use and placed them on the page. Things just grew from there. All the HTML has been provided, I just need to style it and make it reactive. It doesn't have to be 'good', it just has to exist. 

Below is a very tentative idea. We'll see where it goes once I start building. https://github.com/alarrabee/space-edition

![image](https://github.com/user-attachments/assets/88b6f77d-4743-4311-ba68-2e6568eadb70)


### Day 12: September 5th, 2024
**Today's Progress:** I read some advice and got some tips for my portfolio and with that I mapped out a wireframe.  
