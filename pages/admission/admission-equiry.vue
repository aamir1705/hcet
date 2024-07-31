<template>
  <AppContainer>
    <Header title="COURSES OFFERS" />
    <div class="flex flex-col gap-10 md:gap-0 md:flex-row justify-around p-8">
      <a
        target="_blank"
        v-for="(course, index) in couses"
        :key="index"
        :href="course.url"
      >
        <img :src="course.image" alt="" />
      </a>
    </div>
    <div class="flex justify-center py-16">
      <a href="img/HCET Brochure 24-25 PDF.pdf">
        <RoundButton> DOWNLOAD COLLEGE BROCHURE </RoundButton>
      </a>
    </div>

    <Slider />
  </AppContainer>
</template>
<script>
export default {
  data() {
    return {
      main_slider: [
        {
          image: "img/1680343045271.jpg",
        },
        {
          image: "img/1680343045223.jpg",
        },
        {
          image: "img/couns1.jpg",
        },
        {
          image: "img/couns2.jpg",
        },
        {
          image: "img/couns3.jpg",
        },
        {
          image: "img/couns4.jpg",
        },
        {
          image: "img/couns5.jpg",
        },
        {
          image: "img/couns6.jpg",
        },
      ],
      couses: [
        {
          url: "https://forms.gle/XMzr6iNQiRgXBcZa6",
          image: "/img/btech.jpg",
        },
        {
          url: "https://forms.gle/gVuwfkuiApydy4SP7",
          image: "/img/lateral.jpg",
        },
        {
          url: "https://forms.gle/TjAgQPaHhZkDHWpx9",
          image: "/img/mba_mtech.jpg",
        },
      ],
    };
  },
};
</script>
