# vue-mall

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```
# 1、
vue.config.js配置scss
# 2、
component: () => import("@/views/Test.vue") 导入组件
# 3、
箭头函数：const Test = data => console.log(data);
# 4、
axios封装request的配置，api调用request、
# 5、
config.vue.js代理配置
# 6、
promise讲解，链式嵌套记得return promise
# 7、
.vue里面import scss文件
# 8、
路由设置一个hidden属性（自定义）来判断是显示在左侧列表栏里、使用template标签包裹（解决v-for和v-if同时会报错的问题）
# 9、
el里面的navMenu的router属性，来跳转，path作为路径
# 10、
修改el样式不能在vue的scoped改，全局scss改，在vue.config.js里面引入
# 11、
使用svg必须安装svg-sprite-loader依赖
# 12、
props传参required、validator属性、如果类型是数组 default: () => []
# 13、
const svgClass = computed(() => {
      if (props.className) {
        return `svg-icon ${props.className}`;
      } else {
        return `svg-icon`;
      }
    });


# 14、
vuex,异步：action里面需要请求接口返回token，然后再去调用commit，详细见登陆
# 15、
路由守卫
# 16、
封装弹窗等组件 => watch解决单向传值问题
# 17、
自定义全局方法global，封装vuex全局方法
# 21-5 filter 和 map 的使用
# array JSON数组
let arrayData = data.filter(item => item.id == catagory.Id)[0];
# id数组
let arrayId = data.map(item => item.id);