Github-Tutorial
Made by: Myron Leerdam & Miriam Kant 

## Step 1. Create a Repository
A **repository** is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a *README*, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

Your `hello-world` repository can be a place where you store ideas, resources, or even share and discuss things with others.
## To create a new repository

1. In the upper right corner, next to your avatar or identicon, click  and then select **New repository**.
2. Name your repository `hello-world`.
3. Write a short description.
4. Select **Initialize this repository with a README**.

![GitHub Logo](images/1.png)

Click **Create repository** :tada:

# Step 2. Create a Branch
Branching is the way to work on different versions of a repository at one time.
By default your repository has one branch named `master` which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to `master`.
When you create a branch off the `master` branch, you’re making a copy, or snapshot, of `master` as it was at that point in time. If someone else made changes to the `master` branch while you were working on your branch, you could pull in those updates.This diagram shows:
* The `master` branch
* A new branch called feature (because we’re doing ‘feature work’ on this branch)
* The journey that feature takes before it’s merged into master 

![GitHub Logo](images/2.png)

Have you ever saved different versions of a file? Something like:
* `story.txt`
* `story-joe-edit.txt`
* `story-joe-edit-reviewed.txt`

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our `master` (production) branch. When a change is ready, they merge their branch into `master`.

## To create a new branch
1. Go to your new repository hello-world.
2. Click the drop down at the top of the file list that says **branch: master**.
3. Type a branch name, readme-edits, into the new branch text box.
4. Select the blue **Create branch** box or hit “Enter” on your keyboard.

![Newbranch]!!!!!!!!!!!

Now you have two branches, `master` and `readme-edits`. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

## Step 3. Make and commit changes
Bravo! Now, you’re on the code view for your `readme-edits` branch, which is a copy of `master`. Let’s make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.
### Make and commit changes1. Click the `README.md` file.
2. Click the  pencil icon in the upper right corner of the file view to edit.3. In the editor, write a bit about yourself.
4. Write a commit message that describes your changes.
5. Click **Commit changes** button.

![commitchanges](images/3.png)

These changes will be made to just the README file on your `readme-edits` branch, so now this branch contains content that’s different from `master`.

## Step 4. Open a Pull Request
Nice edits! Now that you have changes in a branch off of `master`, you can open a *pull request*.
Pull Requests are the heart of collaboration on GitHub. When you open a *pull request*, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, whether they’re down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub Flow before working on larger projects.
### **Open a Pull Request for changes to the README**
*Click on the image for a larger version*

Step | Screenshot
---- | ----------
Click the  Pull Request tab, then from the Pull Request page, click the green New pull request button. | ![commitchanges](images/4.png)
(images/5.png)
Select the branch you made, readme-edits, to compare with master (the original). |  ![commitchanges](images/6.png)
Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit. | ![commitchanges](images/7.png)
When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button. | ![commitchanges](images/8.png)
Give your pull request a title and write a brief description of your changes. | ![commitchanges](images/9.png)
When you’re done with your message, click **Create pull request!**
> **Tip**: You can use emoji and drag and drop images and gifs onto comments and Pull Requests.

## Step 5. Merge your Pull Request
In this final step, it’s time to bring your changes together – merging your `readme-edits branch` into the `master` branch.

1. Click the green **Merge pull request** button to merge the changes into `master`.
2. Click **Confirm merge**.
3. Go ahead and delete the branch, since its changes have been incorporated, with the **Delete branch** button in the purple box.
 
 ![Deletebranch](images/10.png)
 
### Celebrate!
By completing this tutorial, you’ve learned to create a project and make a pull request on GitHub! :tada: :octocat: :zap:  

Here’s what you accomplished in this tutorial:
* Created an open source repository
* Started and managed a new branch
* Changed a file and committed those changes to GitHub
* Opened and merged a Pull Request

Take a look at your GitHub profile and you’ll see your new contribution squares!

If you want to learn more about the power of Pull Requests, we recommend reading the GitHub Flow Guide. You might also visit GitHub Explore and get involved in an Open Source project :octocat: 

> Tip: Check out our other Guides and YouTube Channel for more GitHub how-tos.
