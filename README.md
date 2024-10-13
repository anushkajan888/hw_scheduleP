# hw_scheduleP
 Overview

This project implements a simple process scheduling simulator in C, demonstrating two scheduling algorithms:
- First Come First Served (FCFS)
- Shortest Job First (SJF) (Non-Preemptive)**

The program calculates the following metrics for each process:
- Turnaround Time (TAT): Time taken from process arrival to its completion.
- Waiting Time (WT): Time a process spends waiting in the queue.
- Response Time (RT): Time from process arrival to the first execution.

It also displays a Gantt Chart for both scheduling algorithms and computes the average values of the above metrics.

Input Format

The program expects the user to provide:
1. The number of processes.
2. Each process’s arrival time and burst time as integer values.



## Output Details

For each algorithm, the program displays:
1. Gantt Chart: The order in which the processes are executed.
2. Metrics for each process:
   - `PID` (Process ID)
   - `AT` (Arrival Time)
   - `BT` (Burst Time)
   - `WT` (Waiting Time)
   - `TAT` (Turnaround Time)
   - `RT` (Response Time)
3. Average Waiting Time, Turnaround Time, and Response Time.


- The program uses non-preemptive versions of the scheduling algorithms, meaning once a process starts executing, it will run until completion without interruption.
- Edge cases handled:
  - Multiple processes with the same arrival time.
  - Varying burst times and arrival times.


