<template>
  <div>
    <nav class="navbar navbar-default navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="/">LOGO</a>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
          <ul class="nav navbar-nav">
            <li class="active"><a href="/">我的企业</a></li>
            <li><router-link to="/student/ciroffriend">朋友圈</router-link></li>
            <li><a href="#contact">我的学习</a></li>
            <li><a href="#contact">我的派送</a></li>
            <li><router-link to="/student/myresume">个人资料</router-link></li>
            <li><search></search></li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
            <li class="active"><a href="../navbar-static-top/">登录</a></li>
            <li><a href="./">注册 <span class="sr-only">(current)</span></a></li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  
</template>
<script>
import search from './search'
export default {
  components: {
    search
  }
}
</script>

