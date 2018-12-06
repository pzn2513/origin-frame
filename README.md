# Origin前端框架
### 宗旨：高效与自由
## Version-0.1.0目录结构

~~~diff
部署目录==
+├─template      页面每个组件的html+css+js，最后将通过巧妙的页面设计，写入父级组件（页面）的js动态加载
+ ├─js            
│  ├─lib        高频实用的js函数库，例如数据处理=>data.js，交互（例如模板渲染与双向绑定）=>interact.js,url请求=>url.js等
│  ├─commom     自定义的公共调用函数
├─source        图片、字体（推荐iconfont.com，管理一套自己熟悉的）、文件等资源文件
├─kit           封装成熟的组件
├─index.html    入口文件
~~~

## Version-0.1.0 重要思想
- 1、将大页面页面分成一个个组件，在一个html文件里结合css+js能实现模块化、低耦合、清晰高效地开发。（中后期将可能面临命名冲突，但现在靠规范命名解决）
- 2、有命名纠结症的人应该能有体会，所以有必要规范一个优秀的命名方式：id可以多用，但需要靠命名取规范唯一性，连接符用下划线（方便js直接写id名称选中，例如nav_top,nav_0），id的子类可以用id.children[]、id.querySelectorAll()，剩下的用class（尽量简单，例如a、b、a0、a1，id.querySelectorAll('.a')这样选中），最后一旦id冲突也能很明细的发现问题及时解决。
- 3、由于现代浏览器将<style><script>同样视为dom元素，为动态引入提供了很好的基础，因此模块化也是基于此思想进行简单而巧妙地设计，想要理解请多看demo

## 你厌倦了大型框架的条条框框、一知半解、重复定义、臃肿等现象吗?
- 这是一款从原生css+js从头打造的框架，遵循"模块化"、"轻量"、"高效"、"自由"、"粒度调控"、"防护"的开发哲学，目前架构简单清晰，掌握它会对代码思路和脉络熟悉后理解能力和开发速度都会上一个档次，从0.0到1.0就是进阶大神之路。
- 悉心经营这个从新一代浏览器技术上构建的开源共识框架，借鉴行业内精炼优秀的代码，不弄花里胡哨的噱头，踏踏实实讲究高效开发、自由开发。因此值得长期投资，不断学习地过程中也将不断提升思维的深度与广度，能力加速累加效应将会使长期投入的人受益匪浅。
