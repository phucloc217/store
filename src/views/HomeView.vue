<template>
  <div class="m-0">
    <section class="row vh-100 p-3 m-0 pe-0" id="new-product">
      <div class="col-md-6 col-sm-8 p-0">
        <img
          src="../assets/img/s3.jpg"
          alt=""
          srcset=""
          class="img-fluid w-auto"
        />
      </div>
      <div class="col-6 p-0 m-0">
        <div class="row m-0 h-100">
          <div class="col">
            <h1 class="fw-bold text-light text-center">Sản phẩm mới</h1>
            <button class="btn btn-primary mt-5 ms-5">Mua ngay</button>
          </div>
          <div class="row pe-0">
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
                    <div class="col-5 pe-0">
                      <a href="#" class="btn btn-sm btn-primary">Mua ngay</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div
              class="row p-2 pe-0 m-0 ps-5 pt-5"
              style="background-color: #a68a6d"
            >
              <div class="ps-5">
                <p class="text-light lh-lg p-0 m-0 ps-5 pt-5 ms-5 w-75 ms-5">
                  Một sản phẩm tuyệt vời do Eames thiết kế luôn có sức hút và
                  lan truyền kỳ lạ, từ những tạp chí nội thất nổi tiếng đến
                  những nhà hàng khách sạn sang trọng hay trong các gia đình
                  tầng lớp thượng lưu bạn đều có thể bắt gặp.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="row vh-100 p-3 m-0 h-100 position-relative" id="section2">
      <div class="w-50 h-75 row position-absolute
              top-50
              start-50
              translate-middle" style="background-color: #d4c7c0">
        <div class="col position-relative">
          <img
            src="../assets/img/p31.webp"
            alt=""
            srcset=""
            class="
              overflow-visible
              img-fluid
              p-4
              ms-5
              position-absolute
              top-50
              start-25
              translate-middle
            "
          />
        </div>
        <div class="col">
          <h1>Aaron</h1>
          <p class="p-3">
            Đến với Aaron, bạn có thể tìm cho mình những bộ bàn ghế phòng khách,
            những bộ sofa, ghế bành, nội thất phòng khách, phòng ngủ,.. tuyệt
            đẹp cho căn nhà của mình.
          </p>
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
#section2 {
  background-image: url("@/assets/img/p2.png");
  background-size: cover;
}
</style>
