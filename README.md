解决Git速度慢的问题
https://www.zhihu.com/question/27159393 

例如科学上网软件的端口是15236，则可以设置如下代理给git
git config http.proxy http://127.0.0.1:15236
git config https.proxy https://127.0.0.1:15236

想要取消代理
git config --unset http.proxy
git config --unset https.proxy

