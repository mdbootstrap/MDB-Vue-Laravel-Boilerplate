<template>
    <mdb-container class="text-center main-text">
      <h1 class="title py-4">Amazing App</h1>
        <div class="d-flex justify-content-center">
          <div class="image-container">
            <img src="../../../public/images/logo.png" class="img-fluid"/>
          </div>
        </div>
        <h2 class="subtitle">MDBootstrap + Vue + Laravel</h2>
        <hr class="my-5"/>
        <div>
          <p>Find out more about MDB Vue components and how to use them:</p>
          <mdb-btn outline="elegant" size="bg"><a href="https://mdbootstrap.com/docs/vue/" target="_blank" class="main-text">Documentation</a></mdb-btn>
        </div>
    </mdb-container>
</template>


<script>
import { mdbContainer, mdbBtn } from "mdbvue";
export default {
    components: { mdbContainer, mdbBtn }
};
</script>
<style>
.container {
  margin: 10vh auto 0 auto;
  min-height: 90vh;
  padding-bottom: 15px;
}

.main-text {
  color: #526488;
}

.image-container {
  max-width: 400px;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
}

.links {
  padding-top: 15px;
}
</style>