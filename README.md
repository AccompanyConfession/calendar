# Calendar日历插件 陪伴是最长情的告白  @陪白
Calendar是一个简单的以HTML5为主，基于jquery的日历显示插件。


- 官网： http://accompanyconfession.online（作者）

### 说明
- 在html页面中引入calendar.min.css和alendar.min.js,前提是已经引入了jquery
- 在主页添加$("#元素选择").loadCalendar();完成初始化。
- 使用详见demo
### 参数
- isZhGlo：是否使用中文
- selectNowStyle：当前时间的样式，自定义需传入对象
- selectStyle：日历标记的样式，自定义需传入对象
- selectArry：日历标记，传入数组对象，例：[{year:2020,month:5,day:11},{year:2020,month:5,day:20}]
- doSomethingMouseoverFun：鼠标移入事件
- changeTimeFun：年，月改变事件
- selectCaleFun：选择日期事件
### 方法
- selectFreshFun（）：日历改变时刷新标记事件，由$("#元素选择").loadCalendar();得到的对象调用。
### 注意
- doSomethingMouseoverFun：参数 time
- changeTimeFun：参数 year month
- selectCaleFun ：参数 year month day
### 版本
- 1.0：基本功能实现


> 如果你有什么疑问欢迎加本人qq讨论交流前端知识与后端知识，大家一起学习，一起进步

> qq:1391548667
 
                



