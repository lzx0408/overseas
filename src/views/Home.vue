<template>
  <div class="home">
    <MyHeader />
    <Zhinan />

    <Abroad />
    <footer class="footer">
            <ul>
                <li>
                    <a href="tel:01051299614">
                        <em><img src="http://www.yuloo.com/zzy/images/scroll_02.png" style="display: inline-block;"></em>
                        <span>电话咨询</span>
                    </a>
                </li>
                <li>
                    <a href="javascript:void(0)" onclick="openJesongChatByGroup(13240,26471);return false;" rel="nofollow">
                        <em><img src="http://www.yuloo.com/zzy/images/scroll_01.png" style="display: inline-block;"></em>
                        <span>在线咨询</span>
                    </a>
                </li>
                <li>
                    <a href="http://cg.yuloo.com/baoming.shtml" rel="nofollow">
                        <em><img src="http://www.yuloo.com/zzy/images/scroll_03.png" style="display: inline-block;"></em>
                        <span>网上报名</span>
                    </a>
                </li>
            </ul>
        </footer>
  </div>
</template>

<script>
// @ is an alias to /src
import MyHeader from './MyHeader/MyHeader.vue'
import Abroad from '@/views/abroad/abroad.vue'
import Zhinan from '@/views/zhinan/index.vue'
export default {
  name: 'Home',
  components: {
    MyHeader,
    Abroad,
    Zhinan
  }
}
</script>
<style lang="scss">
   .footer{
        width: 100%;
        height: 0.40rem;
        background: paleturquoise;
        display: flex;
        ul{
            width: 3.75rem;
            height: 0.4rem;
            margin: 0 auto;
            display: flex;
            li{
                width: 1.225rem;
                height: 0.4rem;
                border-right: 0.01rem #fff solid;
                background-color: #2b4d8b;   
               a{
                    display: inline-block;
                    width: 99.8%;
                    height: 0.4rem;
                    color: #FFF;
                    display: flex;
                    align-items: center;
                    justify-content: space-evenly;
                   span{
                        font-size: 0.14rem;
                        font-weight: 600;
                   }
               }
            }
        }
    }
</style>