# xuanwu（玄武）

主要研究下在 `Taro` 开发小程序过程中的一些最佳实践，以及坑点。

## 安装

```bash
pnnpm add @mini-xuanwu/xxxx
```

##

- [ ] 社区大部分的 `echarts` 组件并没有对 `Apache` 官方的库做同步更新；
  - 本仓库将做做佳实践以及持续同步更新；
- [ ] `Taro` 中 `useReady`/`onReady` 在条件渲染或者在子组件中无法执行；
  - 本仓库将使用 `hack` 方案做处理；
- [ ] `小程序` 中的滚动穿透问题；
  - `PageMeta` 方案；
