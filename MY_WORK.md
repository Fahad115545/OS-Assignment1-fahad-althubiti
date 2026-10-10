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
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [oct 7, 2026, 2:30 PM]
**What I did**: set my student id

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 1 ouers

---

## Your Development Log

### Entry 1 - [oct10 and 5:00]
**What I did**:implmented feture1(proceesc priority)

**Details**:add priority filed
generated random priority

**Challenges**:deciding where in ready qurur

**Solution**:added in inside constructor

**Time spent**:1 houer

---

### Entry 2 - [oct10 and 6;00]
**What I did**:implemented context switch traking mechanism (feature2)

**Details**:added static counter
Incremented it inside scheduler loop
displayed total at end

**Challenges**:choosing coorrect place queue

**Solution**:added after polling thread from queue

**Time spent**:50 minutes

---

### Entry 3 - [oct 10 and 7;30]
**What I did**:added waiting time calculation and reporting( feature 3)

**Details**:added creation time and watiting time
calculated waiting time using System.currentTimeMillis()
printed summary at end

**Challenges**:Understanding waiting time calculation

**Solution**:simplified formula based on total execution delay

**Time spent**:1houe

---

### Entry 4 - [oct10 and 9]
**What I did**:Revise answers for multithreading assignment

**Details**:

**Challenges**:

**Solution**:

**Time spent**:1houer

---

### Entry 5 - [oct10 and 10]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X 6hours]

**Most challenging part**:waiting time calculation and reporting( feature 3)

**Most interesting learning**:Revise answers for multithreading assignment

**What I would do differently next time**:plan features earlier and test each part more thoroughly

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:In this assignment, learned how to create and manage threads in Java using the Runnable interface. I learned how multiple threads can simulate concurrent execution even when they
are running on the same CPU. I also learned about thread life cycle states such as New, Runnable, Running and Terminated. One important thing I learned is how Thread.start() starts execution and Thread.join()
synchronizes. I also learned about scheduling algorithms, like Round-Robin, which give each thread an equal amount of CPU time. This assignment helped me relate the theory in the textbook to real implementation.** *(5-7 sentences)*

[Write your answer here.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:The hardest part was figuring out how the scheduler works with the queue and threads.
The process of re-adding processes to the queue after partial execution was initially unclear. Correctly implementing the waiting time feature presented another difficulty since
it necessitated an understanding of how time is tracked in actual systems. It was also challengin g to decide where to make code changes without altering the original logic. The problem became more complicated due to the interplay between threads and timing. In general, it required both conceptual knowledge** *(5-7 sentences)*

[Write your answer here.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:overcome these obstacles by closely examining the code several times and connecting it to ideas from the Operating Systems textbook. After every change, I also regularly checked the program to make sure it was accurate. I was able to concentrate on one aspect at a time by breaking the task down into smaller pieces.
In order to comprehend program behavior, I also employed debugging strategies such printing intermediate values. My comprehension was further strengthened by watching multithreading tutorials. 1 gradually gained more self-assurance in changing the code.** *(5-7 sentences)*

[Write your answer here.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:Real-world applications like web browsers, where each tab operates as an independent thread, frequently use multithreading. Additionally, servers employ it to manage several client requests at once. Threads are used in games to concurrently handle physics, graphics, and user input. Threads are used by media players to manage user controls and play music and video. I gained a better understanding of how threads increase efficiency and responsiveness thanks to this project. Additionally, it demonstrated how scheduling guaranties equitable resource distribution.** *(5-7 sentences)*

[Write your answer here.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your AnswerA thread is a smaller unit of execution within a process that shares memory, whereas a process is an independent program in execution with its own memory space. Threads are lighter and quicker to construct than processes, which are heavier and need more resources to build and manage.
Compared to processes, threads facilitate faster and easier communication because they share memory. Because threads enable effective simulation of several processes within a single program, they were used in this project. More overhead and intricate communication methods would be needed if distinct procedures were used.:** *(3-5 sentences)*

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:In Round-Robin scheduling, if a process does not finish within its time quantum, it is moved back to the ready queue to wait for another turn. This ensures that all processes get fair access to the CPU and no process monopolizes execution.** *(3-5 sentences)*

[Write your answer here.]

Example from my output:
```
P1 completed quantum 4000ms | Overall progress: 51%
Remaining time: 3837ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 7837ms | Priority:4
```

**Explanation of example:In this example, process P1 executed for its full time quantum (4000ms) but did not complete because it still had 3837ms remaining. As a result, it yielded the CPU and was placed back into the ready queue.
This behavior allows other processes (such as P2, P3, etc.) to execute before P1 gets another turn. This mechanism ensures fairness and prevents starvation in the system.**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when the thread is created using:
Thread thread - new Thread(process);
At this stage, the thread has been created but has not started execution yet.

2. **Runnable**: P1 enters the Runnable state when start) is called: currentThread.start ();
At this point, the thread is ready to run and waiting for CPU scheduling.

3. **Running**:P1 is in the Running state when the CPU executes its run() method. This is shown in the output:
P1 executing quantum [4000ms]
Quantum progress: [████████████████]100%

Here, the thread is actively using the CPU.

4. **Waiting**: P1 enters the Waiting state when Thread. sleep) is called inside the run method during execution. This simulates the execution delay of the process while it is temporarily inactive

5. **Terminated**: P1 reache
Ihe Terminated state when its execution finishes completely, as shown in the output:
P1 completed quantum 3837ms | Overall progress: 180%
Remaining time: Bms
P1 finished execution!
At this point, the thread has completed its task and will not run again.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 web server

**Description**:
A web server uses threads to handle several client requests at the same time.

**Why Round-Robin works well here**:
Round-Robin gives each request a short amount of time to run, making sure no request gets stuck waiting too long.

### Example 2: operating system task scheduling

**Description**:
An operating system schedules multiple running applications using CPU scheduling algorithms.

**Why Round-Robin works well here**:
ensures tha processes get CPU time in a fair manner. It also improves system responsiveness, especially for interactive applications.

## Summary

**Key concepts I understood through these questions:**
1.Difference between theeads and procees
2.Round-Robin scheduling behavior
3.Thread lifecycle

**Concepts I need to study more:**
1.Thread synchronization
2.Advancedschedulinh algorithms

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
