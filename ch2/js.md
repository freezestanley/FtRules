# 适合5年以上工作经验前端开发
## JS 题目

1. 基于Object.defineProperty如何实现数据的双向绑定？
  
2. Proxy 的作用？他和Object.defineProperty区别？

3. 如何实现潜拷贝？

4. 如何实现深拷贝？

5. 是否有尝试进行前端页面的性能监控？如有聊聊如何实现的？

6. 简单描述 set、map 的数据结构的区别？

7. weakmap、weakset是干什么用的？

8. 如何在js内是实现图片压缩？

9. 数组的reduce的方法是使用

10. 数组reduce的第个参数的起什么作用？

11. 如何将下列数组去重

```
var a = [{value: 1}, '1','2',2,[1,1,'2',{value: 1}]]
function filter () {
    ...
}

var b = filter(a)
console.log(b) // [1,2,'1','2']
```

12. 如何将多维数组进行拍平？

```
var a = [
    [1, 2, 3],
    [2, 3, 4]
]
```

13. HTML DOM 下的 children以及childNodes的区别?

14. 什么是http 简单请求？和非简单请求？

15. 什么情况会出发options请求？

16. meta reload 和 refetch的区别？

17. web性能优化有哪些方法？

18. 如何理解函数的柯里化？


## Vue 题目

1. 有了解vue的函数组件么？functional组件？

2. 有了解vue的extend的么？如何使用？

3. 为什么不推荐组件通过想过继承，而是通过mixin来实现组件生成？

4. mixin 选项合并的规则,打印出的结果是什么？

```
var mixin = {
  created: function () {
    console.log('mixin')
  }
}

var a = new Vue({
  mixins: [mixin],
  created: function () {
    console.log('component')
  }
})
```

5. vue服务端渲染是否尝试？原理？



## react

1. react 16和15的生命周期的变化？

2. useEffect的用法？如何代替3个生命周期？

3. 什么是合成事件与原生事件？

4. Diff算法？

5. 合成事件与原生事件？

6. useContext + useReducer 如何构建私有redux?

7. react 性能优化？

8. useRef如何使用？


## Other

1. 随着项目周期变长，项目代码越来越多代码臃肿，编译 发布耗时长，如何去避免这类问题 

2. 如何理解微前端？有了解或尝试么。sing-spa？qiankun?

3. 如何规划组件的拆分？业务组件和基础组件的版本迭代管理？

4. 有搭建过前端脚手架的相关经验？

5. 有了解过AST是什么？起什么作用的？


