<template>
  <div class="success-main">
    <div class="success-img">
      <SuccessImg />
    </div>
    <div class="success-info">
      {{text}}
      {{text1}}
    </div>
    
    
  </div>
</template>

<script>
import SuccessImg from "../success/SuccessImg.vue";
export default {
name:"checkout",

data(){
    
    
    return{
        text: "Order Placed Successfully",
        
        text1: "Thank You!!"

    };
    
},
components: {
    SuccessImg,
  },
}
</script>

<style scoped>
.success-main{
  background-color: teal;
}

.success-info{
  color:whitesmoke;
  font-weight: bold;
  margin-top: 10px;
  margin-left: 130px;
  
}
.success-img{
  margin-left:130px;
  margin-top:130px;
}
</style>
