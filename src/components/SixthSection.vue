<template>
  <section>
      <div>
          <h2>Build great relationships with <br/>those you admire.</h2>
          <p class="tiny-text">With ear1, replies to your DMs are guaranteed!</p>
      </div>

       <div class="box">
        <div class="blackbox one">
      <img class="apple" src="../assets/ant-design_apple-outlined.png" alt="apple" />
      <div>
        <p class="small-text">Get it on</p>
        <p>App store</p>
      </div>
    </div>
    <div class="blackbox two">
      <img class="playstore" src="../assets/Vector.png" alt="vector" />
      <div>
        <p class="small-text">Get it on</p>
        <p>Google play</p>
      </div>
    </div>
       </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
*{
    box-sizing: border-box;
   color: white
}

section{
    background-color: #00BF69;
    width: 1134px;
height: 265px;
border-radius: 30px;
margin: 94px auto;
display: flex;
align-items: center;
justify-content: space-evenly;
}

.box{
    display: flex;
}

.blackbox.one {
  background-color: #39393F;
  border-radius: 5px;
  width: 155px;
  height: 62px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-right: 22px;
 
}
.blackbox.two {
  background-color: #39393F;
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
h2 {
  margin-bottom: 26px;
  font-size: 35px;
  line-height: 115.3%;
  letter-spacing: -0.03em;
  color: #ffffff;
  font-weight: 700;

}

.tiny-text{
    font-size: 18px;
    margin-bottom: 3px;
    line-height: 185.6%;
    letter-spacing: -0.03em;
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
</style>