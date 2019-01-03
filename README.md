实现本地连接使用git

Q&A
Q:github上不去或者网页打开不正常

A:在hosts文件中加入下列IP，保存即可生效
#github
192.30.253.113 github.com
192.30.253.113 github.com
192.30.253.118 gist.github.com
192.30.253.119 gist.github.com

74.125.237.1 dl-ssl.google.com
173.194.127.200 groups.google.com
192.30.252.131 github.com
185.31.16.185 github.global.ssl.fastly.net
74.125.128.95 ajax.googleapis.com

windows下路径为：C:\Windows\System32\drivers\etc\hosts 
Linux下路径：/etc/hosts