# 代码提交规范
##如何提交代码
* 归属项目的commiter可以直接提交代码，按照git flow进行。
* 其他人通过fork到自己代码库并提交pull request的方式进行。

##提交代码的时候如何写描述信息

在代码commit的comments里面描述如下信息：

1. 为何提交 分为new feature或者bug fix，并带上需求编号或者bug编号
2. 简要描述 因为具体什么原因修改
3. 详细描述 具体修改了什么内容
4. 所用时间

例如:
```[bug fix #102] 修改首页面样式
1. xxx
2. xxx
3. xxx
use 30 min```

##如何进行代码review
* 开发小组的team leader必须组织对所有commit和PR的代码评审，并从中总结出代码规范。
* 代码评审采取在commit上进行comments的方式。
* 评审者在comments中给出具体意见，如果无意见也需要写一个”read it”

