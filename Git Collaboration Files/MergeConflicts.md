### Branching, Merging, and Merge Conflicts


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

What causes a merge conflict? Something as simple as a person deleting a file you're working on, or when changes are made to a line of code that you are currently working on. Essentially, a conflict arises when Git has competing commits and needs someone's input to determine which commit to incorporate into the final merge.

You can resolve a merge conflict on GitHub itself only if it is caused by competing line changes. All other merge conflicts must be resolved locally on the command line.

On GitHub, the steps to complete a merge conflict are as follows:

### Steps

1. Navigate to your repository and click on **Pull Requests**

2. Once you are in **Pull Requests**, look for the pull request that has a merge conflict and click **Resolve Conflicts**.

3. 
