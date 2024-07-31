<template>
  <AppContainer>
    <Header title="Campus Records" />
    <div class="grid justify-items-center py-8">
      <RoundButton>BATCH 2019-2023</RoundButton>
    </div>

    <div class="grid md:grid-cols-4 gap-5 px-10 py-8">
      <Cards
        v-for="(batch, index) in batch2023"
        :key="index"
        :name="batch.name"
        :destination="batch.placement"
        :photo="batch.photo"
      />
    </div>
    <div class="grid justify-items-center py-8">
      <RoundButton>BATCH 2018-2022</RoundButton>
    </div>
    <div class="grid md:grid-cols-4 gap-5 px-10 py-8">
      <Cards
        v-for="(batch, index) in batch2022"
        :key="index"
        :name="batch.name"
        :destination="batch.placement"
        :photo="batch.photo"
      />
    </div>
    <div class="grid justify-items-center py-8">
      <RoundButton>BATCH 2017-2021</RoundButton>
    </div>
    <div class="grid md:grid-cols-4 gap-5 px-10 py-8">
      <Cards
        v-for="(batch, index) in batch2021"
        :key="index"
        :name="batch.name"
        :destination="batch.placement"
        :photo="batch.photo"
      />
    </div>
  </AppContainer>
</template>

<script>
export default {
  data() {
    return {
      batch2023: [
        {
          photo: "/img/Amar singh thakur.jpg",
          name: "AMAR SINGH THAKUR, EC",
          placement: "Placed in BYJUS Batch: 2019-2023",
        },
        {
          photo: "/img/Aarti%20Kachhi.jpg",
          name: "AARTI KACHHI, IT",
          placement: "Placed in BYJUS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Aarti%20Kachhi.jpg",
          name: "ANKITA RAJAK, CE",
          placement: "Placed in PIDILITE Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/ARPITJHA.jpg",
          name: "ARPIT JHA, CSE",
          placement: "Placed in BYJUS / AMAZON Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/ARUNESH%20SINGH.jpg",
          name: "ARUNESH SINGH, CSE",
          placement: "Placed in BYJUS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/ASHISH%20SHREEPAL.JPG",
          name: "ASHISH SHREEPAL, ELEX",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/BHAGYASHREE%20TRIVEDI.jpg",
          name: "BHAGYASHREE TRIVEDI, CSE",
          placement: "Placed in SOURCESOFT SOLUTIONS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/DIKSHIKA%20MANEKAR.JPG",
          name: "DIKSHIKA MANEKAR, CSE",
          placement: "Placed in BYJUS / SGS TECHNOLOGIES Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/GAYATRI%20TIWARI.jpg",
          name: "GAYATRI TIWARI, CSE",
          placement: "Placed in MASTEK/SHALIGRAM/OCWEN Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Harshwardhan%20Barha.jpg",
          name: "HARSHWARDHAN BARHA, IT",
          placement: "Placed in BYJUS Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/HAZAN%20RAZA%20KHAN.jpg",
          name: "HASAN RAZA, EC",
          placement: "TECHNOLOGIES Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/HIMANSHU%20PANDEY.png",
          name: "HIMANSHU PANDEY, CSE",
          placement: "Placed in TCS(DIGITAL) Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/ABHISHEK%20GUPTA.jpg",
          name: "ABHISHEK GUPTA, ELEX",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/ANANYASINGH.jpg",
          name: "ANANYA SINGH, CSE",
          placement: "SOLUTIONS Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/PARAS%20VAISHNAV.jpg",
          name: "PARAS VAISHNAV, EC",
          placement: "SOLUTIONS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/PRAKRITI%20AGARWAL.jpg",
          name: "PRAKRITI AGARWAL, CSE",
          placement: "Placed in MASTEK, SHALIGRAM Batch: 2019-2023",
        },

        {
          photo:
            "http://www.hcet.hitkarini.com/img/RAGHVENDRA%20SINGH%20RAJPUT.jpg",
          name: "RAGHVENDRA SINGH RAJPUT, EC",
          placement: "Placed in SOURCESOFT SOLUTIONS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/SATISH%20SINGH.jpg",
          name: "SATISH SINGH, CSE",
          placement: "Placed in SOURCESOFT SOLUTIONS Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/SHIVENDRA%20SINGH.jpg",
          name: "SHIVENDRA SINGH , ME",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/SHRISHTI%20SHUKLA.jpg",
          name: "SHRISHTI SHUKLA, CSE",
          placement: "Placed in TCS(NINJA), MASTEK/SHALIGRAM Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/SHRISHTI%20VISHWAKARMA.jpg",
          name: "SHRISHTI VISHWAKARMA, CE",
          placement: "Placed in SOURCESOFT SOLUTIONS Batch: 2019-2023",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/SHUBHAMSONI.jpg",
          name: "SHUBHAM SONI, ME",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/SIDDHANT%20SULLERE.jpg",
          name: "SIDDHANT SULLERE, EC",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/SOHAIL%20KHAN.jpg",
          name: "SOHAIL KHAN, ELEX",
          placement: "Placed in WAAREE ENERGIES LIMITED Batch: 2019-2023",
        },
      ],
      batch2022: [
        {
          photo: "http://www.hcet.hitkarini.com/img/ashutosh_pandey.jpg",
          name: "ASHUTOSH PANDEY, IT",
          placement: "Placed in AETHEREUS Batch: 2018-2022",
        },
        {
          photo:
            "http://www.hcet.hitkarini.com/img/Abhinav%20Singh%20Rawat.jpg",
          name: "Abhinav Singh Rawat, EC",
          placement: "Placed in TCS (Ninja) Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/abhishek%20PANDEY.jpg",
          name: "Abhishek Pandey, EC",
          placement: "Placed in PIE INFOCOMM Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/AMAN%20PANDEY.jpg",
          name: "PIE INFOCOMM, CE",
          placement: "Placed in PIE INFOCOMM Batch: 2018-2022",
        },

        {
          photo: "",
          name: "Kanishka Sahu, CS",
          placement:
            "Placed in JARO EDUCATION, TCS (Ninja), SYNORIQ, INFOCEPTS,SHALIGRAM and WIPRO Batch: 2018-2022",
        },
        {
          photo: "",
          name: "Muskan Yadav, CS",
          placement: "Placed in AETHEREUS, WIPRO, CAPGEMINI Batch: 2018-2022",
        },
        {
          photo: "",
          name: "Ritik Vinodia, CS",
          placement: "Placed in TCS (Ninja), INFOCEPTS Batch: 2018-2022",
        },
        {
          photo: "",
          name: "Karuna Bisen, CS",
          placement: "Placed in CAPGEMINI Batch: 2018-2022",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/sujay.jpeg",
          name: "Sujay Paul, CS",
          placement: "Placed in TCS (Ninja) and NAGARRO Batch: 2018-202",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/aniket.jpg",
          name: "Aniket Verma, CS",
          placement:
            "Placed in TCS(DIGITAL), SYNORIQ, INFOCEPTS, WIPRO Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/divyansh.jpg",
          name: "Divyansh Singh Thakur, CS",
          placement:
            "Placed in TCS (Ninja), SYNORIQ and INFOSYS Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/drashan%20nayak.jpg",
          name: "Darshan Nayak, CS",
          placement: "Placed in NAGARRO, SYNORIQ and WIPRO Batch: 2018-2022",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/vaibhav_shri.jpeg",
          name: "Vaibhav Shrivastava, CS",
          placement:
            "Placed in TCS (Ninja), NAGARRO, SYNORIQ and INFOCEPTS Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/naman1.jpg",
          name: "Naman Shrivastava, CS",
          placement: "Placed in TCS (Ninja) Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/yash.jpg",
          name: "Yash Tiwari, CS",
          placement: "Placed in INFOCEPTS, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/pragyavishwakarma.jpg",
          name: "Pragya Vishwakarma, CS",
          placement: "Placed in TCS (Ninja) and CAPGEMINI Batch: 2018-2022",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/payal.jpg",
          name: "Payal Nanda, CS",
          placement: "Placed in PIE INFOCOMM, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/vaibhav.jpeg",
          name: "Vaibhav Singh Thakur, CS",
          placement:
            "Placed in SYNORIQ, INFOCEPTS and CAPGEMINI Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/arpit.jpg",
          name: "Arpit Tiwari, ME",
          placement: "Placed in PIE INFOCOMM, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/AshitaNema.jpg",
          name: "Ashita Nema, CS",
          placement:
            "Placed in TCS (Ninja), NAGARRO, SYNORIQ, VIRTUSA, SHALIGRAM and WIPRO Batch: 2018-2022",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/anushka.jpg",
          name: "Anushka Dubey, CS",
          placement: "Placed in PIE INFOCOMM, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/sakshi.jpg",
          name: "Sakshi singh Sengar, ME",
          placement: "Placed in PIE INFOCOMM, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/ayush.jpg",
          name: "Ayush Pratap singh, ME",
          placement: "Placed in PIE INFOCOMM and BYJUS, Batch: 2018-2022",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/apoorv.jpg",
          name: "Apoorva Paigwar, ME",
          placement: "Placed in PIE INFOCOMM, Batch: 2018-2022",
        },
      ],

      batch2021: [
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/sharun.jpg",
          name: "Sharun Kanojia, CS",
          placement: "Placed in TCS and NAGARRO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/hitesh.jpg",
          name: "Hitesh Pant, CS",
          placement: "Placed in TCS, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/nikita.jpg",
          name: "Nikita Shukla, CS",
          placement: "Placed in TCS, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/sanskar.jpg",
          name: "Sanskar Gupta, CS",
          placement: "Placed in Potomac and GREFIO, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/pranjal.jpg",
          name: "Pranjal Tiwari, CS",
          placement: "Placed in TCS, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/ranu.jpg",
          name: "Ranu Thapa, CS",
          placement: "Placed in TCS, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/buddhi.jpg",
          name: "Buddhi Sagar Tiwari, CS",
          placement: "Placed in TCS, NAGARRO and SYNORIQ, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/sachin.jpg",
          name: "Sachin Patel, CS",
          placement: "Placed in TCS AND BLUECURSOR, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/kriti.jpg",
          name: "Kriti Bajpai, CS",
          placement: "Placed in JARO and CINIF Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/aditi.jpg",
          name: "Aditi Saman, CS",
          placement: "Placed in JARO and GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/gaurav.jpg",
          name: "Gaurav Khari, CS",
          placement:
            "Placed in NAGARRO, RAPS-Itech and EUTHISSA CARE Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/ayush.jpg",
          name: "Aysuh Khaskalam, CS",
          placement: "Placed in BLUECURSOR, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/priya.png",
          name: "Priya Gupta, CS",
          placement: "Placed in BLUECURSOR, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/shweta.jpg",
          name: "Shweta Kumari, CE",
          placement: "Placed in RAPS-Itech, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/jasroop.jpg",
          name: "Jasroop Singh Reel, CS",
          placement:
            "Technologies, EUTHISSA CARE Technologies, GREFIO Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/shalini.jpg",
          name: "Shalini Giri Goswami, CS",
          placement: "Placed in XOMIC, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/kuldeep.jpg",
          name: "Kuldeep Lodha, CS",
          placement: "Placed in XOMIC, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/abhishek.jpg",
          name: "Abhishek Jain, CS",
          placement: "Placed in CINIF Technologies, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/akshita.jpg",
          name: "Akshita SK, CS",
          placement: "Placed in CINIF Technologies, Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/aman.jpg",
          name: "Aman Gupta, CS",
          placement:
            "Placed in CINIF Technologies and EUTHISSA CARE Technologies Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/shrishti.jpg",
          name: "Shrishti Shivhare, CS",
          placement:
            "Placed in CINIF Technologies and GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/shubhi.jpg",
          name: "Shubhi Gontia, CS",
          placement: "Placed in CINIF Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/ravi.jpg",
          name: "Ravi Yadav, CE",
          placement: "Placed in CINIF Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/abhay.jpg",
          name: "Abhay Dabhade, CS",
          placement:
            "Placed in CINIF Technologies and EUTHISSA CARE Technologies,Accenture, CAPGEMINI Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/aashima.jpg",
          name: "Aashima Yadav, CS",
          placement:
            "Placed in EUTHISSA CARE Technologies and GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/shraddha.jpg",
          name: "Shraddha Yadav, ME",
          placement: "Placed in EUTHISSA CARE Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/sumit.jpg",
          name: "Sumit Tapa, ME",
          placement: "Placed in EUTHISSA CARE Technologies, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/niyati.jpg",
          name: "Niyati Sharma, EC",
          placement: "Placed in Infosys BPM Batch: 2019",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/rituraj.jpg",
          name: "Rituraj Tripathi, ME",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/samarth.jpg",
          name: "Samarth Patel, ME",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/hritika.jpg",
          name: "Hritika Yadav, ME",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/chinmay.jpg",
          name: "Chinmay Dubey, CE",
          placement: "Placed in GREFIO Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/rishab.jpg",
          name: "Rishab Prajapati, ME",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/sunny.jpg",
          name: "Sunny Singh, ME",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/vivek.jpg",
          name: "Vivek Kurmi, CE",
          placement: "Placed in GREFIO, Batch: 2017-2021",
        },
        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/akash.png",
          name: "Akash Soni, ME",
          placement: "Placed in GREFIO Batch: 2017-2021",
        },

        {
          photo: "http://www.hcet.hitkarini.com/img/Placements/prabhjeet.jpg",
          name: "Prabhjeet Singh, CS",
          placement:
            "Placed in TCS, CINIF Technologies and GRIFEO,Accenture Batch: 2017-2021",
        },

        {
          name: "Naman Chadda, CS",
          placement:
            "Placed in EUTHISSA CARE Technologies, CINIF Technologies and GREFIO, Batch: 2017-2021",
        },

        {
          name: "Rajesh Bharti, CS",
          placement: "Placed in EUTHISSA CARE Technologies, Batch: 2017-2021",
        },

        {
          name: "Aditya Anand, CS",
          placement:
            "Placed in EUTHISSA CARE Technologies and GREFIO Batch: 2017-2021",
        },
      ],
    };
  },
};
</script>
