# Airline Crew Scheduling — Backtracking & Constraint Satisfaction

## Problem
Assign flights to crew members satisfying constraints:
- No overlapping flights for the same crew member.
- Minimum rest time between two flights assigned to same crew (default: 1 hour).
- (Optional) Minimize total cost.

This project demonstrates a backtracking (CSP) approach suitable for small problem sizes, profiling, visualization (Gantt chart), and discussion of limitations and improvements.

## What is included
- `crew_scheduling.py` — Complete implementation including solver, profiler, and plotting.
- Example inputs and visualization for sample schedules.
- Plots of execution time vs number of flights (shows exponential growth).

## Requirements
- Python 3.8+
- Packages: `matplotlib`, `numpy`, `pandas`, `memory_profiler` (optional for memory profiling)
```bash
pip install matplotlib numpy pandas memory_profiler
