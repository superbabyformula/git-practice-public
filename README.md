# Prerequisites
1. Create a dev branch from the master branch
2. Add "1. REMOVE THIS LINE IN MERGE LATER" to the end of this file.
3. Commit the changes with message "1. Add line that will cause merge conflict."
4. Create the following three feature branches from the dev branch
  1. f1
  2. f2
  3. f3

# Instructions
1. Checkout the f1 branch.
2. Add "1.f1 1" to the end of this file.
3. Commit the changes from the previous step with comment "f1 0".
4.  Undo the commit so that the change is still staged.
5. Add a file called f1.txt with text "1.f1 1" inside.
6. Commit the changes to both the README.md and f1.txt files with comment "f1 1"
7. Checkout the f2 branch.
8. Add "2. f2 0" to the end of this file.
9. Stage the changes, but don't commit. Undo the changes so that they are no longer staged.
10.Undo the changes so that they are no longer tracked (i.e. they have been completely rolled back)
11. Add "2. f2 1" to the end of this file.
12. Commit the changes  with comment "f2 1"
13. Checkout the f3 branch.
14. Add "3. f3 1" to the end of this file.
15. Commit the changes from the previous step with comment "f3 1"
16. Add "4. f3 2" to the end of this file.
17. Commit the changes from the previous step with comment "f3 2"
18. Checkout the f1 branch.
19. Add "5. f1 2" to the end of this file.
20. Commit the changes from the previous step with comment "f1 2"
21. Checkout the f2 branch
22. Add "6. f2 2" to the end of this file.
23. Commit the changes with comment "f2 2".
24. Create a new feature branch from the "dev" branch called "f4" and push it to the remote repository
25. Checkout the master branch
26. Delete the f4 branch from the remote repository.
27. Delete the f4 branch from the local repository.
28. Merge the dev branch into the f1 branch with comment "Merge dev into f1".
29. Merge the f1 branch into the dev branch with comment "Merge f1 into dev".
30. Merge the dev branch into the f2 branch with comment "Merge dev into f2".
31. Squash merge the f2 brnach into the dev branch "Merge f2 into dev"
32. Rebase the f3 branch to the dev branch.
33. Rebase the dev branch with the f3 branch.

# Change Log

