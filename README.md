# git-deeplearing
#### git study deep today
#### 联系版本回退1
#### 联系版本回退2
#### git log 查看最近到最远的提交日志 可以加上--pretty=online 过滤输入日志
#### git reset --hard HEAD^ 回退上一个版本 
#### git reset --hard +commit id(前7位) 回退指定版本
#### git checkout --file 丢弃工作区的修改 
- file自修改后没有add 到暂存区 现在撤销修改回到版本库一模一样状态；
- file 已经add到暂存区之后，又做出修改，现在撤销修改回到添加暂存区之后的状态
#### git git reset HEAD file 可以吧已经add到暂存区的修改撤销，重新放回工作区
#### git rm file 版本库中删除改文件 commit