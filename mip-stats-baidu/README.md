# mip-stats-baidu

mip-stats-baidu 用来支持站长添加百度统计。

描述|百度统计组件，用于统计页面数据
----|----
类型| 通用
支持布局|N/S
所需脚本|https://mipcache.bdstatic.com/static/v1.2/mip-stats-baidu.js

## 示例

MIP提供百度统计的插件，便于分析页面数据，需要提前到百度统计这边创建站点，会自动生成js代码使用提取工具提取token，并使用MIP提供的插件，代码示例：

```
    <mip-stats-baidu token="02890d4a309827eb62bc3335b2b28f7f"></mip-stats-baidu>
```

## 属性

### token

说明：token
必填：是
格式：字符串
