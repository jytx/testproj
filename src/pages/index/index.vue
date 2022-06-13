<template>
  <view class="index">
    <text @tap="sayHello">{{ msg }}</text>
  </view>
</template>

<script>
import './index.scss'

export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  },
  methods:{
    async sayHello(){
      await new Promise((resolve, reject) => {
        resolve()
      })
    }
  }
}
</script>
