- 通过父Activity通信：最推荐的方式，解耦合，适合复杂场景。
- 使用Bundle传递数据：简单直接，适合**单向通信。**
- 使用EventBus：适合复杂通信场景，代码简洁，但可能引入额外依赖。
- **使用ViewModel共享数据**：适合需要共享数据的场景，与Jetpack兼容性好。
- 使用LocalBroadcastManager：**适合简单的广播通信**，但不如EventBus灵活。