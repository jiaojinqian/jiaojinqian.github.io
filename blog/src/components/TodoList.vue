<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li> <h2>	JS基础：	</h2></li>
      <li> <a  href="#">	1.DOM，BOM	</a></li>
      <li> <a  href="#">	2.ajax	</a></li>
      <li> <a  href="#">	3.jsonp	</a></li>
      <li> <a  href="#">	4.cors跨域	</a></li>
      <li> <a  href="#">	5.jquery，zepto	</a></li>
      <li> <a  href="#">	6.Html5 + CSS3	</a></li>
      <li> <a  href="#">	7.Html + css	</a></li>
      <li> <a  href="#">	8.常用布局：基础常用 + 瀑布流...	</a></li>

      <li> <h2>	JS版本	</h2></li>
      <li> <a  href="#">	Es5，es6，es7	</a></li>
      <li> <a  href="#">		</a></li>
      <li> <a  href="#">	JS版本转码器	</a></li>
      <li> <a  href="#">	babel，typescript	</a></li>

      <li> <h2>	前端进阶：	</h2></li>
      <li> <a  href="#">	http协议	</a></li>
      <li> <a  href="#">	函数式编程	</a></li>
      <li> <a  href="#">	javascript设计模式	</a></li>
      <li> <a  href="#">	promise	</a></li>
      <li> <a  href="#">	sass less postcss	</a></li>

      <li> <h2>	移动端开发：	</h2></li>
      <li> <a  href="#">	Rem,em,px	</a></li>
      <li> <a  href="#">	媒体查询	</a></li>
      <li> <a  href="#">	Viewpoint	</a></li>
      <li> <a  href="#">	Meta	</a></li>
      <li> <a  href="#">	flexbox弹性盒模型	</a></li>
      <li> <a  href="#">	响应式布局	</a></li>
      <li> <a  href="#">	终端交互优化：tap，iscoll，touch事件，跨终端web	</a></li>
      <li> <a  href="#">	Html5，css3	</a></li>
      <li> <h2>	微信开发：	</h2></li>
      <li> <a  href="#">	微信公众号	</a></li>
      <li> <a  href="#">	微信小程序	</a></li>

      <li> <h2>	前端性能相关：	</h2></li>
      <li> <a  href="#">	浏览器内核原理	</a></li>
      <li> <a  href="#">	http请求流程	</a></li>
      <li> <a  href="#">	页面加载流程	</a></li>

      <li> <h2>	前端框架：	</h2></li>
      <li> <a  href="#">	vue vuex	</a></li>
      <li> <a  href="#">	react flux redux	</a></li>
      <li> <a  href="#">	angular	</a></li>
      <li> <a  href="#">	react native weex	</a></li>
      <li> <a  href="#">	虚拟dom	</a></li>
      <li> <a  href="#">	框架设计	</a></li>

      <li> <h2>	前端模块化：	</h2></li>
      <li> <a  href="#">	amd,cmd,umd,commonJS模式	</a></li>
      <li> <a  href="#">	Requires,seajs	</a></li>
      <li> <a  href="#">		</a></li>
      <li> <h2>	前端构建工具：	</h2></li>
      <li> <a  href="#">	webpack，browserify	</a></li>
      <li> <a  href="#">	grunt，gulp	</a></li>
      <li> <h2>	JS包管理器：	</h2></li>
      <li> <a  href="#">	npm  	</a></li>
      <li> <a  href="#">	yarn	</a></li>
      <li> <a  href="#">	bower	</a></li>

      <li> <h2>	版本控制：	</h2></li>
      <li> <a  href="#">	git	</a></li>
      <li> <a  href="#">	svn	</a></li>

      <li> <h2>	服务端开发：	</h2></li>
      <li> <a  href="#">	nodejs	</a></li>
      <li> <a  href="#">	express	</a></li>
      <li> <a  href="#">	eggjs	</a></li>
      <li> <a  href="#">	koajs	</a></li>

      <li> <h2>	服务器操作：	</h2></li>
      <li> <a  href="#">	linux命令	</a></li>
      <li> <a  href="#">	nginx	</a></li>

      <li> <h2>	数据库：	</h2></li>
      <li> <a  href="#">	mysql	</a></li>
      <li> <a  href="#">	mongoDB	</a></li>
      <li> <a  href="#">	mongoose	</a></li>
      <li> <a  href="#">	redis	</a></li>

      <li> <h2>	前端算法	</h2></li>
      <li> <a  href="#">	排序	</a></li>
      <li> <a  href="#">	查找	</a></li>

      <li> <h2>	前端技术点：	</h2></li>
      <li> <a  href="#">	前端优化	</a></li>
      <li> <a  href="#">	animation	</a></li>
    </ul>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
      <li><a href="https://github.com/PanJiaChen/vue-element-admin" target="_blank">vue-element-admin</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'todoList',
  data () {
    return {
      msg: 'My TodoList'
    }
  }
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
  display: block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
