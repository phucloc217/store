<template>
  <div class="m-0">
    <section class="row vh-100 p-2 m-0" id="new-product">
      <div class="col-6 p-0">
        <img
          src="../assets/img/s3.jpg"
          alt=""
          srcset=""
          class="img-fluid w-auto"
        />
      </div>
      <div class="col-6 p-0">
        <div class="row">
          <div class="col">
            <h1 class="fw-bold text-light text-center">Sản phẩm mới</h1>
            <button>Mua ngay</button>
          </div>
          <div class="row">
            <div class="col">
              <img src="../assets/img/s.jpg" alt="" srcset="" class="img-thumbnail w-25 position-absolute top-100 start-50 translate-middle">
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "HomeView",
  components: {},
};
</script>

<style scoped>
#new-product {
  background-color: #211a10;
}
</style>
