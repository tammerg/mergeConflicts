# Merge Conflicts

* Please take a few moments and read about Git Merge Conflicts. The link is provided below.

* [Merge Conflicts](https://help.github.com/articles/about-merge-conflicts/)

* In this activity we will force a merge conflict to occur, simulating working with a partner and having different code.


# Instruction

* First, lets clone the repo we made to simulate these merge conflicts.

* After we have cloned our repo, let's then `cd` into our newly cloned repo.

* Let's then run a `git fetch origin` &mdash; this will pull down all the branches of our repository and allow us to `git checkout BRANCHNAME` to whatever `branch` we would like.

* Next, let's run `git pull origin mergeConflicts` &mdash; this will pull our `mergeConflicts` branch into our `master` branch.

* The previous step should output:
[fullCLIConflict](images/fullCLIConflict.png)

* We will then go into the file containing the conflict, `conflict.json`. Inside the file we should see something similar to the following:
[conflict.png](images/conflict.png)

* We can either take the `Incoming Change` or keep our `Current Change`. These changes are dilenated by a series of equal signs.

* Now when we go to fix our conflict, our CLI path will look something like this:
[cliConflict](cliConflict.png)

* To remedy this, lets choose which changes we want, then `git add`, `git commit -m`, and finally `git push origin master`!