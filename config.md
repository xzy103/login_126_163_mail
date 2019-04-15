# 如何配置chromedriver和selenium

## 第一步 下载并安装chrome
下载地址：https://www.google.cn/intl/zh-CN/chrome/  
进入界面后直接点`下载Chrome`即可，下载好后安装。

## 第二步 查看chrome浏览器版本
打开浏览器，在地址栏输入`chrome://version/`  
新跳出来的界面第一行就是浏览器的版本，例如我的是`73.0.3683.75 (正式版本)`  
记住这个版本号。

## 第三步 下载chromedriver
下载地址：http://npm.taobao.org/mirrors/chromedriver/  
选择和自己浏览器最接近的版本，例如我应该选的是`73.0.3683.68`  
进入后选择对应的系统，例如`chromedriver_win32.zip`表示windows系统。

## 第四步 配置chromedriver环境
右键单击chrome浏览器图标，选择`打开文件所在的位置`  
例如，我打开以后的位置是`C:\Users\13426\AppData\Local\Google\Chrome\Application`  
接着，将刚才下好的`chromedriver.exe`文件复制到这个文件夹下。  
同时，点击地址栏，复制这个文件夹的地址。  
右键`此电脑`或`我的电脑`→`属性`→`高级系统设置`→`环境变量`  
在弹出的`环境变量`窗口中，上方是用户的变量，下方是系统变量，找到下方系统变量中的`path`，双击。  
选择`新建`，并将刚才复制的地址粘贴到此处，然后点击`确定`退出各个窗口。  
重启电脑就ok了！

## 第五步（可选） python安装selenium
如果装得有python3.5+d的话，可以安装selenium库。  
打开cmd，输入`pip install --user selenium`即可。  


--------------------------------------------  

讲解完毕！