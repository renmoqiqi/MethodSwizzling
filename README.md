# MethodSwizzling

给一个App 扩展打点统计功能 在每个控制器写太费事，继承侵入性太强，分类有可能覆盖类的方法（最好加前缀）

用runtime 方法交换来搞

注意事项：在load 方法里执行， 注意自己要实现方法，别让他调用父类的方法实现，这样下面继承的类会造成问题。

http://linusling.com/2016/03/23/method-swizzling-in-ios/

http://www.cocoachina.com/ios/20160121/15076.html

https://www.zhihu.com/question/30721573
