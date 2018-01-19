<template>
  <div>
       <div class="login">
    <!-- 顶部 -->
    <div class="header">
      <div class="top">
        <div class="fl">
          <img src="logo.png" alt="">
        </div>
        <div class="fr">
          <li>关于BOE</li>
          <li>|</li>
          <li>English</li>
        </div>
      </div>
    </div>
  <!-- 中间登录框 -->
    <div class="center">
        <div class="denglu">
          <h2>登录平台</h2>
          <form action="javascript:;">
            <div>
              <label for="username"></label>
              <input type="text" placeholder="请输入用户名" id="username">
            </div>
            <div>
              <label for="password"></label>
              <input type="password" placeholder="请输入密码" id="password">
            </div>
            <div>

            </div>

          </form>
        </div>
        </div>
    </div>
    <!-- 底部信息 -->
    <div class="footer">
      <span>Copyright@2018 京东方科技集团股份有限公司</span>
    </div>
  </div>
  </div>
</template>

<script>
export default {

  data () {
    return {
        radio: '1'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
