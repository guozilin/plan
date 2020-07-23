### 虚拟 DOM
- 虚拟 DOM 就是用数据结构表示 DOM 结构，它并没有真实的 append 到 DOM 上，因此称之为虚拟
- 操作数据结构远比操作浏览器交互操作 DOM 快很多
- 虚拟 DOM 最终也是挂载到浏览器的真实 DOM 节点，因此使用虚拟 DOM 并不能使得 DOM 操作的数量减少，
- 虚拟 DOM 可以精确的获取最小的罪有必要的操作 DOM 的集合
  