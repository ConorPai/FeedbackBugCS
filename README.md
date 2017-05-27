# CS软件BUG反馈要点
近期有一些CS软件报错后，由于收集的信息太少导致重现、定位问题非常困难。能重现的问题比较好处理，如果遇到不好重现的问题，请在第一时间尽可能全的收集以下信息：

## 要点:
1.版本。包括软件版本（平台版本）、Windows系统版本和配置

2.截图。报错时的截图（不要只截报错提示那一块的局部图，要全屏截图），最好是报错重现录屏或录相

3.日志。软件日志(软件安装目录logs文件夹)、windows系统日志（在控制面板中搜索“事件查看器”，找到报错时间附近的日志信息，截图保存）

4.内存。在任务管理器中查看报错时，软件所占内存大小

5.操作。重现报错的操作流程，如果不能重现则询问大概操作步骤，尤其是最后操作了什么功能导致软件报错

6.数据。软件报错使用的数据

7.效率，反馈效率问题的，不要说慢就没了，要给出在多大数据量下，耗时多久这些具体的描述（比如提两个图层空间叠加分析效率慢，一个图层5000个面，一个图层20000个面，耗时60分钟）