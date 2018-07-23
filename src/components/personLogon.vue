<style scoped>
  /* pages/filedViewRecord/filedViewRecord.wxss */
  .mb10{
    margin-bottom:10px;
  }
  .oh{
    overflow: hidden;
    height:100%;
  }
  .flex {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .flex-v {
    -webkit-box-orient: vertical;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
  .flex-1 {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
  .body-view{
    width:100%;
    background:#fff;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:13px 15px 0;
  }
  .title{
    text-align:center;
  }
  .smlTitle{
    line-height:29px;
    font-size:16px;
    color:#222;
  }
  .bigTitle{
    line-height:27px;
    font-size:18px;
    color:#222;
  }
  .dashImg{
    height:2px;
    width:100%;
    margin:15px 0;
  }
  .dashImg2{
    height:2px;
    width:100%;
    margin:20px 0;
  }
  .textItem{
    line-height:22px;
    color:#333;
    font-size:15px;
  }
  .textItem2{
    line-height:33px;
    color:#999;
    font-size:14px;
  }
  .tableItem{
    border:1px solid #2eab3b;
    margin-top:-1px;
    line-height:16px;
    font-size:15px;
    color:#333;
    overflow:hidden;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .tableItem .tableItemLeft{
    padding:12px 0;
    display:inline-block;
    text-align:center;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
  .tableItem .tableItemRight{
    float:right;
    border-left:1px solid #2eab3b;
    width:77%;
    display:inline-block;
    text-align:center;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:16px 20px;
  }
  .tableItemCenter{
    line-height:43px;
    display:inline-block;
    text-align:center;
    width:100%;
    font-size:13px;
    color:#2eab3b;
    font-weight:700;
  }

  .signBox{
    width:100%;
    border:1px solid #2eab3b;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:12px 14px 11px;
  }
  .firstLine{
    padding:0 0;
    overflow:hidden;
    margin-bottom:18px;
  }
  .imgDiv{
    width:39px;
    align-items:center;
  }
  .imgDiv image{
    width:24px;
    height:24px;
  }
  .firstLineText{
    line-height:22px;
    font-size:14px;
    color:#333;
  }
  .secondLine{
    padding:0 0;
    overflow:hidden;
  }
  .secondLineText{
    line-height:22px;
    font-size:14px;
    color:#333;
  }
  .signShowBox{
    padding-top:15px;
    padding-bottom: 8px;
   
  }
  .openSignButton{
    display:block;
     width:100px;
    height:40px;
     margin-left: 20px;
    text-align:center;
    line-height:40px;
    font-size:15px;
    color:#fff;
    background:#2eab3b;
    border-radius:15px;
  }
  .signedShowBox{
    padding-top:27px;
    height:100px;
  }
  .signedShowBox text{
    display:block;
    float: left;
    width:364px;
    text-align: right;
    font-size:15px;
    color:#222222;
    height: 88px;
    line-height: 88px;
  }
  .signImg{
    width:100px;
    height: 130px;
    transform: rotate(-90deg) translate3d(-100%,0,0);
    transform-origin: left top;
  }

  .bottomTitleView{
    position:relative;
    margin-bottom:28px;
  }
  .bottomTitleBg{
    width:50%;
    height:16px;
    display:block;
    margin:0 auto;
  }
  .bottomTitleText{
    position:absolute;
    top:0;
    left:50%;
    transform:translate3d(-50%,0,0);
    height:16px;
    font-size:15px;
    color:#222;
    line-height:15px;
  }
  .bottomInfo{
    padding:0 13px 44px 34px;
    font-size:13px;
  }
  .textItem3{
    line-height:22px;
    color:#666;
    font-size:13px;
    text-indent:-21px;
  }
  .red{
    color:#ff0000;
  }

  .signWrap{
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 10;
    background:rgba(0,0,0,0.8);
  }
  .signContent{
    position: absolute;
    left: 50%;
    top: 50%;
    transform:translate3d(-50%,-50%,0);
    background:#fff;
    width:90%;
    height: 80vh;
    border-radius:30px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding:17px 60px 0px 18px;
  }
  .signTip1{
    line-height: 40px;
    font-size:18px;
    right:37px;
    top:17px;
    color:#333333;
    width:100%;
    position: absolute;
    transform:rotate(90deg) translate3d(100%,0,0);
    transform-origin:right 50%;
  }
  .signHereBox{
    height:790px;
    width: 60%;
    border:1px solid #dedede;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    text-align: center;
    float: left;
  }
  .signHereTip{
    color:#e2e2e2;
    line-height: 234px;
    font-size:26px;
  }
  canvas{
    height:466px;
    width:100%;
    border-radius:20px;
    border:1px solid #ccc;
  }
  .closeBtn{
    background:#fff;
    position: absolute;
    right:-15px;
    bottom:-15px;
    width: 64px;
    height: 64px;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%;
  }
  .closeBtn img{
    width: 26px;
    height: 26px;
    position: absolute;
    left:19px;
    top: 19px;
  }
  .signContentBottom{
    /*padding-top:12rpx;*/
  }
  .operationBox{
    width:50%;
    height: 116px;
    padding-top:17px;
    padding-left: 70px;
    display: flex;
  }
  .operationBox img{
    display: inline-block;
    width:54px;
    height: 54px;
    transform:rotate(90deg);
  }
  .confirmImg{
    margin-left: 28px;
  }
  .bbn{
    border-bottom:none;
  }
  #img-box,
  #canvas-drawImage h5, #canvas-brush {
    display: none;
  }
  #canvas-drawImage button{
    width: auto;
    position: absolute;
    flex: 1;
  }
  .wrap #control {
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: row;
    text-align: center;
  }
  .fix-body {
    position: fixed !important;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    overflow: hidden;
  }
  .inner.draw {
    display: flex;
    flex-direction: row;
  }
  .draw h5 {
    margin-bottom: 10px;
  }
  #img-box {
    flex: 1;
    padding-left: 10px;
  }
  #img-box .img-item {
    position: relative;
    display: inline-block;
  }
  #img-box .img-item .fa {
    position: absolute;
    cursor: pointer;
    right: 1px;
    top: -1px;
    font-size: 12px;
    font-weight: 1;
    display: none;
    color: #ccc;
  }
  #img-box .img-item:hover .fa {
    display: block;
  }
  #img-box .img-item .fa:hover {
    color: #f2849e;
  }
  #img-box img {
    border: 1px #ccc solid;
    width: 90px;
    height: 60px;
    margin: 5px;
  }
  .wrap{
    width: 740px;
    border: 1px #585858 solid;
    overflow: hidden;
  }
  .fl{
    float: left;
    display: block;
  }
  #canvas{
    border-right: 1px #585858 solid;
    cursor: crosshair;
  }
  #control{
    width: 130px;
    height: 400px;
    margin-left: 4px;
  }
  #control div{
    padding: 5px;
  }
  #canvas-color ul{
    overflow: hidden;
    margin: 0;
    padding: 0;
  }
  #canvas-color ul li{
    float: left;
    display: inherit;
    width: 13px;
    height: 13px;
    border: 3px #fff solid;
    margin: 8px;
    cursor: pointer;
  }
  #canvas-color .active {
    border: 1px solid #f2849e;
  }
  #canvas-brush span{
    display: inline-block;
    width: 20px;
    height: 15px;
    margin-left: 10px;
    cursor: pointer;
  }
  #canvas-brush .small {
    font-size: 12px;
  }
  #canvas-brush .middle {
    font-size: 14px;
  }
  #canvas-brush .big {
    font-size: 16px;
  }

  #canvas-control span{
    display: inline-block;
    font-size: 14px;
    width: 20px;
    height: 15px;
    margin-left: 10px;
    cursor: pointer;
  }
  #canvas-control .active,
  #canvas-brush .active {
    color: #f2849e;
  }
  .drawImage {
    width: 100px;
    height: 30px;
    font-size: 12px;
    line-height: 30px;
  }
  .loss-text{
    display:inline-block;
    text-align:center;
    width:100%;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:9px 20px;
  }
  .tableItem-wrap{
    width:100%;
    position: relative;
    overflow: hidden;
    border-bottom:1px solid #2eab3b;
  }
  .tableItem-left{
    border-right:1px solid #2eab3b;
    width:50%;
  }
  .tableItem-left-li{
    height:30px;
    line-height: 30px;
    text-align: center;
    border-bottom:1px solid #2eab3b;
  }
  .tableItem-right{
    width:66%;
    position:absolute;
    top:0px;
    left:150px;
    text-align: center;
    line-height: 28px;
  }
  .signature-wrap{
    overflow: hidden;
    padding-top:20px;
  }
  .signature-wrap p{
     float:right;
     padding-right:20px;
  }
  .signature-word{
    padding-right:10px;
  }
  .signature-content p{
     text-indent:20px;
     padding-bottom:20px;
  }
  .sq{
    margin-bottom:10px;
  }
  .show{
    display:block;
  }
  .hide{
    display:none;
  }
  .bz{
   font-size: 13px;
    color:#E51C23;
    margin-bottom:10px;
  }
  .left{
    float:left;
  }
  .right{
    float:right;
  }
  .sigin-wrap{
    margin-bottom:20px;
  }
  .clear {
    zoom:1;
  }
  .clear:after {
   clear:both;
   content:'.';
   display:block;
   width: 0;
   height: 0;
   visibility:hidden;
}
</style>
<template>
  <div style="background: #fff;">

    <!--<div class="body-view {{showSignFlag?'oh':''}}">-->
    <div class="body-view">
      <div class="title">
        <span class="smlTitle">{{detailData.insureName}}</span>
      </div>
      <div class="title">
        <span class="bigTitle">机动车辆保险人伤案件信息确定书</span>
      </div>

      <img class="dashImg" style="width:100%;height:2px;" src="../images/dashline.png" />

      <div class="textItem">
        <span>报案号：{{reportNumber}}</span>
      </div>
      <div class="textItem">
        <span>出险时间：{{outTime}}</span>
      </div>
      <div class="textItem">
        <span>出险/查勘地点：{{outPlace}}</span>
      </div>
      <div class="textItem mb10">
        <span>就诊医院：{{clinicHospital}}</span>
      </div>
      <!-- 基本信息 -->
      <div class="textItem2">
        <span>基本信息</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">被保险人</span><span class="tableItemRight">{{insuredName}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">联系人</span><span class="tableItemRight">{{baseVictimName}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">医院等级</span><span class="tableItemRight">{{hospitalLevel}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">负责医师</span><span class="tableItemRight">{{responsibleDoctor}}</span>
      </div>
      <div class="tableItem mb10" >
       <span class="tableItemLeft">联系方式</span><span class="tableItemRight">{{doctorPhone}}</span>
      </div>
       <!-- 伤/亡者基本信息 -->
      <div class="textItem2">
        <span>伤/亡者基本信息</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">姓名</span><span class="tableItemRight">{{suffererName}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">性别</span><span class="tableItemRight">{{genderCode}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">年龄</span><span class="tableItemRight">{{suffererAge}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">户口性质</span><span class="tableItemRight">{{registeredCode}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">职务</span><span class="tableItemRight">{{suffererDuty}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">收入</span><span class="tableItemRight">{{suffererIncome}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">领取形式</span><span class="tableItemRight">{{incomeCode}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">身份证号</span><span class="tableItemRight">{{IDcard}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">工作单位</span><span class="tableItemRight">{{suffererOrganization}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">居住地点及年限</span><span class="tableItemRight">{{residentialLocation}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">住房性质</span><span class="tableItemRight">{{housingCode}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">已住院天数</span><span class="tableItemRight">{{stayLength}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">已花费医疗费用</span><span class="tableItemRight">{{hospitalizationCosts}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">预计花费医疗总额</span><span class="tableItemRight">{{totalAmount}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">是否已手术</span><span class="tableItemRight">{{surgeryCode}}</span>
      </div>
      <div class="tableItem bbn" >
       <span class="tableItemLeft">预估可达伤残等级</span><span class="tableItemRight">{{degreeDisability}}</span>
      </div>
      <div class="tableItem mb10" >
       <span class="tableItemLeft">受伤时所在位置</span><span class="tableItemRight">{{siteCode}}</span>
      </div>

        <!-- 伤情描述 -->
      <div class="textItem2">
        <span>伤情描述</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">受伤部位</span><span class="tableItemRight">{{checkListStr}}</span>
      </div>
      <div class="tableItem mb10">
        <span class="tableItemLeft">描述</span><span class="tableItemRight">{{injuryDescribe}}</span>
      </div>

       <!-- 护理人员情况 -->
      <div v-for="item in nurseMessage">
          <div class="textItem2">
            <span>护理人员情况</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">姓名</span><span class="tableItemRight">{{item.hsXm}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">收入</span><span class="tableItemRight">{{item.hsSr}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">电话</span><span class="tableItemRight">{{item.hsDh}}</span>
          </div>
          <div class="tableItem mb10">
            <span class="tableItemLeft">与伤者关系</span><span class="tableItemRight">{{item.hsGx}}</span>
          </div>
      </div>
      <!-- 家庭成员关系 -->
      <div v-for="item in familyMessage">
          <div class="textItem2">
            <span>家庭成员关系</span>
          </div> 
          <div class="tableItem bbn">
            <span class="tableItemLeft">姓名</span><span class="tableItemRight">{{item.jtXm}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">年龄</span><span class="tableItemRight">{{item.jtNl}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">出生日期</span><span class="tableItemRight">{{item.jtCs}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">有无劳动能力</span><span class="tableItemRight">{{item.jtLd}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">有无生活来源</span><span class="tableItemRight">{{item.jtSr}}</span>
          </div>
          <div class="tableItem bbn">
            <span class="tableItemLeft">户口性质</span><span class="tableItemRight">{{item.jtHk}}</span>
          </div>
          <div class="tableItem mb10">
            <span class="tableItemLeft">与伤者关系</span><span class="tableItemRight">{{item.jtGx}}</span>
          </div>
      </div>
      <!-- 伤者银行卡信息 -->
      <div class="textItem2">
        <span>伤者银行卡信息</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">持卡人姓名</span><span class="tableItemRight">{{cardholderName}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">卡号</span><span class="tableItemRight">{{cardNumber}}</span>
      </div>
      <div class="tableItem mb10">
        <span class="tableItemLeft">开户行</span><span class="tableItemRight">{{cardholderBank}}</span>
      </div>
      <p class="bz">备注：请务必提供伤者本人银行卡信息，便于支付赔款。</p>
      <img class="dashImg2" style="width:100%;height:2px;" src="../images/dashline.png" />

      <div class="sigin-wrap clear">
        <div class="siginLeft left">
             <p>伤者签名：</p>
             <div class="signShowBox">
                <span @click="showSignDiv(1)" class="openSignButton" v-if="sZsignStatus ==0?true:false">点击签字</span>
                 <img  class="signImg" :src="sZsignImgUrl" v-if="sZsignStatus !=0?true:false">
             </div>
        </div>
         <div class="siginLeft right">
             <p>护理人员签名：</p>
             <div class="signShowBox" style="marginRight:20px;">
                <span @click="showSignDiv(2)" class="openSignButton" v-if="hSsignStatus ==0?true:false">点击签字</span>
                <img  class="signImg" :src="hSsignImgUrl" v-if="hSsignStatus !=0?true:false">
             </div>
        </div> 
     </div>
         
    </div>
    
  </div>
</template>

<script>

  import axios from 'axios'
  import phoneData from '../js/phoneData.js'
  export default {
    data() {
      return {
        sZsignStatus:1,//伤者签名状态
        sZsignImgUrl:'https://zcbl.oss-cn-beijing.aliyuncs.com/sign_49cae6bcb65540998820fbbf9ec478e3_1532076698041.jpg',//伤者签名地址
        hSsignStatus:0,//伤者签名状态
        hSsignImgUrl:'',//伤者签名地址

        insuredName:"",//被保险人：
        reportNumber:"",//报案编号：
        outTime:"",//出险时间：
        outPlace:"",//出险地点：
        baseVictimName:"",//受害人/联系人：
        victimPhone:"",//联系电话：
        clinicHospital:"",//就诊医院：
        responsibleDoctor:"",//负责医师：
        doctorPhone:"",//医师电话：
        admissionNumber:"",//住院号：
        bedNumber:"",//就诊科室及床号：
        suffererName:"",//伤者姓名：
        genderCode:"",//伤者性别：
        suffererAge:"",//伤者年龄：
        registeredCode:"",//伤者户口性质：
        suffererDuty:"",//伤者职务：
        suffererIncome:"",//伤者收入：
        incomeCode:"",//伤者收入领取方式：
        IDcard:"",//伤者身份证：
        suffererOrganization:"",//伤者工作单位：
        residentialLocation:"",//伤者居住地点及年限：
        housingCode:"",//伤者住房性质：
        stayLength:"",//伤者已住院天数：
        hospitalizationCosts:"",//伤者已花费医疗费用：
        totalAmount:"",//伤者预计花费医疗总额：
        surgeryCode:"",//伤者是否已手术：
        degreeDisability:"",//伤者预估可达伤残等级：
        siteCode:"",//伤者受伤时所在位置：
        injuryDescribe:"",//伤情描述具体伤情描述：
        cardholderName:"",//伤者银行卡信息持卡人姓名：
        cardholderBank:"",//伤者银行卡信息开户行：
        cardNumber:"",//伤者银行卡信息卡号：
        hospitalLevel:"",//医院等级code 
        checkList: [1,2,3,4],//伤情描述
        checkListStr:"",//解析后的伤情描述
        nurseMessage:[{
           hsXm:"",//姓名
           hsDw:"",//单位
           hsZw:"",//职务
           hsSr:"",//收入
           hsDh:"",//电话
           hsGx:"",//与伤者关系
        }],//护士循环数组
        familyMessage:[{
            jtXm:"",//姓名
            jtNl:"",//年龄
            jtLd:"",//劳动能力
            jtSr:"",//收入
            jtHk:"",//户口性质
            jtGx:"",//与伤者关系
            jtCs:"",//出生日期
        }],//家庭循环数组




        curDetail:"",//照片
        content:"",//理赔信息
        contentState:false,
        phoneData:phoneData,
        thirdPartyListState:false,
        plateNumber:"",
        claimMoney:"",
        src:"",
        lossList:[],
        lossState:false,
        val:true,
        url:"",
        username: "",
        valicode: "",
        userpwd: "",
        loginActive: false,
        detailData:{},
        claimInfo:{},
        targetVehicle: '',
        detailPhotoList:[],
        thirdPartyList:[],
        showSignFlag:false,
        context:null,
        signStatus:0,//签名状态
        signImgUrl:'',//签名地址
        agreeThird:1,
        surveyOrderNo:'',
        colors: ['#fef4ac','#0018ba','#ffc200','#f32f15','#cccccc','#5ab639'],
        brushs: [{
          className: 'small fa fa-paint-brush',
          lineWidth: 3
        },{
          className: 'middle fa fa-paint-brush',
          lineWidth: 6
        },{
          className: 'big fa fa-paint-brush',
          lineWidth: 12
        }],
        context: {},
        imgUrl: [],
        canvasMoveUse: true,
        preDrawAry: [],
        nextDrawAry: [],
        middleAry: [],

      }
    },
    created(){
      this.getDetailData();
      console.log(phoneData)
      this.getSurveyInfo();
    },
    mounted() {
       
    },
    watch: {

    },
    methods: {
      analysisCheckList(arr){
        if(arr.length > 0){
            arr.forEach((item,index)=>{
              if(index  > 0){
                this.checkListStr += ','+item;
                return
              }
              this.checkListStr += item;
           });
        }
        
      },
           // xin
      getSurveyInfo(){
         this.insuredName = "1"; //被保险人：
         this.reportNumber = "2"; //报案编号：
         this.outTime = "3"; //出险时间：
         this.outPlace = "4"; //出险地点：
         this.baseVictimName = "5"; //受害人/联系人：
         this.victimPhone = "6"; //联系电话：
         this.clinicHospital = "7"; //就诊医院：
         this.responsibleDoctor = "8"; //负责医师：
         this.doctorPhone = "9"; //医师电话：
         this.admissionNumber = "10"; //住院号：
         this.bedNumber = "11"; //就诊科室及床号：
         this.hospitalLevel = "12";//医院等级code
         this.suffererName = "13"; //伤者姓名：
         this.genderCode = "14"; //伤者性别：
         this.suffererAge = "15"; //伤者年龄：
         this.registeredCode = "16"; //伤者户口性质：
         this.suffererDuty = "17"; //伤者职务：
         this.suffererIncome = "18"; 
         this.incomeCode = "19"; //伤者收入领取方式：
         this.IDcard = "20"; //伤者身份证：
         this.suffererOrganization = "21"; //伤者工作单位：
         this.residentialLocation = "22"; //伤者居住地点及年限：
         this.housingCode = "23"; //伤者住房性质：
         this.stayLength = "24"; //伤者已住院天数：
         this.hospitalizationCosts = "25"; //伤者已花费医疗费用：
         this.totalAmount = "26"; //伤者预计花费医疗总额：
         this.surgeryCode = "27"; //伤者是否已手术：
         this.degreeDisability = "28"; //伤者预估可达伤残等级：
         this.siteCode = "29"; //伤者受伤时所在位置：
         this.injuryDescribe = "30"; //伤情描述具体伤情描述：
         this.cardholderName = "31"; //伤者银行卡信息持卡人姓名：
         this.cardholderBank = "32"; //伤者银行卡信息开户行：
         this.cardNumber = "33"; //伤者银行卡信息卡号：
         

         this.checkList = [7,8,9,10];//伤情描述
         this.nurseMessage = [{
           hsXm:"34",//姓名
           hsDw:"35",//单位
           hsZw:"36",//职务
           hsSr:"37",//收入
           hsDh:"38",//电话
           hsGx:"39",//与伤者关系
          }];//护理人员基本情况
         this.familyMessage = [{
            jtXm:"40",//姓名
            jtNl:"41",//年龄
            jtLd:"42",//劳动能力
            jtSr:"43",//收入
            jtHk:"44",//户口性质
            jtGx:"45",//与伤者关系
            jtCs:"46",//出生日期
          }];// 家庭成员情况 

        this.analysisCheckList(this.checkList);

      },



      showSignDiv(num){
         this.$router.push({path:'/signName',query:{key:num}});
      },
      changeAgreeThird(){
        if(this.agreeThird == 0){
          this.agreeThird = 1
        }else{
          this.agreeThird = 0
        }
      },
      gotolink: function(id,item){
        var licenseNo = item.licenseNo;
        var idStr = String(id).replace('photoButton','');
        // alert(this.detailPhotoList.length)
        if(idStr=='0'){
          if(this.detailPhotoList.length == 0) {
            this.$message({
                message: '此车暂无照片',
                type: 'error'
              });
          }else{
            localStorage.setItem(licenseNo,JSON.stringify(item.photoList));
            this.$router.push({path:'/photoList/'+licenseNo});
          }
        }else{
           console.log(item,444444444444)
          if(item.photoList.length == 0){
             this.$message({
                message: '此车暂无照片',
                type: 'error'
              });
          }else{
            console.log(item.detailPhotoList,66666666)
            localStorage.setItem(licenseNo,JSON.stringify(item.photoList));
            this.$router.push({path:'/photoList/'+licenseNo});
          }
        }
      },
      open2() {
        this.$message({
          message: '登陆成功',
          type: 'success'
        });
      },
      open4(resdes) {
        this.$message.error(resdes);
      },
      getLossList(str){
         // var str = "1-2-3-4-5-6-7";
         var arr = str.split('-');
         var zarr = ["正前部","左前部","右前部","左中部","正后部","左后部","右后部","右中部"];
         var barr = [];
         for(var i = 0; i < arr.length;i++){
            barr.push(zarr[arr[i]-1])
         };
         return barr
      },
      changeLossList(obj){
        //var obj = [{damagedPart:"1-2-3-4-5-6-7",licenseNo:"1",claimAmount:10},{damagedPart:"1-2-3-4-5-6-7",licenseNo:"1",claimAmount:10}]
        var plateNumber = "";
        var claimMoney = "";
         for(var i = 0; i < obj.length;i++){
             obj[i].damagedPart = this.getLossList(obj[i].damagedPart);
             if(obj[i].licenseNo != this.targetVehicle.licenseNo){
                plateNumber += obj[i].licenseNo;
                claimMoney += "￥" + obj[i].claimAmount;
                // console.log(claimMoney)
             }
             
         };
         this.plateNumber = plateNumber;//车牌
         this.claimMoney = claimMoney;//理赔金
         this.claimInfo = obj //理赔信息集合
         // console.log(obj,44444444444)
      },
      getDetailData(){
        var surveyNo = this.$route.query.num;
        //alert(this.$route.query.num)
        console.log(surveyNo,6666666666666)
        var paramData = {
          'num': surveyNo
        }
        this.$store.commit('setSurveyNoActive',surveyNo);
        axios.post(this.ajaxUrl+"/survey_single/v1/query",paramData)
          .then(response => {
            // console.log(response,77777777777777)
            if(response.status == 200){
               // 理赔指引
              this.content =  response.data.claimsGuidelines;//理赔信息
              if(!this.content){
                 this.contentState = true;
                 $(".bottomInfoTeone").removeClass("hide");
                 $(".bottomInfoTe").addClass("hide");
              }else{
                this.contentState = false;
                $(".bottomInfoTeone").addClass("hide");
                $(".bottomInfoTe").removeClass("hide");
                this.content = this.content.replace(/#phone#/g,phoneData[response.data.targetVehicle.companyName]);
                console.log(this.content,"111111111111")
                $(".bottomInfoTe").html(this.content);
              };
              
             
              console.log(response.data.curDetail,"照片")
              //
              this.curDetail = response.data.curDetail;//照片
              //
              this.detailData = response.data.detail;//基本信息
              this.targetVehicle = response.data.targetVehicle;//标的车信息
              console.log(response.data,"标的车信息")
              this.detailPhotoList = response.data.targetVehicle.photoList;//标的车图片列表
              this.thirdPartyList = response.data.thirdPartyList;//第三方车辆信息
              if(this.thirdPartyList.length == 0){
                   this.thirdPartyListState =  false;
              }else{
                  this.thirdPartyListState =  true;
              }
              this.lossState = response.data.surveySingle.claimInfo ? true:false;
              this.signStatus = response.data.surveySingle.status;
              // this.signStatus = 0
              this.signImgUrl = response.data.surveySingle.signUrl;
              // this.agreeThird = 3 ;
              this.agreeThird = response.data.surveySingle.type;
              if(this.lossState){
                this.changeLossList(response.data.surveySingle.claimInfo);
              }
              
            }
          }, err => {
            console.log(err);
          })
          .catch((error) => {
            console.log(error)
          })
      },
    },
    components: {
    },
  };
</script>

