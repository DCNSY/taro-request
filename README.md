# taro-request
> 对Taro.request进行封装

### **仅适用于taro项目**

## 目录结构

```
servers
├── api.js
├── config.js
├── interceptors.js
├── servers.js               //建议所有接口请求整理在一起再按需引用
└── utils.js
```
###### 组件内使用eg:
```
import { getResultData_servers } from '@src/servers/servers'

getResultData_servers(params).then(res => {
  console.log(res)
}).catch(err => {
  console.log(err)
})

```
* [示例项目](https://github.com/TigerHee/taro-init)
