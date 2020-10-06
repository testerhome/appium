[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
# 旋转

以三维方式旋转设备
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
## 使用样例

```java
// Java
driver.rotate(new DeviceRotation(10, 10, 10));

```

```python
# Not supported
```

```javascript
// Javascript
// webdriver.io example
driver.rotateDevice(100, 100);

// wd example
driver.rotateDevice({x: 114, y: 198, duration: 5, radius: 3, rotation: 220, touchCount: 2});

```

```ruby
# Not supported
# Not supported
```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
driver.Rotate(new Dictionary<string, int> { { "x", 114 }, { "y", 198 }, { "duration", 5 }, { "radius", 3 }, { "rotation", 220 }, { "touchCount", 2 } });

```


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
## 支持

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### Appium Server

|平台|驱动|平台版本 |Appium 版本|驱动版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/cn/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/cn/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [UiAutomator2](/docs/cn/drivers/android-uiautomator2.md) | None | None | None |
|  | [Espresso](/docs/cn/drivers/android-espresso.md) | None | None | None |
|  | [UiAutomator](/docs/cn/drivers/android-uiautomator.md) | None | None | None |
| Mac | [Mac](/docs/cn/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/cn/drivers/windows.md) | None | None | None |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### Appium Clients

|语言|支持|文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/AppiumDriver.html#rotate-org.openqa.selenium.DeviceRotation-) |
|[Python](https://github.com/appium/python-client/releases/latest)| All |  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2470) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All |  |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/blob/master/src/Appium.Net/Appium/AppiumDriver.cs) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
## HTTP API Specifications

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### Endpoint

`POST /session/:session_id/appium/device/rotate`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### URL Parameters

|名称|描述|
|----|-----------|
|session_id|将指令发往的会话（session）的ID|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### JSON 参数

|名称|类型|描述|
|----|----|-----------|
| x | `number` | 用于旋转手势中心的x偏移量|
| y | `number` | 用于旋转手势中心的y偏移量 |
| radius | `number` | 从圆弧的中心到边缘的距离（以点为单位）|
| rotation | `number` |弧度的旋转长度 |
| touchCount | `number` | 指定手势中要使用的触摸次数。 （有效地，用户用来做出指定手势的手指数。）有效值为1到5. |
| duration | `number` | 指定手势的保持时间长度，以秒为单位. |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
### 响应

null

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/interactions/rotate.yml)
## 参考

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L424)