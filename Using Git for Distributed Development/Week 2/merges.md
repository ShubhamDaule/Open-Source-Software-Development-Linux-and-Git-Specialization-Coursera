## Merges


**Q1. Which procedure does a better job of preserving a project's history?**

Answer:
* `git merge`

**Q2. Why might a merge result in problems that do not show conflicts (select all correct answers)?**

Answer:
* There may be two different solutions to the same problem which interfere with other
* A merge might affect code in a very different part of the product in a non-obvious way and not receive enough testing

**Q3. A git rebase**

Answer:
* adapts a branch to incorporate the latest changes in another branch without yet merging this branch into the other branch

**Q4. How would you merge two branches (br1 and br2) into the master branch?**

Answer:
* `git checkout master && git merge br1 && git merge br2`

**Q5. What do you do when a merge fails?**

Answer:
* Evaluate the conflict, see what the correct result should be and then fix
