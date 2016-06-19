# express搭建博客步骤
## 1.找到自己想要新建项目的文件夹
```
1.npm install -g express-generator
```
```
生成一个项目
2.express -e myblog(这里的myblog名字是自己取的文件夹名字)
```
```
进入生成的项目并安装依赖
3. cd myblog && npm install
```
```
设置环境变量并启动服务器 在命令行中执行此命令
4.SET DEBUG=zhufengpeixunblog:* & npm start
```
```
5.在浏览器里访问 http://localhost:3000 就可以显示欢迎页面
```
### <font color=red>以上5步我们就用express生成器生成了一个使用ejs模板的示例工程。</font>