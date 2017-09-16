2017-9-14 <br>
Thinking in java coding <br>
引入net.mingview.util架包时出错，在项目中新建lib文件夹，复制net.jar，add build path <br>
详见<a href="http://www.cnblogs.com/togeek/p/thiking_in_java_net_mindview_util_package.html">博客</a>

2017-9-16 <br>
第九章 复用类 清理<br>
许多情况下，清理并不是问题，垃圾回收器会帮我们完成工作。但是我们得习惯，除了内存以外，不能依赖垃圾回收器去做任何事情。如果需要清理，我们需要自己编写清理程序（dispose），try finally之中，不要使用finalize()。
