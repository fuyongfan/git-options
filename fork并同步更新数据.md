- 地址
- fork的仓库： A
- 自己仓库： B
1. fork代码
在别人仓库点击 ‘ fork ’ ，将内容克隆到自己的仓库

2. 下载到本地
```
git clone B
```
3. 查看本地remote
```
git remote -v
```
4. 添加远程仓库
```
git remote add git-options A  
// git-options 为自定义名字
```
5. 跟新远程仓库通道
```
git remote update git-options
git pull git-options master
```
END
