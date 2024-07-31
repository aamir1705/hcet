<template>
  <AppContainer>
    <Header title="Department of Humanities" />
    <Department>
      <section>
        <img
          alt=""
          class="img-responsive img-bordered"
          src="/img/Anshuta.JPG"
          width="120px"
          style="margin-right: 100px; padding-left: 25px"
        />
        <p><strong>PROF. ANSHUTA SHARMA</strong></p>
        <p><strong>Head</strong></p>
      </section>

      <p class="text-justify">
        <strong>Communication Skill :</strong> Communication is the pre-
        requisite for the survival of an individual. Communication is not just
        the process of transferring an information from one to another but is a
        means to express oneself not just professionally but also emotionally,
        physically and mentally. A person when communicating with another person
        creates and develops an understanding which is a basis of healthy
        relationship. We at HCET provide congenial atmosphere to an individual
        so that he /she can not only learn to communicate aptly but also make
        bonds for their lifetime. We believe in understanding and sustaining
        long relationship and thus ensure to groom the students such that they
        can communicate and command the globe. This is done with the help of the
        state- of-the-art communication lab with fully equipped technical
        facilities and learning aids.
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
      data: [["1", "PROF. ANSHUTA SHARMA", "PROF. & HOD"]],
    };
  },
};
</script>
