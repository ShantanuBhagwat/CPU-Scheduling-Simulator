CPU Scheduling Simulator Project - Frontend
📌 Overview

This project provides the frontend implementation of a CPU Scheduling Algorithm Simulator, designed to help students and learners visualize how different scheduling algorithms work in real time.
The simulator allows interactive process input, generates Gantt charts, and calculates important performance metrics such as Average Waiting Time (AWT), Turnaround Time (TAT), and Response Time (RT).

📖 Theory
🔹 CPU Scheduling Algorithms

In operating systems, CPU scheduling is one of the most important responsibilities of the scheduler. It determines the order in which processes execute on the CPU.
This simulator demonstrates the following algorithms:

First-Come, First-Served (FCFS)

Non-preemptive algorithm.

Processes are executed in the order they arrive in the ready queue.

Simple but may cause the convoy effect, leading to poor performance in certain cases.

Shortest Job First (SJF) / Shortest Job Next (SJN)

Selects the process with the shortest burst time first.

Optimizes average turnaround time.

Requires prior knowledge of burst times (not always practical).

Round Robin (RR)

Preemptive scheduling algorithm.

Each process gets a fixed time quantum to execute.

If incomplete, the process goes to the back of the queue.

Provides fairness but may increase context switching overhead.

Priority Scheduling

Each process is assigned a priority value.

The CPU executes the process with the highest priority first.

Can lead to starvation of lower-priority processes unless aging is used.

🎯 Features

Interactive Visualization → Gantt charts show execution order dynamically.

User Input Support → Arrival time, burst time, and priority can be entered.

Real-Time Simulation → Algorithms execute step-by-step for clarity.

Performance Metrics → Average Waiting Time, Turnaround Time, and Response Time are calculated.

🛠 Technologies Used

HTML – Structure and input forms.

CSS – Styling, themes, and UI design.

JavaScript – Algorithm implementation and visualization logic.

Input:
Open index.html in any modern browser.

Output:
Input process details → Choose an algorithm → Generate simulation.

👨‍💻 Made By

Sarth Joshi

Shantanu Bhagwat

Harshraj