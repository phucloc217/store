<template>
  <div class="m-0">
    <section class="row vh-100 p-3 m-0" id="new-product">
      <div class="col-md-6 col-sm-8 p-0">
        <img
          src="../assets/img/s3.jpg"
          alt=""
          srcset=""
          class="img-fluid w-auto"
        />
      </div>
      <div class="col-6 p-0 m-0">
        <div class="row m-0  h-100">
          <div class="col">
            <h1 class="fw-bold text-light text-center">Sản phẩm mới</h1>
            <button class="btn btn-primary">Mua ngay</button>
          </div>
          <div class="row ">
            <div class="row">
              <div class="col">
                <div
                  class="
                    card
                    position-absolute
                    start-50
                    translate-middle
                    shadow
                    p-3
                    mb-5
                    bg-white
                    rounded
                  "
                  style="width: 18rem"
                  id="card"
                >
                  <img
                    src="../assets/img/s.jpg"
                    class="card-img-top pt-4 ps-4 pe-4"
                    alt="..."
                  />
                  <div class="row card-body">
                    <h5 class="card-title">Ghế vintage</h5>
                    <div class="col-7">
                      <p class="card-text">2.000.000 đ</p>
                    </div>
                    <div class="col-5">
                      <a href="#" class="btn btn-sm btn-primary">Mua ngay</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row p-2 pe-0 m-0 " style="background-color:#A68A6D;">
              <p class="text-light p-0 m-0">
                 Một sản phẩm tuyệt vời do Eames thiết kế luôn có sức hút và lan truyền kỳ lạ, từ những tạp chí nội thất nổi tiếng đến những nhà hàng khách sạn sang trọng hay trong các gia đình tầng lớp thượng lưu bạn đều có thể bắt gặp.
              </p>
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

#card {
  top: 470px;
}
</style>
