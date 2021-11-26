<template>
    <!-- <div class="p-2 bg-light border">
        <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><router-link to="/">Home</router-link></li>
    <li class="breadcrumb-item active" aria-current="page">Contact</li>
  </ol>
</nav>
    </div> -->
    <Header/>
    <div class="p-2 bg-primary border text-white">
        <h1>Contact Form </h1></div>
    <div class="container">
        <form class="row g-3">
  <div class="col-md-4">
    <label for="validationDefault01" class="form-label">First name</label>
    <input type="text" class="form-control" id="validationDefault01" value="Mark" required>
  </div>
  <div class="col-md-4">
    <label for="validationDefault02" class="form-label">Last name</label>
    <input type="text" class="form-control" id="validationDefault02" value="Otto" required>
  </div>
 
  <div class="col-md-6">
    <label for="validationDefault03" class="form-label">Enquiry</label>
    <textarea class="form-control is-invalid" id="validationTextarea" placeholder="Required example textarea" required></textarea>
  </div>
  
  
  <div class="col-12">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" value="" id="invalidCheck2" required>
      <label class="form-check-label" for="invalidCheck2">
        Agree to terms and conditions
      </label>
    </div>
  </div>
  <div class="col-12">
    <button class="btn btn-primary" type="submit">Submit form</button>
  </div>
</form>
    </div>
    <br>
    <br>



    <Footer/>
</template>

<script>

import Footer from '@/components/Footer'
import Header from '../components/Header.vue'
    export default {
        name:'Contact',
        components: {
    Footer,
    Header
}
    }
</script>

<style scoped>

</style>