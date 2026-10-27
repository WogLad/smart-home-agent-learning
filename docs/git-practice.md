# Git practice record

## Context

This is a fresh demonstration repository created after the course.
My original course repository was later used for other activities
and testing, so I created this focused artefact to demonstrate my learning.

## Starting point

I initialised a local Git repository, created a README and .gitignore,
and imported an existing smart-home AI evaluation notebook.

## Branch and pull request

I created a documentation branch, added run instructions and metric
definitions, pushed the branch and opened a pull request.

After inspecting the changes, I merged the pull request and pulled
the updated main branch into my local repository.

## Merge conflict exercise

I deliberately edited the same sentence differently on two branches.
Git reported a conflict when I merged the second branch.

I inspected the conflict markers and combined both intended meanings:
routing accuracy and complete task success. I staged the resolved file
and committed the merge.

## Revert exercise

I committed a temporary documentation sentence and then used git revert
to undo it. Git created a new commit reversing the change while preserving
the original commit in the history.
