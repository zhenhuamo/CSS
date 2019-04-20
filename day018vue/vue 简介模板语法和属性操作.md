vue js:
    是一个类似于jquery的js库（框架)
    
    MVVM:
        M   model:模型 数据模型
        V   view: 视图
        vm  viewModel:  视图数据模型的实例
        
    实现双向数据绑定：
        当model当中的数据发生变化，视图里面的数据也会跟着发生变化
        如果视图当中的数据发生变化，model当中的数据也会发生变化
    
模板语法:
    {{}}
    可以写数值类型，字符串，对象，数组，简单运算
    不能写表达式
文本指令：
以v-开头，对html元素的功能拓展
    v-html 可以解析标签
    v-text 不可以解析标签
    
属性操作：
    v-bind:属性名=""
    简写   :属性名=''
    
类名操作：
    数组语法：
    v-bind:class=[变量名，变量名]、
    data{
        变量名:类名
    }
    对象语法：
    v-bind:class={类名：true/false}
style的操作：
    数组语法：
    :style=[obj1,obj2]
    data{
        obj1:{
            width:'100px',
            height:'100px',
            background:'red',
        },
        obj2:{
            border:'1px solid green'
        },      
    } 
    对象语法：
    :style= {width;w}
    data:{
        w:'100px',
    }     
    