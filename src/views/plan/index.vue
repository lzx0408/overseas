<template>
  <div class="planb">
    <div class="planb_header">
      <h3>出过留学规划</h3>
    </div>
    
      <div class="planb_crowd">
        <h4>出国留学人群</h4>
        <ul class="planba">
          <li>我要读高中</li>
          <li>我要读本科</li>
          <li>我要读硕士</li>
        </ul>
      </div>
     <div class="planb_crowd">
        <h4>出国留学人群</h4>
        <ul class="planba">
          <li>留学预科</li>
          <li>2+2留学</li>
          <li>3+2留学</li>
        </ul>
      </div>
      <div class="planb_coutry">
        <h4>出国留学人群</h4>
        <ul class="planc">
          <li>英国</li>
          <li>美国</li>
          <li>澳洲</li>
          <li>加拿大</li>
          <li>韩国</li>
          <li>日本</li>
        </ul>
      </div>
    
    <div class="planb_questions">
      <h4>出过问题必答</h4>
      <div class="planb_qinpt">
        <input type="text" name="" id="" placeholder="学生姓名" />
        <input type="text" name="" id="" placeholder="手机号码" />
        <input type="text" name="" id="" placeholder="出生年月" />
        <input type="text" name="" id="" placeholder="外交学院" />
        <select >
           <option value="请选择学历">请选择学历</option>
          <option value="高中">高中</option>
          <option value="专科">专科</option>
          <option value="本科">本科</option>
        </select>
        <input type="text" name="" id="" placeholder="您的疑问" />
      </div>
      <div class="planb_bottom">
          <button class="planb_qbtn">立即提交</button>
      <div class="planb_ys">《隐私保障》</div>
      </div>
     
    </div>
  </div>
</template>
<script>
export default {
  name: "Plan",
};
</script>
<style scoped>
.planb{
  width: 3.2rem                          ;
  margin: 0 auto;
  padding: .1rem;
}
.planb_header {
 padding-bottom: .1rem;

}
.planba{
 display: flex;
  justify-content: space-around; 
  margin: .1rem 0 .1rem 0;
}
.planba li{
width: 1rem;
  height: .3rem;
  border: 1px solid #c0c9e4;;
  border-radius: .1rem;
  color: #36477a;
  line-height: .3rem;
  text-align: center;

  border-radius: .09rem;
}
.planc{
 display: flex;
 flex-flow: wrap;
 
}
.planc li{
  width: 1rem;
  height: .3rem;
  border: 1px solid #c0c9e4;;
  border-radius: .1rem;   
  line-height: .3rem;
  text-align: center;
  margin-right: .04rem;
  border-radius: .09rem;
  margin-top: .08rem;
}
.planb_questions{
  background: rgb(243, 243, 243);
  margin: .1rem;
  border-radius: .1rem ;
}
.planb_questions h4{
  padding: .09rem;
}
.planb_questions input{
   width: 40%;
   height: .25rem;
   margin: .1rem;
}
.planb_questions select{
   width: 40%;
   height: .25rem;
   margin: .1rem;
}
.planb_bottom{
  text-align: center;
  margin-bottom: .1rem;
}
.planb_qbtn{
  width: 1rem;
  height: .35rem;
  color: white;
  background: rgb(240, 139, 89);
  font-size: .16rem;
}
.planb_ys{
  padding: .2rem;
}
</style>