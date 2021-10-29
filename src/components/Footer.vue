<template>
  <footer>
      <div class="footer-wrapper">
<div>
    <img class="logo" src="../assets/Group-6-Copy Copy.png" alt="logo">
<p><img class="copyright" src="../assets/Copyright.png" alt="copyright">2020 ear1Social</p>
<p class="privacy">Privacy policy  |  Terms of service</p>
</div>

<div>
    <ul v-for="list in footerLists" v-bind:key="list">
        <li>{{list}}</li>
    </ul>
</div>

<div class="feedback">
    <h4>Get in touch</h4>
    <p class="questions">Questions or feedback?, we <br/> would love to hear from you.</p>
    <img src="../assets/icons.png" alt="icons">
</div>
      </div>
  </footer>
</template>

<script>
export default {
data() {
    return {
        footerLists: [
            "Company",
            "About us",
            "FAQs",
            "Contact us"
        ]
    };
}
}
</script>

<style scoped>


footer{
    background-color: #39393F;
    width:inherit;
    height: 344px;
    color: white;
    margin: 0;
    display: flex;
    justify-content: center;
}

.footer-wrapper{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    align-items: center;
    justify-content: center;
    column-gap: 200px;
}


li, .questions, .privacy{
color: #BBBBBB;
font-size: 18px;
}
p, ul:first-child{
    font-size: 20px;
line-height: 84.6%;
color: #FCFCFC;
}
.questions{
    line-height: 25px;
}

ul{
    list-style-type:none ;
}

.logo{
    padding-bottom:10px ;
}

.copyright{
    margin-right:8px ;
}

.feedback{
    padding-bottom: 30px;
}


</style>