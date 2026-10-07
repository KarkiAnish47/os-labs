# Lab 2: Investigating Process Lifecycles and OS Interaction

Cyber Security Fundamentals (ST4014CMD), Softwarica College / Coventry University
Author: Anish Karki

## Programs
| File | Task |
|------|------|
| task1_alive.c | Long-running process monitored with ps |
| task2_identity.c | PID and PPID with getpid() / getppid() |
| task3_exit.c | Exit codes checked with $? |
| task4_input.c | Standard input and output streams |
| task5_control.c | Conditional execution and exit codes |

## How to compile and run
gcc task1_alive.c -o task1
./task1 &

(Same pattern for the other tasks.)

## Environment
Ubuntu in a Docker container, gcc, nano, procps.

## Documentation
See Lab2_Documentation.pdf and the screenshots folder.
