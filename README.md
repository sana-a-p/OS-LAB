# Operating Systems Lab Programs

This repository contains C programs implementing various **Operating System algorithms** for process scheduling, disk scheduling, file allocation, and page replacement.

---

## 📂 Process Scheduling Algorithms  
**Folder:** `CPU Scheduling/`

1. **First Come First Serve (FCFS)**  
   [fcfs.c](./CPU Scheduling/fcfs.c) – Implements FCFS CPU scheduling with arrival and burst times.

2. **Shortest Job First (SJF)**  
   [sjf.c](./CPU Scheduling/sjf.c) – Implements non-preemptive SJF scheduling.

3. **Priority Scheduling**  
   [priority.c](./CPU_Scheduling/priority.c) – Implements non-preemptive priority-based scheduling.

4. **Round Robin Scheduling**  
   [roundrobin.c](./CPU_Scheduling/roundrobin.c) – Implements Round Robin scheduling with a time quantum.

---

## 📂 Disk Scheduling Algorithms  
**Folder:** `Disk Scheduling/`

1. **FCFS Disk Scheduling**  
   [fcfs.c](./Disk_Scheduling/fcfs.c) – Implements disk head movement using the FCFS approach.

2. **SCAN (Elevator) Algorithm**  
   [scan.c](./Disk_Scheduling/scan.c) – Implements SCAN disk scheduling.

3. **C-SCAN (Circular SCAN) Algorithm**  
   [cscan.c](./Disk_Scheduling/cscan.c) – Implements C-SCAN disk scheduling.

---

## 📂 File Allocation Methods  
**Folder:** `file_allocation/`

1. **Sequential File Allocation**  
   [sequential.c](./File_Allocation/sequential.c) – Implements sequential allocation of files on disk.

2. **Linked File Allocation**  
   [linked.c](./File_Allocation/linked.c) – Implements linked allocation of disk blocks.

3. **Indexed File Allocation**  
   [indexed.c](./File_Allocation/indexed.c) – Implements indexed file allocation.

---

## 📂 Page Replacement Algorithms  
**Folder:** `page_replacement/`

1. **FIFO (First In First Out)**  
   [fifo.c](./Page_Replacement/fifo.c) – Implements FIFO page replacement, replacing the oldest loaded page first.

2. **LRU (Least Recently Used)**  
   [lru.c](./Page_Replacement/lru.c) – Implements LRU page replacement, replacing the page that hasn’t been used for the longest time.

3. **LFU (Least Frequently Used)**  
   [lfu.c](./Page_Replacement/lfu.c) – Implements LFU page replacement, replacing the page with the fewest accesses.

---

## ⚙️ How to Compile and Run

Navigate into the relevant folder and run:
```bash
gcc filename.c -o outputname
./outputname
