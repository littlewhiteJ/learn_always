# AWS-CLI简易使用方法
AWS是亚马逊提供的云存储服务 效果类似于远端访问一个文件系统 方便不同用户 不同设备间文件的传输存储分享等

虽然该服务允许使用其他第三方软件登陆操作 但使用官方提供的接口功能更全面 强大

如果只是进行简单操作 请左转[AWS Console](https://aws.amazon.com/console/)

## 安装
根据不同的系统执行不同的安装方法
### Windows
[windows64](https://s3.amazonaws.com/aws-cli/AWSCLI64.msi)
[windows32](https://s3.amazonaws.com/aws-cli/AWSCLI32.msi)

以上两个网址似乎需要**科学上网**

### Linux & Mac
```
	pip install awscli
```
关于[pip](https://pypi.org/project/pip/)

### From Github
如果使用Windows不支持**科学上网** 或使用Linux or Mac不喜欢pip:)

可以选择通过[Github](https://github.com/aws/aws-cli)下载源码并运行
```
	cd <path_to_awscli>
	python setup.py install
```

## 登入
安装完成后 我们打开它

并使用命令行登入

登入有多种方法
### 直接输入
输入命令
```
	aws configure
```
shell会弹回各种config 重要的就是前两行的
```
	AWS Access Key ID [None]:
	AWS Secret Access Key [None]:
```
可以认为就是用户名和密码

请最好使用复制粘贴以免输错

后面的
```
	Default region name [None]: us-west-2
	Default output format [None]: json
```
可以默认输目前我给出的

前者是默认选择的区域

后者是输出格式

### 其他方法
也可以写个config文件放到一些指定的目录

[具体操作](https://docs.aws.amazon.com/zh_cn/cli/latest/userguide/cli-multiple-profiles.html)

## 文件操作
### help
当不知道如何使用某些命令时候
```
	aws help
```
### ls
列出当前文件
```
	aws s3 ls
```

### cp
复制文件
```
	aws s3 cp [Source] [Dest]
```
**可以使用该命令进行文件传输**

### mv
移动文件 相当于剪切粘贴
```
	aws s3 mv [Source] [Dest]
```
**该命令较危险 详见Unix中mv介绍**

### sync
同步文件
```
	aws s3 sync [Source] [Dest]
```
**方便快捷的进行整体文件传输**

[其他相关命令](https://docs.aws.amazon.com/zh_cn/cli/latest/userguide/using-s3-commands.html)
