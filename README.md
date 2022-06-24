# xp_CAPTCHA(瞎跑-白嫖版)

* 若要准确率更高，请用 https://github.com/smxiazi/xp_CAPTCHA （这个调用别人商业成熟的验证码识别接口）

**********

### 更新4.1 2022-6-24

* 大改版，强烈安装新版本

*********

### 说明
xp_CAPTCHA (白嫖版)
* 验证码识别
* burp插件
* 支持验证码返回包为json格式

*********
### 使用

<img width="1250" alt="image" src="https://user-images.githubusercontent.com/30351807/175553035-9c3ad8a8-397f-48af-acd3-9f6d3cc3e0bf.png">

<img width="1250" alt="image" src="https://user-images.githubusercontent.com/30351807/175553590-9702d872-26a3-4b87-8b3c-0b6a6831e4ab.png">

<img width="1204" alt="image" src="https://user-images.githubusercontent.com/30351807/175553779-103f90f5-2283-4022-ad32-87eee8443086.png">

<img width="1159" alt="image" src="https://user-images.githubusercontent.com/30351807/175554183-3e68d3e0-6345-4e17-bd93-d1517c431340.png">



### 安装

需要python3 小于3.7的版本

安装 `muggle_ocr` 模块（大概400M左右）
```
python3 -m pip install -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com muggle-ocr
```

![image](https://user-images.githubusercontent.com/30351807/115872316-3f4b6780-a474-11eb-8f25-a2de13274510.png)


运行 server.py 


![image](https://user-images.githubusercontent.com/30351807/115872339-470b0c00-a474-11eb-8339-109b82f464eb.png)


等待显示出 Starting server, listen at: 0.0.0.0:8899 访问 http://127.0.0.1:8899/ 显示下面界面即为正常。

![image](https://user-images.githubusercontent.com/30351807/115872365-4ffbdd80-a474-11eb-8be6-cd4150242d66.png)

linux 下安装可能会需要

![image](https://user-images.githubusercontent.com/30351807/115872401-58ecaf00-a474-11eb-9a1a-e933173585a7.png)

安装即可
```
yum install libglvnd-glx-1.0.1-0.8.git5baa1e5.el7.x86_64
```



