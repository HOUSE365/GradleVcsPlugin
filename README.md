Welcome to GradleVcsPlugin!
===================


**Gradle plugin** used to download source code from the **Version Control System**（**SCM**，***Source Code Management***）.

>***警告:***该项目为初始阶段.

----------


描述
-------------

该插件用于为基于Gradle的Android Studio项目提供构建过程中的源码下载支持。


 - 为Daily Build准备最新的源码，并记录与之相关的仓库、分支、版本、更改记录等信息。
 - 根据指定的Daily Build的源码信息重新准备与之相同的源码，用于Release Build/Variant Build。



> **类似项目:**

> -  [gradle-scm-plugin](https://github.com/nebula-plugins/gradle-scm-plugin)

> -  [gradle-release](https://github.com/researchgate/gradle-release)


> -  [gradle-release-plugin ](https://github.com/ari/gradle-release-plugin)

> -  [GradleVcsDependencyPlugin](https://github.com/alexvasilkov/GradleVcsDependencyPlugin)



>**不是轮子:**

> - 我们需要一个与Jenkins以及现有生产工具结合的构建/测试/发布工具链.主要目的是快速,简单的构建测试/正式/衍生版本.
> - 目前内部已有基于ANT的相关实现,在向Android Studio迁移过程中需要将该实现转换为Gradle.以保持我们现有的研发体系与规则不变.
