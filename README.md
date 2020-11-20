# study_doc

从这点看：

策略模式是通过不同的算法做同一件事情：例如排序

而命令模式则是通过不同的命令做不同的事情，常含有（关联）接收者。

目标不同！

命令模式是含有不同的命令（含有接收者的请求）：做不同的事情；隐藏接收者执行细节。常见菜单事件，

而策略模式含有不同的算法，做相同的事情；

区别在于是否含有接收者。命令模式含有，策略模式不含有。命令模式中的命令可以单独运行。

打个比喻就是：

 命令模式等于菜单中的复制，移动，压缩等，而策略模式是其中一个菜单的例如复制到不同算法实现。