# PushDemo

通知 push

工作原理

搭建环境

push  交互设置

local push 的介绍———便捷哦


高级用法 

 push 的 业务功能 

iOS7  的业务 功能 

iOS 8   push  的新交互 


VOIP push  



------------


最熟悉  用的最多的 
多核  运算的    引入了 Block   

GCD  


任务方面：
同步 异步  会不会 阻塞 主线程 
 
同步 会 阻塞

队列 相关  ：

串行：任务1  任务 2

并行：多个 线程 同时进行 


dispatch_get_main_queue     UI 的 刷新

dispatch_get_global_queue



NSOperation ————-gcd 的封装

1 NSOperationQueue

a addOperation
b setMaxConcurrentOperationCount

2  状态

ready cancelled executing  finished  asynchronous

3 依赖 — addDependency
