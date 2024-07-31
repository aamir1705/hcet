<template>
  <AppContainer>
    <Header title="Department of Chemistry" />
    <Department>
      <section>
        <img
          alt=""
          class="img-responsive img-bordered"
          width="100"
          height="100"
          src="/img/vibha.jpg"
        />
        <p><strong>DR. VIBHA PATEL</strong></p>
        <p><strong>Head</strong></p>
      </section>
      <section>
        <p class="text-justify">
          The knowledge of engineering chemistry is being given to first year
          student to give solid foundation for their engineering studies. In
          higher semester student get opportunity to understand important
          aspects of life and also applicable to their Engineering knowledge
          i.e. information regarding environment availability of energy and if
          efficient use and impact on society.
        </p>

        <p class="text-justify">
          The faculty in the deptt of Engineering Chemistry is very experienced.
          Student avail the best facilities for performing experiment in fully
          equipped laboratory. The experiments are designed in such manner which
          covers the entire syllabus of RGPV. The environment provided is so
          much aspiring and motivating to make them feel how theoretical
          knowledge can be tested experimentally.
        </p>

        <p class="text-justify">
          It is well known saying that chemistry of any educational institute
          decide the product it can make, likewise the engineering chemistry
          deptt. of HCET is developed to strengthen the concept of chemistry
          which helps the student to absorb the engineering student of different
          branches.
        </p>
      </section>
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
        ["1", "DR. VIBHA PATEL", "PROF. & HOD"],
        ["2", "PROF. DEEPIKA DUBEY", "	A.PROF."],
      ],
    };
  },
};
</script>
