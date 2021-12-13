## ngrok for pierced 原项目-https://github.com/open-dingtalk/pierced   

### 已知；*.vaiwan.com 使用钉钉的CDN   

### 且外网可访问   

### 那我们可以 ngrok for pierced + web 用自己电脑提供各种程序(网站+下载+各类服务) + 正常域名反代   

#### 玩法1 - 通用；   
##### 下载https://github.com/open-dingtalk/pierced   
##### cd切换到 ~/windows_64 目录执行 ding -config=ding.cfg -subdomain=二级域名 端口  
##### 使用nginx或者其他 创建一个网站或者其他，   
##### enjoy!!!   

#### 玩法2 - 下载；   
##### 下载本仓库   
##### 修改 ~\resources\app\dist\electron\static\data.json 修改 subdomain 二级域名   
##### 运行 任意门.exe 添加文件和文件夹   
##### enjoy!!!    

## 二级域名 并不需要你去哪里申请 填你自己喜欢的词组数字 如果和其他人有冲突会导致你的域名无法正常访问；
