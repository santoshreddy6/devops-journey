## Process Management (Day 02)

A process is a running instance of a program.

### Key Concepts
- Process vs Thread
- Each process has a unique PID (Process ID)
- Processes can run in foreground or background

### Common Commands
- ps aux → List all running processes
- top → Real-time process monitoring
- jobs → List background jobs
- sleep & → Run a process in background
- kill PID → Terminate a process

### Notes
- High CPU or memory usage can be identified using top
- Background processes do not block the terminal
- kill -9 PID forcefully stops a process (use carefully)
