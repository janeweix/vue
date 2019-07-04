1. 看书。JSON，Ajax.

2. 学习vue。

* 插值表达式

* 指令，v-text，v-html，v-if，v-show，v-for，v-on，v-bind

* 组件通信，props和$emit

* slot插槽

* 过滤器，局部过滤器与全局过滤器

* watch监听，监听简单类型和复杂类型的数据

```
watch: {
    // 基本数据类型
    msg: function(newV, oldV) {
        console.log(newV, oldV);
        if(newV === "hello") {
            console.log("world");
        }
    },
    // 复杂数据类型（array，object）要深度监听
    stu: {
        deep: true, // 深度监听
        handler: function(newV, oldV) {
            console.log(newV);
        }
    }
}
```

* 计算属性，getter和setter

* 生命周期

```
beforeCreate
created
beforeMount
mounted
beforeUpdate
updated
activated
deactivated
beforeDestroy
destroyed
errorCaptured
```