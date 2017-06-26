# angular4
angular2/4 开发经验

一、简单的介绍一下@angular/cli脚手架的使用。

快速安装
npm install -g @angular/cli

创建新项目
ng new angular-demo

启动项目
ng serve

还可以加上参数：
ng serve --open

使用--open（或-o）参数可以自动打开浏览器并访问http://localhost:4200/。
新建组件
ng g component component-name

g是generate的缩写 还可以创建其他文件：
// 创建类  

ng g class class-name   



// 创建指令  

ng g directive directive-name   



// 创建模块  

ng g module module-name   



// 创建管道  

ng g pipe pipe-name   



// 创建服务  

ng g service service-name

启动测试
ng test

编译项目
ng build
