# fe-repo
front end repo

## vue+element+ui

### 动态添加表格

![动态添加表格](images/动态添加表.png)
 主要思路就是我们在创建时运用 `v-for` 来创建这边的表格 ,具体数据用 `[[]]`,我们在创建表的时候，我们通过将这个`array.push([])`

具体代码在`.\code\dynamic-add-table\App.vue`  

### 父子传递数据

+ 父向子传递数据使用`props`
+ 子向父传递数据使用`$emit`调用父级的方法，并传递参数
