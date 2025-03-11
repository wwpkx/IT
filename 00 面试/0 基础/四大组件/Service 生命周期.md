- startService一般是绑定后台服务
- bindService适合通信的时候绑定

onDestroy 的执行时机
1. **StopService() 被调用**: 当应用调用 `stopService()` 方法时，Service 将被停止，触发 `onDestroy()` 方法。
2. **调用 stopSelf()**: 如果 Service 内部完成了任务，可能会调用 `stopSelf()` 方法停止自己。
3. **系统资源紧张**: 在一些特定情况下，系统会主动停止 Service，比如设备内存不足等情况。

![](../../../photo/Pasted%20image%2020250311183451.png)

![](../../../photo/Pasted%20image%2020250311183712.png)