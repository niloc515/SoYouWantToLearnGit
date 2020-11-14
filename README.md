So You Want to Learn Git
========================

Great! You've come to the right place! Here I will post a bunch of useful git/github resources and I encourage anyone who wants to contribute to do the same!

Lets start off by going over a couple of things real quick.



Introduction to Some Concepts
-----------------------------

### **Git, why should I care?**
[![Git logo][gitLogo]](https://git-scm.com)

Have you ever been writing a paper and ended up with a bunch of documents like *EssayDraft.dox*, *EssaySecondDraft.dox* *EssayFinal.dox*, *EssayFinalForReal.dox*, and as the caffeine wears off and 11:59 approaches *Essayasdklf;ajk;ekjahaskjd.dox*. 

Now your documents folder is a mess and you know that, but you did all this with a reason, each of those documents probably has something unique that you weren't quite willing to get rid of just in case you needed to go back to it. 

Wouldn't it be nicer to have the ability to go back to old versions but still only have one file? Wouldn't it be nice to have a system to write little messages about the changes that you made so you know what the differences between the version are? Thats where Git comes in.

### **Ok, tell me more**

Git is a piece of [version control software](https://www.atlassian.com/git/tutorials/what-is-version-control) originally released in 2005 that allows you to do just that! With Git you can save the changes you make to files and folders in small pieces called **Commits**. You can use these commits to look at the changes made in various versions of code, keep track of how things changed, and attach messages to them so you know at a glance what changes were made in that commit.

Git even allows you to experiment with new versions of your files with out affecting your "good copy" through **Branches**. But I'll let you learn more about that on your own later 😉

### **Cool! so Github is like Git right?**
[![Github logo][githubMark]](https://github.com)

Github is a website made specifically for storing the packages of commits and branches that Git makes called **Repositories** or **Repos** for short. You can do some git things on github (like making new branches and some basic file editing) but github should be treated more like a file storage server. Working with Git and Github does have some cool advantages, such as [Github pages](https://pages.github.com) and others that I would whole heatedly encourage you to look at once you are more familiar with git. Remember, its entirely separate from git and you can use git just fine on your personal computer without it.

### **Alright! How do I get started?**

I'm not going to be the best person to explain everything for you in depth, but now that I've hopefully answered some questions you might have, I'll start off with some learning resources and some good places to really get your bearings.

Courses
-------

- **[DataCamp Introduction to Git](https://www.datacamp.com/courses/introduction-to-git)** 
    The first chapter of the DataCamp git course provides an interactive look at all the things that makes Git a great tool to use. And if you want to do more of the DataCamp course, the [Github student pack](https://education.github.com/pack) provides you with 3 months of DataCamp access for free!

- **[Udacity Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123)**
    This Udacity course is very good at touching on git and github and even has good opportunity and instructions on getting some hands on experience! This one is my personal favourite and best part is that it is free!

### Videos

- **[FreeCodeCamp Git and GitHub for Beginners - Crash Course[1:08:29]](https://www.youtube.com/watch?v=RGOj5yH7evk)**
     An all round overview of  Git and github, a great whirlwind introduction to everything Git and Github covering everything from making an account, to setting up SSH keys and forking other repositories. I would use this mainly to supplement other courses or as a refresher once you have already use Git/Github a bit

- **[Fireship Git It? How to use Git and Github [12:18]](https://www.youtube.com/watch?v=HkdAHXoRtos&list=WL&index=28)** 
    Not a full course, but a good overview of Git and Github for those looking to use specifically Visual Studio Code as their main IDE.

---

This is a lot of information, Ain't nobody got time for that!
------------------------------------------------------------

I completely understand, Git has a pretty steep learning curve and trying to take this in all at once can be more than a little overwhelming. That is why there is plenty of cheat sheets out there for quick reference from [github](https://education.github.com/git-cheat-sheet-education.pdf), [Atlasian](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet), and [git-tower](https://www.git-tower.com/blog/git-cheat-sheet/) and for the most part, thats all you really need when using git! 
If you want to go deep into git, [Here is the official docs](https://git-scm.com/docs)

How about some quick references right here?
-------------------------------------------

Here you go!

| Task                                                | How to                                               | Example                                                                     |
|-----------------------------------------------------|------------------------------------------------------|-----------------------------------------------------------------------------|
|Make a new repository                                | `git init`                                           |`git init`                                                                   |
|Clone a repository                                   | `git clone [URL]`                                    |`git clone https://github.com/Marak/faker.js.git`                            |
|Check on the staging area                            | `git status`                                         | `git status`                                                                |
|Add an item to the staging area                      | `git add [NAME OF FILE]`                             | `git add index.html`                                                        |
|Add all items with changes to the staging area       | `git add .`                                          | `git add .`                                                                 |
|Add all items of a specific type to the staging area | `git add *.[FILE EXTENSION]`                         | `git add *.js`                                                              |
|Remove a file from the staging area                  | `git reset HEAD -- [PATH TO FILE]`                   | `git reset HEAD -- index.html`                                              |
|Create a new commit                                  | `git commit -m "[YOUR COMMIT MESSAGE]"`              | `git commit -m "Fixes bug where logo didn't load properly"`                 |
|Create a and switch to a new Branch                  | `git checkout -b [NAME OF NEW BRANCH]`               | `git checkout -b newFeature`                                                |
|View list of all branches                            |`git branch`                                          |`git branch`                                                                 |
|Change current branch                                |`git checkout [BRANCH YOU WISH TO CHANGE TO]`         |`git checkout main`                                                          |
|Merge a branch into the current branch               |`git merge [BRANCH YOU WISH TO MERGE]`                |`git merge newFeature`                                                       |
|Set a remote for your local repo                     |`git remote add [NAME FOR REMOTE] [ADDRESS OF REMOTE]`|`git remote add my_awesome_new_remote_repo https://github.com/user/repo.git` |
|Keep your local repo in sync with the remote         |`git pull`                                            |`git pull`                                                                   |
|Mirror your commits to the remote                    |`git push [NAME OF REMOTE] [NAME OF BRANCH]`          |`git push origin main`                                                       |



[gitLogo]: https://git-scm.com/images/logo@2x.png "Git Logo"
[githubMark]: ./images/GitHub-Mark-120px-plus.png "Github logo"