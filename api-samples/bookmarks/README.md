# chrome.bookmarks

此示例演示了如何使用 chrome.bookmarks API 来搜索、添加和删除用户书签树中的书签。
## Overview (概述)

该扩展会调用 chrome.bookmarks.getTree() 方法来显示用户书签树的完整结构。用户可以通过输入来搜索书签，也可以使用按钮来添加或删除书签。
`chrome.bookmarks.create`is used to add 'https://www.google.com/' to the user's bookmarks. The `chrome.bookmarks.remove` and `chrome.bookmarks.search` APIs are used to find and delete any bookmarks that match 'https://www.google.com/'.

## Running this extension (运行此扩展)

1. 克隆本代码仓库
2. 在 Chrome 中加载此目录作为[未打包扩展](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked)。
3. 将扩展固定到任务栏，以便访问操作按钮。
4. 点击操作按钮打开扩展弹出窗口，并与 UI 进行交互。
