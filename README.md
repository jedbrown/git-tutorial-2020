# Git Tutorial

* Where: [DLC 1B70](https://calendar.colorado.edu/discovery_learning_center)
* When: [Friday, Feb 7 at 10-11:30](https://calendar.colorado.edu/event/git_tutorial)
* Who's invited: Everyone!
* What to bring: your laptop, with or without Git installed

Git is a powerful system for managing individual and group projects,
including source code and papers.  We will introduce everyday Git
functionality as well as common workflows for individual, small-group,
and community projects.  In addition to contributor roles like preparing
and revising pull requests, we will also explore integrator roles such
as reviewing, merging, and release/branch management, as well as related
services.

## Group activity

* Clone my repository
```
    git clone https://github.com/jedbrown/git-tutorial-2020
```
* Fork my repository and add your fork as a remote
```
    git remote add yourusername https://yourusername@github.com/yourusername/git-tutorial-2020
```
* Pick some neighbors and choose a group name

* Edit `groups.csv` to add yourself (with your group name)

* Commit your changes
```
    git add groups.csv
    git commit
```
* Push to your repository
```
    git push yourusername master
```
* Nominate one of your group members as "integrator" and make a pull
  request to their repository.

## Resources

* [Official site](https://git-scm.com/)
* [GitHub help site](https://help.github.com/en)
  * [Set up Git](https://help.github.com/en/github/getting-started-with-github/set-up-git)
  * [Connectigs to GitHub with SSH](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
* [Git Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html)
* [Learn Git Branching](https://learngitbranching.js.org/) (interactive/game)
* [Git for Computer Scientists](https://eagain.net/articles/git-for-computer-scientists/)
* [gitworkflows(7)](https://git-scm.com/docs/gitworkflows)
![](https://cucs-hpsc.github.io/fall2019/git/simplified-gitworkflows7.png)
