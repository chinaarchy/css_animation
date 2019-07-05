### 任务目的
- 熟悉 CSS3 过渡子属性
- 通过 JavaScript 触发过渡效果
- 理解语义化，合理地使用 HTML 标签来构建页面


### 任务笔记
- transition(过渡动画)

```
transition ：[<'transition-property'> || <'transition-duration'> ||
  <'transition-timing-function'> || <'transition-delay'> [, [<'transition-property'> 
  || <'transition-duration'> || <'transition-timing-function'> || <'transition-delay'>]]* 
```

|参数|描述|
|----|----|
|transition-property|设置过渡效果的CSS属性的名称|
|transition-duration|设置完成过渡效果需要的时间|
|transition-timing-function|设置完成效果的速度曲线|
|transition-delay|设置效果的延迟时间|

- 兼容性：
- IE10+, Firefox16+, Chrome26+ ,Safari6.1+ , iOS Safari7+, Android Browser4.4+, Android Chrome25+
- 兼容方法：
```$xslt
p {
  -webkit-transition: all .5s ease-in-out 1s;
  -moz-transition: all .5s ease-in-out 1s;
  -o-transition: all .5s ease-in-out 1s;
  transition: all .5s ease-in-out 1s;
}
```