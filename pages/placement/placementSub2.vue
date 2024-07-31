<template>
  <AppContainer>
    <Header title="Admission" />
    <section class="probootstrap-section" style="padding-top: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstrap-flex">
              <div class="probootstrap-text probootstrap-animate">
                <div class="sorting-block">
                  <ul class="row sorting-grid" style="list-style: none">
                    <li class="col-md-2 col-sm-4 col-xs-12" v-for="(image, index) in images" :key="index">
                      <img class="img-responsive" :src="image" alt="">
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </AppContainer>
</template>


<script>
export default {
  data() {
    return {
      images:[
        "img/recruiters/1.jpg",
        "img/recruiters/2.jpg",
        "img/recruiters/3.jpg",
        "img/recruiters/4.jpg",
        "img/recruiters/5.jpg",
        "img/recruiters/6.jpg",
        "img/recruiters/8.jpg",
        "img/recruiters/9.jpg",
        "img/recruiters/11.jpg",
        "img/recruiters/12.jpg",
        "img/recruiters/13.jpg",
        "img/recruiters/14.jpg",
        "img/recruiters/15.jpg",
        "img/recruiters/16.jpg",
        "img/recruiters/17.jpg",
        "img/recruiters/18.jpg",
        "img/recruiters/19.jpg",
        "img/recruiters/23.jpg",
        "img/recruiters/24.jpg",
        "img/recruiters/26.jpg",
        "img/recruiters/27.jpg",
        "img/recruiters/28.jpg",
        "img/recruiters/29.jpg",
        "img/recruiters/30.jpg",
        "img/recruiters/32.jpg",
        "img/recruiters/56.jpg",
        "img/recruiters/57.jpg",
        "img/recruiters/58.jpg",
        "img/recruiters/59.jpg",
        "img/recruiters/61.jpg",
      ]
    }
  },
}
</script>
