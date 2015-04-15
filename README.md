###SWABTS
+ GIT - Understand the purpose of git
+ GITHUB/GIT - Fork and clone a repository


### Motivation / Why Should You Care?
+ Who here has used google docs before?
+ Github is the google docs of code. While there is a ton you can do with Github, today we’re just going to learn how to make a copy of a project located on Github.com and bring it down locally to your computer so you can work on it.
+ Git is a powerful version control system
+ Github gives you an online footprint of all your coding history. The first thing companies ask for when they interview you for a developer job is "what is your github profile"

### Lesson Plan
***Students should have a `development` directory created on their desktop where they keep all their work. If they don't, they need to make it.***
+ In Learn, go to the Student Directory lesson.
+ In Learn, go ahead and click the blue link at the top of the page with the name of the lesson.
  * Take you to Github.com page - the repository for this project
  * A repository is just a Github word for a project. 
+  Fork button in the top right corner of the page. 
  * Forking a repository is just like making a photocopy of a handout. There is always the master version of a handout, and then every student gets a copy to do their own work.
  * Forking it is making a digital copy from Flatiron School’s Github account to your own.
+ You should get a window that asks you to select where you want the forked version to go. 
  * Click your own account!
+ Github should then redirect you to a page with your username in the URL. Your account now has a copy.
+ But this repository still only exists on github.com. You can’t actually edit it on your computer and open it up in Sublime yet.
+ The next step is to clone this repository. Cloning a repository just means to take a copy from github.com and put it locally on your computer.
+ On the right hand column, you’ll want to look for the fork button, and make sure that it says HTTPS url.
  * If it doesn’t you’ll want to click the link below that says HTTPS to change the type of url.
+ Once you find it, you’ll want to copy the url.
+ In terminal, in your development directory, enter `git clone` and paste the url.
+ Terminal will prompt you to enter your username and password. * When you type your password, the words won’t show up, but i promise you’re typing.
+ Once it finishes, enter ls and you should see the new directory.

### Conclusion / So What?
+ Git and Github let you save your work on the cloud. If you constantly save your work and put it on Github, you will never lose your projects even if your computer breaks.
+ Github is a powerful way for developers to collaborate together and share code. 

### Hints and Hurdles
+ Make sure the students select `HTTPS` for cloning. They don't have SSH keys set up on their computer so that version of cloning won't work.