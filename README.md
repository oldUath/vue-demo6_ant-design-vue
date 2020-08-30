# ant-design-vue的学习
[ant-design-vue的网站](https://www.antdv.com/docs/vue/getting-started-cn/)
## 安装
```
yarn add ant-design-vue
```
在main.js中添加
```
import Vue from 'vue';
import Antd from 'ant-design-vue';
import App from './App';
import 'ant-design-vue/dist/antd.css';
Vue.config.productionTip = false;

Vue.use(Antd);

/* eslint-disable no-new */
new Vue({
  el: '#app',
  components: { App },
  template: '<App/>',
});
```

