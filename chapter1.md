# git submodule

不需要更新 submodule 到最新的commit

```
git submodule init && git submodule update
```

需要更新 submodule 到最新的commit

```
git submodule foreach git checkout master
git submodule foreach git pull origin master
```



