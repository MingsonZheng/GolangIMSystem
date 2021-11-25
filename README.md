# GolangIMSystem
An instant messaging system based on golang

- 构建基础Server
- 用户上线功能
- 用户消息广播机制
- 用户业务层封装
- 在线用户查询
- 修改用户名
- 超时强踢功能
- 私聊功能
- 客户端类型定义与连接
- 解析命令行
- 菜单显示
- 更新用户名
- 公聊模式
- 私聊模式

构建代码
```
go build -o server main.go server.go

go build -o client client.go
```

启动服务
```
./server
```

启动客户端
```
./client
```

菜单显示
```
1.公聊模式
2.私聊模式
3.更新用户名
0.退出
```
