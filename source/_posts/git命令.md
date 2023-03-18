```
cd : d/myblog // 进入D盘myblog文件夹
$ git clone git@github.com:Aldia-Alex/Aldia-Alex.github.io.git 
//git@github.com:Aldia-Alex/Aldia-Alex.github.io.git为ssh协议生成的clone链接路径
```

```
git init有什么作用
git init 命令用于初始化一个 Git 仓库，将当前目录（或者指定的目录）转换为一个 Git 仓库。在执行 git init 命令后，Git 将在当前目录中创建一个名为 .git 的文件夹，用于存储 Git 仓库的所有信息，包括版本控制历史记录、分支信息、配置等等。

在一个目录中执行 git init 命令后，该目录及其所有子目录中的文件将成为 Git 仓库中的文件。Git 仓库可以跟踪和管理这些文件的修改历史，并可以在不同版本之间进行切换、合并和比较等操作，实现版本控制。

git init 命令通常在以下情况下使用：

在新项目中创建一个空白的 Git 仓库。
在一个已有的项目中添加版本控制功能，即将该项目转换为 Git 仓库。
在从远程仓库中克隆一个 Git 仓库到本地时，Git 会自动执行 git init 命令，将远程仓库克隆到本地并初始化为一个 Git 仓库。
执行 git init 命令后，还可以通过 .gitignore 文件来忽略某些不需要被 Git 跟踪和管理的文件和文件夹，从而使 Git 仓库更加清晰和简洁。
```

