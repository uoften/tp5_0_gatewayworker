```
tp5.0结合gatewayworker
主要文件
/apps/websocket/controller/Run.php   --启动文件
/apps/websocket/controller/Events.php  --业务逻辑
/websocket.php     --入口文件

/extend/workweman      --workerman与gatewayworker的核心类包
/vender/GatewayClient/GatewayClient.php

运行：在更目录下执行：php wensocket.php start
```