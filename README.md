# Advent of Code Template

This project contains a template for solutions to the Advent of Code competition (https://adventofcode.com/).

All of this was created just for fun, so no guarantees on anything.

Usage:

- set the current year in definitions.py
- The entry point is: `python advent_of_code_template/main.py`
- If you call `python advent_of_code_template/main.py --task XX` for any task that was not yet created, the structure
  for your solution is automatically generated.
  - If never done before, the terminal will ask you for your session ID in order to download your input data. Please refer to https://pypi.org/project/advent-of-code-data/ on how to get this. 
  - (optional) add the task description to `task.md`
  - The example input and expected output has to manually be added to the test file in `tests/` 
  - Your solution should be implemented in `tasks/taskXX.py` in the methods `solve_task` and `solve_bonus_task`.