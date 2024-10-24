# demo-kbuild

## Overview
This demo-project showing how-to use KConfig in own project. [See article](https://habr.com/ru/articles/515398/)  
Simple script show information for last logins. It can forward output to current console or to file. Show last info for all user or for current-only.

To run KConfig you need KConfig interpritier in system(for example, kconfig-frontends project).

## Using
First clone repo:
```bash
git clone https://github.com/skif-web/demo-kbuild.git
```

Next run KConfig for configuring:
```bash
cd demo-kbuild
kconfig-mconf KConfig
```

Last step: run script to test:
```
./getLast.sh
```
