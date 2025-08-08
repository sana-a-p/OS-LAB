# OS-LAB
# Operating Systems Lab Programs

This repository contains C programs implementing various **Operating System algorithms** for process scheduling, disk scheduling, and file allocation.

## 📂 CPU Scheduling Algorithms

1. **First Come First Serve (FCFS)**  
   [fcfs.c](./fcfs.c) – Implements FCFS CPU scheduling with arrival and burst times.

2. **Shortest Job First (SJF)**  
   [sjf.c](./sjf.c) – Implements non-preemptive SJF scheduling.

3. **Priority Scheduling**  
   [priority.c](./priority.c) – Implements non-preemptive priority-based scheduling.

4. **Round Robin Scheduling**  
   [roundrobin.c](./roundrobin.c) – Implements Round Robin scheduling with a time quantum.

---

## 📂 Disk Scheduling Algorithms

1. **FCFS Disk Scheduling**  
   [fcfs_disk.c](./fcfs.c) – Implements disk head movement using the FCFS approach.

2. **SCAN (Elevator) Algorithm**  
   [scan.c](./scan.c) – Implements SCAN disk scheduling.

3. **C-SCAN (Circular SCAN) Algorithm**  
   [cscan.c](./cscan.c) – Implements C-SCAN disk scheduling.

---

## 📂 File Allocation Methods

1. **Sequential File Allocation**  
   [sequential.c](./sequential.c) – Implements sequential allocation of files on disk.

2. **Linked File Allocation**  
   [linked.c](./linked.c) – Implements linked allocation of disk blocks.

3. **Indexed File Allocation**  
   [indexed.c](./indexed.c) – Implements indexed file allocation.

---

## 📂 Page Replacement Algorithms

1. **FIFO (First In First Out)**  
   [fifo.c](./fifo.c) – Implements FIFO page replacement, replacing the oldest loaded page first.

2. **LRU (Least Recently Used)**  
   [lru.c](./lru.c) – Implements LRU page replacement, replacing the page that hasn’t been used for the longest time.

3. **LFU (Least Frequently Used)**  
   [lfu.c](./lfu.c) – Implements LFU page replacement, replacing the page with the fewest accesses.

---

## ⚙️ How to Compile and Run

Open a terminal in the folder containing the program and run:

```bash
gcc filename.c -o outputname
./outputname
