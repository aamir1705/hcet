<template>
  <div class="flex flex-col md:flex-row justify-around py-10">
    <div class="flex items-center gap-5 flex-col">
      <img class="h-32" src="/img/vector_logo.png" />
      <h1>ESTD. 1997</h1>
    </div>
    <div class="flex flex-col justify-around">
      <h1 class="text-5xl font-bold">
        Hitkarini College of Engineering Technology
      </h1>
      <div class="font-light">
        Approved by AICTE, New delhi| Affiliated to RGPV, Bhopal | Recognised by
        Directorate by Technical education, Bhopal, MP
      </div>
      <div>
        <div class="blink-bg">
          <a href="admissionEnquiry.html">For Admission Enquiry click here!!</a>
        </div>
      </div>
        <ul class="flex flex-col gap-2 p-2 md:flex-row md:justify-around md:p-0">
        <li
          v-for="(item, index) in links"
          :key="index"
          class="dropdown"
        >
          <a :href="item.url">{{ item.name }}</a>
          <ul
            v-if="item.hasOwnProperty('sub_links')"
            class="dropdown-menu"
          >
            <li v-for="sub_link in item.sub_links">
              <a :href="sub_link.url">{{ sub_link.name }}</a>
            </li>
          </ul>
        </li>
      </ul>

    </div>
  </div>
</template>
<style>
.dropdown {
  position: relative;
}
.dropdown-menu {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 270px;
  padding: 12px 16px;
  gap: 1em;
  z-index: 1;
}
.dropdown:hover .dropdown-menu {
  display: flex;
  flex-direction: column;

}
@media screen and (max-width: 480px){
  .dropdown-menu{
    z-index: 0;
    min-width: auto;
    position: relative;
  }
}
</style>
<script>
export default {
  data() {
    return {
      links: [
        {
          name: "Home",
          url: "/",
        },
        {
          name: "Faculty",
          url: "/faculty",
        },
        {
          name: "Events",
          active: false,
          sub_links: [
            {
              name: "Hitkarini Mahotsav",
              url: "/events/hitkarini-mahotsav",
            },
            {
              name: "National Service Scheme Camp",
              url: "/events/national-service-scheme-camp",
            },
            {
              name: "National Cadet Corps",
              url: "/events/national-cadet-corps",
            },
            {
              name: "Events,Workshops & Seminars",
              url: "/events/events-and-workshops",
            },
            {
              name: "Cultural Events",
              url: "/events/cultural-events",
            },
            {
              name: "National Conferences",
              url: "/events/national-conferences",
            },
          ],
        },
        {
          name: "Admission",
          active: false,
          sub_links: [
            {
              name: "Admission Enquiry",
              url: "/admission/admission-equiry",
            },
            {
              name: "Admission",
              url: "/admission/admission",
            },
            {
              name: "Academic Rules",
              url: "/admission/academic-rules",
            },
            {
              name: "Hostel Admission",
              url: "/admission/hostel-admission",
            },
            {
              name: "Documents Required",
              url: "/admission/https://hcet.hitkarini.com/img/document_required.pdf",
            },
          ],
        },
        {
          name: "Department",
          active: false,
          sub_links: [
            {
              name: "Information Technology",
              url: "/department/information-technology",
            },
            {
              name: "Computer Science & Engineering",
              url: "/department/Computer-science-and-engineering",
            },
            {
              name: "Electronics & Communication",
              url: "/department/electronics-and-communication",
            },
            {
              name: "Electrical & Electronics",
              url: "/department/electrical-and-electronics",
            },
            {
              name: "Mechanical Engineering",
              url: "/department/mechanical-engineering",
            },
            {
              name: "Civil Engineering",
              url: "/department/civil-engineering",
            },
            {
              name: "Chemistry",
              url: "/department/chemistry",
            },
            {
              name: "Physics",
              url: "/department/physics",
            },
            {
              name: "Mathematics",
              url: "/department/mathematics",
            },
            {
              name: "Humanities",
              url: "/department/humanities",
            },
            {
              name: "Master of Business Administration",
              url: "/department/master-of-business-administration",
            },
          ],
        },
        {
          name: "Placement",
          active: false,
          sub_links: [
            {
              name: "Training & Placement",
              url: "/placement/training-and-placement",
            },
            {
              name: "Prominent Recruiters",
              url: "/placement/prominent-recruiters",
            },
            {
              name: "Placement Records",
              url: "/placement/placement-records",
            },
            {
              name: "Our Mission",
              url: "/placement/our-mission",
            },
            {
              name: "Accreditration by TCS",
              url: "/placement/accreditration-by-tcs",
            },
          ],
        },
        {
          name: "HECAA",
          active: false,
          sub_links: [
            {
              name: "HECAA",
              url: "https://hecaa.in/",
            },
            {
              name: "Alumni Association",
              url: "/hecaa/alumni-association",
            },
            {
              name: "HECAA Gold Medal Distribution",
              url: "/hecaa/hecca-gold-medal-distribution",
            },
          ],
        },
        {
          name: "More",
          active: false,
          sub_links: [
            {
              name: "About Us",
              url: "/more/about-us",
            },
            {
              name: "Courses",
              url: "/more/courses",
            },
            {
              name: "Download",
              url: "/more/about-us",
            },
            {
              name: "Gallery",
              url: "/more/gallery",
            },
            {
              name: "News",
              url: "/more/news",
            },
          ],
        },

        {
          name: "Contact",
          url: "/contact",
        },
      ],
    };
  },
};
</script>
