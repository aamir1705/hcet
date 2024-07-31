<template>
  <footer class="flex flex-col p-5 bg-[#00008B] text-white md:px-36 md:py-40 md:flex-row md:justify-around ">
    <div class="">
      <h3 class="text-4xl pb-14">Useful Links</h3>
      <div class="flex flex-col gap-5 md:flex-row md:gap-20">
        <ul v-for="(link, index) in links" :key="index">
          <li v-for="url in link" class="py-1">
            <a :href="url.url">{{ url.name }}</a>
          </li>
        </ul>
      </div>
    </div>
    <div>
      <div>
        <h3 class="text-4xl pb-14">Contact Info</h3>
        <ul>
          <li>
            <i class="icon-location2"></i>
            <span
              >Hitkarini Hills, Dumna Airport Road, Tembhar, Jabalpur Madhya
              Pradesh-482005</span
            >
          </li>
          <li>
            <i class="icon-mail"></i
            ><span
              >admission_hcet@hitkarini.edu.in /
              principal_hcet@hitkarini.edu.in</span
            >
          </li>
          <li>
            <i class="icon-phone2"></i
            ><span>+91 - 761- 2600 222, 223, 300</span>
          </li>
          <li><i class="fa fa-fax"></i><span> +91 - 761 - 2600 223</span></li>
        </ul>
      </div>
      <div>
        <h3>Social</h3>

        <a href="https://twitter.com/HcetJabalpur"
          ><i class="icon-twitter"></i>
        </a>
        <a
          href="https://www.facebook.com/Hitkarini-College-of-Engineering-Technology-227598244116619/"
          ><i class="icon-facebook"></i
        ></a>

        <a href="https://www.instagram.com/hcetjabalpur/"
          ><i class="icon-instagram2"></i
        ></a>

        <a
          href="https://www.youtube.com/channel/UCbcc4Mk-kHpw78K627QDpRg/featured"
          ><i class="icon-youtube"></i
        ></a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      links: [
        [
          {
            name: "Home",
            url: "/",
          },
          {
            name: "Sabha",
            url: "",
          },
          {
            name: "Admission",
            url: "",
          },
          {
            name: "Academics",
            url: "",
          },
          {
            name: "Courses",
            url: "",
          },
        ],
        [
          {
            name: "Vision & Mission",
            url: "",
          },
          {
            name: "College Committees",
            url: "",
          },
          {
            name: "HECAA",
            url: "",
          },
          {
            name: "Infrastructure",
            url: "",
          },
        ],
        [
          {
            name: "Sports & Atheletics",
            url: "",
          },
          {
            name: "Prominent Recruiters",
            url: "",
          },
          {
            name: "Placement Records",
            url: "",
          },
          {
            name: "National Award",
            url: "",
          },
          {
            name: "Admission Enquiry",
            url: "",
          },
        ],
      ],
    };
  },
};
</script>
