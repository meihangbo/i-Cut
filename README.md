﻿##UI开发框架

这个框架适合用与手机和响应式页面制作，陆续更新中，不断实践和修复bug。

##项目的src/css文件解释

onebase.css是底层文件，没有设置任何关于数值的属性

style.css是设置关于有数值的样式的文件(有响应式栅格)

t.css是设置关于组件样式的文件

##移动端开发规则

规则1：要求设计师设计的PSD宽度为640px或其他标准尺寸，但DPI必须是为72,这样才接近一比一还原。

规则2：在index.html中head加了一段js,这个是为了动态改变根元素的字体大小，变量改成你设计稿的大小。

规则3：字体单位为REM,PSD里的字体点数除以10就是字体大小。建议用Flexbox布局。

规则4：宽度、高度、内边距、外边距的单位全部为百分比（目标PSD宽度/PSD尺寸宽度）

##响应式开发

文件名为cc.html里有案例，对于平常用的bootstrap框架的同学一下就能看懂，吸(有)取(点)精(污)华用于自己的项目中。

这里有篇文章讲得挺好的，推荐一下，希望对大家有帮助（对布局的重点讲得很好，最好自己懂得些设计）

https://www.douban.com/note/489518516/


