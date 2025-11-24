# chrome.alarms

此示例通过允许用户使用扩展页面设置闹钟，演示了 chrome.alarms API 的功能。
## Overview (概述)

该扩展会调用 chrome.alarms.create() 方法来设置一个初始闹钟，该闹钟会显示在扩展页面上。用户可以通过输入来设置更多闹钟

## Running this extension (运行此扩展)
1. 克隆此存储库。
2. 在 Chrome 中加载此目录作为[未打包扩展](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked)。
3. 将扩展固定到任务栏，以便访问操作按钮。
4. 点击操作按钮打开扩展弹出窗口，并与 UI 进行交互。
