# 非技术人员版小白ICP流程介绍
## 一、准备工作
- 注册GitHub账号
   - [官网地址](http://github.com/)
   - [参考步骤](http://jingyan.baidu.com/article/455a9950abe0ada167277864.html)
- 下载安装GitHub客户端，[下载地址](https://desktop.github.com)


## 二、进行小白贡献者认证
#### 流程图如下
![image](https://raw.githubusercontent.com/AmberGN/images/develop/认证流程图.jpg)

## 三、工作流程与部分关键操作说明

##### 1.总体工作流程图
![image](https://github.com/AmberGN/images/raw/develop/工作流程图.png)

#### 部分关键操作：
##### 2. 在小白public库中新建issue
步骤如下：

点击【new issue】按钮
![image](https://github.com/AmberGN/images/raw/develop/1.jpg)

issue的描述为考核内容，考核内容如下表所示

项目 | 结果
---|---
申请者 | GitHub账号
mentor | github账号
ICP流程测试 | pr链接及size数量
ICP理解测试 | issue链接
ICP协作测试 | 申请者耗时（小时）/协作者耗时（小时）
issue响应速度 | 分钟/次

当所有测试完成后，汇总该表，在comment中展示出来
![image](https://github.com/AmberGN/images/raw/develop/2.jpg)

更多详细规则详见[《issue规范》](https://github.com/sibbay-ai/public/blob/master/issue%20规范.md)

##### 3. 在自己当GitHub中创建一个新的仓库（repository）
这里描述网页端建库的方式：
找到网页端右上角的+号，选择后点击【new repository】

![image](https://github.com/AmberGN/images/raw/develop/3.jpg)
点击后，进入下图页面
可以随意命名，权限选择public就可以，填写完成后点击【create repository】

![image](https://github.com/AmberGN/images/raw/develop/4.jpg)

##### 4. 在仓库中新建分支

可以提前新建分支，也可以在提交commit时新建分支
分支命名规则见[《pull request规范》](https://github.com/sibbay-ai/public/blob/master/pull%20request%20规范.md)

![image](https://github.com/AmberGN/images/raw/develop/网页端添加添加新分支.png)


##### 5. 新建markdown文件或上传本地文件

入口如图所示

![image](https://github.com/AmberGN/images/raw/develop/创建新文件和上传文件入口.png)

不论是创建新文件还是上传本地文件，都需要进行commit操作

![image](https://github.com/AmberGN/images/raw/develop/commit规则.png)

此时也可以进行新分支当创建，分支创建规则和commit命名具体规则详见[《pull request规范》](https://github.com/sibbay-ai/public/blob/master/pull%20request%20规范.md)



##### 6. 新建pull request

commit成功后直接跳转至以下页面来新建pr，具体操作如下所示
![image](https://github.com/AmberGN/images/raw/develop/新建pr.png)

##### 7. 修改更新文件

将文件push至原文件相同分支下即可


##### 8. 删除分支

当pr已被合并（merge）后，需要将该pr曾经对应对自分支删除

![image](https://github.com/AmberGN/images/raw/develop/删除分支.png)


## 四、交付件格式
通常来说，非代码类的一切提交物均以md文件（markdown）格式提交，可以在文本中包含链接

纯图片视频类可以直接通过上传本地文件进行上传

