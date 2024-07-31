<template>
    <div class="flex flex-col justify-between p-3 md:flex-row">
      <div class="flex flex-col-reverse gap-4 md:flex-row">
        <div>
          <i class="icon-location2"></i>Dumna Airport Road, Jabalpur, India -
          482005
        </div>
        <div>
          <i class="icon-phone2"></i><a href="tel:07614129820">0761-4129820</a>,
          <a href="tel:+918602476036">8602476036</a>,
          <a href="tel:+917771918925">7771918925</a>
        </div>
        <div>
          <i class="icon-mail"></i
          ><a href="mailto:admission_hcet@hitkarini.edu.in"
            >admission_hcet@hitkarini.edu.in</a
          >
        </div>
      </div>
      <div class="flex gap-2">
        <a v-for="(item, index) in social_media" :key="index" target="_blank" :href="item.links"
          ><img class="h-7 w-7" :src="item.photo" :alt="item.name"
        /></a>
      </div>
    </div>
  </template>
  
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
  