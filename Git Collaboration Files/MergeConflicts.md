# Branching, Merging, and Merge Conflicts


## Branching & Merging

Let's say you want to add a feature to the original repository, or fix a bug. You can create a branch to work on your feature/bug without ever disturbing the master branch. Because it is so simple to create one, it is probably a good idea to do it if you are working on a large project.

If you want to create a branch while in the command line, follow these steps:

### Steps

1. To create the branch of your feature, enter this into your command line: 

```$ git create branch new_feature```

2. Now that it has been created, you want to make sure you are on the branch to make your changes: 

``` $ git checkout new_feature```

It should indicate now which branch you are on in the command line.

3. You've made your changes, written new code, and you are ready to merge the changes. You add the files and commit them. Now you'll want to switch back to the master branch.

```$ git checkout master```

4. Next, you want to push the branch to GitHub:

```$ git push origin new_feature```

5. If you're happy with the changes and want to merge them into the master branch:

```$ git checkout master```

_Switching to the master branch_

```$ git merge new_feature```

_Merging your new feature to the master branch_

6. If you are done with the branch and would like to delete it:

```$ git branch -d new_feature```

7. Keep in mind, if you've already pushed the branch to GitHub, it will still exist there even after you perform the above command. So, you'll have to perform the following command to delete it from GitHub:

```$ git push origin --delete new_feature```

Congratulations, you're now able to create a branch and do a simple merge. There will be times, however, you will run into merge conflicts. This is especially prevalent the more complex the projects become. 

## Merge Conflicts

What causes a merge conflict? When faced with one, it is best to understand what actually happened. For example, did someone delete a file you're working on? Or did someone modify a line of code that you are currently working on? Essentially, a conflict arises when Git has competing commits and needs someone's input to determine which commit to incorporate into the final merge.

You can resolve a merge conflict on GitHub itself only if it is caused by competing line changes. All other merge conflicts must be resolved locally on the command line.

On GitHub, the steps to complete a merge conflict are as follows:

### Steps

1. Navigate to your repository and click on **Pull Requests**

2. Once you are in **Pull Requests**, look for the pull request that has a merge conflict and click **Resolve Conflicts**.

3. You will then be able to decide which changes to keep. You can keep just your own branch's changes, the other branch's changes, or you can make an entirely new change which incorporates changes from both of the branches. You must delete the conflict markers ```<<<<<<<```, ```=======```, ```>>>>>>>``` and make your changes you want to be in the final merge.

4. Once you've completed all your changes and resolved the conflicts, you can go ahead and click **Mark as Resolved**. 

5. You can repeat these steps for all files in which you have conflicts. Once they are completed, you can click **Commit merge**, which will merge the entire base branch into the head branch.

6. You may need to commit this to a branch, so when prompted, click **I understand, update YOUR_BRANCH**.


### Steps - Command Line

The steps below are for more complext merge conflicts that cannot be done on the GitHub UI.

1. If there's a conflict when you're pulling a branch, you may get an error message like so:

```
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
```

2. You can navigate to the file it is referring to, in this case it is the README.md file. 

3. When you open the file, you will see an indicator of where the conflict is occurring in the code.

```
<<<<<<< HEAD
The line you created.
=======
The line your friend created.
>>>>>>> 031389f2cd2acde08e32f0beb084b2f7c3257fff
```

4. You can edit the lines between ```<<<<<<<``` and ```>>>>>>>``` to make it what you want. 

5. Once you are finished, you can do your ```git add```, ```git commit```, and ```git push``` commands.
