# 重新组织项目时 ui-common 安装失败

删除ui项目下的ui-common包，然后在ui项目下执行一下命令

```
git rm ui-common
git submodule add --name ui-common -f -b master URL
```



