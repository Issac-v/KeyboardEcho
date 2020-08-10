# KeyboardEcho

[![Version](https://img.shields.io/github/v/release/Issac-v/KeyboardEcho.svg?label=version)](https://github.com/Issac-v/KeyboardEcho/releases)
[![License](https://img.shields.io/github/license/Issac-v/KeyboardEcho.svg?colorB=44cc11?maxAge=2592000)](https://github.com/Issac-v/KeyboardEcho/blob/master/LICENSE)

运行于windows平台的键盘回显应用, 基于[KeyCastOW](https://github.com/brookhong/KeyCastOW)修改而成. 可以在录屏时显示按键, 也适合平时有键盘回显需求的用户(比如刚开始学vim命令的我)

* 占用空间小(不到200kb)
* 绿色便携, 仅依赖于windows系统的dll
* 丰富的设置选项, 可自由定制
* 不需要时可通过热键关闭显示(如在录屏中输入敏感信息时)

## 相关设置的中英文对照
*(按从左至右自上而下顺序对各项设置进行翻译)*  

`Alignment` : 设定左对齐or右对齐  
`Position` : 在设置页中选择文本框的位置  
`Draggable Label` : "可拖拽文本", 若开启, 可直接拖拽文本框以调整其位置  
`Branding` : 在屏幕左上方长期固定显示的文本内容(一般时录屏者放自己的推广文本, 个人使用时一般留空)  
`Toggle Capturing` : 关闭显示文本框的热键, 默认为`Alt+b`  

`Keystroke Delay(ms)` : "击键延迟", 间隔在该时间内的两次击键会被放进同一个文本框连续显示  
`Linger Time(ms)` : "持续时间", 文本框显示时间达到该值后会消失  
`Fade Dration(ms)` : "淡入时间", 文本框从开始消失到彻底消失所用时间  
`Maximum Lines` : "最大行数", 同时显示文本框的最大行数  
`Combination Chars` : "组合键的关联字符", 默认为`<->`, 比如按下`Alt+Tab`, 会显示`<Alt-Tab>`. 可以修改成`[+]`等类似形式  
`Display Standalone Modifier Key` : "显示单独的修改键", `Alt`,`Ctrl`之类一般不会单独使用的键称为修改键, 关闭后只按下`Alt`则不会显示在文本框中  
`SHIFT as Modifier Key` : "将SHIFT设定为修改键", 若不开启, 单独按下`Shift`不会显示内容, 通过`Shift`按出的一些符号(如`@`)会正常显示, 否则这些符号会以组合键的形式显示(`@`=>`Shift+2`)  
`Only Command Keys` : "只显示命令键", 只显示修改键以及`ESC`之类的命令键  
`Hold Down to Repeat` : "持续按键进行重复按键", 开启后一直按住7, 文本框会显示`777777....`, 若关闭, 不仅文本框只显示一个`7`, 也会影响你的输入(故建议开启)  

`Background Color` : "文本框背景颜色"  
`Background Opacity(0-255)` : "文本框背景透明度"  
`Text Font` : "文本框使用的字体"  
`Text Color` : "文本框字体颜色"  
`Text Opacity` : "文本框字体透明度"  
`Border Size` : "边框尺寸"  
`Border Color` : "边框颜色"  
`Border Opacity(0-255)` : "边框透明度"  
`Label Spacing` : "文本框之间的间隔距离"  
`Corner Size` : "文本框圆角尺寸", 0为尖状边角, 值越高边角越远  
`Mouse Action`  : "是否记录鼠标的动作"  
`Mouse Only With Modifier` : 只在与修改键一起按下时才显示鼠标的动作  
`Detect Click/DbClick` : "检测鼠标单击/双击", 若关闭, 则单击一次鼠标会被显示成`鼠标左键按下`和`鼠标左键抬起`两个动作  
