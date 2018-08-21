# appium-uiautomator2-server-patched
This is the patched binaries of appium-uiautomator2-server for the waitForIdle bug. Tested with `appium 1.7.2`

## Usage
1. Uninstall original `uiautomator2`
```
adb uninstall io.appium.uiautomator2.server
adb uninstall io.appium.uiautomator2.server.test
```

2. Install patched `uiautomator2` 
```
adb install appium-uiautomator2-server-v0.3.0.apk
adb install appium-uiautomator2-server-debug-androidTest.apk
```
