注册方式：​
- 静态注册：
	- **在 AndroidManifest.xml 中注册广播接收器，即使应用没有运行，也能接收广播。**
	- **监听系统开机广播**
		- 在 AndroidManifest.xml 中注册一个 BroadcastReceiver
		- 并设置 intent - filter 监听android.intent.action.BOOT_COMPLETED广播​
- 动态注册：
	- 在代码中通过 registerReceiver 方法注册广播接收器。
	- **这种方式灵活性更高，可以根据应用的运行状态动态地注册和注销广播接收器。**
	- 可以避免在 Activity 不可见时仍然接收广播，浪费资源
	- 动态注册的广播接收器在注册的 Activity 或 Service 销毁时需要及时注销，否则会导致内存泄漏。

广播类型：​
- 普通广播：
	- 通过 **sendBroadcast** 方法发送，
	- 所有感兴趣（在 intent - filter 中匹配了相应 action 等）的广播接收器**都能接收。**
	- 通常用于通知各个组件数据更新
- 有序广播：
	- 通过 sendOrderedBroadcast 方法发送
	- 广播接收器会按照优先级依次接收广播。
	- 在 AndroidManifest.xml 中注册广播接收器时，可以通过 intent - filter 的 android:priority 属性设置优先级，**值越大优先级越高**。
	- 优先级高的广播接收器先接收广播，它**可以选择是否继续传播广播（通过 abortBroadcast 方法）**
- 粘性广播：
	- **已废弃，它可以让广播接收器获取到之前发送的广播内容。**
	- 使用粘性广播可以让新注册的广播接收器立即获取到当前的电池电量信息，而不需要等待下一次电池电量变化广播的发送。
	- 但由于粘性广播存在一些安全和性能问题，在 Android 5.0（API 21）之后被废弃。