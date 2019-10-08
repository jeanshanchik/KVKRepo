# Continuous Integration & Automation in Businesses
Author: Kelley Shann

## What is Continuous Integration?

**Continuous Integration** (CI) is an important practice within the software development community that allows developers to frequently integrate code into a shared repository. It can occur several times a day, and it aids in the detection of errors and bugs more quickly and easily. It also encourages committing small changes more frequently than large changes less frequently. If done properly, each commit will trigger an automated test can determine if the new changes break the code when integrated. In short, it means to integrate, build, and test code on a regular basis. 

There are several key principals that are considered best practice in CI. They are listed below and explained.

### 1. **Version Control**

Version control systems are a way to keep track of all of your previous versions/files of your software project. VCS also makes collaboration with your team easier and more efficient. Essentially, they are central repositories for the data/code, which helps make CI possible. **Git** is the most popular VCS.

### 2. **Build Automation**

Simply put, build automation is the process of scripting and automating software code from a repository and compiling it. Instead of having to manually initiate a test or publish code, a build automation script would do it for you.

Some popular build automation tools include **Jenkins**, **CircleCI**, and **Travis CI**.

### 3. **Automated Testing**

Automated testing checks if the software is functioning appropriately and meeting requirements before it is released into production.
This is a part of CI that occurs within build automation by means creating a script to test it automatically. Automated testing tools produce reports of the outcomes of the tests and reconciles it against earlier test runs.

There are open-source automated testing softwares that are called **Selenium**, **Robotium**, and **Cypress**.


### 4. **Continuous Delivery**

Continuous delivery is the practice of keeping your code automatically prepared for a release to production. If properly implemented, software developers should always have a deployment-ready build, that has passed through a standardized test process, at their disposal. It allows developers to thorougly validate updates and proactively discover potential bugs. With CD, new releases of the app/software can be deployed sustainably.

### 5. **Continuous Deployment**

Continuous deployment takes continuous delivery one step further. It makes it so that deployment of the changes that have passed all stages of the production pipeline is done automatically, without human intervention. The benefit here is that development does not have to be interrupted for releases.


## Benefits of CI for Businesses

There are many benefits to implementing a proper CI process:

1. **Better Feedback Loop**: Having a CI process allows for valuable insights to be obtained much faster, and in doing so, allows for the team and management to make changes more efficiently. These insights enable faster technological and business decisions, and gives management the information they need to see the progress of the project more clearly.

2. **Clearer Communication**: The code sharing within the software development team improves visibility and collaboration between teammates. Over time, this improves the efficiency of the developers and the project(s).

3. **Cost Reduction**: Testing software costs money and time. While implementing CI may have an initial upfront cost, the cost reduction over time makes up for it, as automated testing reduces costs by running hundreds of them in a matter of seconds. 

4. **Quality Improvement**: Because the team spends less time doing QA and running tests, they can focus more on features and improving the overall quality and user experience of the application/software. 

5. **Risk Reduction**: Releases are much less risky, and are inherently easier to fix when deployed, as they are deployed in small batches. 



**References**

- [Continuous Integration Essentials](https://codeship.com/continuous-integration-essentials)
- [What is Continuous Integration?](https://nevercode.io/blog/what-is-continuous-integration-and-how-to-benefit-from-it/)
- [Build Automation](https://www.aemcorp.com/devops/build-automation)
- [What is Automated Software Testing?](https://searchsoftwarequality.techtarget.com/definition/automated-software-testing)
- [Continuous integration vs. continuous delivery vs. continuous deployment](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)




# Git's contribution to helping a company improve productivity and competitiveness

Author: Karan Walanj

**Git**, an open source project is a widely used modern distributed version control system that has become popular in the past decade. Several software projects rely on Git because of it's many usages that not only improve productivity but also give companies a competitive edge. 

![Git Image](https://github.com/enforcer20/KVKRepo/blob/master/VI_image/gitimage.png)

1. **Version Control**

Git offers a remote repository which is stored in a server and a local repository stored in local computers of all developers. Small to large scale projects can generally have multiple developers working parallely. Git's capability to branch provide developers with an isolated environment to make changes to their code. Branching reduces corrupting the production level code that is in master and gives developers their own workspace. This helps a company be more organized and productive. There are many instances where multiple developers working at the same time can rewrite another developer's code and lose considerable progress.

2. **Flexibility**

Project requirements are rarely concrete. Git's version control system allows developers to revert and go back to an older version of the code in case of any changes. This in turn helps retain a solid customer base but makes the companies easier to rely on.

3. **Security**

Git's security features make it a reliable version control system. All content and changes made in a Git repository are secured with a cryptographically secure hashing algorithm called SHA1. This protects code and change history against accidental or malicious changes. This ensures a fully traceable history. 

4. **Collaboration**

Git offers a pull request functionality. A pull request is a way for a developer to merge one of their branches into another developers' repository. This makes collaboration much easier and project leads can keep better track of changes. Developers can discuss on an issue that someone might need help with and share code to maintain productivity. 

5. **Community**

Git has a very active community. Open source projects shared by an several developers provide a means to reach out to other experienced developers who can fork their code with the users.

6. **Iterative Process**

The biggest feature Git offers is a faster release cycle. Git's capabilities facilitate an agile workflow where developers share small incremental changes more frequently in forms of sprints. Changes can be pushed down the developement pipeline into production. These small victories help companies succeed competitively with their customers and productively with their developers.

7. **Configuration**

Git is easy to configure. Developers can set up their system to deploy the most recent commit from the developement branch to the test server whenever antyone merges a pull request into it. This allows for automation and peer review, which reduces risk and and increases confidence as you deploy your chanfges into production with certainty. 

**References**

- [Git Source #1](https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/)
- [Git Source #2](https://www.atlassian.com/git/tutorials/why-git)
- [Git Source #3](https://www.atlassian.com/git/tutorials/what-is-git#performance)
