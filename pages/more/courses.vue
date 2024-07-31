<template>
  <AppContainer>
    <Header title="Our Courses" />
    <section class="probootstrap-section" style="padding: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstap-flex-block">
              <div class="probootstrap-text probootstrap-animate">
                <div class="text-uppercase probootstrap-uppercase">
                  Featured Course
                </div>
                <H3Light>COMPUTER SCIENCE</H3Light>
                <section class="flexslider">
                  <ul class="slides">
                    <li>
                      <div class="item">
                        <img alt="" src="/img/csDept1.jpg" />
                      </div>
                    </li>
                  </ul>
                </section>
                <p>
                  H.C.E.T. has the latest software like ORACLE 8 I Workgroup
                  Server 8.0, Developer 2000, Visual Studio 6.0, Turbo C++/
                  Turbo assembler, Auto Desk, AutoCad R14, Cobol, Pascal,
                  Fortran77, MS Office 2000 running on OS like Win NT, Win 98,
                  Win ME and Windows 2000.
                </p>

                <p>
                  Generally Speaking, the courses related with the
                  word"Computing" come with a variety of titles. Courses with
                  the word 'computing' in their title will be more biased
                  towards practical applications, and courses based around
                  'computer science' will have a more theoretical content.
                  Computer Science and Engineering covers Software
                  Engineering,Computer systems, Artificial Intelligence,
                  Information System Management, Computer Science and
                  Mathematics
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-7">
      <RecCards
        v-for="(course, index) in courses"
        :key="index"
        :image="course.image"
        :title="course.title"
        :desc="course.desc"
        :url="course.url"
      />
    </div>
  </AppContainer>
</template>
<script>
export default {
  data() {
    return {
      courses: [
        {
          image: "/img/informationTechnology.png",
          title: "Information Technology",
          desc: "Our best in class department of Information & Technology with some of the best laboratories to learn by doing, lead by our best faculity members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
        {
          image: "/img/electronicsCommunication.jpg",
          title: "Electronics & Communication Engg.",
          desc: "Our best in class, department of Electrical & Electronics, equipped with best instruments and tools to understand the circuits and systems, also it is lead by our best faculty members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
        {
          image: "/img/civilEngg.jpg",
          title: "Civil Engineering",
          desc: "Our best in class Civil Engineering Department, equiped with best constructing, measurings instruments with best laboratories, lead by our best faculity members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
        {
          image: "/img/computerScience1.jpg",
          title: "Computer Science",
          desc: "Our best in class department of Computer Science & Engineering, with best Computer and Operating Systems laboratories, lead by our best faculity members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
        {
          image: "/img/electricalEngineering.jpg",
          title: "Electrical & Electronics Engg.",
          desc: "Our best in class, department of Electrical & Electronics, equipped with best instruments and tools to understand the circuits and systems, also it is lead by our best faculty members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
        {
          image: "/img/mechanicalEngg1.jpeg",
          title: "Mechanical Engineering",
          desc: " Our best in class Mechanical Engineering Department, equiped with best laboratories and tools, lead by our best faculity members.",
          url: "https://docs.google.com/forms/d/e/1FAIpQLSfkJl1aqLL5wESnTipy1ZsW6rQNqqVAA9K0qfdfhCMtkvSj1Q/viewform",
        },
      ],
    };
  },
};
</script>
