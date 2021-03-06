[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
# 获取元素矩形

获取元素的维度和坐标
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
## 样例

```java
// Java
MobileElement element = (MobileElement) driver.findElementByAccessibilityId("SomeAccessibilityID");
Rectangle rect = element.getRect();

```

```python
# Python
element = self.driver.find_element_by_accessibility_id('SomeAccessibilityID')
element.rect

```

```javascript
// Javascript
// webdriver.io example
let element = $("~SomeAccessibilityId")
let rect = driver.getElementRect(element.elementId);

// wd example
let element = await driver.elementByAccessibilityId("SomeAccessibilityID");
let rect = await element.getRect();

```

```ruby
# Ruby
# ruby_lib example
element = find_element :accessibility_id, "SomeAccessibilityID"
element.rect

# ruby_lib_core example
element = @driver.find_element :accessibility_id, "SomeAccessibilityID"
element.rect

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
var element = driver.FindElementByAccessibilityId("SomeAccessibilityID");
Rectangle rect = element.Rect;

```


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
## 支持

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### Appium Server

|平台|Driver|平台版本|Appium版本|Driver版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | ?+ | 1.6.4+ | All |
| Windows | [Windows](/docs/en/drivers/windows.md) | 10+ | 1.6.0+ | All |


[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### Appium Clients

|语言|支持|文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [seleniumhq.github.io](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html#getRect--) |
|[Python](https://github.com/appium/python-client/releases/latest)| All |  |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All |  |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/gems/selenium-webdriver/Selenium/WebDriver/Element#rect-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| All | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All | [github.com](https://github.com/appium/appium-dotnet-driver/blob/master/src/Appium.Net/Appium/AppiumWebElement.cs) |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
## HTTP API规范

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### 端点

`GET /session/:session_id/elements/:element_id/rect`

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### URL参数

|名称|描述|
|----|-----------|
|session_id|发送命令用来会话的id|
|element_id|获取元素矩形的id|

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### JSON 参数

无

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
### 响应

|名称|类型|描述|
|----|----|-----------|
| x | 数值类型 | X 坐标 |
| y | 数值类型 | Y 坐标 |
| height | 数值类型 | 矩形框的高度 |
| width | 数值类型 | 矩形框的宽度 |

[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/element/attributes/rect.yml)
## 另请参见

* [W3C Specification](https://www.w3.org/TR/webdriver/#dfn-get-element-rect)
