LabVIEW X-Controls
========================================

使用说明
-----------------

1.	部分XControl 依赖OpenG
2.	开发环境 LabVIEW 2014，高版本可以直接拷贝至开发目录使用。

列表
-----------------

 1. [XIconBtn](https://github.com/nevstop/LabVIEW-UI-XCtl/#xiconbtn)
 ：自定义图案按钮,可在编辑时右键中选择载入的按钮图案，可设置Label 文字和字体。
 2. [XLEDDisplay](https://github.com/nevstop/LabVIEW-UI-XCtl/#xleddisplay)
 ：LED 字符滚动显示控件
 3. [XpnlTab](https://github.com/nevstop/LabVIEW-UI-XCtl/#xpnltab)
 ：带Tab的Subpanel控件
 4. [XpnlWizard](https://github.com/nevstop/LabVIEW-UI-XCtl/#xpnlwizard)
 ：功能Btn，可调用 VI或触发 CommandLine 命令
 5. [XTwoColSelector](https://github.com/nevstop/LabVIEW-UI-XCtl/#xtwocolselector)
 ：双列List，用于列表项选择
 6. [XAdvanceList](https://github.com/nevstop/LabVIEW-UI-XCtl/#xadvancelist)
 ：增强LabVIEW String List
 7. [NEVSTOP_ProgressDlg](https://github.com/nevstop/LabVIEW-UI-XCtl/#nevstop_progressdlg)
 ：基于消息机制的进度条/忙碌窗口

功能说明
-----------------

### XIconBtn
自定义图案按钮,可在编辑时右键中选择载入的按钮图案，可设置Label 文字和字体。

### XLEDDisplay
LED 字符滚动显示控件，字符可预设或运行时修改。

### XpnlTab
带Tab的Subpanel控件，可设置 tab 位置。  

### XpnlWizard
来源于 LabVIEW DSC 中的按钮XControl，移除不必要的dsc 相关界面内容。可以在按钮右键菜单中选择  
 1. 触发 CommandLine 命令
 2. 调用 VI
 
### XTwoColSelector
双列List，用于列表项选择  
![XTwoColSelector](https://github.com/nevstop/LabVIEW-UI-XCtl/blob/master/XTwoColSelector/_img/2017-11-26_212921.png?raw=true)

### XAdvanceList
增强LabVIEW String List 功能

### NEVSTOP_ProgressDlg
基于消息机制的进度条/忙碌窗口。
 1. 调用Initialize 自动配置显示进度窗口；
 2. 调用Set Information VI 更新进度信息；
 3. 使用Release 隐藏窗口.
