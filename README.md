## 提取wireguard 


#### 访问 https://你的团队名.cloudflareaccess.com/warp 


#### 登陆后按F12,进入控制台輸入以下内容即可获取token,刷新網頁重複操作可刷新token 


```
console.log(document.querySelector("meta[http-equiv='refresh']").content.split("=")[2])
```

#### 登录github进入仓库,创建代码空间 ####


#### 创建完成后进入，在终端输入 ./warp.sh -T 复制的token


#### 可能会遇到401错误,那就刷新一次token再次尝试即可
