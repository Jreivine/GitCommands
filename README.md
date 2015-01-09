# Git Commands

### Creating a repository for the <b>1st time </b>!

``` sh
$ touch README.md # initialize your git repository locally
$ git init
$ git add README.md # adds everything changed from local to staging
$ git commit -m "first commit" # commits everything in staging to be pushed to GitHub
$ git remote add origin https://github.com/Jreivine/GitCommands.git
$ git push -u origin master
# put in username & password
```

### When adding on your repository on line with changes
``` sh
$ git add .
$ git commit -m "what has changed"
$ git push
# put in username & password
```