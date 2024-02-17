[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/SqkZA8g-)
# CECS 326 Reading Assignment: Introduction to Operating Systems

### Assignment Description
Answer the following questions from the Chapter 1 reading from your text- book. Be through and complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. What are the two main functions of an operating system?

    The two main functions is offering a clean interface to work on and managing hardware reasources.

2. What is the difference between timesharing and multiprogramming systems?
    
    In a timesharing system there can be multiple people can use a computing system on their own device. Multiprogramming means a system that can run mutlipleprograms at the same time. Timesharing falls under multiprogramming.
3. The family-of-computers idea was introduced in the 1960s with the IBM System/360 mainframes. Is this idea now dead as a doornail or does it live on?

    This idea still lives on. Though at home and for personal use we might not need this there are still companies that use these ideas to be able to hold massive databases. Still using batch computing. 

4. What is the difference between kernel and user mode? Explain how having two distinct modes aids in designing an operating system.
    
    Most of the time we are in user mode. Allowed to only be able to run things that are not critical. Kernel mode has full access to the CPU. When looking at it in a tree User mode is a small child of Kernel mode. This is useful to have in an operating system to stop the user from messing up critical data.

5. On early computers, every byte of data read or written was handled by the CPU (i.e., there was no DMA). What implications does this have for multiprogramming?
    
    This would essentially make multiprogramming useless since without DMA there is no way for a CPU to run more than one thing at a time since it will always be used at %100 for one thing.

6. There are several design goals in building an operating system, for example, resource utilization, timeliness, robustness, and so on. Give an example of two design goals that may contradict one another.
    
    Two design goals that can contridict eachother is timelisness and protections. For example the smart card operating system having the OS being old we can find issues in protection though these woudld be considered timeless.
7. Which of the following instructions should be allowed only in kernel mode?
    (a) Disable all interrupts.
    (b) Read the time-of-day clock.
    (c) Set the time-of-day clock. 
    (d) Change the memory map.
    
    Here the choices that will only be allowed in Kernel mode are the ones where major alterations are made to the system, a, c, and d.
8. Consider a system that has two CPUs, each CPU having two threads (hyperthreading). Suppose three programs, P0, P1, and P2, are started with run times of 5, 10 and 20 msec, respectively. How long will it take to complete the execution of these programs? Assume that all three programs are 100% CPU bound, do not block during execution, and do not change CPUs once assigned.

9. What is a trap instruction? Explain its use in operating systems.

10. Modern operating systems decouple a process address space from the machine’s physical memory. List two advantages of this design.

### Deliverables
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: .txt, .md, .pdf. .html (renderable) or anything that is web-readable on Github. Other formats will only be accepted with explicit approval.
