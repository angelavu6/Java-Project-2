# C-Project-2
## Project Overview

This project simulates a virtual memory system for a computer with RAM and virtual memory. The simulation includes processes, page tables, and memory management, focusing on page loading, eviction, and Least Recently Used (LRU) page replacement. The program reads input data from a file, simulates the loading of pages into RAM, and outputs the state of the system to an output file.

The system features:
- **RAM Size**: 16 slots.
- **Virtual Memory Size**: 32 slots.
- **Page Size**: 2 contiguous memory locations.
- **Processes**: 4 processes, each with 4 pages.
- **Frames in RAM**: 8 frames available.
- **Disk Pages**: Pages that are not currently in RAM are stored on virtual memory (disk), indicated by the value `99`.
