---
title: 小蓝笔记本的首页
layout: default
---


# 欢迎来到我的笔记主页 ✨

这里是我整理的笔记索引，点击查看详情：

- [心理笔记](/GitNotebook/笔记库/心理笔记)

<ul>
  <li><a href="/GitNotebook/笔记库/物理笔记">物理笔记</a></li>
</ul>

---

- [ ] 这是个任务
  - [x] 更新测试

1. 好好<mark>好</mark>
  1. **不错不错**


### 数理模块：
> [!info]
> 公式前后必须要有空格，和其他内容分开（好像 $\KaTeX$ 可以不用？）
> 所以这个站点的所有公式是采用 $\KaTeX$ 引擎渲染


$$
\begin{align}
&\alpha + \beta  = \gamma \\
&F = \frac{\rm{d}p}{\rm{d}t}
\end{align}
$$

这是没有对齐包的公式块，当然也有 $E = mc^2$ 的行内公式 和`行内代码`

$$
F = \frac{\rm{d}p}{\rm{d}t}
$$



```mathematica
Plot[Sin@x, {x, -Pi, Pi}]
z = 6
Print[#&@%]
```

### 视频图片模块 

嵌入的b站视频：
<div style="position: relative; padding: 28.1% 45%;">
  <iframe src="//player.bilibili.com/player.html?isOutside=true&aid=228086186&bvid=BV1ch411L7aL&cid=1111035512&p=1&autoplay=0" frameborder="no" scrolling="no" allowfullscreen="true" sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts" style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;">
  </iframe>
</div>



嵌入图床图片：

- **普通md语法**
  
  ![这是图片注释](https://pica.zhimg.com/v2-29c64bd652a59a28a8c98952cb25c752_r.jpg){: style="width: 60%"}

  ```html
  <!-- 因为jekyll解析机制，会把md语法解析成下面的格式，
  而 alt语法 在静态页面中不显示 -->
  <img 
      src="https://pica.zhimg.com/v2-29c64bd652a59a28a8c98952cb25c752_r.jpg" 
      alt="图片描述"
      width="60%" >
  ```


- **这是html图文组合，不是md语法**
<figure style="text-align: center; width: 60%; margin: 0 auto;">
  <img src="https://pica.zhimg.com/v2-29c64bd652a59a28a8c98952cb25c752_r.jpg" alt="示例图片">
  <figcaption style="font-size: 0.9em; color: #88; margin-top: 1px;">图片说明：这是一张示例图片</figcaption>
</figure>
