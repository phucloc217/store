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
                <p class="text-light fs-5 lh-lg p-0 m-0 ps-5 pt-1 ms-5 w-75 ms-5">
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
      <div
        class="w-50 h-75 row position-absolute top-50 start-50 translate-middle"
        style="background-color: #d4c7c0"
      >
        <div class="col-md-2 col-sm-8 position-relative">
          <img
            src="../assets/img/p31.webp"
            alt=""
            srcset=""
            class="
              overflow-visible
              h-100
              w-auto
              p-4
              ms-5
              position-absolute
              top-50
              start-25
              translate-middle
            "
          />
        </div>
        <div class="col-md-10 col-sm-8 position-relative pt-5 ps-5">
          <h1
            id="Aaron"
            class="mt-5 position-absolute bottom-25 end-50 translate-middle"
          >
            Aaron
          </h1>
          <div class="d-flex align-items-end h-100">
            <p class="p-3 ps-5 mb-5 ms-5 fs-5 lh-lg" id="text-section2">
              Đến với Aaron, bạn có thể tìm cho mình những bộ bàn ghế phòng
              khách, những bộ sofa, ghế bành, nội thất phòng khách, phòng ngủ,..
              tuyệt đẹp cho căn nhà của mình.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="row vh-100 p-0 m-0" id="section3">
      <div
        class="col-md-5 col-sm-12 p-3 ps-5 pt-5 h-100"
        style="background-color: #a68a6d"
      >
        <h1 class="text-light fw-bold ms-4 mt-5">Nội thất sang trọng</h1>
        <p class="fs-5 fw-light text-light ms-4 lh-lg mt-5 pe-5">
          Thiết kế nội thất chính là bước “thổi hồn” vào không gian sống khi ban
          đầu chỉ có gỗ, đá thô kệch. Nội thất có đẹp có tiện ích về công năng,
          sẽ mang lại năng lượng tích cực cả về sức khỏe và tinh thần cho gia
          chủ.
        </p>
      </div>
      <div
        class="
          col-md-7 col-sm-12
          h-100
          ps-0
          pt-3
          d-flex
          align-items-end
          position-relative
        "
        style="background-color: #211a11"
      >
        <div
          class="
            row
            w-50
            h-auto
            p-3
            ms-5
            position-absolute
            top-25
            start-50
            translate-middle
          "
          style="background-color: #a68a6d"
        >
          <h1 class="text-light">Về chúng tôi</h1>
          <p class="text-light">
            PHUC LOC LUXURY INTERIOR mang sứ mệnh đem đến những sản phẩm nội
            thất sang trọng, phù hợp dành riêng cho ngôi nhà của bạn.
          </p>
        </div>
        <div class="row mt-5">
          <div class="col w-75">
            <img
              src="../assets/img/p3.webp"
              alt=""
              srcset=""
              class="img-fluid h-75 w-auto ms-0"
            />
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
@font-face {
  font-family: Virtual;
  src: url("@/assets/font/Virtual-Regular.ttf");
}
@font-face {
  font-family: RoxboroughCF;
  src: url("@/assets/font/RoxboroughCF-Thin.otf");
}
#section2 {
  font-family: RoxboroughCF;
  color: #4a3022;
}
#Aaron {
  font-family: Virtual;
  font-size: 10rem;
  color: #4a3022;
}
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
