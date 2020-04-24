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
