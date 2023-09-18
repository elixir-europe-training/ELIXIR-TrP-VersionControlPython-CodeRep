# 4 Learn the workflow from case studies

We have now installed Git on our local machine, familiarised ourselves with the interfaces, and tested out a local repository. However, to realize more advantages of version control (e.g. collaboration, improving reproducibility), we will need to take it online.

This chapter will guide you through exactly how this is done, step by step, from simpler use cases to more advanced ones.

As discussed previously, there are a wide variety of hosting services. Here, only as an example, we use the well-known GitHub platform as our remote server. 

## 4.1 Starting a new single person repository

In this example, we will make a repository on GitHub and send our code to it, so that our local work is backed up online.

First, log in to GitHub. Click the "+" and then "New repository" on the top right corner.

![Create new repo](images/add-new-repo.png)

Then, give the new repo a meaningful name, and why not add a README file. Click the big green button at the bottom. Simple as that, we made a repository on GitHub.

ADD-IMAGE-IF-KNOW-WHAT-CODE-TO-USE

A very convenient feature of the online platforms like GitHub is that they allow us to make certain changes directly from the browser. For example, click into the `README.md` file, and then click on the pencil button on the right hand side:

![Edit button](images/edit-button.png)

Now we are in a text editor, and can make any changes we want to this file. Once finished, click the green "Commit changes" to save.

!!! info Note
    Why the "Commit changes", but not a simple "Save"? Remember, Git keeps a history for everything. By editing on from the browser, we have essentially done "saving the file", "stage the file" and "commit changes" with one step!

