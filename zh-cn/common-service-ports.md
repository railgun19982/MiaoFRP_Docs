# 常用服务映射端口

| 服务            |端口  |协议（标注 * 的表示非必要） | 注意事项        |
| -------------- | ---- | --------------------------- | --------------- |
| FTP数据端口     |20   | TCP UDP*                     | 暂无           |
| FTP控制端口     | 21   | TCP UDP*                    | 暂无            |
| SSH            | 22   | TCP UDP*                    | 详见 “安全指南” |
| Telnet终端仿真  | 23   | TCP UDP                     | 未加密          |
| HTTP           |80    |TCP UDP*                     |中国大陆需要备案|
| HTTPS          |443   |TCP UDP*                     |中国大陆需要备案|
| SQL（数据库服务）|3306 |TCP UDP*                     |详见 “安全指南”|
| RDP（远端桌面） |3389  |TCP UDP*                     |详见 “安全指南”|
| VNC（远端桌面） |5900  |TCP UDP*                     |同上|

-----
- 仅列出部分常用服务，如需补充请联系管理员