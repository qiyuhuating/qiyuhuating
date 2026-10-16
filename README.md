# 你好，我是祈雨

我正在学习软件工程，持续探索**可靠性、分布式系统、存储与搜索**。

我更关心系统在真实约束和故障下的表现：不仅让功能运行起来，也希望能够**观察过程、复现问题、验证结果**。

## 置顶项目

### [颐和健康](https://github.com/qiyuhuating/yihe-health) · 社区照护与风险管理

面向社区照护场景的应用原型，涵盖居民档案、设备信号、用药任务、风险事件和工作人员处置流程。

后端采用 Python 与 SQLite，着重实现**权限与隐私边界、读写事务隔离、风险事件状态管理及自动化验收**。

[在线体验](https://qiyuhuating.github.io/yihe-health/) · [源码与测试](https://github.com/qiyuhuating/yihe-health)

> 在线页面使用浏览器本地模拟数据，不连接真实医疗后端，也不提供医疗诊断。

### [Faultline](https://github.com/qiyuhuating/faultline-lab) · 故障恢复与任务执行

可注入故障的本机任务执行实验室。通过真实 Worker 进程崩溃、租约过期与接管、旧令牌提交拒绝等场景，观察系统如何恢复并保持结果一致。

核心机制包括 **SQLite 持久化队列、租约、栅栏令牌、幂等处理与故障轨迹验证**。

[故障轨迹演示](https://qiyuhuating.github.io/faultline-lab/) · [架构与验证](https://github.com/qiyuhuating/faultline-lab)

> 公开页面回放已录制的故障轨迹；新的故障实验需要在本地运行。

### [skipverse](https://github.com/qiyuhuating/skipverse) · 向量检索引擎

使用 TypeScript 实现的向量检索引擎，支持 **HNSW 近似最近邻搜索、预写式日志、快照恢复与向量量化**。

在线可视化展示搜索如何逐层遍历图索引，并复用引擎本身的检索核心。

[交互式搜索演示](https://qiyuhuating.github.io/skipverse/) · [源码与接口](https://github.com/qiyuhuating/skipverse)

### [Quorum Lab](https://github.com/qiyuhuating/quorum-lab) · 分布式共识实验室

基于 Raft 协议构建的**五节点确定性共识实验室**。支持模拟网络分区、消息延迟与丢失、节点崩溃，逐事件观察领导者选举、日志复制与故障恢复。

借助**虚拟时钟、故障注入与确定性回放**，将抽象的分布式协议转化为可以检查和复现的实验。

[在线共识实验](https://qiyuhuating.github.io/quorum-lab/) · [架构与测试](https://github.com/qiyuhuating/quorum-lab)

## 其他探索

[**contrapunctus**](https://github.com/qiyuhuating/contrapunctus) · 基于 Fugue Max Tree CRDT 的协同文本引擎，探索并发编辑、乱序消息投递与副本收敛。[体验协同实验](https://qiyuhuating.github.io/contrapunctus/)。

以上项目均提供本地运行方法、测试入口和实现范围说明。我希望让设计取舍有据可查，让系统行为能够被验证，而不是只展示运行成功的一面。

---

*我要我们在一起*
