**This is a toy Git repository with the aim to test some features of Git, in particular the collaborative aspects.**

__Here are the steps to participate to this toy example :__

- [Fork this repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
- Clone it locally, and link it to the master repository
`git remote add upstream https://github.com/AlexisArnaud/R_tests.git`
- Uptade your fork with latest changes form the master repository (fetch and merge) 
`git pull upstream master`
- Write your name inside the file `names.txt`.
- Commit your changes
`git add names.txt; git commit -m "Add my name to the file names.txt"`
- Push your commit (on your fork)
`git push origin master`
- Create a [Pull Request](https://help.github.com/articles/creating-a-pull-request/) (that will be reviewed and accepted by the master of this repository)
