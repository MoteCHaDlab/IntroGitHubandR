# Introduction to GitHub and R

 For use by Mote's Coral Health and Disease lab members. 
 
## Repository Description

 Repository with information and resources for getting started using GitHub and R, along with the best practices for working in the MoteCHaDLab GitHub organization. 
 
 Disclaimer: I (Sara) am fairly new to collaborating on code using GitHub. This will be messy and we will learn together. Google is your (our) best friend.
 
 Responsible member(s): Sara Williams, swilliams@mote.org

## Repository Organization

Below: Getting started with GitHub information and links

R folder: Getting started with R and some useful code (to be added later)

## Getting Started with GitHub

### First Steps

1. Make a GitHub account if you don't have one already. https://github.com/

  a. If you still have a student email, you can get github pro for free: https://education.github.com/discount_requests/student_application

2. Send me (swilliams@mote.org) your account name so that I can add you to the lab's GitHub Organization (MoteCHaDlab)
  
3. Download and install GitHub Desktop https://desktop.github.com/

4. Check to make sure you have git on your computer
  a. on a mac, open up the terminal
  b. on a windows pc, open up the command prompt
  c. type 'git version' and enter, it should return your version if you have git.
  d. if you don't have git, https://github.com/git-guides/install-git 
  
### ... So what exactly are Git and GitHub?

**[Git](https://git-scm.com)** is a free and open source distributed version control system. Version control lets you track changes and go back to previous versions of files. You can recover your code after making a mistake and go back to a known good state. Now what about **[GitHub](https://github.com)**? It's a for-profit company / website and cloud-based service that helps you store and manage your code, as well as track changes (using git). It makes it a lot easier for individuals and teams to use Git for version control and collaboration since it is (mostly) user friendly. 

You can use git and github through the terminal/command prompt, BUT **[GitHub Desktop](https://desktop.github.com/)** exists and provides a nice, easier to use interface. 

### Git-ting the lingo:

* Repository: The source code for a project. *Local* repository is where you edit your code (usually on your computer) and the *remote* repository is the place you send it after you're finished (i.e. GitHub).
* Commit: kind of like saving a file. It's a collection of content - anything you want to add. Goes with a commit message that explains what you changed
* Branch: version of the repository that diverges from the main working project where you can make your own commits without interrupting others working on the same repository. You can later *merge* the branch back in.
* Clone: make a copy of the target repository
* Fetch: gets the most updated version of a repository from the remote source
* Origin/Master: Default name for the default branch of your root directory, so like the initial location of everything in the repository from when it was created.
* Pull request: Ask the person in charge of the branch to include your code - let other know about changes you've pushed to a branch in a repository
* Fork: create an entirely new repository by duplicating the repository being forked
* HEAD: points to the most recent commit on the current branch
* Merge: joins two or more commit histories

#### Forking vs. Branching?

Think of forking as divergent evolution of code and branching as convergent evolution of code... this metaphor mostly works. 

When you *fork* you are creating an entirely new repository by duplicating the repository being forked. You create a new origin/master. Forks are best for when the you intend to split and create an independent project, which will never reunite with its parent. Unless you are the one developing a tutorial/example repository in the organization, you should fork them. 

*Branches* are sort of like 'construction zones.' They are used to create a temporary place to work through a feature (like a code notebook) and make some changes that you plan on merging back with the origin branch later. Branching is something that you should consider using when actively collaborating on a code repository with a team.

### Basic workflow with GitHub

1. Navigate to the repository you want to work on in github desktop
2. **Fetch origin**: check to see if any changes were made by others and committed to the remote repository. Kind of like a refresh button.
3. **Pull origin**: This updates your local repository to be the same version as the remote repository. So if a collaborator made changes, your code and files will now be updated with the new commits. 
4. Write your own code or make changes to existing code in the repository. Save the file.
5. Go back into github desktop and you will see that it shows that you made changes and also shows what changes you made. 
6. Write a **commit message** in the space provided (bar with "Update README.md" next to an icon of your github profile picture, below the list of changed files on the left). This can be as short or as informative as you want.
7. Click **Commit to main**
8. **Push origin**: Updates the remote repository with you local changes.

#### How to resolve merge errors/conflicts

Ok, so here is where google and a bit of luck are your two best friends. Explaining how to resolve errors is a bit above  my experience level. 

A helpful youtube video on the subject: https://www.youtube.com/watch?v=-Q-WIOH1XSA.

If two people are editing the same file at the same time (in the same location(s)), then you will run into conflicts when one person commits after the other. The problem occurs when the 2nd person tries to merge into the master. Git will insert some pointers to where the merge conflicts are in the file. YOU have to go in and edit the file... remove the indicators, edit it to the appropriate changes, and then re-commit and merge. 

## CHaD Lab Organization GitHub Rules and Best Practices

1. Communicate often and well with your repository collaborators.
2. In the main README.md for a repository:

    * At the top, list the names and contact info for the main person responsible for the repository
    * Include an outline/organization scheme for what the repository contains and where to find it. Consider listing out file names and what they are here as well.
    * Keep a change log that you update every time you make major changes
3. **Fetch, Pull, Save your work, and Push often!**
4. If you are not working on the project specific to a repository, do not branch it. However, you may fork it in order to learn from and use the code. Admins for the repository should manage access of members in order to avoid issues.
5. Keep a repository private unless it is in its final publication form UNLESS all collaborators agree to make it public. 
6. Be respectful of others' data. If you have sensitive data, consider using the .gitignore file to exclude the file or not putting the repository in the shared lab organization. 
7. Comment your code. It doesn't have to be perfect or a novel, and you can go back and edit later, but someone should be able to look at your code and have a *good enough* idea of what you are doing.
8. The first chunk of every Rnotebook should contain the R packages used in the code. 

## Updates log

* 04/01/2021: Sara created this repository and learned a whole lot more about github doing so.
* 04/02/2021: Sara made a small change to readme and made repository public so that lab members not yet in the organization can see the files and learn how to be added to the lab's GitHub organization.
