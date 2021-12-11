<template>
    <div >
        <div class="card-group py-5 px-5" >
  <div class="card" v-for= "item in products" :key="item.title">
    <img :src="item.image" class="card-img-top" >
    <div class="card-body">
      <h5 class="card-title">{{item.title}}</h5>
      <p class="card-text">{{item.desc}}</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <!-- <div class="card">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div> -->
</div>
    </div>
</template>

<script>
    export default {
        name:'Products',
        data(){
            return{
                products : [
                    {
                        title:'paintings',
                        desc:'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                        image:'/assets/img/card2.png'
                    },
                    {
                        title:'gifts',
                        desc:'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                        image:'/assets/img/card1.png'
                    },
                    {
                        title:'technology',
                        desc:'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                        image:'/assets/img/card3.png'
                    },
                ]
            }
        }
        
    }
</script>

<style scoped>

</style>