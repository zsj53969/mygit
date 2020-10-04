# git

1. 要明白这3个概念，工作区（working tree），暂存区（index /stage），本地仓库（repository），git跟不同的参数，比较不同的区间的版本。

* git diff：是查看working tree与index的差别的。
* git diff --cached：是查看index与repository的差别的。
* git diff HEAD：是查看working tree和repository的差别的。其中：HEAD代表的是最近的一次commit的信息。

2. 