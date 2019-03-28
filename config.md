# 环境配置

## Git 下载 安装
https://git-scm.com/downloads

## NodeJS 下载 安装
http://nodejs.cn/download/

## VSCode 下载 安装
https://code.visualstudio.com/download


## 验证安装结果
1. `win + R` 调起运行输入`cmd`，回车  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/fsHT2oO0gCvx.png?imageslim)

2. `git --version`   
3. `node -v`  
4. `npm -v`  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/jlJzFera5M6Q.png?imageslim)

## 全局安装 Gitbook 和 gh-pages
```
npm install -g gitbook
npm install -g gh-pages
```

## 指定目录克隆文档
1. 右键 - `Git Bash Here`
2. `git clone https://github.com/NiXuebing/teddy.git` 回车
3. 第一次输入账号密码
4. 下载完成  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/vJWdCDsSx7eX.png?imageslim)

## VSCode 编辑
1. 打开 VSCode，打开文档目录
2. `Markdown` 语法编辑
3. 设置自动保存 `File - Auto Save`

## 编译 预览 发布
1. 打开终端 Terminal 
2. 编译 `gitbook build`, 有报错再试一次  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/uos7KnnsrAvc.png?imageslim)

3. 本地预览 `gitbook serve`, 打开 `http://localhost:4000` 本地预览，停止`Ctrl + C`  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/axFeRCy6GNQb.png?imageslim)

4. 发布线上 `gh-pages -d _book`, 每次发布前都重新进行一次`gitbook build`，确保修改生效  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/cBY41Ff1YARs.png?imageslim)

## 文档提交
1. `commit` - 提交日志 - 回车  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/yLmGiB3U5IuK.png?imageslim)

2. `push` - 推送到服务器  
![mark](http://pic-cloud.ice-leaf.top/pic-cloud/20190328/yyHenSjDR4nV.png?imageslim)

3. 两台电脑间操作，先进行`pull`同步
