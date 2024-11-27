# CPU Scheduler Simulator

## Overview
Simulates CPU scheduling algorithms with both GUI and console-based outputs.

## Features
- **Algorithms**:
  - Priority Scheduling
  - Shortest Job First (SJF)
  - Shortest Remaining Time First (SRTF)
  - FCAI Scheduling
- Gantt Chart visualization
- Dynamic quantum allocation for FCAI Scheduling.

## Getting Started
1. Clone the repository.
2. Open in IntelliJ.
3. Run `SchedulerGUI.java` for the GUI version.

## Input
- Process Name
- Arrival Time
- Burst Time
- Priority

## Output
- Execution order
- Waiting time
- Turnaround time
- Gantt chart visualization.

## Example
**Input**:
- P1: Arrival=0, Burst=10, Priority=1
- P2: Arrival=2, Burst=5, Priority=3

**Output**:
- Execution Order: P1 -> P2
- Gantt Chart: [P1][P2]
