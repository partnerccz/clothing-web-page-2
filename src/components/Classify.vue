<template>
  <div style="width:100%;height: 100%;">
    <top-search></top-search>
    <!--<div class="classify">-->
      <!--<div v-for="item in typeGroups" class="item line-block" :key="item.id">-->
        <!--<div class="title">{{item.name}}</div>-->
        <!--<div class="item-child">-->
          <!--<router-link v-for="itemChild in types" v-if="itemChild.group_id == item.id" :to="productListUrl(itemChild.id)" :key="itemChild.id">{{itemChild.name}}</router-link>-->
        <!--</div>-->
        <!--<router-link :to="productListGroupUrl(item.id)" class="more">全部</router-link>-->
      <!--</div>-->
    <!--</div>-->
    <div class="classify" style="display: flex;flex-direction: row;height: 100%;margin-bottom:5px;">
      <ul style="font-size:18px;cursor: pointer;flex: 2; height: 100%;">
        <li v-for="item in typeGroups" :key="item.id" @click.navite="" style="text-align:center;height: 50px;line-height: 50px;background-color: #EB89AA;border-bottom: 1px solid white;color: white;">{{item.name}}</li>
      </ul>
      <div style="flex: 5;">
        <ul>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333;"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
          <li style="width:96%;height: 100px;background-color: white;margin:5px auto 0;display:flex;flex-direction: row;">
            <div style="width: 100px;height: 100px;background-color: white;">
              <img width="94px" height="94px" style="margin:3px;" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1817078193,1178912899&fm=27&gp=0.jpg"/>
            </div>
            <div style="padding:3px 10px;position: relative;width: 100%;">
              <div style="font-size:16px;color:#333"><span>进口</span>智利产JJJ车厘子</div>
              <div style="font-size:12px;color:#556462;margin-top:8px;">又硬又甜，爆浆车厘子</div>
              <div style="position: absolute;bottom: 5px;right: 5px;display: flex;flex-direction: row;">
                <span style="color: red;font-size:14px;line-height: 35px;width:70px;">$198/件</span>
                <div style="width:100px;height: 35px;border-radius: 3px;background-color: blue;text-align: center;line-height: 35px;color: white;background-color: red;">加入购物车</div>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <bottom-menu  style="line-height: 16px;"></bottom-menu>
  </div>
</template>

<script>
  import TopSearch from './common/TopSearch'
  import BottomMenu from './common/BottomMenu'

  export default {
    name: 'Classify',
    components: {
      TopSearch,
      BottomMenu
    },
    created: function () {
    },
    mounted: function () {
      this.getData()
    },
    data () {
      return {
        typeGroups: [],
        types: []
      }
    },
    methods: {
      goSearch: function (val) {
        console.info('搜索商品关键字为：%s', val)
      },
      getData: function () {
        this.$http.post('/classify/get').then((response) => {
          this.typeGroups = response.data.groups
          this.types = response.data.types
        })
      },
      productListUrl: function (typeId) {
        return '/product/list/' + typeId
      },
      productListGroupUrl: function (groupId) {
        return '/product/list/0-' + groupId
      }
    },
    computed: {
    }
  }
</script>
<style scoped lang="scss">
  .classify {
    /*overflow: auto;*/
    margin-top:20px;
    padding: 44px 0;
    box-sizing: border-box;
    /*height: 100%;*/
    .item {
      padding: 10px;
      background: white;
      .title,.more {
        text-align: center;
        padding: 5px 0;
        font-size: 17px;
      }
      .title {
        font-weight: bold;
        border-bottom: 1px solid #e4e4e4;
      }
      .item-child {
        padding: 10px 10px;
        a {
          display: inline-block;
          padding: 10px;
          color: black;
        }
      }
      .more {
        display: block;
        color: black;
        border-top: 1px solid #e4e4e4;
      }
    }
    .line-block {
      margin-bottom: 15px;
      box-sizing: border-box;
      overflow-y: hidden;
      background: white;
    }
  }
</style>
