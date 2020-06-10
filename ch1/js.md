# 适合3-4年工作经验前端开发
## JS 题目

1. 请解释变量声明提升 (hoisting)?

2. 什么是 “use strict”; ? 使用它的好处和坏处分别是什么？

3. 什么是闭包 (closure)，为什么要使用它？

4. 下面代码运行的结果？为什么？
```
console.log('One')
setTimeout(function () {
    console.log('Two')
}, 0)
console.log('Three')
```

5. 下面代码的结果？
```
console.log(typeof NaN === 'number');
```

6. 下面代码运行的结果？
```
var x = 10;
function fn() {
    console.log(x);
}
function show(f) {
    var x = 20;
    f();
}
show(fn);
```

7. 简单说一下事件冒泡机制？事件捕获？

8. e.preventDefault()与e.stopPropagation()的区别?

9. 如何在react/vue 组件内添加e.preventDefault()？

10. 如何理解虚拟dom?为什么说他性能比较好？

11. cmd Amd ems的区别？

12. 如何实现节流函数？

13. 如何实现防抖函数？

14. web worker 如何使用？

15. 宏任务、微任务与Event Loop是如何理解的？console的结果？

```
setTimeout(_ => console.log(4))

new Promise(resolve => {
  resolve()
  console.log(1)
}).then(_ => {
  console.log(3)
})

console.log(2)
```


16. async/await函数是宏任务还是微任务？



## Vue 题目
1. 什么时候使用_nextTicket?他是同步还是异步的？

2. 什么时候使用_forceUpdate?

3. vmode 如何运用在纯div的组件内？

4. next有使用过么？

5. 箭头函数与普通函数的区别？

6. 箭头函数能否通过new实例化？
```
var a = () => {}
var b = new a()
```

7. vue.extends的作用？

8. vue mixin是起什么作用的？

## React

1. useEffect的用法？如何代替3个生命周期？

2. UseMemo和UseCallback的区别?

3. Redux的运行流程？

4. dva是什么？

5. react 性能优化？

6. react 方法为什么要bind this?

7. 如何理解Fiber架构？带来的优点是哪些？

8. getDerivedStateFromProps生命周期的作用？

9. getSnapshotBeforeUpdate 的生命周起的作用？

10. Redux遵循的三个原则是什么？


