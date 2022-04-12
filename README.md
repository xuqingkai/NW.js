3. 在当前路径下新建index.html,添加测试代码。（用它作为程序的默认页面）


<span style="font-family:Microsoft YaHei;font-size:12px;"><!DOCTYPE html>
<html>
    <head>
        <title>node-webkit</title>
    </head> 
    <body>
        <div>hello node-webkit!</div>
    </body> 
</html></span>
4. 在当前路径创建package.json文件，“main”的值指定初始页面
<span style="font-family:Microsoft YaHei;font-size:12px;">{  
    "name": "nw-demo","main": "index.html"
}</span>
5.将html文件和json文件打成zip包，在这里就是index.html和package.json。并将其后缀名改为.nw，如app.nw。
6.将app.nw和nw.exe合成一起可执行文件。在windows下，在命令行窗口，执行copy /b nw.exe+app.nw app.exe
