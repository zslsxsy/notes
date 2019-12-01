socket是网络通信的端点

ip和port生成一个socket



同步VS异步     主要基于接收方
同步即等一个交互完成才能进行下一个交互  
异步即即时返回不需要等待

阻塞VS非阻塞    主要基于请求方
阻塞是请求方被阻塞了
非阻塞是请求方没有被阻塞


Java提供的ExcutorService创建线程池
提供了runnable和callable两种任务   结果是feature对象

Excutors提供四种生成4种线程池  特殊的两个  newCachedThreadPool   newScheduledThreadPool