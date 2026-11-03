# 待办日历 (todo-calendar)

把待办事项挂在日历上的桌面小工具：按月看全局，点某天加事，到期高亮提醒。

> 本仓库为说明与示例数据。主程序是 PyInstaller 打包的免安装版，见 Releases。

## 功能

- 月历视图，每天格子内显示当天待办条数
- 点击某天新增 / 编辑 / 完成待办
- 到期未完成自动标红
- 数据存本地 `TodoCalendarData/todos.json`，纯离线

## 数据存放

程序目录下的 `TodoCalendarData/`：

| 文件 | 说明 |
|---|---|
| `todos.json` | 全部待办 |
| `settings.json` | 界面偏好 |

仓库里 `data/*.example.json` 是空结构样例。

## 成品

见 Releases 页的 `todo-calendar-win-x64.zip`，解压后双击 `待办日历.exe`。
