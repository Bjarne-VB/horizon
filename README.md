# horizon
## 纯rust代码的分布式服务器框架，服务器在linux下运行

## 整个系统分为
1. gateway：网关服
2. forward：转发服
3. login：登录服
4. lobby：大厅服
5. loader：游戏加载服
6. games：游戏服
7. data：数据服
8. kernel：核心功能
9. conf：配置文件
10. pb：消息体

## 和客户端之间的联系
- 使用websocket，可用ws或wss
- 使用protobuf传递信息