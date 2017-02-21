# miniCAD
>本程序是一个简单的CAD画板

作者：疯zi损
邮箱：suntfen@163.com

[TOC]
## 本程序实现功能
- **绘制图形：**包括直线、椭圆、圆、矩形、文字；
- **图形属性：**删除、移动图形、缩放图形、改变图形线的粗细、改变颜色、改变字体、改变字号、改变字体加粗和斜体属性；
- **画布：**改变画布大小；
- **文件：**保存文件、读取文件、新建文件

## 具体操作方法
- **绘制功能：**从左侧工具栏选择`直线`、`椭圆`、`圆`、`矩形`工具，在画布上`左键拖动`鼠标可以绘制图形；
- **添加文字：**从左侧工具栏选择`文字`工具，在画布上`单击左键`选择添加位置，输入需要添加的文字就能完成文字绘制；
- **选中图形：**鼠标移动到需要选择的图形上，指针变为`箭头`时，`单击鼠标右键`即可选中图形；
- **删除图形：**
    * 选中图形后，按键盘`delete`或者`backspace`即可删除；
    * 从左侧工具栏中选择`删除`工具，在画布上移动鼠标，当鼠标指针变为`×`时，`单击鼠标左键`就能删除对应图形；
- **移动图形：**
    * 鼠标移动到想要移动的物体，指针变为`移动`时，`按住鼠标右键拖动`即可移动图形；
    * 从左侧工具栏中选择`移动`工具，在画布上移动鼠标，当指针变为`移动`时，`按住鼠标左键拖动`即可移动图形；
- **缩放图形：**
    * 按键盘`上`、`下`；
    * 滚动`鼠标滚轮`；
    * 从左侧工具栏中选择`缩放`工具，在画布上移动鼠标，当鼠标指针变化时，`按住鼠标左键拖动`即可缩放图形；
- **图形线的粗细：**
    * 按键盘`左`、`右`；
    * 滚动`鼠标滚轮`（注：`鼠标滚轮的功能可以通过单击滚轮来进行切换`）
- **改变颜色、改变字体、改变字号、改变字体加粗和斜体属性：**鼠标右键选中图形，从面板上调整相应的属性
- **画布大小：**
    * 鼠标移到画布边缘，当指针出现变化时，`按住鼠标左键拖动`画布边框即可改变画布大小；（注：`直接拖动的功能效果不是很好，还需要完善`）
    * 菜单栏`编辑——画布大小`
- **保存文件、读取文件、新建文件：**菜单栏`文件`