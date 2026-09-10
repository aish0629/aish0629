<h1 align="center">Hi, I'm Aishwarya </h1>

<p align="center">
  <b>Software Engineer • Systems Programming Enthusiast • Builder of Weird Little Utilities</b>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1800&color=C2FFC7&center=true&vCenter=true&random=false&width=900&lines=I+like+knowing+what+happens+under+the+hood.;From+fork()+to+exec()+to+epoll();Reading+The+Linux+Programming+Interface.;Turning+books+into+small+working+utilities.;If+it+works%2C+I+still+want+to+know+why." alt="Typing SVG"/>
</p>

---

<details open>
<summary><b> About Me</b></summary>

<br>

I'm a software engineer who enjoys going **one layer deeper**.

I work primarily with **C#, .NET, Angular and SQL**, but lately I've been deliberately moving closer to the machine — learning Linux internals, system calls, processes, filesystems, IPC, signals, I/O and networking.

### 📚 Currently Learning

* 📗 **The Design of the UNIX Operating System — Maurice J. Bach (MJB)**
* 📘 **The Linux Programming Interface — Michael Kerrisk (TLPI)**
* 🐧 Linux system programming
* ⚙️ Processes, threads, signals & IPC
* 📂 Filesystems, file descriptors & directory operations
* 🔌 System calls & low-level I/O
* 🌐 Networking & sockets
* 🧵 Concurrency and synchronization

But I don't want to just *read* about these things.

> **The goal is to turn every interesting chapter into something I can compile, run, break, debug and understand.**

</details>

---

<details open>
<summary><b>⚙️ What I'm Building</b></summary>

<br>

### 🐧 Linux Utilities — Inspired by TLPI

I'm currently building a collection of **small Linux/system utilities while working through TLPI**.

The idea is simple:

**Read → Understand → Implement → Break → Debug → Understand better**

Current / planned utilities include:

* 📂 **Directory Watcher**

  * Monitor filesystem/directory activity
  * Detect file creation, deletion and modification
  * Explore Linux filesystem notification mechanisms
  * Understand what happens beneath higher-level file watchers

* 🔍 File inspection utilities

* 📄 File descriptor experiments

* ⚡ Process utilities

* 🔀 `fork()` / `exec()` experiments

* 📡 Signal-handling utilities

* 🧵 Threading & synchronization experiments

* 🔌 IPC utilities

* 🌐 Socket-based utilities

* ⏱️ Timer/event-driven utilities

* 🐚 Small Unix-style command-line tools

This isn't meant to become another huge framework.

**The point is to understand the operating system by writing against it.**

</details>

---

<details open>
<summary><b>🔬 My Current Rabbit Hole</b></summary>

<br>

```text
                 APPLICATION
                      │
                      ▼
              ┌───────────────┐
              │    .NET / C#  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │   Linux APIs  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ System Calls  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │    Kernel     │
              └───────┬───────┘
                      │
                      ▼
                  HARDWARE
```

I enjoy figuring out what happens in that space between:

**"I called a function"**

and

**"the operating system actually did something."**

</details>

---

<details open>
<summary><b>🧰 Languages & Technologies</b></summary>

<br>

<h3 align="center">💻 Languages</h3>

<p align="center">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" height="40" alt="C"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="40" height="40" alt="C#"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" width="40" height="40" alt="Go"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript"/>
</p>

<p align="center">
    <b>C • C# • Go • SQL • TypeScript • JavaScript</b>
</p>

<h3 align="center">🧩 Backend & Frameworks</h3>

<p align="center">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dotnetcore/dotnetcore-original.svg" width="40" height="40" alt=".NET"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" width="40" height="40" alt="Angular"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js"/>
</p>

<p align="center">
    <b>.NET • ASP.NET • Angular • Node.js</b>
</p>

<h3 align="center">🐧 Systems & Tools</h3>

<p align="center">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40" alt="Linux"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="40" height="40" alt="GitHub"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" width="40" height="40" alt="GitHub Actions"/>
</p>

