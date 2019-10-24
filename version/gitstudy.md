###  git
* 工作区

      写代码
* 暂存区

      打算提交还没提交临时存储的地方
* 本地库

      历史版本
      
<工作区>---->git add  <暂存区>---->git commit <本地库>

###  git和代码托管中心
* git
        维护本地库
* 代码托管中心
    1. 网络托管(外网)
            维护远程库
            github、码云 
    1. 本地托管(局域网)
            gitlab
            
```
团队本地库A————>push 远程库  (把本地内容推送到远程库）

团队成员本地库B————>clone 远程库A （将远程库内容下载到）本地库B --->对本地库B代码修改 push 到远程库 
本地地库成员A加入到（团队） 本地库A 对远程库进行 pull 拉取到团队 

团队外部人员----->fork 远程库A （将远程库A内容下载到）远程库C --->对远程C---->clone到  团队外部人员 本地库C 
团队外部人员修改代码 push到远程库C  远程库C ----> pull request 请求 --->审核 ---> merge 远程库A
```

### 基本命令
* git init 

        初始化工作区
* git staues

        查看工作区或暂存区状态
* git add filename.

        将文件放在暂存区
* git commit file.

        将暂存区数据提交到本地仓库

### 项目级别签名
* git config user.name name
    
* git config user.email email


### 系统级别签名
* git config global user.name name
    
* git config global user.email email

        一般使用系统级别签名 两个都设置使用，执行项目级别签名命令,
        会在.git目录生成config。
