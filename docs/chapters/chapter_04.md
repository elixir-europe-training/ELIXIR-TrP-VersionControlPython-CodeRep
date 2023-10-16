# 4 Learn the workflow from case studies

We have now installed Git on our local machine, familiarised ourselves with the interfaces, and tested out a local repository. However, to realize more advantages of version control (e.g. collaboration, improving reproducibility), we will need to take it online.

This chapter will guide you through exactly how this is done, step by step, from simpler use cases to more advanced ones.

As discussed previously, there are a wide variety of hosting services. Here, only as an example, we use the well-known GitHub platform as our remote server. 

## 4.1 Starting a new single person repository

In this example, we will make a fresh repository on GitHub, make some changes from the browser, and clone a local copy so that we can work on it offline.

!!! info Note
    If you already have a local repository, like we have done in the previous chapter, go to chapter 4.2.

### Create a repo on GitHub

First, log in to GitHub. Click the "+" and then "New repository" on the top right corner.

![Create new repo](images/add-new-repo.png)

Then, give the new repo a meaningful name (we will call it `learn-git`), and why not add a README file. Click the big green button at the bottom. Simple as that, we made a repository on GitHub.

![Create repo](images/create-repo.png)

### Made changes from the browser

A very convenient feature of the online platforms like GitHub is that they allow us to make certain changes directly from the browser. For example, click into the `README.md` file, and then click on the pencil button on the right hand side:

![Edit button](images/edit-button.png)

Now we are in a text editor, and can make any changes we want to this file. Once finished, click the green "Commit changes" to save.

!!! info Note
    Why the "Commit changes", but not a simple "Save"? Remember, Git keeps a history for everything. By editing on from the browser, we have essentially done "saving the file", "stage the file" and "commit changes" with one step!

![Commit change online](images/commit-change-online.png)

Here you can input a commit message to describe what changes you have made. Then click the green "Commit changes" button again, and all done.

### Clone the repo to local computer

For day to day coding and scripting, we probably still want to work locally on our computers with IDEs or more sophisticated editors. To do this in our new repository, we first need to make a local clone on our computer. This is very easy to do.

Go to the homepage of our repo on Github. Click the green "< > Code" button at the top right corner above the file list. Click on the "SSH" tab.

![Clone repo](images/clone-repo.png)

!!! info Note
    SSH is more secure than HTTPS. If you have set up your SSH keys successfully in the previous chapter, always try to use the SSH links.

Now there are several options:

- If you are working with GitHub Desktop, simply click on the link "Open with GitHub Desktop". You can choose where you want to keep the local copy.

![Clone GHD](images/clone-repo-ghd.png)

- Otherwise, copy the line of link (with the button on the right). Go to your preferred IDE and clone the repo there. ===Screenshots!===

- If you work with commandlines, go to the parent folder where you want the new repo to be copied into, and then use the `git clone` command (replacing `<some-parent-folder>` and `<your-github-id>`):

```bash
cd <some-parent-folder>
git clone git@github.com:<your-github-id>/learn-git.git
```

Look inside the `learn-git` folder. You have the new repo cloned onto your computer!

### Make changes locally and keep the remote updated

As you make new changes in this folder, you can make local commits just as you did in #3.6. As long as you are on a single branch, the only extra step to take to update the remote is "pushing". Here is an example:

===screenshots====


## 4.2 Setting up a new online repository for an existing local repository

Sometimes, we may have already written some code and created a local repository (like what we did in #3.6). Now we want to set up a remote repository and send our code to it, so that our local work is backed up online, and later be shared.

If you have followed through #4.1 as well, you will find this very familiar, except in some small details. 

### Create a repo on GitHub

First, log in to GitHub. Click the "+" and then "New repository" on the top right corner.

![Create new repo](images/add-new-repo.png)

Then, give the new repo a meaningful name (probably sensible to be the same as your local folder name). To make life simple, do NOT initialize or add any files.

!!! example "Exercise"
    What will happen if we initialized with, e.g. a README file?

    ??? success "Solution"
        The remote repo on Github will have the README file, while our local repo does not. On the other hand, remember that our local repo has some existing codes that the remote does not have. Therefore, as soon as we try to link the two together, there will be a conflict.

Click the big green button at the bottom. Simple as that, we made a repository on GitHub.