<p align="center">
    <b>Linux • POSIX APIs • System Calls • Git • GitHub Actions</b>
</p>

</details>

---

<details open>
<summary><b>📚 Books That Are Shaping How I Code</b></summary>

<br>

### 📗 The Design of the UNIX Operating System — Maurice J. Bach

I've worked through **Maurice J. Bach's *The Design of the UNIX Operating System*** to build a stronger understanding of UNIX kernel architecture and operating-system fundamentals.

```text
                 UNIX
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
    Processes   Memory     Filesystem
        │         │         │
        └─────────┼─────────┘
                  ▼
             UNIX Kernel
```

### 📘 The Linux Programming Interface — Michael Kerrisk

I'm currently reading **TLPI** and implementing concepts instead of treating the book as something to simply finish.

Topics I'm exploring include:

```text
File I/O
   ↓
File Descriptors
   ↓
Processes
   ↓
fork() / exec()
   ↓
Signals
   ↓
Threads
   ↓
IPC
   ↓
Sockets
   ↓
I/O Multiplexing
   ↓
Event-driven Systems
```

### 🧠 The Bigger Picture

```text
             BACH
              │
              ▼
     Understand UNIX design
              │
              ▼
            TLPI
              │
              ▼
   Understand Linux interfaces
              │
              ▼
           BUILD
              │
              ▼
     Small system utilities
              │
              ▼
       Understand by doing
```

> Don't just learn the API.
> **Understand the abstraction underneath it.**

</details>

---

<details open>
<summary><b>🛠️ Current Project — Directory Watcher</b></summary>

<br>

One of my current projects is a **small Linux directory/file monitoring utility**, built while studying TLPI.

Instead of using a high-level framework and stopping there, I'm using the project to understand what actually happens when a filesystem changes.

```text
Directory
    │
    ├── File created
    ├── File deleted
    ├── File modified
    └── File moved
             │
             ▼
       Linux notification
             │
             ▼
       File descriptor
             │
             ▼
          read()
             │
             ▼
       Parse the event
             │
             ▼
       Notify the user
```

The utility is intentionally small.

**The learning isn't.**

</details>

---

<details open>
<summary><b>🎯 Things I Like Exploring</b></summary>

<br>

```text
Operating Systems
        │
        ├── Processes
        ├── Threads
        ├── Scheduling
        ├── Memory
        ├── Filesystems
        └── System Calls

Linux
        │
        ├── File Descriptors
        ├── Signals
        ├── IPC
        ├── Pipes
        ├── Sockets
        └── epoll / event-driven I/O

Programming
        │
        ├── Concurrency
        ├── Distributed Systems
        ├── Networking
        ├── Performance
        └── Debugging
```

</details>

---

<details open>
<summary><b>🚀 Philosophy</b></summary>

<br>

I don't want to be the developer who only knows:

```text
"How do I use this API?"
```

I want to be able to ask:

```text
"What is this API actually doing?"

"Which system call is underneath?"

"Who owns this resource?"

"What happens when it fails?"

"What happens when two things happen simultaneously?"

"What does Linux do with this?"

"Can I build a smaller version myself?"
```

So I build things.

Usually small things.

Sometimes unnecessarily low-level things.

**But that's where the fun is. 😄**

</details>

---

<details open>
<summary><b>📊 GitHub Activity</b></summary>

<br>

<p align="center">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=aish0629&theme=github-compact&area=true&hide_border=true&custom_title=Contribution%20Graph&bg_color=000000&color=C2FFC7&line=CB9DF0&point=C2FFC7&area_color=CB9DF0" />
</p>

</details>

<p align="center">
  <img src="https://raw.githubusercontent.com/aish0629/aish0629/output/github-contribution-grid-snake.svg" alt="snake"/>
</p>

---

<p align="center">
  <i>"If at first you don't succeed, call it version 1.0."</i>
</p>

<p align="center">
  <b>Still learning. Still breaking things. Still figuring out what happens underneath.</b>
</p>
