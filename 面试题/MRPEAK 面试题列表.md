# MRPEAK 面试题列表

* 什么是arc？（arc是为了解决什么问题诞生的？）

* 请解释以下keywords的区别： assign vs weak, __block vs __weak

* __block在arc和非arc下含义一样吗？

* 使用atomic一定是线程安全的吗？

* 描述一个你遇到过的retain cycle例子。(别撒谎，你肯定遇到过)

* +(void)load; +(void)initialize；有什么用处？

* 为什么其他语言里叫函数调用， objective c里则是给对象发消息（或者谈下对runtime的理解）

* 什么是method swizzling?

* UIView和CALayer是啥关系？

* 如何高性能的给UIImageView加个圆角？（不准说layer.cornerRadius!）

* 使用drawRect有什么影响？（这个可深可浅，你至少得用过。。）

* ASIHttpRequest或者SDWebImage里面给UIImageView加载图片的逻辑是什么样的？（把UIImageView放到UITableViewCell里面问更赞）

* 麻烦你设计个简单的图片内存缓存器（移除策略是一定要说的）

* 讲讲你用Instrument优化动画性能的经历吧（别问我什么是Instrument）

* loadView是干嘛用的？

* viewWillLayoutSubView你总是知道的。。

* GCD里面有哪几种Queue？你自己建立过串行queue吗？背后的线程模型是什么样的？

* 用过coredata或者sqlite吗？读写是分线程的吗？遇到过死锁没？咋解决的？

* http的post和get啥区别？（区别挺多的，麻烦多说点）

* 我知道你大学毕业过后就没接触过算法数据结构了，但是请你一定告诉我什么是Binary search tree? search的时间复杂度是多少？我很想知道！


## 进阶版

* NSString如何计算字符的个数？

* PKI体系当中加密和签名有什么区别？

* 如何自己高效实现NSUserDefault?

* 解释下tcp的慢启动特性。

* 如何用HTTP实现长连接？

* HTTP2.0针对同一个域名的多个请求，会建立多少个tcp连接？

* 数据库建表的时候索引有什么用？

* Full Text Search为什么快？

* iOS下如何实现指定线程数目的线程池？

* 介绍下iOS设备获取唯一设备号的历史变迁。

* 函数式编程当中的 first-class function是什么意思呢？

* 如何使用runtime hook一个class的某个方法，又如何hook某个instance的方法？

* 谈下Objective C都有哪些锁机制，你一般用哪个？

* 聊下HTTP post的body体使用form-urlencoded和multipart/form-data的区别。

* 让你设计一种机制检测UIViewController的内存泄漏，你会怎么做？

* 通过[UIImage imageNamed:]生成的对象什么时候被释放？

* applicationWillEnterForeground和applicationDidBecomeActive都会在哪些场景下被调用？举例越多越好。

* 如何终止正在运行的工作线程？

* 穷举iOS下所有的本地持久化方案。

