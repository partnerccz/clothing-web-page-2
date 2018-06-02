<template>
  <div class="bottom-fixed-footer">
    <table>
      <!--<tr>-->
      <!--<td><router-link  to="/" replace><icon scale="1.2" name="home"></icon><div style="color: white;margin-top:1px;">首页</div></router-link></td>-->
      <!--<td><router-link to="/classify" replace><icon scale="1.2" name="th"></icon><div style="color: white;margin-top:1px">分类</div></router-link></td>-->
      <!--&lt;!&ndash;<td><router-link to="/a"><icon scale="1.2" name="heart"></icon><div>赚钱</div></router-link></td>&ndash;&gt;-->
      <!--<td><router-link to="/cart" replace><icon scale="1.2" name="shopping-cart"></icon><div style="color: white;margin-top:1px">购物车</div></router-link></td>-->
      <!--<td><router-link to="/person" replace><icon scale="1.2" name="user"></icon><div style="color: white;margin-top:1px">我的</div></router-link></td>-->
      <!--</tr>-->
      <tr>
        <td>
          <router-link to="/" replace>
            <img src="../../images/bottommenuicon/home0.png" width="25px" height="25px"/>
            <div class="bottom-common-color">首页</div>
          </router-link>
        </td>
        <td>
          <router-link to="/classify" replace>
            <img src="../../images/bottommenuicon/classify0.png" width="25px" height="25px"/>
            <div class="bottom-common-color">分类</div>
          </router-link>
        </td>
        <!--<td><router-link to="/a"><icon scale="1.2" name="heart"></icon><div>赚钱</div></router-link></td>-->
        <td>
          <router-link to="/cart" replace>
            <img src="../../images/bottommenuicon/shopCart0.png" width="25px" height="25px"/>
            <div class="bottom-common-color">购物车</div>
          </router-link>
        </td>
        <td>
          <router-link to="/person" replace>
            <img src="../../images/bottommenuicon/myIcon0.png" width="25px" height="25px"/>
            <div class="bottom-common-color">我的</div>
          </router-link>
        </td>
      </tr>
    </table>
  </div>
</template>

<script>
  import 'vue-awesome/icons/home'
  import 'vue-awesome/icons/th'
  import 'vue-awesome/icons/heart'
  import 'vue-awesome/icons/shopping-cart'
  import 'vue-awesome/icons/user'
  import Icon from 'vue-awesome/components/Icon'

  export default {
    name: 'BottomMenu',
    components: {
      Icon
    },
    created: function () {
    },
    mounted: function () {
    },
    data () {
      return {
        homeIcon: [
          {
            homeIconIndex: 0,
            homeIconUrl: require('../../images/bottommenuicon/home0.png')
          },
          {
            homeIconIndex: 1,
            homeIconUrl: require('../../images/bottommenuicon/home1.png')
          }
        ],
        classifyIcon: [
          {
            classifyIconIndex: 0,
            classifyIconUrl: require('../../images/bottommenuicon/classify0.png')
          }, {
            classifyIconIndex: 1,
            classifyIconUrl: require('../../images/bottommenuicon/classify1.png')
          }
        ],
        shopCartIcon: [
          {
            shopCartIconIndex: 0,
            shopCartIconUrl: require('../../images/bottommenuicon/shopCart0.png')
          }, {
            shopCartIconIndex: 1,
            shopCartIconUrl: require('../../images/bottommenuicon/shopCart1.png')
          }
        ],
        myIcon: [
          {
            myIconIndex: 0,
            myIconUrl: require('../../images/bottommenuicon/myIcon0.png')
          }, {
            myIconIndex: 1,
            myIconUrl: require('../../images/bottommenuicon/myIcon1.png')
          }
        ]
      }
    },
    methods: {}
  }
</script>
<style>
  .bottom-fixed-footer{

  }
</style>
<style scoped lang="scss">
  .bottom-fixed-footer table {
    width: 100%;
    height: 100%;
    text-align: center;
    line-height: 16px;
    a {
      color: #6a6a6a;
    }
    div {
      font-size: 10px;
    }
    i {
      font-size: 16px;
    }
  }
  .bottom-common-color{
    color:#EB89AA;
  }
</style>
<style>
  /*.bottom-fixed-footer .router-link-exact-active,*/
  /*.bottom-fixed-footer a:-webkit-any-link {*/
  /*color: inherit;*/
  /*}*/
  .bottom-fixed-footer .router-link-exact-active {
    /*.bottom-fixed-footer .router-link-active {*/
    color: black !important;
  }
</style>
