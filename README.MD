### 通用工具方法

#### xid
根据雪花算法改造，弱依赖zk，解决时钟回拨问题。
1. 增加启动校验服务器是否是否正常
2. 通过比较时钟回拨阈值来判断是否等待或者更换workid