# SE Intern Assessment – Data Structures & Systems Design

## Problem 1: LRU Cache

Implemented an LRU (Least Recently Used) Cache using a **hash map + doubly linked list**.

- `get(key)` – returns the value if key exists, else -1. Marks key as recently used.
- `put(key, value)` – inserts or updates key. Evicts the least recently used item if at capacity.

Both operations run in **O(1)** time.

**File:** `lru_cache.py`

---

## Problem 2: Event Scheduler

Two functions to manage meeting events given as `(start, end)` tuples.

- `can_attend_all(events)` – returns `True` if no two events overlap.
- `min_rooms_required(events)` – returns the minimum number of rooms needed to run all events simultaneously.

Uses sorting + a **min-heap** for efficient room allocation. Time complexity: **O(n log n)**.

**File:** `event_scheduler.py`

---

## Language
Python 3
