# 我是any-rule作者, 🔥2019年开发者让我新加了这些正则!

![1.png](https://ws1.sinaimg.cn/large/630deecfly1gaehq42crkj20ti0a0aao.jpg)

**实时star✨** 

<a target="new" href="https://github.com/any86/any-rule"><img src="https://img.shields.io/github/stars/any86/any-rule.svg?style=social"/></a>

6月28日开的项目, 截至本文star已经增长到**1625**, 这要非常感谢平台曝光和各位优质开发者的认可😊, 请收下微臣的膝盖orz. 

经过半年的维护, 共计解决了**45**条[issue](https://github.com/any86/any-rule/issues), 🍔根据开发者反馈新增了**14**条正则. 下面我就列出这些新增的正则, 算是为19年的[any-rule](https://github.com/any86/any-rule)做一个总结.

## 🍔 根据开发者反馈, 新增加的正则

### 火车车次
```javascript
/^[GCDZTSPKXLY1-9]\d{1,4}$/
```

### 手机机身码(IMEI)
```javascript
/^\d{15,17}$/
```

### 必须带端口号的网址(或ip)
```javascript
/^(((ht|f)tps?):\/\/)?[\w\-]+(\.[\w\-]+)+:\d{0,5}\/?/
```

### 网址(支持端口和"?+参数"和"#+参数)
```javascript
/^(((ht|f)tps?):\/\/)?[\w\-]+(\.[\w\-]+)+([\w\-.,@?^=%&:\/~+#]*[\w\-@?^=%&\/~+#])?$/
```

### 统一社会信用代码
```javascript
/^[0-9A-HJ-NPQRTUWXY]{2}\d{6}[0-9A-HJ-NPQRTUWXY]{10}$/
```

### 迅雷链接
```javascript
/^thunderx?:\/\/[a-zA-Z\d]+=$/
```

### ed2k链接(宽松匹配)
```javascript
/^ed2k:\/\/\|file\|.+\|\/$/
```

### 磁力链接(宽松匹配)
```javascript
/^magnet:\?xt=urn:btih:[0-9a-fA-F]{40,}.*$/
```

### 子网掩码
```javascript
/^(?:\d{1,2}|1\d\d|2[0-4]\d|25[0-5])(?:\.(?:\d{1,2}|1\d\d|2[0-4]\d|25[0-5])){3}$/
```

### linux"文件夹"路径
```javascript
/^\/(\w+\/?)+$/
```

### linux"文件"路径
```javascript
/^\/(\w+\/)+\w+\.\w+$/
```

### window下"文件夹"路径
```javascript
/^[a-zA-Z]:\\(?:\w+\\?)*$/
```

### window下"文件"路径
```javascript
/^[a-zA-Z]:\\(?:\w+\\)*\w+\.\w+$/
```

### A股代码
```javascript
/^(s[hz]|S[HZ])(000[\d]{3}|002[\d]{3}|300[\d]{3}|600[\d]{3}|60[\d]{4})$/
```

### 大于等于0, 小于等于150, 支持小数位出现5, 如145.5, 用于判断考卷分数
```javascript
/^150$|^(?:\d|[1-9]\d|1[0-4]\d)(?:.5)?$/
```


## 🚀 typescript系列课程
如果你对ts感兴趣了, 欢迎看看我的ts基础教程.

[第一课, 体验typescript](https://juejin.im/post/5d19ad6de51d451063431864)

[第二课, 基础类型和入门高级类型](https://juejin.im/post/5d1af3426fb9a07ed4411a9b)

[第三课, 泛型](https://juejin.im/post/5d27f160e51d45108223fcf9)

[第四课, 解读高级类型](https://juejin.im/post/5d3fe80fe51d456206115987)

[第五课, 命名空间(namespace)是什么](https://juejin.im/post/5d5d04dfe51d4561af16dd24)

[特别篇, 在vue3🔥源码中学会typescript🦕 - "is"](https://juejin.im/post/5da6d1aae51d4524ad10d1d8)

[第六课, 什么是声明文件(declare)? 🦕 - 全局声明篇](https://juejin.im/post/5dcbc9e2e51d451bcb39f123)

## 🧨 最后
还是要感谢平台, 希望新的一年平台越来越好.

## 微信群
![WechatIMG32646.jpeg](https://ws1.sinaimg.cn/large/630deecfly1gaekd016mnj20u0186whu.jpg)


## 微博
刚玩微博, 咱们可以互相关注, 嘿嘿
![weibo.png](https://ws1.sinaimg.cn/large/630deecfly1gaek9e85ynj20mi0scgnm.jpg)