<template>
  <AppContainer>
    <Slider v-for="(slider, index) in firstSlider" :key="index" />

    <p>
      Yoga-Championship | State Level Nodal Level Your Bright Future is Our
      Mission Nurturing Every Student Fulfill their Dreams 1 2 3 4 5 6 7 8 9 10
      11 12 13 14 15 16 17 18 A proud moment for all HCETians!!! The success of
      soft landing of Chandrayaan-3 has been celebrated all across the country.
      But we at Hitkarini College of Engineering & Technology, have an
      additional reason to celebrate because one of the ISRO team members
      working on the Chandrayaan-3 project is an alumni of our college. Ms Megha
      Khare, after completing her B.E. from Hitkarini College of Engineering &
      Technology (HCET) batch 2003 from Electronics and Tele Communications
      branch, has been working with ISRO since 2004. Currently she is posted at
      ISRO's U. R. Rao Satellite Centre in Bangalore. As the Project Manager for
      the Chandrayaan-3 project, Ms. Khare has led her team to this amazing
      achievement.
    </p>
    <div>
      <img src="img/sabha150.png" alt="" />
      <h3>About HCET</h3>
      <p>
        Jabalpur, Situated by the banks of sacred river Narmada and surrounded
        by the hills of Madan Mahal, the tapasya-bhoomi of sage Jabaali, a
        witness to the valor of Rani Durgawati ornamented with the title of
        “Sanskardhani” by Acharya Vinoba Bhave, The city has its own magnificent
        and enriching history. Hitkarini Sabha,for its continuous hard work in
        education and society, indelible mark on Jabalpur and adode of well
        known academic institutions.
      </p>
      <p>
        Hitkarini Sabha was established in 1868,with the combined effort of Shri
        Raja Balwant Rao Kher, Shri Diwan Bihari Lal Khajanchi and Shri Ambika
        Charan Banerjee.One of the oldest educational organization , Hitkarini
        Sabha , for more than a century, the institution has been working
        towards the educational and social upliftment of the citizens of Madhya
        Pradesh. Since its inception year 1868 Hitkarini Sabha has focused on
        instilling the essence of National consciousness and etiquettes in the
        young minds through academics. Hitkarini Sabha is one the oldest
        academic Societies, not just of Madhya Pradesh, but of modern India. In
        truth, the history of Hitkarini Sabha and rise of nationalistic
        consciousness in the state coincides.Established a decade after the
        first freedom movement, this Organisation has played an impartive role
        in creating the feeling of independence, inspiring its citizens to be
        educated, cultured, independent and self-reliant. Hitkarini Sabha was
        Established with the foremost intention of creating such individuals who
        excel in behavioral, cultural, traditional, social, physical and mental
        aptitude so they are able and contribute in the progression and
        development of our Nation with combining these administrative skills
        with the literary and philosophical mindset.
      </p>
      <p>
        The National movement of 1919 presented Hitkarini Sabha an opportunity
        of an active role, when Mahatma Gandhi called for the non-cooperation
        movement, all the sabha members, teachers and students joined in and the
        schools were transformed into national schools. Father of the nation,
        Mahatma Gandhi’s was so that, Hitkarini Sabha became his admirer and
        follower. The British Rule, of that time, did not approve of it and
        recognition of all educational institutes run by Hitkarini Sabha was
        cancelled, which was later restored in 1923. And this how, Hitkarini
        Sabha has made a special contribution in the national Swaraj Movement.
        The brutality of British rule had taken control of the whole of India.
        So, the need for education and educational institutes was quickly felt.
        With this objective in mind, the well-wishers and academicians of
        Jabalpur city started their struggle to open education institutes;
        Hitkarini Sabha was the first to go ahead on this objective and the
        progression stream in the field of education is still ongoing.
      </p>
      <div>
        <button>Learn More</button>
      </div>
    </div>

    <div>
      <Slider v-for="(slider, index) in secondslider" :key="index" />
    </div>

    <div>
      <h3>Placements</h3>
      <Slider v-for="(slider, index) in thirdslider" :key="index" />
    </div>

    <div>
      <h3>Highlights</h3>
      <button>Featured News</button>
      <button>Events</button>
    </div>

    <RollSlider />

    <div>
      <h3>Important Links</h3>
      <p>
        Some of the Important Sites You Can Visit From Our Site, to Get More
        Details
      </p>
    </div>

    <div>
      <h3>Our Featured Courses</h3>
      <p>Courses we offer to brighten up your future, do visit them</p>
      <div>
        <RecCards />
      </div>
    </div>

    <div>
      <h3>Prime Movers</h3>
      <Cards
        v-for="(card, index) in cards"
        :key="index"
        :name="card.name"
        :destination="card.destination"
        :photo="card.photo"
      />
    </div>

    <div>
      <h3>Achievements</h3>
      <p>
        Highlights of our most valueable achievements, because achievements is
        what that define us
      </p>
      <Slider />
    </div>

    <div>
      <h3>Message From - Founder Chairman (Shri Chandra Mohan)</h3>
      <div>
        <img src="/img/chairman.jpg" alt="" />
        <p>
          "We cannot always build the future for our youth, but we can build our
          youth for the future."
        </p>
        <b>Franklin D. Roosevelt</b>
      </div>
      <p>
        HITKARINI COLLEGE OF ENGINEERING & TECHNOLOGY is the first top-tier
        Institute in CENTRAL INDIA Established in 1997.It Holds 24 years of rich
        experience under the aegis of HITKARINI SABHA and inherits the cultural
        and academic values of 153 YEARS .As H.C.E.T works diligently to realize
        its mission of providing the best learning, teaching and research
        opportunities to students and Faculties alike, it continues to supply
        students with the basics of modern knowledge and high values .H.C.E.T
        provides active extra-curricular activities like sports, cultural ,
        literature ,science & technological events on regular basis. The College
        inculcates the development in all facets of life. Our team of dedicated
        and highly qualified faculty strives to widen the student’s horizon of
        learning, thereby helping every student to taste success with high
        grades.
      </p>
      <p>
        I BEING AN EDUCATIONIST FOR 50 YEARS, AM PROUD TO BE ASSOCIATED WITH
        FIRST ENGINEERING COLLEGE OF MAHAKOHSAL REGION AND GUIDE OUR STUDENTS TO
        BE BEST ENGINEERS AND NATION BUILDERS.
      </p>
      <b>WELCOME!!! TO H.C.E.T</b>
      <h3>Message From - Chairman (Prof Y.C UPRIT)</h3>
      <img src="/img/uprit.jpg" />
      <p>
        "As the chairman of this institution, I anticipate the full
        participation and cooperation of the students and parents to make it
        possible for us to transform those dreams to reality. And if there is
        any assistance that you might need, may it be personal or professional,
        I shall always be willing to hear from you."
      </p>
      <b>I Welcome you in, H.C.E.T</b>
      <h3>Why Choose HCET</h3>
      <p>
        We at HCET strongly believe in moulding ourselves and our students with
        the changing time, technology and expectation yet holding firmly to our
        traditions and values. Our mission is to be an Institution at par with
        the world's best, offering high quality education and training by
        continuous improvement in all our activities
      </p>
    </div>
    <div>
      <div v-for="(icon, index) in icons" :key="index">
        <i></i>
        <div>
          <h4>{{ icon.topic }}</h4>
          <p>{{ icon.desc }}</p>
        </div>
      </div>
    </div>
  </AppContainer>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      icons: [
        {
          topic: "Facilities",
          desc: "We at HCET, offers best facilities and comfort to all our students so that they can focus in studies and can perform their best.",
        },
        {
          topic: "Atmosphere",
          desc: "We have best in class enviroment throughout our whole campus, which gives a vibe to do something more.",
        },
        {
          topic: "Courses",
          desc: "We offer best and variety of courses, with high quality of laboratories and faculty members.",
        },
        {
          topic: "Library",
          desc: "We believe that for any institution, library is really a big part, so we focused and made a library filled with books and space to read, understand and implement.",
        },
        {
          topic: "Teaching Quality",
          desc: "We have best in class teaching facilities, all credits to our faculty members, who do there best to raise our students level and make them confident in what so over they want to become in there lifes.",
        },
        {
          topic: "Practicality",
          desc: "We believe that the knowlege comes only by doing, so we focus more on practical implementation, rather than just the lectures.",
        },
      ],
      cards: [
        {
          name: "Shri Chandra Mohan",
          destination: "Founder Chairman",
          photo: "img/chairman.jpg",
        },
        {
          name: "Shri Chandra Mohan",
          destination: "Founder Chairman",
          photo: "img/chairman.jpg",
        },
        {
          name: "Shri Chandra Mohan",
          destination: "Founder Chairman",
          photo: "img/chairman.jpg",
        },
        {
          name: "Prof Y.C UPRIT",
          destination: "Chairman",
          photo: "img/uprit.jpg",
        },
        {
          name: "Shri Rajesh Agarwal",
          destination: "President, Hitkarini Sabha",
          photo: "img/Rajesh.jpg",
        },
        {
          name: "Shri Vishwamohan",
          destination: "Secretary, Hitkarini Sabha</",
          photo: "img/vishvamohan.jpg",
        },
        {
          name: "Shri Mukul Khamparia",
          destination: "Joint Secretary, Hitkarini Sabha",
          photo: "img/mukul.jpg",
        },
        {
          name: "Er. R. K. Shrivastava",
          destination: "Member Governing Body, HCET",
          photo: "img/RkShrivastav.jpg",
        },
        {
          name: "Shri Naman Aagarwal",
          destination: "Member Governing Body, HCET",
          photo: "img/naman.jpg",
        },
      ],
      firstSlider: [
        {
          image: "img/admission2024.jpg",
        },
        {
          image: "img/yoga1.JPG",
        },
        {
          image: "img/vahak.jpg",
        },
        {
          image: "img/hcet.jpg",
        },
        {
          image: "img/tcs_digital.jpg",
        },
        {
          image: "img/IMG_4159.JPG",
        },
        {
          image: "img/IMG_4142.JPG",
        },
        {
          image: "img/DSC_0737.JPG",
        },
        {
          image: "img/DSC_0815.JPG",
        },
        {
          image: "img/s3.JPG",
        },
        {
          image: "img/s1.png",
        },
        {
          image: "img/placement2021.jpg",
        },
      ],
      secondslider: [
        {
          image: "img/gallery/3_leader.png",
        },
        {
          image: "img/gallery/H2.jpg",
        },
        {
          image: "img/gallery/H3.jpg",
        },
        {
          image: "img/gallery/H4.jpg",
        },
        {
          image: "img/gallery/H5.jpg",
        },
        {
          image: "img/gallery/H6.jpg",
        },
      ],
      thirdslider: [
        {
          image: "img/plac_2022_1.jpg",
        },
        {
          image: "img/plac_2022_2.jpg",
        },
        {
          image: "img/plac_2022_3.jpg",
        },
        {
          image: "img/plac_2022_4.jpg",
        },
        {
          image: "img/plac_2022_5.jpg",
        },
        {
          image: "img/plac_2022_8.jpg",
        },
        {
          image: "img/plac_2022_9.jpg",
        },
        {
          image: "img/tcs_digital.jpg",
        },
        {
          image: "img/groupPhoto2.jpg",
        },
      ],

      roll_gallery: [
        {
          image: "img/gallery/15aug5.jpg",
          url: "/gallery",
          title: "75th Independence Day 2021",
          desc: "Ceremony",
        },
        {
          image: "img/dc2.jpeg",
          url: "/gallery",
          title: "Dental Camp 2021",
          desc: "December 09, 2021",
        },
        {
          image: "img/YOGA1.jpeg",
          url: "",
          title: "Yoga Championship 2021",
          desc: "December 16, 2021",
        },
        {
          image: "img/holi_2024.jpeg",
          url: "",
          title: "Holi Celebration 2024",
          desc: "Ceremony",
        },
        {
          image: "img/vote_awareness.jpeg",
          url: "",
          title: "Vote Awareness 2024",
          desc: "Ceremony",
        },
        {
          image: "img/induction_programe6.jpeg",
          url: "",
          title: "26 January Celebration 2024",
          desc: "Ceremony",
        },
        {
          image: "img/induction_programe6.jpeg",
          url: "",
          title: "Induction Programme Celebration 2024<",
          desc: "Ceremony",
        },
        {
          image: "img/IMG-20230304-WA0002.jpg",
          url: "",
          title: "Holi Celebration 2023",
          desc: "Ceremony",
        },
        {
          image: "img/yoga1.JPG",
          url: "",
          title: "State Level Inter Nodal Tournament 2022-23",
          desc: "Ceremony",
        },
        {
          image: "img/induction1.JPG",
          url: "",
          title: "Induction Programme Celebration 2022",
          desc: "Ceremony",
        },
        {
          image: "img/FLEX 2022.jpg",
          url: "",
          title: "Engineer's Day Celebration 2022",
          desc: "Ceremony",
        },
        {
          image: "img/gallery/15aug5.jpg",
          url: "",
          title: "75th Independence Day 2021",
          desc: "Ceremony",
        },
        {
          image: "img/dc2.jpeg",
          url: "",
          title: "Dental Camp 2021",
          desc: "Ceremony",
        },
        {
          image: "img/YOGA1.jpeg",
          url: "",
          title: "Yoga Championship 2021",
          desc: "Ceremony",
        },
        {
          image: "img/holi_2024.jpeg",
          url: "",
          title: "Holi Celebration 2024",
          desc: "Ceremony",
        },
        {
          image: "img/vote_awareness.jpeg",
          url: "",
          title: "Vote Awareness 2024",
          desc: "Ceremony",
        },
        {
          image: "img/induction_programe6.jpeg",
          url: "",
          title: "26 January Celebration 2024",
          desc: "Ceremony",
        },
      ],
      courses: [
        {
          photo: "img/it.jpg",
          title: "Information Technology",
          desc: "Our best in class department of Information & Technology with some of the best laboratories to learn by doing, lead by our best faculity members.",
          url: "",
          student_enrolled: 2928,
        },
        {
          photo: "img/cs.jpg",
          title: "Computer Science",
          desc: "Our best in class department of Computer Science & Engineering, with best Computer and Operating Systems laboratories, lead by our best faculity members.",
          url: "",
          student_enrolled: 12582,
        },
        {
          photo: "img/ec.jpg",
          title: "Electronics & Communication Engg.",
          desc: "Our best in class, department of Electrical & Electronics, equipped with best instruments and tools to understand the circuits and systems, also it is lead by our best faculty members.",
          url: "",
          student_enrolled: 2928,
        },
        {
          photo: "img/ex.jpg",
          title: "Electrical & Electronics Engg.",
          desc: "Our best in class, department of Electrical & Electronics, equipped with best instruments and tools to understand the circuits and systems, also it is lead by our best faculty members.",
          url: "",
          student_enrolled: 2928,
        },
        {
          photo: "img/civil.jpg",
          title: "Civil Engineering",
          desc: "Our best in class Civil Engineering Department, equiped with best constructing, measurings instruments with best laboratories, lead by our best faculity members.",
          url: "",
          student_enrolled: 7202,
        },
        {
          photo: "img/me.jpg",
          title: "Mechanical Engineering",
          desc: "Our best in class Mechanical Engineering Department, equiped with best laboratories and tools, lead by our best faculity members.",
          url: "",
          student_enrolled: 9582,
        },
      ],
      achievements: [
        {
          photo: "img/news/news8.jpg",
          title:
            "Our Brillent team from Computer Science Branch, Batch-2021 making there position in the coding competition held by RGPV.",
          link: "news.html",
        },
        {
          photo: "img/news/vc1.JPG",
          title: "Chancellor Awards",
          link: "news",
        },
        {
          photo: "img/visaward.jpg",
          title:
            'The students of Hitkarini Engineering College were honored with "Chhatra Vishwakarma Award" by AICTE Delhi.',
          link: "/gallery",
        },
        {
          photo: "img/gallery/62.jpg",
          title:
            "Kriti Bajpai, our 2021 batch Computer Science student being honoured.",
          link: "gallery.html",
        },
        {
          photo: "img/news/news8.jpg",
          title:
            "Our Brillent team from Computer Science Branch, Batch-2021 making there position in the coding competition held by RGPV.",
          link: "news",
        },
        {
          photo: "img/news/vc1.JPG",
          title: "Chancellor Awards.",
          link: "news",
        },
        {
          photo: "img/visaward.jpg",
          title:
            'The students of Hitkarini Engineering College were honored with "Chhatra Vishwakarma Award" by AICTE Delhi.',
          link: "gallery",
        },
        {
          photo: "img/gallery/62.jpg",
          title:
            "Kriti Bajpai, our 2021 batch Computer Science student being honoured.",
          link: "gallery",
        },
      ],
    };
  },
};
</script>
