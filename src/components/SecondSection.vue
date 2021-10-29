<template>
  <div class="second-section">
    <div class="shola">
      <img src="../assets/Shola.png" alt="Shola" />
    </div>
   <div class="box">
        <div class="greenbox one">
      <img class="apple" src="../assets/ant-design_apple-outlined.png" alt="apple" />
      <div>
        <p class="small-text">Get it on</p>
        <p>App store</p>
      </div>
    </div>
    <div class="greenbox two">
      <img class="playstore" src="../assets/Vector.png" alt="vector" />
      <div>
        <p class="small-text">Get it on</p>
        <p>Google play</p>
      </div>
    </div>
   </div>
    <div class="moe">
      <img src="../assets/Moe.png" alt="moe" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
*{
    box-sizing: border-box;
}
.second-section {
  display: flex;
  align-items: flex-start;
  justify-content: space-evenly;
  column-gap: 10px;
  padding-top: 50px;
}
.box{
    display: flex;
}

.greenbox.one {
  background-color: #00bf69;
  border-radius: 5px;
  width: 155px;
  height: 62px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-right: 22px;
 
}
.greenbox.two {
  background-color: #00bf69;
  border-radius: 5px;
  width: 180px;
  height: 62px;
  display: flex;
  align-items: center;
  justify-content: space-around;
 
}
p {
  margin: 0;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: -0.03em;
  color: #ffffff;
  margin-right: 20px;
  font-weight: 500;
}

.small-text{
    font-size: 12px;
    margin-bottom: 3px;
}
.apple{
    width: 29px;
    height: 29px;
}

.playstore{
    width: 22px;
    height: 26px;
    margin-left: 10px;
}

.shola{
padding: 80px 0 0 120px;
}

.moe{
     padding: 80px 120px 0 0;
}

</style>