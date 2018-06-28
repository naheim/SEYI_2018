# SEYI:Bidiversity Data Collection
Data collection is the not the main focus of the internship this year. Nevertheless, I want you to spend a few hours collecting some new data. The main beneficiary of this work is you, as you will develop a much better sense of where the data come from and what the sources of error/assumptions are. A secondary benefit is that tyou will also have more data to work with.

Much of the original data came from a project called the *Treatise on Invertebrate Paleontology*, which was a project started in the 1950s to provide an authorative guide to the genera of invertebrate fossils. Over the years, revisions of old volumes were made and new ones added. About 10 years ago, the project went online as the [Treatise Online](https://journals.ku.edu/treatiseonline). You will enter new data from newly published versions of the data from the Cephalapod and, if there's time, Decapod issues of *Treatise Oline*.

### Types of Data
* Stratigraphic ranges of genera
* Names of genera, including their authority
* Multiple linar body size measurements
* Metadata on the spcecimens measured, including species names

## Getting the Data Files
Below is the list of Excel files I've created. Click on the appropriate partner pair to download the file. Only one of you needs to download the file and upload it to a repository. (**NOTE:** I randomly assgned data collection partners...usint R, of course.)

* [Ameya & Shannon](cephAmeyaShannon.xlsx)
* [Ashli & Stephanie](cephAshliStephanie.xlsx)
* [Chris & Bella](cephChrisBella.xlsx)
* [Loc &Noah](cephLocNoah.xlsx)
* [Saket & Sriram](cephSaketSriram.xlsx)

Move the file you downloaded to a directory on your project page. You can put it in the main directory or make a new directory. It's up to you.

## Getting to Work

* Start adding data to the Excel file you downloaded and moved to your project repository.
* Use the online guide for naviagting the [texed-based](../cephTreatise.pdf) and [figure-based](../images/cephTreatiseFig.pdf) data collection proecesses. I will also give you a printed copy of this guide.
* When you are finished with your data colleciton session, make sure your Excel file is saved.
* Now you should use git to update your repository with your data file. To update your remote version of the repo, remember:

````sh
git add .
git commit -m "your commit message"
git push
```` 
* Over the weekend I will download your files and add them to the database!

<!--
## Forking the repository and making pull requests
In oder for you to add data to a spreadsheet and return the changes, you need to *fork* the SEYI_2018 repository to your GitHub account. [Here](https://gist.github.com/Chaser324/ce0505fbed06b947d962) is a more detailed description of forking and pull requests, but here is a short step-by-step guide.

* Go to the online home of the [SEYI_2018](https://github.com/naheim/SEYI_2018) repository. Once there click on the *Fork* button in the upper right. This will make a copy of the repository on your account.
* Open the terminal, and use the ``cd`` command to navigate to your ``git`` directory.
* Use ``git clone https://github.com/yourUserName/SEYI_2018``.

* You will want to make sure you keep your fork up to date by tracking the original "upstream" repo that you forked. To do this, you'll need to add a remote:

````sh
# Add 'upstream' repo to list of remotes
git remote add upstream https://github.com/naheim/seyibExercises.git

# Verify the new remote named 'upstream'
git remote -v
````
* The next steps are to make sure that your brach of the repository is up to date with changes made by others before you begin making changes. For now, there hanven't been any made, but we'll go through the processess anyway. In gernarl, whenever you want to update your fork with the latest upstream changes, you'll need to first fetch the upstream repo's branches and latest commits to bring them into your repository:

````sh
# Fetch from upstream remote
git fetch upstream

# View all branches, including those from upstream
git branch -va
````
* Now, checkout your own master branch and merge the upstream repo's master branch:

````sh
# Checkout your master branch and merge upstream
git checkout master
git merge upstream/master
````
### Now it's time to do your work
* Go to the *dataCollection* directory and start adding data to the Excel file with yours and your partner's names on it. (I randomly assgned data collection partners).
* Use the online guide for naviagting the [texed-based](../cephTreatise.pdf) and [figure-based](../images/cephTreatiseFig.pdf) data collection proecesses. I will also give you a printed copy of this guide.
* When you are finished with your data colleciton session, make sure your Excel file is saved.
* Now you should use ``git add .``, ``git commit -m "your commit message"``, and ``git push`` to update your remote version of the repo.
* Now, it's time to make a pull request. For your project repositories, you can just push your changes and they are automatically accepted because you are the 'owner'. However, because I am the owner of the main branch of the SEYI_2018 repository, you need to ask me to *pull* your changes in.
* To begin the pull request process you want to "checkout" your own master branch and merge the upstream repo's master branch:

````sh
# Checkout your master branch and merge upstream
git checkout master
git merge upstream/master
````
-->
## <a name="resources"></a>Resources
* [Using GitHub](https://github.com/naheim/seyibExercises/blob/master/GitTutorial/gitTutorial.md)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown)