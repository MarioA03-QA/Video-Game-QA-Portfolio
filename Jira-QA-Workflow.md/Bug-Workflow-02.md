# QA Bug Workflow

## Overview

For my portfolio project, I created a Jira workflow to simulate the lifecycle of a defect within a game development environment.
The workflow allows issues to move between different stages depending on their current state and whether they have been successfully resolved and verified.
I have also included a description of each workflow element to showcase my understanding of each step of the bug reporting lifecycle.

## Workflow

**Open → In Progress → Ready for Test → Failed / Reopened → Fixed → Retest → Done**

### Open

The bug has been identified and documented but has not yet entered the investigation stage.

### In Progress

The bug is currently being investigated or is being worked on.

### Ready for Test

A proposed fix has been issued and the bug is ready for further QA testing.

### Failed / Reopened

The bug remains present after testing or the proposed solution has introduced another problem. The bug is returned to the development team for further investigation.

### Fixed

The developer has indicated that the bug has been addressed and is ready for QA testing.

### Retest

The bug is tested again to confirm whether the solution has successfully resolved the original issue.

### Done

The bug has been successfully resolved and verified.


<img width="1920" height="918" alt="jira-bug-workflow" src="https://github.com/user-attachments/assets/3e0b62fb-d77e-44f2-bb40-38e298ab6139" />
