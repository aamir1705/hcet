<template>
  <AppContainer>
    <Header title="Department of Mathematics" />
    <Department>
      <section>
        <img
          alt=""
          class="img-responsive img-bordered"
          width="100"
          height="100"
          src="img/sharad.jpeg"
        />
        <p><strong>PROF. SHARAD NEMA</strong></p>
        <p><strong>Head</strong></p>
      </section>
      <p class="text-justify">
        It is a universal fact that Mathematics was born in our country INDIA.
        Mathematics as rightly said does not just teach people to calculate
        numbers but also makes them calculative and manipulative in life. It
        gives a student the qualities of an analytical mind and logical
        understanding. With competent staff, focused studying aids and huge
        library support HCET happens to be the premium place to learn the
        subject.
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
        ["1", "PROF. SHARAD NEMA", "PROF. & HOD"],
        ["2", "DR. NEELESH PANDEY", "	PROFESSOR"],
        ["3", "PROF. GEETANJALI PHADATARE", "	A.PROF."],
        ["4", "PROF. SOMYA MODI", "	A.PROF."],
      ],
    };
  },
};
</script>
