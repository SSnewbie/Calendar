# jquery日历 周历 插件
给别人做的，时间也比较急，感觉很多地方都没做好，而且也不像插件，这个准备慢慢填坑...
bug较多！在项目中请谨慎使用！！

## 部分效果截图
![](screenshot/demo.gif)

## todo

### 修复
- [ ] 重新设计周历的核心算法或者对现在算法的边界情况进行测试
- [X] 事件重复绑定的bug修复
- [ ] 兼容测试
- [ ] 优化动画
- [ ] 整理应该向外暴露的api
- [ ] 重构部分冗余代码

### 新功能
- [ ] 可以自定义样式，提供友好的接口

### 预计开放api
**调用方法$(selector).Calendar(api);**
- [ ] 获取选择的时间
- [X] 切换到周历/月历（动画）
	- $(selector).Calendar('switchWeek'); //切换到周历
	- $(selector).Calendar('switchMonth'); //切换到月历
- [X] 切换到 上/下 一 周/月/（动画）
	- $(selector).Calendar('switchPreMonth') //切换到上一月
	- $(selector).Calendar('switchNextMonth') //切换到下一月	
- [X] 切换到当前的时间的 周/月历（动画）（初始化状态）
	- $(selector).Calendar('init');

### 事件
- [ ] 当前选择时间变化事件 参数(currentDate,originDate)

- [ ] 周历月历变化事件 参数(flag)



