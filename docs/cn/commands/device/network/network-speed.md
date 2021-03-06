# 网络速度

设置网络速度 (仅支持模拟器)

## 使用示例

```java
// Java
driver.setNetworkSpeed(NetworkSpeed.LTE);

```

```python
# Python
self.driver.set_network_speed(NetSpeed.LTE)

```

```javascript
// Javascript
// webdriver.io example
driver.toggleNetworkSpeed('lte');

// wd example
await driver.networkSpeed('Network type');

```

```ruby
# Ruby
# ruby_lib example
set_network_speed :lte

# ruby_lib_core example
@driver.set_network_speed :lte

```

```php
// Not supported
```

```csharp
// Not supported
```



## 支持


### Appium 服务端

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/cn/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/cn/drivers/ios-uiautomation.md) | None | None | None |
| Android | [UiAutomator2](/docs/cn/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [Espresso](/docs/cn/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator](/docs/cn/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/cn/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/cn/drivers/windows.md) | None | None | None |



### Appium 客户端

|Language|Support|Documentation|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/android/SupportsSpecialEmulatorCommands.html#setNetworkSpeed-io.appium.java_client.android.NetworkSpeed-) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [appium.github.io](https://appium.github.io/python-client-sphinx/webdriver.extensions.android.html#webdriver.extensions.android.network.Network.set_network_speed) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L3411) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/master/Appium/Core/Android/Device/Emulator#set_network_speed-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| None |  |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None |  |


## HTTP API 规范


### 路径

`POST /session/:session_id/appium/device/network_speed`


### URL 参数

|名称|描述|
|----|-----------|
|session_id|新建会话(session)后用来标识当前会话(session)的ID|


### JSON 参数

|名称|类型|描述|
|----|----|-----------|
| netspeed | `string` | 网络类型有 - 'full','gsm', 'edge', 'hscsd', 'gprs', 'umts', 'hsdpa', 'lte', 'evdo' |


### 响应

null


## 参考

* [JSONWP 规范](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L418)
