# GIT
### Deeper understanding of GIT:

Great course can be found [here](https://missing.csail.mit.edu/2020/version-control/)

### Rebase:

If your branch is behind master and the changes don't impact your branch, rebase!

```shell
git fetch
git rebase origin/master
git pull
git push
```



### Clone Repo but change name

Say you want to clone a repo but you have a similar named repo or just want an easier name to remember. You can clone it down but use the name you want like so:
```shell
git clone https://github.com/sferik/sign-in-with-twitter.git signin
```

