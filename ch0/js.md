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

13. session 和 token 的区别

14. localStorage 和 sessionStorage的区别？ 

15. cookie的作用？cookie在设置path后对domain的影响？
