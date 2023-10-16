# 4 Getting familiar with Git and GitHub

## 4.1 Create / setup GitHub account

Here you can enter text and create inline citations[@Garcia2020] by using the bibtex plugin. Add your references in `references.bib`, and cite [@hoebelheinrich_nancy_j_2022_6769695] by adding the @refid inside brackets like this `[@10.1093/bioinformatics/btt113]`

You can also embed videos from a local source (with a relative path) or from an url (like youtube). To use a youtube URL, 
just attach the ID of the video to a youtube embedded video link: `https://youtube.com/embed/`. For example, the Elixir training video `https://youtu.be/oAD8FdGf8tI` has the ID `oAD8FdGf8tI`, so the final link would be:

```
![type:video](https://youtube.com/embed/oAD8FdGf8tI)
```

![type:video](https://youtube.com/embed/oAD8FdGf8tI)

!!! note "Note"

    Here you can put a note using admonitions.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


## 4.2 Installation of GitHub Desktop

## 4.3 Git User Interface in PyCharm, GitHub Desktop

## 4.4 Create account, project, change settings

## 4.5 Graphical overview of concepts and terminology

### What is a git repository

A project folder usually contains only the latest version of your files (in case of cloud storage you might have some file history). Such project folder can be converted into a *Git repository* (how to do so described in Section 4.6) if the folder will track changes in files and directories. In other words, a **Git repository** (or just **repository**) is centralized location of files and all changes made to the files.

### What is a fork

If several people work on the same project you would need to have shared access to the same Git repository. However, different people might have different level of experience and project owner might limit writing access to the project repository. How to contribute to the project in this case? You have to work on your *own copy* of the repository in order to make changes. In other words, you have to work on your **fork**.

<img src="../img/chapter_4/forking.png" alt="What is fork" width="200"/>

### What is a commit

Your repository (your file(s)) is in a certain state. Every change moves the repository to a new state. Every change added to the sequence of changes is called **commit**.

TODO: image from Trilogy

Every commit has:
- content - what?
- a message - why?
- an author - who?
- a timestamp - when?
- unique identifier - tracking number

TODO: image from Trilogy

### What is a branch

A sequence of commits (changes) is referred to as **branch**. A new branch can be created by branching off from a commit on another branch. A branch can also be understood as a named version of your repository.

TODO: image from Trilogy



### What is the difference between a *fork* and a *branch*?

1. Fork is a copy of a repository, branch is parallel version of a code within the same repository. 
2. Fork is independent from the original repository, if the original repository is deleted, the fork remains. Branch exists on specific repository, if it si deleted, branch is also deleted.
3. Fork is mandatory if you do not have writing access to an original repository. Branch is recommended when you start development of new feature (fixing a bug).
4. Changes made in fork are *proposed* to original repository via *pull requests*. Changes made in branch are *merged* into another branch on the same repository.

TODO: image from Trilogy (Quick recap)

## 4.6 Case study 0 - working with local repository