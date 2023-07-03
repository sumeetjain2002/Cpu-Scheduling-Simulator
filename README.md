# Cpu-Scheduling-Simulator


[![Python version](https://img.shields.io/badge/python-%5E3.8.1-purple?style=flat-square)](https://www.python.org/)
[![BSD Licence](https://img.shields.io/badge/licence-BSD-geen?style=flat-square)](LICENSE)
[![Follow me](https://img.shields.io/github/followers/sumeetjain2002?label=follow%20me&style=flat-square)](https://github.com/sumeetjain2002)


This is an OS simulation that has been implemented by the CPU scheduling algorithms such as:<br>
- First Come, First Serve (<a href="https://en.wikipedia.org/wiki/Scheduling_(computing)#First_come,_first_served">FCFS</a>)
- Round Robin (<a href="https://en.wikipedia.org/wiki/Round-robin_scheduling">RR</a>)
- Shortest Job First (<a href="https://en.wikipedia.org/wiki/Shortest_job_next">SJF</a>)
- MultiLevel Feedback Queue (<a href="https://www.geeksforgeeks.org/multilevel-feedback-queue-scheduling-mlfq-cpu-scheduling/">MLFQ</a>) :
  - First queue: RR Time Quantum 8 ms
  - Second queue: RR with time Quantum 16 ms
  - Third queue: FCFS
<br>
<br>
<p align='center'>
    <img src="photos/csa.png" width="600" alt="cpu-scheduling-algos" />
</p>

<br>

## Program Input
Input data must be entered through a comma-separated values (.csv) and the columns must be like this:

| process_id | arrival_time | cpu_time1 | io_time | cpu_time2 |
| :---: | :---: | :---: | :---: | :---: |
| 1 | 1 | 2 | 3 | 4 |
| 2 | 12 | 3 | 4 | 1 |
| 3 | 5 | 4 | 5 | 3 |
| 4 | 13 | 4 | 5 | 15 |
| 5 | 13 | 5 | 6 | 7 |


## Program Output
1. the program will process the processes and will calculate the following information:
    - Response Time
    - Turnaround Time
    - Waiting Time
    - Process Start Time
    - Process End Time
2. after running the algorithms for each process these parameters will be shown for the algorithm:   
    - Total Time and Idle Time
    - Average Waiting Time
    - Average Response Time
    - Average Turnaround Time
    - CPU Utilization
    - Throughput


## Installation

_Below is an example of how you can clone and run the project on your local._

1. Clone the repo
   ```sh
   git clone https://github.com/sumeetjain2002/Cpu-Scheduling-Simulator.git
   ```
2. Install required libraries
   ```sh
   pip install pandas
   ```
3. Run the os_simulation.py file in your IDE.
4. Drink tea and enjoy the simulation! 🚀


<p align="right">
    (<a href="#top">back to top</a>)
</p>
