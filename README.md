# repo

Repo is a tool built on top of Git.  Repo helps manage many Git repositories,
does the uploads to revision control systems, and automates parts of the
development workflow.  Repo is not meant to replace Git, only to make it
easier to work with Git.  The repo command is an executable Python script
that you can put anywhere in your path.

使用方法：

## 准备repo

git clone git@10.240.219.129:lnv-openbmc/openbmc-lnv/lnv-devbranch/repo-tool.git

cd repo-tool

cp repo /usr/local/bin/repo

chmod a+x /usr/local/bin/repo

## 初始化仓库方法1 (http)
repo init -u http://10.240.219.129/lnv-openbmc/openbmc-lnv/lnv-devbranch/repo-manifest -m default.xml

## 初始化仓库方法2（git)
repo init --repo-url git@10.240.219.129:lnv-openbmc/openbmc-lnv/lnv-devbranch/repo-tool.git -u git@10.240.219.129:lnv-openbmc/openbmc-lnv/lnv-devbranch/repo-manifest.git -m default_with_git.xml

## Checkout源码
repo sync
