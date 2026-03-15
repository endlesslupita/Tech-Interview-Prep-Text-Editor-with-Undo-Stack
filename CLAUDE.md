# Tech Interview Prep: Simple Text Editor with Undo Functionality

## Assignment Context
- Course: AD311 Intermediate Application Development 1
- Task: Implement a simple text editor with add, delete, and undo operations using a stack
- Scenario: Create a text editor that tracks operations on a stack to support undo functionality

## Problem Summary
Implement a text editor that:
- Adds a character to the text and records the action on a stack
- Deletes the last character and records the deletion on a stack
- Undoes the last operation using the stack (supports multiple consecutive undos)
- Displays the current text state after each operation

Define a `TextOperation` class representing an operation (type: add or delete, and the character involved).

## Deliverables Required
- Solution in `solution.py`
- ASCII diagrams/flowcharts of the approach
- Clarifying questions documented
- Pytest unit tests: 3+ normal cases, 3+ edge cases
- Time and space complexity analysis
- Optimized solution with trade-off explanation

## Workflow (from parent CLAUDE.md)
- Generate naive solution first, then optimize
- Analyze time/space complexity for both versions
- Create pytest unit tests (3+ normal, 3+ edge cases)
- Create simple ASCII diagrams for whiteboard explanation

## Style (from parent CLAUDE.md)
- Use Pythonic idioms
- Include docstrings with complexity analysis

## Constraints
- Must be presentable as a live coding interview (talk through decisions)
- Communicate clearly throughout - explain why you make each decision