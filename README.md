# myBeego

1. ### init

   ```
   在 gopath 下
   bee new rojectName
   cd projectName
   bee run
   ```

2. ### install beego bee

   ```
   mkdir go_project 
   cd go_project
   go env -w GOPROXY=https://goproxy.cn,direct
   ```

   

   ```
   替换 bee 源
   fork github.com/beego/bee
   mod 初始化
   go mod init github.com/xxx/projectname
   修改go.mod
   module github.com/xxx/projectname
   replace github.com/beego/bee v1.10.0 => github.com/xxx/bee v1.10.0
   go 1.13
   ```

   ```
   安装beego bee
   go get -u github.com/astaxie/beego
   export GO111MODULE=off && go get -u github.com/beego/bee
   go get -u github.com/beego/bee
   ```

   