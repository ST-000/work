#### XX项目开发文档

当前版本 | 作者 | 编写说明日期 
---|---|---|---
1.0 | 孙腾 | 2019.12.11 


#### 项目综述

- 项目主要功能

登录、注册、主页面、查看成绩、提交成绩

- 项目受众

老师、学生

- 项目目的

方便老师了解学生的学习成绩,关注学生学习动态


#### 项目目录概述
前端
```
|---node_modules
|---public
|---src
|----|---api
|----|----|---info.js
|----|----|---login.js
|----|----|---registry.js
|----|---assets
|----|---components
|----|---config
|----|----|---element.config.js
|----|---router
|----|----|---index.js
|----|---store
|----|---utile
|----|----|---request.js
|----|---views
|----|----|---Login
|----|----|----|---index.js
|----|----|---Home
|----|----|----|---index.js
|----|----|---Index
|----|----|----|---index.js
|----|---APP.vue
|----|---main.js
|---gitignore
|---babel.config.js
|---package-lock.json
|---package.json
|---README.md
|---vue.config.js
```




后台
```
|---app
|----|---controller
|----|----|---index.js
|----|----|---user.js
|----|---public
|----|---router.js
|---config
|----|---config.default.js
|----|---plugin.js
|---logs
|---node_modules
|---run
|---app.js
|---package-lock.json
|---package.json
```



#### 项目功能概述
功能 | 作者 | 实现思路 | 使用技术 
---|---|---|---|---
首页侧边弹窗 | 孙腾 | 用egg搭建后台、验证前端，结合数据库储存数据，用vue写前端 | egg,数据库,vue


#### 项目开发周期
<table>
	<tr>
	    <th rowspan="2">模块</th>
	    <th colspan="2">开发时间</th>
	    <th colspan="2">测试时间</th>  
	</tr >
	<tr>
	    <th >计划时间</th>
	    <th>完成时间</th>
        <th>计划时间</th>
	    <th>完成时间</th>
	</tr>
	<tr>
	    <td>egg后台</td>
	    <td>12.11-12.12</td>
        <td>12.11-12.12</td>
	    <td>12.12-12.12</td>
        <td>12.12-12.12</td>
	</tr>
	<tr>
	    <td>登录</td>
	    <td>12.12-12.13</td>
        <td>12.12-12.13</td>
	    <td>12.13-12.13</td>
        <td>12.13-12.13</td>
	</tr>
	<tr>
	    <td>注册</td>
	    <td>12.14-12.15</td>
        <td>12.14-12.15</td>
	    <td>12.15-12.15</td>
        <td>12.15-12.15</td>
	</tr>
	<tr>
	    <td>主界面</td>
	    <td>12.15-12.16</td>
        <td>12.15-12.16</td>
	    <td>12.16-12.16</td>
        <td>12.16-12.16</td>
	</tr>
	<tr>
	    <td>查看成绩</td>
	    <td>12.17-12.18</td>
        <td>12.17-12.18</td>
	    <td>12.18-12.18</td>
        <td>12.18-12.18</td>
	</tr>
	<tr>
	    <td>提交成绩</td>
	    <td>12.18-12.19</td>
        <td>12.18-12.19</td>
	    <td>12.19-12.19</td>
        <td>12.19-12.19</td>
	</tr>
</table>
