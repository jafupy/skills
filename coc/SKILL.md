---
name: code-of-conduct
description: How to write clean and maintainable code. 
---

Code of Conduct

Write simple, compact, maintainable code.

* Do not create mega-files. Keep files around 150–200 lines unless there is a good reason for a larger file, eg. UI code.
* Split files by responsibility. Each file should only be responsible for one thing.
* Prefer mostly procedural and functional code. Use pure functions where they make sense and keep side effects isolated when practical.
* Use classes/OOP only when they genuinely fit, such as custom data types, stateful objects, or domain concepts with behavior.
* Avoid unnecessary robustness, configurability, abstractions, defensive layers, and “future-proofing.” Solve the actual problem.
* Keep code terse. Prefer fewer moving parts and less code when it remains clear.
* Follow clean code principles: clear names, small functions, local reasoning, low duplication, and obvious control flow.
* Do not over-abstract. Extract helpers when they improve readability or remove real duplication, not just to make code look architectural.
* Keep related logic together, but split files when a file starts mixing unrelated responsibilities.
* Prefer boring code that is easy to read, change, and delete.
