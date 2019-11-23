<template>
    <div id="member" :style="root_style" >
      <div :style="card_style" style="padding-top: 46px">
        <div id="title">
        <i class="firework_icon"></i>
         <span style="width:228px;
height:34px;
font-size:36px;
font-family:PingFang SC;
font-weight:bold;
text-align: center;
color:rgba(241,96,102,1);
">SVIP 升级说明</span>
          <i class="firework_icon"></i>
        </div>

        <div
             class="title_div"
        >
        <i class="start_icon"></i>
          <span style="
height:28px;
font-size:30px;
font-family:PingFang SC;
font-weight:500;
color:rgba(51,51,51,1);">我的草莓精选</span>
        </div>

      </div>

    </div>

</template>

<script>
    export default {
        name: "Menmber",
        data(){
            return{
                root_style: {
                      overflow:"hidden",
                      marginTop:"0px",
                      backgroundImage : "url("+"/static/bg.webp"+")",
                      backgroundRepeat:"no-repeat",
                      height: "1672px",
                      backgroundSize :"100% 100%",
                      width: "749px"

                },
                card_style:{

                    marginLeft:"30px",
                    marginRight:"30px",
                    marginTop:"611px",
                    background:"rgba(255,255,255,1)",
                    backgroundRepeat:"no-repeat",
                    width: "690px",
                    height: "760px",
                    borderRadius:"20px"

                }
            }

        }
    }


</script>
<style type="text/css">
  .start_icon{
    content: "";
    background: url("/static/staricon.webp");
    background-size:contain;
    display: inline-block;
    width: 37px;
    height: 38px;

  }
 .firework_icon{
      content: "";
      background: url("/static/fireworkicon.png");
      background-size:contain;
       display: inline-block;
      width: 53px;
      height: 42px;

 }
  .title_div{
    display: -webkit-box;
    -webkit-box-align: center;
    box-align: center;
    -webkit-align-items: center;
  }

</style>

