<template>
    <div class="title-info">
      <div class="top-fixed-header title">
        <div class="back" @click="$router.go(-1)">
          <!--<icon scale="1.6" name="angle-left"></icon>-->
          <img src="../../images/default/turnLeft1-1.png" width="25px" height="25px"/>
        </div>
        <div class="title-desc">{{titleContent}}</div>
      </div>
    </div>
</template>

<script>
  import 'vue-awesome/icons/angle-left'
  import Icon from 'vue-awesome/components/Icon'
  import 'mint-ui/lib/style.css'

  export default {
    name: 'title-info',
    props: {
      'titleContent': this.titleContent
    },
    components: {
      Icon
    }
  }
</script>

<style scoped>
  .title-info{
    margin:0 0 0 0;
    padding:0;
    height: 10px;
  }
  .title {
    text-align: center;
    box-sizing: border-box;
    padding: 10px 20px 0;
    font-size: 18px;
    font-weight: bold;
  }
  .back{
    position: absolute;
    top: 10px;
    left:15px;
  }
  .title-desc{
    color:white;
  }
</style>
