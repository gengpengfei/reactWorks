# reactWorks
***
本地开发环境解决跨域问题
使用creat-react-app创建的项目

在package.json中
加入 "proxy":"http://localhost:8080" （服务器端口8080）
请求的时候，就可以不带域名了直接 fetch（‘/login’）
***
