## git

​	git是一个开源的分布式版本控制系统，可以有效、高速的处理从小到大的项目版本管理系统，能更好管理我们的代码，可以实现远程存储及更新

### 建立本地仓库

创建文件夹

打开git Bash Here->git init git初始化仓库，并将代码复制粘贴至仓库

 ->git status 查看仓库，发现复制进来的文件显示为红色，表示待添加到本地仓库

git add ‘项目文件’或git add .添加到本地仓库

gitstatus显示文件为绿色说明已添加到本地仓库

git commit -m '修改说明' 表示提交，-m后添加提交说明，

#### 去GitHub创建自己的Repository

点击Create repository，一步一步执行下去即可，创建成功后拿到创建的仓库的https地址

将本地仓库关联到github上

git remote add origin 地址

#### 上传至远程仓库

git push -u origin master

