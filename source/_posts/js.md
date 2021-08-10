---
titile: js Object
tags: JavaScript ES6+
---

## Object扩展方法
 ### Object.create()
 ```
 var car = {name:"汽车"，run:function(){console.log('跑起来')}}
 var Passat = Object.create(car,{
 brand:{
 value:'帕萨特',
 writabkle:true, //属性是否可以修改
 configurable:true,//属性是否可以删除
 enumerable：false // 属性是否可以枚举 }，
 price:{
 get:function(){},
 set:function(){}
 }
 })
 ```
 ### Object.defineProperties()

 ```
let sanlun = {name : "三轮车"}
Object.defineProperties（sanlun,{
brand: {value:'zzz'}
})

```

