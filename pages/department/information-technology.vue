<template>
  <AppContainer>
    <Header title="Department of Information Technology" />
    <div
      
    >
      <section>
        <img alt="" class="max-w-64 h-auto" src="/img/sarita.png" />
        <p class="text-center"><strong>Head</strong></p>
      </section>

      <section>
        <p class="text-justify py-8">
          Department of Information Technology is fully equipped to meet the
          need of the hour as well as the syllabi of the university. The new lab
          of Data Communication has been established to meet the syllabus in
          which LAN experiment consisting of point-to-point communications,
          multicast/broadcast communications, network management etc.are
          performed. In addition to this serial communication using RS-232,
          parallel interface, testing of various data communications protocols
          have been included. Testing of routing algorithms has also been nicely
          implemented.
        </p>

        <p class="text-justify py-8">
          The department is already equipped with a computer lab having PIV
          computers where practical knowledge of DBMS, multimedia and graphics,
          oops, Visual Basic, Visual C++, LINUX and Windows programming etc. are
          provided. Microprocessors and digital laboratory with standard
          equipments and interface devices are available to meet the current
          industrial requirements.
        </p>
      </section>
    </div>
    <Table :table_row_names="table_rows" :data_sets="data" />
    <h2 class="text-3xl font-light py-8">Major Project Presentation</h2>

    <Slider />
  </AppContainer>
</template>
<script>
export default {
  data() {
    return {
      slider: [
        {
          image: "/img/it.JPG",
        },
        {
          image: "/img/csDept1.jpg",
        },
        {
          image: "/img/csDept2.jpg",
        },
      ],
      table_rows: ["#", "Name", "Designation"],
      data: [
        ["1", "PROF.SARITA PATEL", "Head & A.PROF."],
        ["2", "PROF. RICHA KURARIA", "A.PROF."],
        ["3", "PROF. SYED MANZOOR ALI", "A.PROF."],
        ["4", "PROF. ATUL GARG", "A.PROF."],
        ["5", "PROF. MANISH SONI", "A.PROF."],
        ["6", "PROF. ASHISH GUPTA", "A.PROF."],
        ["7", "PROF. BHUPENDRA THAKUR", "A.PROF."],
        ["8", "PROF. PRAGYA GARG", "A.PROF."],
        ["9", "PROF. AVDHESH SOLANKI", "A.PROF."],
      ],
    };
  },
};
</script>
