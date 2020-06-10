# 适合1-2年工作经验前端开发
## Javascript 题目

1. const、let、var的区别？
  
  
2. 运行下面代码，打印的结果是什么? 为什么？
```
FunOne();
FunTwo();
function FunOne () {
    console.log('this is FunOne');
}
var FunTwo = function () {
    console.log('this is FunTwo');
}
```

3. 运行下面代码，打印的结果是什么? 将var改let打印的结果？为什么？
```
for(var i = 0; i < 10; i++){
    setTimeout(function(){
        console.log(i);
    },100);
}
```

4. 解释一下this指向？
```
var a = {
    doit: function () {
        console.log(this)
    },
    doit1: () => {
        console.log(this)
    }
}
a.doit()
a.doit1() 
var b = a.doit
b()
var c = a.doit1
c()
```

5. js prototype的作用（原型链）？__proto__是什么可以修改吗？

6. call、apply、bind的区别？箭头函数能否被修改上下文？

7. javascript 的6大类？

8. 邮箱的正则匹配？

9. 手机号的正则匹配？

10. 运行如下代码的结果？为什么？
```
console.log(['1', '7', '11'].map(parseInt))
```

11. js 判断类型有哪几种方法？

12. typeof与instanceof的区别？

13. session 和 cookie 的区别

14. localStorage 和 sessionStorage的区别？ 

15. cookie的作用？cookie在设置path后对domain的影响？



## Vue 题目

1. watch和computed的区别？

2. vuex的作用？描述state,getter，mutation,action运行的流程？

3. vue的生命周期有哪些？

4. vue-router 的实现模式？两者的区别？

5. vue keep-alive的作用？

6. vue中 key 值的作用？

7. v-model的作用？

8. v-on 能一次监听多个事件么？

9. vue template 不同写法？

10. 子组件为什么不可以修改父组件传递的Prop？

11. vue.extend和vue.extends的区别？

12. vue mixin的作用？

13. mvvm框架是什么？

14. 为什么要用到vue.$set


## react

1.	key的作用？

2.	React组件创建的方式？

3.	函数组件是否会被实例化？能访问this?

4.	React生命周期有哪些？16或15版本

5.	React组件传值有哪些方法？

6.	React hooks 有什么作用？

7.	是否使用umi? 追问dva和redux的区别？

8.	在react中如何使用innerHTML?

9.	Refs有什么作用？什么时候使用？

10.	什么是可控组件？

11.	什么是非可控组件？

12.	什么是Purecomponent? 

13.	React.Fragment起什么作用？

14.	useState的用法？

15.	为什么虚拟dom会提高性能？

16.	什么是高阶组件？


