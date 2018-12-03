<template>
  <div class="hello">
<pre>
一、环境准备：（打开cmd窗口）
	node -v			如果没有显示版本号，安装node
	vue -V 			如果没有显示版本号，cnpm install vue-cli -g 安装
	webpack -v 		如果需要重新安装，cnpm install webpack -g  
	vue init webpack name	生成vue-cli 项目 
			等待生成项目
	cd name			进入目录
	cnpm install		安装依赖
	cnpm run dev		启动项目	按ctrl+C 返回CMD命令行模式
			浏览器输入http://localhost:8080	出现Vue图标的页面 则运行成功
二、项目各目录介绍：
	src/			存放源代码的目录
	src/assets/ 		这里存放css js 等资源
	src/components/		这里放.vue 的组件
	src/router/index.js		这里配置路由
	src/App.vue		这是根组件
	src/main.js		这是程序主入口
</pre>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
