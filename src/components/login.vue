<template>
  <div>
       <div class="login">
    <!-- 顶部 -->
    <div class="header">
      <div class="top">
        <div class="fl">
          <li>BOE</li>
          <li>|</li>
          <li>协同创新平台</li>
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
              <i></i>
              <input type="text" placeholder="请输入用户名">
            </div>
            <div>
              <i></i>
              <input type="password" placeholder="请输入密码">
            </div>
            <div>
              <input type="text">
            </div>
            <div>
               <el-radio v-model="radio" label="1">English</el-radio>
              <el-radio v-model="radio" label="2">简体中文</el-radio>
            </div>
            <div></div>

          </form>
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
