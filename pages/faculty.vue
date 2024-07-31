<template>
  <AppContainer>
    <Header title="Our Faculty Members" />
    <div class="grid p-2 md:grid-cols-4 md:gap-4 md:p-24">
      <Cards
        v-for="(teacher, index) in teachers"
        :key="index"
        :name="teacher.name"
        :destination="teacher.destination"
        :photo="teacher.photo"
        :twitter="teacher.twitter"
        :facebook="teacher.facebook"
        :instagram="teacher.instagram"
        :google_plus="teacher.google_plus"
      />
    </div>
  </AppContainer>
</template>

<script>
export default {
  data() {
    return {
      teachers: [
        {
          name: "Dr. Rinku Kathuria",
          destination: "Principal",
          photo: "img/rinku.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Highest Qualification: </strong> Phd</p>
                        <p><strong>Total Experience: </strong> 25 years</p>
                      <p><strong>Subject of Interest:</strong> Quantum Mechanics, Solid State Physics, Wave Optics</p>
  
                      <p><strong>Research Interest: </strong> Antistoke lumnincence, upconversion lumniscence</p>
  
                      <p><strong>Publication in National & International Journal: </strong>16</p>
                      <p><strong>Professional Membserships: </strong>Indian association of physics teacher, lumniscence
                        society of india</p>
                      <p><strong>Other Achievements: </strong>Book published " Text book of Engg. Physics &amp;
                        experimental
                        approach"by satya prakash publication, new dehli</p>`,
        },
        {
          name: "Dr. Shalem Earnest",
          destination: "Professor, CE",
          photo: "img/shaleem.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Nitin Jharbade",
          destination: "Head of Department, Computer Science",
          photo: "img/nitin.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Vandana Tripathi",
          destination: "Head of Department, EC",
          photo: "img/vandana.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: ` <p><strong>Highest Qualification: </strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 19 years and 2 years Industrial</p>
                      <p><strong>Subject of Interest:</strong> ANALOG AND DIGITAL COMMUNICATION, SATELLITE COMMUNICATION,
                        DIGITAL SIGNAL PROCESSING, ANALOG CIRCUITS, MICROWAVE ENGINEERING</p>
  
                      <p><strong>Research Interest: </strong> OFDM ( COMMUNICATION SYSTEM )</p>
  
                      <p><strong>Other Achievements: </strong>Pursuing Phd.</p>`,
        },
        {
          name: "Prof. M.K Chowdhary",
          destination: "Head of Department, Mechanical Engg",
          photo: "img/manish.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Department: </strong>Mechanical Engineering</p>
                      <p><strong>Highest Qualification:</strong> Phd</p>
                      <p><strong>Total Experience: </strong> 24 years</p>
                      <p><strong>Subject of Interest:</strong> MACHINE DESIGN, INDUSTRIAL DESIGN, INDUSTRIAL ENGG.
                        PRODUCTION ENGG. PRODUCTION MANAGEMENT, ADVANCE MANUFACTURING PROCESSES, WORK SHOP, ENGG.
                        GRAPHICS.
                      </p>
  
                      <p><strong>Research Interest: </strong> INDUSTRIAL DESIGN, PRODUCTION ENGG, PRODUCTION MANAGEMENT,
                        THERMAL, ENERGY</p>
  
                      <p><strong>Publication in National & International Journal: </strong>03 International Journals and
                        01
                        National Journal</p>
  
                      <p><strong>Other Achievements: </strong>NPTL CERTIFICATE (NETWORK CERTIFICATE)</p>
  `,
        },
        {
          name: "Prof. Richa Kuraria",
          destination: "Asst. Professor, IT",
          photo: "img/richa.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Vibha Patel",
          destination: "Head of Department, Chemistry",
          photo: "img/vibha.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Pooja Dubey",
          destination: "Asst. Professor, CSE",
          photo: "img/poojad.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Shanu Shukla",
          destination: "Asst. Professor, MBA",
          photo: "img/shanus.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Rashmi Tiwari",
          destination: "Asst. Professor, MBA",
          photo: "img/rashmi.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Amit Kuraria",
          destination: "Asst. Professor, CSE",
          photo: "img/amitk.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Lt. Archana Patel",
          destination: "Asst. Professor, EC",
          photo: "img/archanap.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Shashank Yadav",
          destination: "Asst. Professor, CE",
          photo: "img/shashanky.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Praveen Patel",
          destination: "Asst. Professor, CE",
          photo: "img/praveen p.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Neelesh Pandey",
          destination: "Professor, Mathematics",
          photo: "img/neelesh.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Gaurav Bhandari",
          destination: "Head of Department, Civil",
          photo: "img/gaurav.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Atul Garg",
          destination: "Asst. Professor, IT",
          photo: "img/atul.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Vinay Patel",
          destination: "Asst. Professor, Civil",
          photo: "img/vinay.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Sarita Patel",
          destination: "Asst. Professor",
          photo: "img/sarita.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `
                        <p><strong>Department: </strong>Information Technology</p>
                        <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                        <p><strong>Total Experience: </strong> 16 years</p>
                        <p><strong>Subject of Interest:</strong> INFORMATION SECURITY, NETWORK SECURITY </p>
  
                        <p><strong>Research Interest: </strong>IMAGE MINING </p>`,
        },
        {
          name: "Prof. Ashish Gupta",
          destination: "Asst. Professor, IT",
          photo: "img/akg.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Rakesh Tiwari",
          destination: "Asst. Professor, EC",
          photo: "img/rakesh.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Raja Namdeo",
          destination: "Asst. Professor, EC",
          photo: "img/raja.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Syed Manzoor Ali",
          destination: "Asst. Professor",
          photo: "img/syed.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `  
                      <p><strong>Department: </strong>Information Technology</p>
                      <p><strong>Highest Qualification:</strong> Phd</p>
                      <p><strong>Total Experience: </strong> 13 years</p>
  `,
        },
        {
          name: "Prof. Devanshu Pyasi",
          destination: "Placement Officer, Asst. Professor, ME",
          photo: "img/devanshu.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Department: </strong>Mechanical Engineering</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 10 years</p>
                      <p><strong>Subject of Interest:</strong> Refrigeration & Air Conditioning, Heat & Mass Transfer,
                        Internal Combustion Engines, Turbo Machinery, Automobile Engg, Basic Mechanical Engineering,
                        Manufacturing Technology, Fluid Mechanic, Thermal Engg</p>
  
                      <p><strong>Research Interest: </strong>Thermal Engineering, Energy Technology </p>
                      <p><strong>Publication in national &amp; International Journal: </strong>03</p>`,
        },
        {
          name: "Prof. Pradeep Khanna",
          destination: "Head of Department, EX",
          photo: "img/pradeep.png",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Department: </strong>Electrical and Electronics Engineering</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 20 years</p>
                      <p><strong>Subject of Interest:</strong>POWER SYSTEM,CONTROL SYSTEM ,EMT,NETWORK ANALYSIS</p>
  
                      <p><strong>Publication in national &amp; International Journal: </strong>Power system Analysis and
                        optimization,power system security,Distribution system analysis and optimization</p>
  
                      <p><strong>Other Achievements: </strong>As a mentor get scrutinized Vishwakarma award in First phase
                        for the successsive two years.Result for the second phase vishwakarma award for this year is still
                        under waiting </p>`,
        },
        {
          name: "Prof. Manish Soni",
          destination: "Asst. Professor, IT",
          photo: "img/manish.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: ` <p><strong>Department: </strong>Information
                        Hitkarini-College-of-Engineering-Technology-227598244116619</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 14 years</p>
                      <p><strong>Subject of Interest:</strong>OOPM,CN,CGM</p>`,
        },
        {
          name: "Prof. Javed Hussain Ansari",
          destination: "Asst. Professor, EX",
          photo: "img/javed.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Department: </strong>Electrical and Electronics Engineering</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 13 years</p>
                      <p><strong>Subject of Interest:</strong>POWER SYSTEM</p>
                      <p><strong>Research Interest: </strong>POWER SYSTEM</p>
  
                      <p><strong>Publication in national &amp; International Journal: </strong>NATIONAL JOURNAL
                        02,INTERNATIONAL JOURNEL 02</p>`,
        },
        {
          name: "Prof. Shivya Prashar",
          destination: "Asst. Professor, EX",
          photo: "img/shivya.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `<p><strong>Department: </strong>Electrical and Electronics Engineering</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech</p>
                      <p><strong>Total Experience: </strong> 5+ years</p>
                      <p><strong>Subject of Interest:</strong>ENERGY TECHNOLOGY,CONTROLSYSTEMS , ELECTEICAL MACHINES </p>
                      <p><strong>Research Interest: </strong>Renewable Energy Source(CSP)</p>
  
                      <p><strong>Publication in national &amp; International Journal: </strong>2</p>
  
                      <p><strong>Other Achievements: </strong>NSDC certification for Electeical Trainer</p>`,
        },
        {
          name: "Prof. Sandeep Bhalaiya",
          destination: "Asst. Professor, CS",
          photo: "img/sandeep.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof. Kushagra Sharma",
          destination: "Asst. Professor, CE",
          photo: "img/kushagra.jpeg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `
                      <p><strong>Department: </strong>Civil Engineering</p>
                      <p><strong>Highest Qualification:</strong> M.E/M.Tech MBA</p>
                      <p><strong>Total Experience: </strong> 10 years</p>
                      <p><strong>Subject of Interest:</strong>Industrial Engineering and Design (software) </p>
                      <p><strong>Research Interest: </strong>Industrial</p>`,
        },
        {
          name: "Prof Sharad Nema",
          destination: "Head, Mathematics",
          photo: "img/sharad.jpeg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: `
                      <p><strong>Department: </strong>Mathematics</p>
                      <p><strong>Highest Qualification:</strong> M.Sc.</p>
                      <p><strong>Total Experience: </strong> 20 years</p>
                      <p><strong>Subject of Interest:</strong>Mathematics </p>`,
        },
        {
          name: "Prof Deepika Dubey",
          destination: "Asst. Professor, Chemistry",
          photo: "img/Deepika.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof Shresth Jain",
          destination: "Asst. Professor, Civil",
          photo: "img/shresthJain.jpeg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Prof Abhishek Pandey",
          destination: "Asst. Professor, EC",
          photo: "img/abhishek.jpg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
        {
          name: "Dr. Abhishek Soni",
          destination: "Asst. Professor, Mechanical",
          photo: "img/a_soni.jpeg",
          twitter: "",
          facebook: "",
          instagram: "",
          google_plus: "",
          learn_more: "",
        },
      
      ],
    };
  },
};
</script>
