# react-swipe-official-demo
官网的一个小用例，这个例子的事件调用，官网用了::这个符号，目前对这个符号的用法不清楚，而且运行也不通过，故改成惯常用法 <br/>
原例子用的是`<button type="button" onClick={::this.prev}>Prev</button>` 且没有在构造函数内注册`this.prev = this.prev.bind(this)`
