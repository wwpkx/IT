- onCreate
- onStart
- onResume
- onPause
- onStop
- onDestroy

横竖屏切换场景
- 默认情况下，横竖屏切换时 Activity 会被销毁并重新创建
    - 调用 onPause、onStop、onDestroy，然后重新调用 onCreate、onStart、onResume
- 在 AndroidManifest.xml 中设置android:configChanges="orientation|screenSize"来避免 Activity 的重新创建    
    - 只会调用 onConfigurationChanged 方法

按 Home 键场景
- 按下 Home 键，Activity 会依次调用 onPause、onStop
- 当再次从后台切换到前台时，会调用 onRestart、onStart、onResume。