# repo

Repo is a tool built on top of Git.  Repo helps manage many Git repositories,
does the uploads to revision control systems, and automates parts of the
development workflow.  Repo is not meant to replace Git, only to make it
easier to work with Git.  The repo command is an executable Python script
that you can put anywhere in your path.

使用方法：

## 准备repo

git clone https://gitlab.xpaas.lenovo.com/fangjj2/repo-tool.git

cd repo-tool

cp repo /usr/local/bin/repo

chmod a+x /usr/local/bin/repo

## 初始化仓库方法
repo init -u https://gitlab.xpaas.lenovo.com/fangjj2/repo-manifest -m Default_RR13.xml

## Checkout源码
repo sync -j 4
