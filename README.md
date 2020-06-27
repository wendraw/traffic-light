异步编程的能力对于一门语言来说是非常重要的，但是我们的 JS 在 ES5 之前是没有这个能力的。我们只能通过宿主（浏览器）的全局对象 window 提供的超时回调（setTimeout）和定时器（setInterval）来实现并行执行。还有一种就是用事件（Event）来实现。

到了 ES5 给我们提供了 Promise，ES6 提供了 async / await。从此我们的 JavaScript 就真的有了异步编程的能力。

为了能够更直观的体验的异步编程的好处，我们来看一个实际的问题：
> 完成一个路口的红路灯，会按照绿灯亮 10 秒，黄灯亮 2 秒，红灯亮 5 秒的顺序无限循环。请编写 JavaScript 代码来控制这个红路灯。

![traffic-light](https://cdn.nlark.com/yuque/0/2020/gif/422224/1593276630457-0e0f1deb-7f3b-4c8d-839a-7999740bd7d5.gif)

更详细的内容见 [异步编程](https://www.yuque.com/wendraw/fe/asynchronous-programming)
