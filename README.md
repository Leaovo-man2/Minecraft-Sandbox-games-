# Minecraft Simulation

## 运行截图

![运行截图](img)

## 使用说明

### 环境准备

1. 请确保您已安装 `pyglet` 模块。您可以使用以下命令安装：
   ```bash
   pip install pyglet

## 运行程序

1.运行 main.py 文件：
   ```bash
   python main.py
   ```
## 游戏控制
- ### 移动控制

- 前进：W
- 后退：S
- 向左：A
- 向右：D
- 环顾四周：鼠标移动
- 跳起：空格键
- 切换飞行模式：Tab
- ### 选择建筑材料
- 砖：1
- 草：2
- 沙子：3
- ### 建筑操作
- 删除建筑：鼠标左键单击
- 创建建筑块：鼠标右键单击
- ### 退出程序
- 按 ESC 键退出程序

## 常见问题
- 错误提示：`NameError: name 'GL_FOG' is not defined`

    解决方法：请运行 Releases 附件中的 Bug_fixes.bat 文件。

- 移动时不受控制

    解决方法：尝试切换输入法设置。
