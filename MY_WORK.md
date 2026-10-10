# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [alanoud alqahtani] |
| **Student ID** | [444051735] |
| **University Email** | [444051735@std.psau.edu.sa] |
| **GitHub Username** | [alanoud444051735] |
| **Repository Link** | [ https://github.com/alanoud444051735/OS-Assignment1-alanoud-alqahtani] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1uIjfkIyDIdeqDW_q6OkiMw3wQgRayt37/view?usp=sharing]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 3, 2026, 7:00 PM]
**What I did**: Created and set up my GitHub repository.

**Details**:
- Created my repository from the assignment starter project.
- Set up the project so I could start working on the Java code.
- Prepared the repository for saving my changes using Git commits.

**Challenges**: I was not very familiar with forking a repository and using Git commits.

**Solution**:I followed the instructions step by step and watch a tutorial video on youtYouTube and learned how to make changes, commit them, and push them to GitHub.

**Time spent**: 40 minutes

---

### Entry 2 - [October 4, 2026, 7:30 PM]
**What I did**: Worked on process priority.

**Details**:
- Added a priority variable to the Process class.
- Used a random number between 1 and 10 for each process.
- Updated the output to show the priority when a process enters the ready queue.
- Kept the scheduling order unchanged because priority is only displayed.

**Challenges**: I was not sure where to add the priority variable and how to display it without changing the scheduling order.

**Solution**:I added the priority to the Process class and displayed it when the process entered the ready queue. I kept the FIFO scheduling unchanged.

**Time spent**: 70 minutes

---

### Entry 3 - [October 6, 2026, 7:30 PM]
**What I did**: Added the context switch counter.

**Details**:
- Added a static variable to count context switches.
- Increased the counter whenever the scheduler started a thread for CPU execution.
- Added a message at the end of the simulation to show the total count

**Challenges**: At first, I was confused about where to increase the counter because the same process can run more than once.

**Solution**: I reviewed the scheduler loop and added the counter before currentThread.start() so it increases whenever a thread starts running.

**Time spent**: 60 miunutes

---

### Entry 4 - [October 7, 2026, 7:30 PM]
**What I did**: Implemented waiting-time and turnaround-time tracking.

**Details**:
- Added variables to store the waiting time for each process.
- Used System.currentTimeMillis() to calculate how long each process waited in the ready queue.
- Updated the waiting time whenever a process returned to the ready queue.
- Calculated turnaround time by adding waiting time and burst time.
- Added a table at the end of the simulation to display the results for all processes.

**Challenges**: Understanding how to calculate waiting time was difficult because a process can enter the ready queue multiple times.

**Solution**: : I used System.currentTimeMillis() to record when a process entered and left the ready queue. I added the waiting periods together to calculate its total waiting time.

**Time spent**: 90 minutes

——-

### Entry 5 - [October 8–10, 2026]
**What I did**: Completed the assignment documentation and added my personal information and project links.

**Details**:
- Added my full name, student ID, and university email.
-;Added my GitHub username and repository link.
- Updated the development log with the dates and details of my work.
- Answered the reflection and technical questions.
- Added the video demonstration link.
Reviewed the documentation and assignment requirements before submission.

**Challenges**: I found it difficult to explain some technical concepts in my own words and make sure all the required information was included.

**Solution**: I reviewed the assignment instructions and Java code again. I used examples from my simulation to explain the concepts and checked the documentation to make sure I had completed the required sections.

**Time spent**: 90 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log ## Development Log Summary

> 馃挕 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [5 hours and 50 minutes]

**Most challenging part**: Calculating waiting time when a process returns to the ready queue.

**Most interesting learning**: Understanding how Java threads simulate Round-Robin scheduling.

**What I would do differently next time**: Test each change earlier and document my progress after every session.

---

# Part B: Reflection (0.5 mark)

> 馃洃 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> 鈿狅笍 **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 馃挕 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 馃挕 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 馃挕 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

I learned:How Java creates and manages threads. The Runnable interface defines the work a thread performs. Thread.start() starts a thread. Thread.join() makes the main thread wait. Thread.sleep() pauses execution temporarily. I also learned how a scheduler controls the execution order.

## Question 2: What was the most challenging part of this assignment?

> 馃挕 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The hardest part was calculating waiting time. A process can enter the ready queue several times. Each visit adds more waiting time. I needed to record these periods correctly. I also had to calculate turnaround time. This required understanding the scheduler loop.

## Question 3: How did you overcome the challenges you faced?

> 馃挕 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I read the code carefully. I focused on the scheduler loop. I divided the problem into smaller steps. I used System.currentTimeMillis() to measure waiting time. I reviewed the calculations after each change. This helped me understand the implementation.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 馃挕 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful in many applications. Browsers use threads for different tasks. Video players can download data while playing videos. Servers use threads to handle requests. Operating systems schedule tasks to share CPU time. This assignment helped me understand these applications.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 馃洃 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> 鈿狅笍 **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 馃挕 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 馃挕 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is a running program, while a thread runs inside a process. Threads share memory and are faster to create than separate processes. In this assignment, Process simulates a process, while new Thread(process) in addProcessToQueue() creates a real Java thread. We use threads because they are easier and faster to manage.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> 鈿狅笍 **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 馃挕 **TIP:** Pick a process with a large burst time (e.g., more than 2 脳 time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, unfinished processes return to the ready queue. In my output, P1 was re-queued 2 times because its burst time was 11604ms and the time quantum was 5000ms. Re-queuing ensures fairness by allowing other processes to run.

Example from my output:

➕ P1 added to ready queue │ Burst time: 11604ms
▶️ P1 executing quantum [5000ms]
Remaining time: 6604ms
↻ P1 yields CPU for context switch
➕ P1 added to ready queue │ Burst time: 11604ms

▶️ P1 executing quantum [5000ms]
Remaining time: 1604ms
↻ P1 yields CPU for context switch
➕ P1 added to ready queue │ Burst time: 11604ms

▶️ P1 executing quantum [1604ms]
✓ P1 finished execution!

**Explanation of example:**
P1 needed three CPU turns to finish. It returned to the ready queue twice, allowing other processes to execute between its turns.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 馃挕 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: new Thread(process) creates P1's thread.

2. **Runnable**: start() makes P1 ready to execute.

3. **Running**: P1 executes its run() method.

4. **Waiting**: sleep() pauses P1 temporarily, while join() makes the main thread wait.

5. **Terminated**: P1's thread ends when run() finishes.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 馃挕 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduling]

**Description**:
An OS runs multiple programs, like browsers and editors. Each program acts as a process.

**Why Round-Robin works well here**:
Each process gets a fixed time quantum. The CPU switches between processes. This ensures fairness and responsiveness.

### Example 2: [Web Server]

**Description**:
A web server handles requests from multiple users. Each request acts as a task.

**Why Round-Robin works well here**:
Each task gets limited processing time. The server switches between tasks. This prevents one request from blocking others.

## Summary

**Key concepts I understood through these questions:**
1. Threads and processes.
2. Round-Robin scheduling.
3. Context switching.

**Concepts I need to study more:**
1. Thread synchronization.
2. Other CPU scheduling algorithms.
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [✓] Repository is **PUBLIC** (Settings 鈫� Danger Zone 鈫� Visibility)
- [✓] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [✓] Student ID is set in `SchedulerSimulation.java` (line 150)
- [✓]Code compiles and runs with no errors
- [✓] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✓] Each feature has clear comments

**Commits**
- [✓] **At least 3 meaningful commits, ideally 6 or more**
- [✓] **One commit per feature**
- [✓] Commits are spread over **different dates** (not all in the last hour)
- [✓] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [✓] Full name and student ID filled in at the top
- [✓] Development log has **5+ entries** on different dates
- [✓] Reflection: 4 questions, 5-7 sentences each
- [✓] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [✓] No `[...]` placeholders left
- [✓] No section headers deleted

**Video**
- [✓] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [✓] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [✓] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [✓] Submit **only** the link to your public GitHub repository


> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
