<template>
  <AppContainer>
    <Header title="Department of Engineering Physics" />

    <Department>
      <section>
        <img alt="" class="img-responsive img-bordered" src="/img/rinku.jpg" />
        <p><strong>Dr. Rinku Kathuria</strong></p>
        <p><strong>Head</strong></p>
      </section>
      <section>
        <p class="text-justify">
          In physics you don’t have to go around making trouble for yourself –
          nature does it for you.
        </p>

        <p class="text-justify">
          This department has been rendering excellent teaching since the
          inception of this grand institute imparting the knowledge of physics
          to engineering students, may be rightly called the mother of all
          engineering branches. With the passage of time it was felt necessary
          that this should be upgraded to stature.
        </p>

        <p class="text-justify">
          This department has a tradition of having up-to- date facility of many
          laboratories at graduate level ably backed up by the learned teaching
          staff offering their knowledge and expertise in destiny of the
          student.
        </p>

        <p class="text-justify">
          Keeping in view the advancement and changing scenario we have kept
          pace with the changing time by having new labs and facilities in the
          department keeping the old values intact. Presently we have the
          undergraduate BE labs with modern experiments and well equipped
          Nuclear science lab, solid state / Material science lab, and
          electronics and digital lab for UG students.
        </p>
      </section>

      <H3Light>Facilities</H3Light>

      <p>
        " G.M Counter"
        <br />
        " Hall Effect setup"

        <br />
        " Laser & Fibre Optics Setup"

        <br />
        " Planck Constant Setup"
        <br />

        " Various Methods of inference Diffraction & Polarization of Optical
        Rays."
        <br />
        " Various setup regarding the behavior of Semiconductor Devices."
      </p>
    </Department>
    <Table :table_row_names="table_row" :data_sets="data" />
  </AppContainer>
</template>

<script>
export default {
  data() {
    return {
      table_row: ["#", "Name", "Designatiom"],
      data: [
        ["1", "Dr. Rinku Kathuria", "HOD"],
        ["2", "PROF. DEVASHISH MUKERJI", "PROFESSOR"],
        ["3", "PROF. PRIYANKA AGRAWAL", "	A.PROF."],
        ["4", "PROF. PALLAVI SHUKLA", "	A.PROF."],
      ],
    };
  },
};
</script>
