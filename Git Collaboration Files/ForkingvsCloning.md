# Forking vs. Cloning Overview

Forking and cloning in Github are often confused, as the differences are small but significant with respects to project collaboration. In this tutorial, you will learn the difference between them, how to execute a fork or a clone, and in which situations you should use them


# Forking Explained

Say you've just added a collaborator to your repository. The logical next step would be for that person to start working on the project. However, you've already put a lot of files into the repository and have a working application. You don't know if what the collaborator is doing will work seamlessly with your code. To prevent their code interfering with yours before knowing if it is bug-free, the collaborator can **fork** the repository. 

Essentialy, a fork is a **copy** of a repository, and it allows you or your collaborator(s) to experiment with or make changes to the original project without affecting the main source code. After changes are made, the collaborator can make a pull request to the project-owner so they can either accept or reject your changes.

## How do you fork a repository?

### Steps

1. Click on the link to the original repository.

2. Click on the upper right-hand button that says **"Fork"** and has a little picture of a diverging line. ![Fork](https://github.com/jeanshanchik/KVKRepo/blob/master/Git%20Collaboration%20Files/images/fork.png)

3. Your fork has been created. You will know you're in your fork when your repository name looks like this:

```jeanshanchik/KVKRepo```

And underneath it, it says:

```forked from username/KVKrepo```

Congratulations! You've just forked a repository and can now start making changes to it. 

## What if you're the owner of the repository?

If you are the owner of the repository, you will not be able to fork it. Only other people can. If you hover over the **Fork** button, you will see this:

![Fork](https://github.com/jeanshanchik/KVKRepo/blob/master/Git%20Collaboration%20Files/images/forkingexample.png)


# Cloning Explained

Cloning is related and sometimes intertwined with forking, however they are not interchangeable. A clone is a copy of the repository onto your local machine/directory. Any changes you make to it will be on your local machine, as it is a completely separate instance of the project. If you want to make a change, you have to push what you've done to the repository. 

For example, if you wanted to make changes to an existing repository, you would want to fork it first to make your own copy of the project, and then clone it onto your local machine to start the changes. You would then push your changes to your forked version of the project upstream, and then submit a pull request of said changes to the project-owner. 

## How do you clone a repository?

### Steps

1. You will want to navigate to a location on your local machine where the clone will be placed. Have that directory off-hand.

2. Open your git command line (git bash or your docker terminal), and change directories to where you want to place the clone:

  ```git cd /c/Users/kelley/IS601```

3. Then, to ensure you are in the right directory, use ```pwd```.

4. Navigate to the original repository whose code you want to work on, just as we did when we forked it.

2. Look for the green button all the way to the right that says **"Clone or download"** and click. 

3. Copy the link that appears below the button.

5. In your git command line, type and hit enter:

  ```git clone https://github.com/jeanshanchik/KVKRepo.git```

  Replacing my link above, of course, with the link you've copied.

6. Once the clone has been made, you can go ahead and do ```cd KVKRepo``` replacing my repository name with the one you cloned.

7. Your command line should show which folder you're in, and which repository branch you are on. In this case, it should say **"master"**.

Congratulations, you are now ready to make changes in your clone. When you've made the changes you want, you can push them to the forked repository and then follow-up with a pull request to have them added to the original source code.

**Definition Recap:**

**Fork** = Copy of the main repository/project

**Clone** = Copy of the fork onto local machine to make changes
