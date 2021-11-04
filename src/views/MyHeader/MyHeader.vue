<template>
    <div class="wrap">
        <header class="header">
            <div class="hint">
                <p>育路出国留学网-专注出国留学提供高质量的留学规划服务</p>
            </div>
            <div class="hint_buttom">
                <div class="hint_buttom_left">
                    <div class="hint_buttom_left_img">
                        <img src="http://cg.yuloo.com/images/yuloo-logo.png" alt="">
                    </div>
                    <div class="hint_buttom_left_text">
                       <h1>
                           出国留学
                        </h1>
                    </div>
                </div>
                <div class="hint_buttom_rigth">
                    <p class="btn" >
                        <svg class="icon" aria-hidden="true">
                            <use xlink:href="#icon-liebiao"></use>
                        </svg>
                    </p>
                </div>
            </div>
            <div class="lunbo">
                <div class="block">
                    <el-carousel height="1.0938rem"  arrow="always">
                    <el-carousel-item v-for="(item,index) in lunbo" :key="index">
                        <!-- <h3 class="small">{{ item }}</h3> -->
                    
                        <img :src= "item.src"  >
                    </el-carousel-item>
                    </el-carousel>
                </div>
            </div>
        </header>
        <main class="main">
            <div class="main_nav">
               <p>当前位置：首页 > 出国留学网</p>
            </div>
            <div class="consult">
                <div class="consult_nav">
                    <div class="nav_text">
                         <svg class="icon" aria-hidden="true">
                                <use xlink:href="#icon-zixun"></use>
                            </svg> 
                        <span>
                           
                            出国留学最新资讯
                        </span>
                    </div>
                    <div class="nav_chu">
                        <span class="nav_chu_left">出国留学动态</span>
                        <span  class="nav_chu_right">中外合作留学动态</span>
                    </div>
                    <div class="nav_yasu">
                        <div class="nav_yasu_img">
                             <img src="http://www.yuloo.com/d/file/2111/9cf5dca49c8788f57fc812b849ad819c.jpg" alt="">
                        </div>
                        <div class="nav_yasu_text">
                            <div class="nav_yasu_rigth">
                                 <a href="http://cg.yuloo.com/xwzx/1766390.shtml" title="哪个国家留学可以免雅思申请？">
                                             哪个国家留学可以免雅思申请？
                                 </a>
                            </div>
                             <div class="nav_yasu_button">
                                 <p>   雅思成绩不好的学生出国留学，希望能去免雅思成绩的国家，那么，有没有这样</p>
                              
                             </div>
                        </div>
                       
                    </div>
                     <div>
                        <ul class="news-list clearfix">
                            <li><a href="http://cg.yuloo.com/xwzx/1766652.shtml" title="北京出国留学院校哪些办得比较好？">北京出国留学院校哪些办得比较好？</a><span>11-04</span></li>
                            <li><a href="http://cg.yuloo.com/xwzx/1766634.shtml" title="留学预算低，可以去哪些国家留学？">留学预算低，可以去哪些国家留学？</a><span>11-04</span></li><li><a href="http://cg.yuloo.com/xwzx/1766627.shtml" title="2022QS亚洲地区大学排名重磅发布！">2022QS亚洲地区大学排名重磅发布！</a><span>11-04</span></li>
                            <li><a href="http://cg.yuloo.com/xwzx/1766621.shtml" title="雅思分数低的学生出国留学有哪些方案？">雅思分数低的学生出国留学有哪些方案？</a><span>11-03</span></li><li><a href="http://cg.yuloo.com/xwzx/1766534.shtml" title="日本TOP10院校硕士留学直接申请条件详解">日本TOP10院校硕士留学直接申请条件详解</a><span>11-02</span></li>
                            <li><a href="http://cg.yuloo.com/xwzx/1766533.shtml" title="本科毕业出国读研是考GMAT还是GRE？">本科毕业出国读研是考GMAT还是GRE？</a><span>11-02</span></li>
                            <li><a href="http://cg.yuloo.com/xwzx/1766417.shtml" title="出国留学什么专业最值得读？">出国留学什么专业最值得读？</a><span>11-01</span></li><li><a href="http://cg.yuloo.com/xwzx/1766390.shtml" title="哪个国家留学可以免雅思申请？">哪个国家留学可以免雅思申请？</a><span>11-01</span></li>
                            <li><a href="http://cg.yuloo.com/xwzx/1766371.shtml" title="出国留学GPA不够可以读国内预科吗？">出国留学GPA不够可以读国内预科吗？</a><span>11-01</span></li>                     
                        </ul>
                    </div>
                    <div class="dynamic">
                        <a class="btn-more" href="http://cg.yuloo.com/xwzx/" title="出国留学动态">
                                <span>查看更多出国留学动态&gt;&gt;</span>
                        </a>
                    </div>
                </div>
                
            </div>
        </main>
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
export default {
    data(){
        return{
            lunbo:[
              {src:require('../../assets/banner1.jpg')},
              {src:require('../../assets/banner2.jpg')},
              {src:require('../../assets/banner3.jpg')}
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
body{
    font-size: 0.14rem;
}
a{
    text-decoration: none;
}
li {
    list-style: none;
}
.icon {
    width: 0.25rem; height: 0.25rem;
    vertical-align: -0.15rem;
    fill: currentColor;
    overflow: hidden;
}
.wrap{
    height: 100%;
    display: flex;
    flex-direction: column;
    .header{
       width: 3.75rem;
       margin: 0 auto;
       color: #838c94;
       background-color: #eeeeee;
       .hint{
           width: 3.5635rem;
           height: 0.4rem;
           background:#eeeeee ;
           display: flex;
           align-items: center;
         
           p{
              font-size: 0.12rem;
              color: #838c94;
              padding: 0 0 0 0.12rem;
           }
       }
       .hint_buttom{
           width: 3.75rem;
           height: 0.7rem;
           background: #fff;
           display: flex;
           align-items: center;
           margin: 0 auto;
           .hint_buttom_left{
               width: 2.0rem;
               height: 0.7rem;
            //    background: palevioletred;
               display: flex;
               justify-content: space-evenly;
               .hint_buttom_left_img{
                   display: flex;
                   align-items: center;
                   img{
                       width: 0.84rem;
                       height: 0.238rem;
                   }
               }
               .hint_buttom_left_text{
                   display: flex;
                   align-items: center;
                   h1{
                     background: url(../../assets/jb.jpg) no-repeat center center;
                     border-radius: 0.3rem;
                     font-weight: bold;
                     color: #fff;
                     border-radius: 0.03rem;
                     font-size: 0.14rem;
                     padding: 0.06rem 0.15rem;
                    }
               }    
           }
           .hint_buttom_rigth{
               width: 0.50rem;
               height: 0.4rem;
               background: #fff;
               display: flex;
               justify-content: space-around;
               align-content: space-around;
               margin: 0 0 0 1rem;
               border-radius: 0.05rem;
               border: 1px solid #eeeeee;
             
           }
       }
       .lunbo{
           width: 3.75rem;
           height: 1.0938rem;
        //    background: red;
            .el-carousel__item h3 {
                color: #475669;
                font-size: 0.14rem;
                opacity: 0.75;
                line-height:1.0938rem ;
                margin: 0;
                .el-carousel__item:nth-child(2n) {
                    background-color: #99a9bf;
                }
                
                .el-carousel__item:nth-child(2n+1) {
                    background-color: #d3dce6;
                }
            }
            img{
                width: 3.75rem;
                height: 1.0938rem;
            }
       }
    }
    .main{
        flex: 1;
        overflow-y: scroll;
        background-color: #F5F7F9;
        .main_nav{
            width: 3.75rem;
            height: 0.40rem;
            font-size: 0.12rem;
            margin: 0 auto;
            color: #9fa9b3;
            background-color: #F5F7F9;
            display: flex;
            align-items: center;
            p{
                  padding: 0 0.10rem;
            }
        }
        .consult{
            width: 3.5625rem;
            height: 5.40rem;
            background: #fff;
            margin: 0.10rem auto;
            border-radius: 4px;
            display: flex;
            justify-content: space-around;
            .consult_nav{
                width: 3.2625rem;
                height: 5.40rem;
                background: #fff;
                .nav_text{
                    width: 3.2625rem;
                    height: 0.35rem;
                    // background: papayawhip;
                    margin: 0.15rem 0 0.15rem 0;
                    display: flex;
                    align-items: center;
                    span{
                        font-size: 0.2rem;
                        font-weight: 900;
                        line-height: 0.25rem;
                        margin: 0 0.05rem;
                        color: #333333;
                    }
                }
                .nav_chu{
                    width: 3.2625rem;
                    height: 0.32rem;
                    // background: yellow;
                    margin: 0 0 0.15rem 0;
                    .nav_chu_left{
                        width: 1.61125rem;
                        height: 0.3rem;
                        display: block; 
                        color: #fff !important;
                        background: #cc8b59 !important;
                        border-color: #cc8b59 !important;
                        float: left;
                        line-height: 0.30rem;
                        text-align: center;
                        border: 0.01rem solid #ddd !important;
                        border-radius:  0.04rem  0.04rem 0 0;
                    }
                    .nav_chu_right{
                        width: 1.61125rem;
                        height: 0.30rem;
                        display: block; 
                        font-size: 0.14rem;
                        float: left;
                        line-height: 0.30rem;
                        text-align: center;
                        color: #333;
                        border: 0.01rem solid #ddd !important;
                        background: #fff !important;
                        border-radius: 0.04rem  0.04rem 0 0;
                    }
                }
                .nav_yasu{
                    width: 3.2625rem;
                    height: 0.8rem;
                    margin: 0 0 0.20rem;
                    // background: plum;
                    display: flex;
                    .nav_yasu_img{
                        width: 1.20rem;
                        height: 0.8rem;
                        img{
                            width: 1.20rem;
                            height: 0.8rem;
                        }
                    }
                    .nav_yasu_text{
                        display: flex;
                        flex-wrap: wrap;
                        justify-content: flex-end;
                        .nav_yasu_rigth{
                            width: 1.92548rem;
                            height: 0.48rem;
                            // background: red;
                            a{
                                display: inline-block;
                                font-size: 0.16rem;
                                line-height: 0.24rem;
                                color: #333;
                                font-weight: bold;
                            }
                        }
                        .nav_yasu_button{
                            width: 1.92548rem;
                            height: 0.32rem;
                            // background: papayawhip;
                            p{
                                font-size: 0.12rem;
                                height: 0.32rem;
                                overflow: hidden;
                                line-height: 0.16rem;
                                color: #666;
                                
                            }
                            
                        }
                    }
                }
                .news-list{
                    display: flex;
                    flex-wrap: wrap;
                    li{
                        width: 3.1972rem;
                        height: 0.3rem;
                        display: flex;
                        justify-content: space-between;
                        a{
                            width: 2.6972rem;
                            height: 0.3rem;
                            font-size: 0.14rem;
                            line-height: 0.3rem;
                            color: #555;
                            white-space: nowrap;
                            text-overflow: ellipsis;
                            overflow: hidden;
                        }
                        span{
                            width: 0.4rem;
                            font-size: 0.12rem;
                            color: #aaa;
                        }
                    }
                   
                }
                .dynamic{
                    width: 3.2625rem;
                    height: 0.32rem;
                    margin: 0.16rem 0 0;
                    // background: palevioletred;
                    a{
                        display: block;
                        line-height: 0.28rem;
                        text-align: center;
                        border: 0.01rem solid #cc8b59;
                        border-radius: 0.04rem;
                    }
                    span{
                        padding: 0 0.1rem;
                        color: #cc8b59;
                        font-size: 0.14rem;
                    }
                }
            }
        }
    }
    
}
</style>