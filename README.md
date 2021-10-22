# repo

Repo is a tool built on top of Git.  Repo helps manage many Git repositories,
does the uploads to revision control systems, and automates parts of the
development workflow.  Repo is not meant to replace Git, only to make it
easier to work with Git.  The repo command is an executable Python script
that you can put anywhere in your path.

# 使用方法：

## 准备repo (首次未安装repo时需要)


cd repo-tool

cp repo /usr/local/bin/repo

chmod a+x /usr/local/bin/repo

## 初始化仓库方法

repo init -u https://x.x.x.x -m test.xml

## 同步所有源码

repo sync

如果需要看详细的输出，可加入-v选项：

repo sync -v
