<template>
  <div class="homePage">
    <img class='bg' src="../assets/img/bg.png"/>
    <div class="wraps">
         <a href="#/four" class="enter_btn">
            <img  mode="widthFix" src="../assets/img/enter_4.png"/>
         </a>
          <a href="#/six" class="enter_btn">
               <img  mode="widthFix" src="../assets/img/enter_6.png"/>
          </a>
         <a href="#/nine" class="enter_btn">
             <img  mode="widthFix" src="../assets/img/enter_9.png"/>
         </a>
    </div>
  </div>
</template>

<script>
export default {
  data () { // 选项 数据
    return {

    }
  },
  components: { // 定义组件

  },
  methods: { // 事件处理方法

  },
  created () { // 生命周期函数

  }

}
</script>

<style lang="less">
.homePage{
    width: 100%;
    height: 100%;
    .bg{
      width: 100%;
      height: 100%;
      display: block;
    }
    .enter_btn{
      display: inline-block;
      width: 130/7.5VW;
      margin-right: 70/7.5VW;
      img{
          width: 100%;
          height: auto;
      }
    }
    .wraps{
      position: absolute;
      bottom: 110/7.5VW;
      z-index: 10;
      padding-left: 100/7.5VW;
    }
}
</style>
