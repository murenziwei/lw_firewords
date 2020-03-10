# 鼠标点击小烟花特效
#### 介绍
鼠标点击出现小烟花特效

#### 在线演示
https://murenziwei.github.io/lw_firewords/index.html

#### 源码Git地址

Gitee: https://gitee.com/murenziwei/lw_firewords.git

Github: https://github.com/murenziwei/lw_firewords.git

#### 主要内容

我在浏览某个博文时，偶然遇到的一个小特效，简单又好看，自己也搞了一个，顺便模块化，上传到npm，方便适用于node项目

#### 用法

npm安装

`npm i lw_firewords -S`

导入lw_firewords包

```javascript
import LwFirewords from 'lw_firewords'
```

导入成功，创建烟花实例

```javascript
const lw_f = new LwFirewords();//创建实例
lw_f.init();//启动事件
```
