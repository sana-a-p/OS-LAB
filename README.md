# Operating Systems Lab Programs

This repository contains C programs implementing various **Operating System algorithms** for CPU scheduling, disk scheduling, file allocation, and page replacement.

---

## 📂 CPU Scheduling Algorithms  
**Folder:** `CPU Scheduling/`

1. **First Come First Serve (FCFS)**  
   [fcfs.c](./CPU%20Scheduling/fcfs.c) – Implements FCFS CPU scheduling with arrival and burst times.

2. **Shortest Job First (SJF)**  
   [sjf.c](./CPU%20Scheduling/sjf.c) – Implements non-preemptive SJF scheduling.

3. **Priority Scheduling**  
   [priority.c](./CPU%20Scheduling/priority.c) – Implements non-preemptive priority-based scheduling.

4. **Round Robin Scheduling**  
   [roundrobin.c](./CPU%20Scheduling/roundrobin.c) – Implements Round Robin scheduling with a time quantum.

---

## 📂 Disk Scheduling Algorithms  
**Folder:** `Disk Scheduling/`

1. **FCFS Disk Scheduling**  
   [fcfs.c](./Disk%20Scheduling/fcfs.c) – Implements disk head movement using the FCFS approach.

2. **SCAN (Elevator) Algorithm**  
   [scan.c](./Disk%20Scheduling/scan.c) – Implements SCAN disk scheduling.

3. **C-SCAN (Circular SCAN) Algorithm**  
   [cscan.c](./Disk%20Scheduling/cscan.c) – Implements C-SCAN disk scheduling.

---

## 📂 File Allocation Methods  
**Folder:** `File Allocation/`

1. **Sequential File Allocation**  
   [sequential.c](./File%20Allocation/sequential.c) – Implements sequential allocation of files on disk.

2. **Linked File Allocation**  
   [linked.c](./File%20Allocation/linked.c) – Implements linked allocation of disk blocks.

3. **Indexed File Allocation**  
   [indexed.c](./File%20Allocation/indexed.c) – Implements indexed file allocation.

---

## 📂 Page Replacement Algorithms  
**Folder:** `Page Replacement/`

1. **FIFO (First In First Out)**  
   [fifo.c](./Page%20Replacement/fifo.c) – Implements FIFO page replacement, replacing the oldest loaded page first.

2. **LRU (Least Recently Used)**  
   [lru.c](./Page%20Replacement/lru.c) – Implements LRU page replacement, replacing the page that hasn’t been used for the longest time.

3. **LFU (Least Frequently Used)**  
   [lfu.c](./Page%20Replacement/lfu.c) – Implements LFU page replacement, replacing the page with the fewest accesses.

---

## ⚙️ How to Compile and Run

Navigate into the relevant folder and run:
```bash
gcc filename.c -o outputname
./outputname
