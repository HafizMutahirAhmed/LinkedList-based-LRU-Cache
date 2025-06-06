# LRU Cache Implementation with GUI in Python

This project implements an **LRU (Least Recently Used) Cache** using a **doubly linked list** and **hash map** (dictionary) in Python. It also includes a simple **Graphical User Interface (GUI)** built with **Tkinter** to interactively put and get cache entries and visualize the current cache contents along with the miss rate.

---

## Features

- **LRU Cache Data Structure**  
  - Supports `get(key)` and `put(key, value)` operations.  
  - Automatically evicts the least recently used item when capacity is exceeded.  
  - Maintains cache order with a doubly linked list for O(1) insertions and deletions.  
  - Tracks cache hits, misses, and access counts to compute miss rate.

- **GUI Interface**  
  - User-friendly interface to input keys and values.  
  - Buttons for `Put` and `Get` operations.  
  - Visual representation of cache contents as labeled boxes.  
  - Displays current cache miss rate dynamically.  
  - Handles invalid inputs with error messages.

- **Test scripts included** for validating cache functionality and behavior.

---

## Files

- `lru_cache.py` (or the main script file): Contains the LRU cache class implementation and the Tkinter GUI.

---

## How to Run

1. Ensure you have **Python 3.x** installed.

2. Run the script from the command line or an IDE:

   ```bash
   python lru_cache.py
