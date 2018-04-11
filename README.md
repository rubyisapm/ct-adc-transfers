## ct-adc-transfers

list-list穿梭框组件

## 组件示例图

[!img](图片地址)

## 在线demo

[在线demo]({在线demo地址})

## 功能点

1.
2.
3.

## 使用

从npm安装ct-adc-transfers

```
npm install ct-adc-transfers --save
```
在代码中使用

```
import {LLTransfer} from 'ct-adc-transfers';

var LLTransfer = LLTransfer;
Vue.component(LLTransfer.name,LLTransfer);

或

new Vue({
    el: '#app',
    components: {
        LLTransfer
    }
})
```

## props

参数 | 说明 | 类型 | 默认值 | 可选值 | 描述 |
--- | --- | --- | --- | ---- | ---
dataSource | 原始数据 | Array | []
selectedItems | 已选择的列表(右边的数据) | Array | []
matchKey | 自动匹配输入时可被匹配的key | Array | ['Id']
showKey | 显示在单个列表项中的key，如果key有多个,组件采用'-'进行分割内容 | Array | ['Name']
leftLoading | 左侧列表加载状态 | Boolean | false
rightLoading | 右侧列表加载状态 | Boolean | false
button | 按钮的html内容 | Object(button.toLeft / button.toRight) | false
leftListTitle | 左侧列表的title | String | '全部列表'
rightListTitle | 右侧列表中的title | String | '已选择列表'


## 方法

### 方法名称

方法描述。。。。。。

#### 参数列表

参数 | 说明 | 类型 | 默认值 | 可选值 | 描述 |
--- | --- | --- | --- | ---- | ----
readable | 说明 | Boolean | true |  |

返回值

类型: {Object}

说明: ......

## 事件

### 事件列表

事件名称 | 说明 | 回调参数 | 描述
change | 选中值发生改变 |  | 当穿梭框的'向左'/'向右'被执行后触发该事件。

## 更新日志

[更新日志]({CHANGELOG.md的线上地址})

## 外部资源依赖列表

无

