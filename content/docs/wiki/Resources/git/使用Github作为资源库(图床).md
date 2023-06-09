---
weight: 300
title: "使用Github作为资源库(图床)"
---

## Tips
https://raw.githubusercontent.com 域名需要修改dns或vpn才能访问
  

## 1. 创建一个资源库专用Repository
![](/images/202304171650868.png)  
  

## 2. 生成免密token
点击用户头像 -> Settings -> Developers Settings;  
创建新token: Personal access tokens -> Tokens -> Generate New Token  
![](/images/202304171653555.png)  
  
过期时间选择永不过期; 权限范围勾选repo所有权限.  
 ![](/images/202304171655474.png)  

创建生成token, 注意保存token, 关闭页面后无法再查询.  
  

## 3. 安装 PicGo
[Github/PicGo](https://github.com/Molunerfinn/PicGo)  
  

## 4. 配置 PicGo Github
![](/images/202304171701090.png)  
  

## 5. 使用CDN(jsdelivr)加速资源访问(Deprecated)
模版:  
```bash
https://cdn.jsdelivr.net/gh/${username}/${repository}/path/to/file.txt
```
eg:  
```bash
https://cdn.jsdelivr.net/gh/nctsc/resources/images/202304171701090.png
```
  

## 参考文档
[使用Github+picGo搭建图床](https://zhuanlan.zhihu.com/p/489236769)  

