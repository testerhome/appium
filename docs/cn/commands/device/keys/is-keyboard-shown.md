[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
# 是否显示键盘


是否显示软键盘
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
## 使用样例

```java
// Java
boolean isKeyboardShown = driver.isKeyboardShown();

```

```python
# Python
driver.is_keyboard_shown()

```

```javascript
// Javascript
// webdriver.io example
driver.isKeyboardShown();

// wd example
await driver.isKeyboardShown();

```

```ruby
# Ruby
# ruby_lib example
is_keyboard_shown

# ruby_lib_core example
@driver.is_keyboard_shown

```

```php
// Not supported
```

```csharp
// Not supported
```


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
## 支持

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### Appium Server

|平台|驱动|平台版本 |Appium 版本|驱动版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/cn/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/cn/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [Espresso](/docs/cn/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/cn/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/cn/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/cn/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/cn/drivers/windows.md) | 10+ | 1.6.0+ | All |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### Appium Clients

|语言|支持|文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/HasOnScreenKeyboard.html#isKeyboardShown--) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [appium.github.io](https://appium.github.io/python-client-sphinx/webdriver.extensions.html#webdriver.extensions.keyboard.Keyboard.is_keyboard_shown) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| None |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All | [github.com](https://github.com/admc/wd/blob/master/lib/commands.js#L2638) |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#is_keyboard_shown-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| None |  |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None |  |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
## HTTP API 规范

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### 端口

`GET /session/:session_id/appium/device/is_keyboard_shown`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### URL 参数

|name|description|
|----|-----------|
|session_id|将指令发往的会话（session）的ID|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### JSON 参数

None

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
### 响应

True if the keyboard is shown. (`boolean`)

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/keys/is-keyboard-shown.yml)
## 参考

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L498)
