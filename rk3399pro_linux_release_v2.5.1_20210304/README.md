本压缩包内包含一个 .repo 目录,解压之后,在当前目录下执行以下操作

```
.repo/repo/repo sync -l
.repo/repo/repo sync -c --no-tags
.repo/repo/repo start firefly --all
```

后续可以使用以下命令更新 SDK
```
.repo/repo/repo sync -c --no-tags
```

