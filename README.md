
# GradleVcsPlugin


----------


Gradle plugin used to download source code from the Version Control System.


>***警告:***该项目为初始开发阶段.


> **描述:**

>     用于在持续构建过程中的从VCS(包括Git,Subversion,Mercurial)上下载源码,并生成ChangeLog与VcsInfo信息.
>     ChangeLog:
>         记录本次从VCS下载的源码距上次构建的所有更新日志.
>         方便测试及其他相关人员了解版本更改信息以及测试回归.
>     VcsInfo:
>         记录本次从VCS下载的源码的仓库路径,分支,版本等信息.
>         通过该文件可以完整重构本次构建过程所使用的源码,用于在当前构建的版本测试通过后构建正式版本以及其他衍生版本.
