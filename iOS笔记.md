#iOS笔记
1.当设置TextFiled的文本框属性security属性为NO时，系统键盘会出现小地球 <br/>
解决方案: 监控TextFiled获取焦点，当获取焦点时，设置security为YES；监控键盘的状态，当键盘弹出时，设置security为NO。<br/><br/>
2.TextField设置security在NO和YES之前切换时，游标不会随之移动，另外设置为NO时，此时如果该TextField仍然为第一相应者，文字的颜色和字体会发生变化 该问题属于IOS系统bug，各位有好的解决方案可以共享。<br/><br/>
 3.设置IOS的键盘属性为邮箱类型，没什么卵用。