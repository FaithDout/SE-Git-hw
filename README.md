# SE-Git-hw

Assignment 1 for CINS 5318, Software Engineering. This project is a small
exercise in using Git and GitHub: setting up a repository, working with
branches, opening a pull request, resolving a merge conflict, and tracking
work with Issues.

## Files

- `hello.py` - a simple Hello World program, added in the first commit on `main`.
- `apple.py` - added on the `feature-1` branch, prints `I eat apple`.

## How to run

Both files are plain Python scripts.

```
python3 hello.py
python3 apple.py
```

## Workflow used

1. Created the repository and made the first commit with `hello.py` on `main`.
2. Created a branch called `feature-1` and added `apple.py`, then opened a
   pull request to merge it into `main`.
3. Had the pull request reviewed, then merged it and deleted the branch.
4. Created two more branches that both edited the same line in `hello.py`,
   merged them one after another to produce a merge conflict on purpose, and
   resolved it by hand.
5. Opened two Issues to track follow-up tasks, assigned them, and closed
   them once the work was done.

## Issues

| Issue | Assigned to | Status | Resolution |
|-------|------------|--------|------------|
| Add comments to hello.py explaining what it does | Faith Doutimiwei | Open | Update this row to Closed once done, with a one-line note on what was added. |
| Add a second print statement to apple.py | Pending a classmate | Open | This one needs a real classmate added as a collaborator first (see RUNBOOK.md, Part 6). Update the assignee, status, and resolution once that happens. |

## Reflection

A written reflection on this exercise is submitted separately as a PDF,
covering the setup, branching, pull requests, the merge conflict, and
what was learned.
