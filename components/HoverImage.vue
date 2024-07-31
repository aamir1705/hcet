<template>
  <div class="icon-hover">
    <a
      target="_blank"
      v-for="(social, index) in social_media"
      :href="social.links"
      :key="index"
    >
      <img
        :style="'background-color:' + social.backgorund_color"
        :src="social.photo"
        :alt="social.name"
      />
    </a>
  </div>
</template>
<style>
.icon-hover {
  position: fixed;
  left: 0;
  top: 160px;
  display: flex;
  flex-direction: column;
  z-index: 100;
}

.icon-hover img {
  padding: 3px 5px 3px 2em;
  height: 50px;
}
</style>
<script>
export default {
  data() {
    return {
      social_media: [
        {
          name: "facebook",
          photo: "/img/header/icon__facebook.png",
          backgorund_color: "#1877f2",
          links:
            "https://www.facebook.com/Hitkarini-College-of-Engineering-Technology-227598244116619",
        },
        {
          name: "whatsapp",
          photo: "/img/header/icon__whatsapp.png",
          backgorund_color: "#25d366",
          links: "",
        },
        {
          name: "instagram",
          photo: "/img/header/icon__instagram.png",
          backgorund_color: "#feda75",
          links: "https://www.instagram.com/hcetjabalpur/",
        },
        {
          name: "x",
          photo: "/img/header/icon__x.png",
          backgorund_color: "#000",
          links: "https://twitter.com/HcetJabalpur",
        },
      ],
    };
  },
};
</script>
