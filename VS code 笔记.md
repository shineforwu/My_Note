<!-- Shift + Alt + A -->
# VS code 笔记

## 插件从C盘移动到其他路径
- 找到Vs code 默认插件位置为
一般为`C:\Users\{YourUsername}\.vscode\extensions`
- 创建一个文件夹 
如 `D:\Develop_Tool\Microsoft VS Code\MyExtensions`
- 创建一个 连接
- 打开cmd
- 运行 mklink/j "C:\Users\{YourUsername}\.vscode\extensions" "D:\Develop_Tool\Microsoft VS Code\MyExtensions"
 
- 创建一个快捷方式到桌面
然后修改其`目标`
"D:\Develop_Tool\Microsoft VS Code\Code.exe" --extensions-dir "D:\Develop_Tool\Microsoft VS Code\MyExtensions"

## 添加右键的`发送到`
- 打开路径 C:\Users\{YourUsername}\AppData\Roaming\Microsoft\Windows\SendTo
- 把刚才的快捷方式复制到这个文件夹中