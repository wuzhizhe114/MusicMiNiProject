<template>
  <div class="container">
    首页
    <i-button>按钮</i-button>
  </div>
</template>

<script>

export default {
  data () {
    return {
      // motto: 'Hello World',
      // userInfo: {}
    }
  },

  components: {},

  methods: {
    // bindViewTap () {
    //   const url = '/packageA/logs'
    //   wx.navigateTo({ url })
    // },
    // getUserInfo () {
    //   // 调用登录接口
    //   wx.login({
    //     success: () => {
    //       wx.getUserInfo({
    //         success: (res) => {
    //           this.userInfo = res.userInfo
    //         }
    //       })
    //     }
    //   })
    // },
    // clickHandle (msg, ev) {
    //   // eslint-disable-next-line
    //   console.log('clickHandle:', msg, ev)
    // }
  },

  created () {
    // 调用应用实例的方法获取全局数据
    // this.getUserInfo()
  }
}
</script>

<style scoped>
</style>
