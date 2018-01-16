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
![image](https://github.com/AmberGN/images/raw/develop/工作流程图.jpg)

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

##### 4. 建好仓库后，需要clone到本地
对于自己新建的仓库，新建成功后，点击页面中的【set up in desktop】既可以clone至本地，并通过客户端GitHub打开。

![image](https://github.com/AmberGN/images/raw/develop/8.jpg)

对于其他人的仓库，通过以下页面方式
点击【clone or download】
![image](https://github.com/AmberGN/images/raw/develop/5.jpg)

点击后出现下拉选项，点击【open in desktop】

![image](https://github.com/AmberGN/images/raw/develop/6.jpg)

##### 5. 在仓库中新建分支

点击当前分支

![image](https://github.com/AmberGN/images/raw/develop/9.jpg)
找到目标分支或创建新分支
![image](https://github.com/AmberGN/images/raw/develop/11.jpeg)
分支命名规则详见[《pull request规范》](https://github.com/sibbay-ai/public/blob/master/pull%20request%20规范.md)


##### 6. 在仓库中新建文件并编辑

找到本地仓库的地址并打开文件夹，可以在其中新建、修改、删除文件。
![image](https://github.com/AmberGN/images/raw/develop/14.jpg)

##### 7. 将改动提交至分支和云端github库中

改动后的文件会在列表中展示，这时在下方commit处正确命名，详见[《pull request规范》](https://github.com/sibbay-ai/public/blob/master/pull%20request%20规范.md)

修改好后点击commit to [对应分支名]
![image](https://github.com/AmberGN/images/raw/develop/12.jpg)

这时文件已经归类到对应的分支了，这时需要将本地仓库同步至云端

![image](https://github.com/AmberGN/images/raw/develop/13.jpg)

##### 8. 新建pull request

在网页端github的【pull request】分页中点击【new pull request】后，通过比较分支，来创建新的pr

![image](https://github.com/AmberGN/images/raw/develop/100.jpg)
严格按照规定格式命名，需要关联issue
![image](https://github.com/AmberGN/images/raw/develop/101.jpg)

## 四、交付件格式
通常来说，非代码类的一切提交物均以md文件（markdown）格式提交，可以在文本中包含链接
markdown编辑器可以自行选择，推荐markdown pad、有道云笔记
![image](https://github.com/AmberGN/images/raw/develop/111.jpg)