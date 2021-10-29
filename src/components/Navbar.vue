<template>
  <nav>
      <div class="logo">
          <img src="../assets/green-logo.png" alt="logo">
      </div>

      <div class="list">
          <ul v-for="list in navLists" v-bind:key="list">
              <li>{{list}}</li>
              
          </ul>
    
      </div>
  </nav>
</template>

<script>
export default {
data() {
    return {
        navLists: [
            "About",
            "FAQs",
            "Contact us"
        ]
    };
}
}

</script>

<style scoped>
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
 ul{
     list-style-type: none;
     
 }

 .list{
          display: flex;
          margin-right: 123px;
          font-size: 16px;
          color: #6A6A70;
          column-gap: 40px;
          
 }

 .logo{
     margin-left: 113px;
 }
</style>