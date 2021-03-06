# 1.1. 编写本文档的目标

SystemTap允许使用者监控Linux系统当前的运行情况，以便进一步分析。这将有助于运维或开发人员缉查bug或性能问题的罪魁祸首。

在SystemTap开发出来之前，要想监控一个运行中的内核，有些时候需要注入检测代码（instrument），重新编译，安装，还要重启一下。SystemTap的诞生，把程序员从这一串繁琐的步骤中解放出来。现在要想完成同样的工作，你只需要简单地运行下自己写的SystemTap脚本。

不过，SystemTap的目标用户是那些对内核驾轻就熟的老手。对于内核菜鸟来说，SystemTap依旧难以上手。雪上加霜的是，现存的许多SystemTap文档都假定读者有相当丰富的内核经验，这使得学习SystemTap的路途道阻且长。

为了降低入门的门槛，我们编写了《SystemTap新手指南》。它包括下面的内容：
1. 介绍SystemTap和它的用法，并列出各种型号内核下的安装方式。
2. 提供监控系统各组件的运行详情的SystemTap脚本作为例子，并介绍它们的运行方式和分析其输出。
