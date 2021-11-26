<template>
  
     <Header/>
    
   
    <Body msg="Welcome to Your Vue.js App"/>
    <Card/>
    
    <Footer/>
 
</template>

<script>
// @ is an alias to /src
import Body from '@/components/Body.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import Card from '@/components/Card.vue'


export default {
  name: 'Home',
  components: {
  Body,
  Header,
  Card,
  Footer,
  
  }
}
</script>
