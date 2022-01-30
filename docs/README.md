```shell
cnpm install --save-dev electron-packager
npm run package
```

```
https://cloud.tencent.com/developer/section/1115971

electron-v16.0.8-darwin-x64.zip
https://npm.taobao.org/mirrors/electron/v16.0.8/
```

```
https://cloud.tencent.com/developer/section/1115971

new BrowserWindow([options])
options 对象（可选） 
width整数（可选） - 窗口的宽度（以像素为单位）。默认是800。
height整数（可选） - 窗口的高度（以像素为单位）。默认是600。
x整数（可选）（如果使用y，则为必需） - 窗口的左偏移屏幕。默认是将窗口居中。
y整数（可选）（如果使用x，则为必需） - 窗口与屏幕的偏移量。默认是将窗口居中。
useContentSize布尔（可选） - width和height将用作网页的大小，这意味着实际窗口的大小将包括窗口框架的大小并略大。默认是false。
center 布尔（可选） - 在屏幕中心显示窗口。
minWidth整数（可选） - 窗口的最小宽度。默认是0。
minHeight整数（可选） - 窗口的最小高度。默认是0。
maxWidth整数（可选） - 窗口的最大宽度。默认是没有限制的。
maxHeight整数（可选） - 窗口的最大高度。默认是没有限制的。
resizable布尔（可选） - 窗口是否可调整大小。默认是true。
movable布尔（可选） - 窗口是否可移动。这在Linux上没有实现。默认是true。
minimizable布尔（可选） - 窗口是否可以最小化。这在Linux上没有实现。默认是true。
maximizable布尔（可选） - 窗口是否可以最大化。这在Linux上没有实现。默认是true。
closable布尔（可选） - 窗口是否可关闭。这在Linux上没有实现。默认是true。
focusable布尔（可选） - 窗口是否可以聚焦。默认是true。在Windows上设置focusable: false也意味着设置skipTaskbar: true。在Linux设置下focusable: false，窗口停止与wm进行交互，所以窗口将始终保持在所有工作区的顶部。
alwaysOnTop布尔（可选） - 窗口是否应始终保持在其他窗口之上。默认是false。
fullscreen布尔（可选） - 窗口是否应以全屏显示。当明确设置为false全屏按钮时，将在macOS上隐藏或禁用。默认是false。
fullscreenable布尔（可选） - 窗口是否可以进入全屏模式。在macOS上，最大化/缩放按钮是否应该切换全屏模式或最大化窗口。默认是true。
skipTaskbar布尔（可选） - 是否在任务栏中显示窗口。默认是false。
kiosk布尔（可选） - 自助服务终端模式。默认是false。
title字符串（可选） - 默认窗口标题。默认是"Electron"。
icon（NativeImage |字符串）（可选） - 窗口图标。在Windows上，建议使用ICO图标来获得最佳的视觉效果，您也可以将其保留为未定义的，以便使用可执行文件的图标。
show布尔（可选） - 创建时是否显示窗口。默认是true。
frame布尔（可选） - 指定false创建一个无框窗口。默认是true。
parentBrowserWindow（可选） - 指定父窗口。默认是null。
modal布尔（可选） - 是否是模态窗口。这只适用于窗口是子窗口的情况。默认是false。
acceptFirstMouseBoolean（可选） -  Web视图是否接受同时激活窗口的单个鼠标按下事件。默认是false。
disableAutoHideCursor布尔（可选） - 是否在键入时隐藏光标。默认是false。
autoHideMenuBar布尔（可选） - 除非Alt按下键，否则自动隐藏菜单栏。默认是false。
enableLargerThanScreen布尔（可选） - 使窗口的调整大小大于屏幕。默认是false。
backgroundColor字符串（可选） - 窗口的背景颜色为十六进制值，如#66CD00or #FFF或#80FFFFFF（支持alpha）。默认是#FFF（白色）。
hasShadow布尔（可选） - 窗口是否应该有阴影。这只在macOS上实现。默认是true。
darkTheme布尔（可选） - 强制使用黑暗主题作为窗口，仅适用于某些GTK + 3桌面环境。默认是false。
transparent布尔（可选） - 使窗口透明。默认是false。
type字符串（可选） - 窗口的类型，默认为正常窗口。请参阅下面的更多信息。
titleBarStyle字符串（可选） - 窗口标题栏的样式。默认是default。可能的值是：
default  - 导致标准灰色不透明的Mac标题栏。
hidden  - 导致隐藏标题栏和全尺寸内容窗口，但标题栏仍然在左上角具有标准窗口控件（“交通信号灯”）。
hidden-inset- 弃用，hiddenInset改为使用。
hiddenInset  - 在隐藏的标题栏中显示交通灯按钮稍微偏离窗口边缘的替代外观。
customButtonsOnHover布尔（可选） - 在macOS无框窗口上绘制自定义关闭，最小化和全屏按钮。这些按钮不会显示，除非在窗口的左上角悬停。这些自定义按钮可防止与标准窗口工具栏按钮发生的鼠标事件相关的问题。注意：此选项目前是实验性的。
```