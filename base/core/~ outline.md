---
Title: Zemo Core Initial Outline
Author: Zachary Warsalla.
Date of Creation: 10/27/2026

---

# Outline Core Execution Sequence

Core Execution Sequence:
 
1. Startup.
2. Pull base system context and core config files (from cache or fresh dynamically), mostly hardware and software/OS info for thread executor.
3. Begin thread executor taking base context into account and building an optimal thread executor profile. The thread executor should have its own custom base error logging system which allows for errors to be logged on all threads and from the core iteself.
4. Load core UI.
5. Load input processor core with thread executor.


# Loose:

Contains self-management (keeping track of current directory and overall program structure), logging, thread management, raw context compilation; mostly lower level operations in general.

