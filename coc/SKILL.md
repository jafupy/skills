---
name: code-of-conduct
description: How to write clean and maintainable code. 
---

# Code of Conduct

Write simple, compact, maintainable code.

* Structure files by responsibility.
* Do not create mega-files. Keep files around 150–200 lines unless there is a good reason for a larger file, eg. UI code.
* Keep related logic together, but split files when a file starts mixing unrelated responsibilities.
* When breaking up large files use folders or submodules to organize related code.

* Prefer boring code that is easy to read, change, and delete.
* Keep code terse. Prefer fewer moving parts and less code when it remains clear.
* Follow clean code principles: clear names, small functions, local reasoning, low duplication, and obvious control flow.
* Do not over-abstract. Extract helpers when they improve readability or remove real duplication, not just to make code look architectural.
* Don't overuse helper functions. If it's like 2 lines of code, just inline it.

* Prefer mostly procedural and functional code. Use pure functions where they make sense and keep side effects isolated when practical.
* Use classes/OOP only when they genuinely fit, such as custom data types, stateful objects, or domain concepts with behavior.
* Use lambdas / arrow functions where it makes sense, eg. callbacks that don't get used anywhere else. Otherwise use use the function keyword.

* Solve the actual problem.
* Avoid unnecessary robustness, configurability, abstractions, defensive layers, and “future-proofing.”

* When refactoring code. don't be afraid to boil the ocean and make large changes.
* Create an architecture plan and double check with the human that the proposal is a good fit for the codebase. 
* If your harness allows, use sub-agents to fan out and parallelize work.
